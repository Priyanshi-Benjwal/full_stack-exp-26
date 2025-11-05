# 🚀 CI/CD Pipeline using GitHub Actions

🎯 Objective
Automate testing and deployment for a React app using GitHub Actions.

📁 Project Structure
.github/workflows/main.yml → Workflow configuration
src/ → React app source files
public/ → Static assets
⚙️ Workflow Summary
Runs automatically on every push to main.
Installs dependencies.
Runs tests.
Builds the app.
Deploys to GitHub Pages (if configured).
🧠 Deployment Setup
Go to your repository Settings → Pages.
Set the branch to gh-pages and folder to / (root).
Commit and push — your app will deploy automatically.
Check the Actions tab for workflow progress.
✅ Expected Output
A running CI/CD pipeline visible in GitHub’s Actions tab.
Automatic deployment after successful build.
Live React app on GitHub Pages.
