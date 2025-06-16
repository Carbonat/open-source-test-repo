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

# Place for improvement

1. The repository is raw and may not adhere to best practices for documentation deployment.
1. Speed up the conversion of the AsciiDoc file into HTML. Use caching or publicly available official Docker Images.
1. `peaceiris/actions-gh-pages@v4` creates and uses `gh-pages` to store the conversion results. I'm not sure if it's the best option.
1. "Heading 2" of AsciiDoc files are used to create separate HTML pages. There may be another criterion for how an asciidoctor decides to create a page.
1. Use CSS to make the generated page prettier.
