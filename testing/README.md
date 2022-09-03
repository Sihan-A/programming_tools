Code Format
===

Content

1. `pre-commit`
2. `black`
3. `flake8`
4. `shellcheck`

Reference

- [Automate Python workflow using pre-commits: black and flake8](https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/)
- [How to setup your project with pre-commit, black, and flake8](https://dev.to/m1yag1/how-to-setup-your-project-with-pre-commit-black-and-flake8-183k)

![](https://ljvmiranda921.github.io/assets/png/tuts/precommit_pipeline.png)

pre-commit
---

```shell
pre-commit autoupdate
```

black
---

- Check and reformat the current directory
    ```shell
    python -m black .
    ```

- [`jupyter-black`](https://pypi.org/project/jupyter-black/): To beautify python code in Jupyter Notebook
