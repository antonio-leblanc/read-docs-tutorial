# Read the docs tutorial

Do not remember exactly the setps lol
something like

Steps to init
- created venv
- installed dependencies that are now saved on requirements.txt
- to test the HTML run `make html`

---
References
- https://docs.readthedocs.com/platform/stable/tutorial/index.html
- https://www.youtube.com/watch?v=PO4Zd-6a6fA


The steps where
*   **Install Sphinx and the Read the Docs theme**: `pip install sphinx sphinx-rtd-theme`.
*   **Initialize your Sphinx project**: Run `sphinx-quickstart` in your project's root directory and answer the prompts. Ensure you answer "yes" to separating source and build directories.
*   **Modify the `conf.py` file** (located in the source directory) to set the `html_theme` to `'sphinx_rtd_theme'`.
*   **Write your documentation** in reStructuredText (`.rst`) files, starting with `index.rst`.
*   **Build your documentation locally** to preview: Run `make html`. The HTML files will be in the `build/html` directory.
*   **Create a public repository** on GitHub and push your local repository to it. **Your repository must be public** for Read the Docs to access it.
*   **Create a `readthedocs.yaml` configuration file** in the root of your repository.
*   **Create a `requirements.txt` file** in the root of your repository and list `sphinx-rtd-theme` in it if you encounter build issues.
*   **Log in to Read the Docs** (community version) and connect your GitHub account.
*   **Import your project** by clicking "Import a Project" and selecting your repository.
*   Give your project a name and click "Next" and then "Finish".
*   Read the Docs will now build your documentation automatically. You can check the build status.
*   **View your documentation** at the provided Read the Docs URL.
*   **Any changes you push to your public GitHub repository will automatically trigger a rebuild** of your documentation on Read the Docs.