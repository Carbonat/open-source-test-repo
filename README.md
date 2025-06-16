# open-source-test-repo

1. To enable the branch `gh-pages` creation, in the repository Settings:
   1. Actions -> General
   1. Workflow permissions -> Read and write permissions.
1. During the deployment, the branch `gh-pages` is created.
1. To deploy the generated index.html file to GitHub Pages, in the repository Settings:
   1. Pages
   1. In "Build and deployment", choose the branch `gh-pages`, the directory `/ (root)`, and click the button "Save".
   1. Wait until the GitHub Actions in the `gh-pages` branch deployment is finished.
   1. The https://carbonat.github.io/open-source-test-repo/ is ready to be opened.
