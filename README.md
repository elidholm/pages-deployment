# GitHub Actions Deployment Workflow

This project demonstrates a simple GitHub Actions workflow that automatically deploys a static website to GitHub Pages whenever changes are made to the `index.html` file.

## 🚀 Live Demo

Visit the deployed website: <https://elidholm.github.io/pages-deployment/>

## ⚙️ How It Works

1. The GitHub Actions workflow is defined in `.github/workflows/deploy.yml`
2. It's triggered whenever changes to `index.html` are pushed to the `master` branch
3. The workflow:
   - Checks out the repository
   - Sets up GitHub Pages
   - Uploads the site files as an artifact
   - Deploys the artifact to GitHub Pages

## 🧪 Testing the Workflow

To test that the workflow correctly triggers on changes to `index.html`:

1. Modify the `index.html` file
2. Commit and push the changes
3. Check the "Actions" tab to see the workflow running
4. Visit your GitHub Pages URL to see the updated site

## 📚 What I Learned

- How to set up GitHub Actions workflows
- How to deploy to GitHub Pages using CI/CD
- How to configure workflow triggers for specific files
- Basic principles of Continuous Integration and Continuous Deployment

## 📄 License

This project is licensed under the Apache-2.0 license - see the [LICENSE](LICENSE) file for details.

## 🔗 Project URL
<https://roadmap.sh/projects/github-actions-deployment-workflow>