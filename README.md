# jbang-jupyter-tutorial

Jupyter notebook based tutorial for getting started with Java using jbang.

Tested to work in vscode and vscodium locally and in following browser based environments directly:

- [GitPod.io](https://gitpod.io/#https://github.com/jbangdev/jbang-jupyter-tutorial/)
- [GitHub Codespaces](https://github.com/jbangdev/jbang-jupyter-tutorial/codespaces) 
- [OpenShift Workspaces](https://workspaces.openshift.com/?url=https://github.com/jbangdev/jbang-jupyter-tutorial/)

Also tested to work with plain Jupyter Notebook in [Red Hat OpenShift Data Science](https://developers.redhat.com/products/red-hat-openshift-data-science/overview) sandbox.

- using it in [PyCharm](https://www.jetbrains.com/pycharm/)
  - open the repository as new project in PyCharm, e.g. one possible way

        cd $this_repo_root
        pycharm .
  - create a virtual Python environment <br>
    open PyCharm settings - press `CTRL+ALT+S` <br>
    navigate to `Project > Project Interpreter` <br>
    click on `Add Interpreter` <br>
    create a new `Virtual Environment` in `$this_repo_root/venv`
  - double click on the Jupyter notebook file `jbang_tutorial.ipynb` <br>
    allow to install Jupyter
  - when the Jupyter installation (and a possible package reindexing) is finished <br>
    click with the left mouse button in the first Notebook cell (it starts with `import os`) <br>
    press `SHIFT+ENTER` to install JBang (the executed installation command is part of this cell)

## How to use

Open the [jbang tutorial notebook](jbang_tutorial.ipynb), and you should be able to read the instructions and run the code cells directly.

If IDE asks if you want to install the recommended  extensions, say yes. Makes it easier to work with the notebook and generated files.

## Work in progress

I recently realized Jupyter Notebooks works well as a tutorial format with `jbang`. Made this very quickly to test it out.

Will see where it goes!

Suggestions and PR's very welcome :)
