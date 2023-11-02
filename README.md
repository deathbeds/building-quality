<!-- 

    This file can be viewed as a slideshow in `jupyterlab-deck`.

-->

---

# Building Quality

> _a talk about how teams can use tools to assess, maintain, and improve quality_

---

## Running the talk

This talk is meant to be walked through interactively.

---

### On `mybinder.org` (recommended)

- Launch it on [![binder-badge]][binder]

---

### On Your Computer

> Probably only works on Linux... _maybe_ MacOS

- get [Mambaforge]
- clone this repo
    ```bash
    git clone https://github.com/deathbeds/building-quality
    cd building-quality
    ```
- create and activate the environment
    ```bash
    mamba env update --prefix .venv --file .binder/environment.yml
    source activate .venv
    ```
- start JupyterLab
    ```bash
    jupyter lab talk/00-intro.ipynb
    ```
- open [the talk](./talk/00-intro.ipynb)
- start JupyterLab [Deck mode][deck-mode]

---

### Either Way

- crank up the zoom to about 200%
- run through the slides
    - <kbd>space</kbd> to continue
    - <kbd>shift+enter</kbd> to run cells
        - right click on a cell output and _Enable Scrolling for Outputs_ if needed

---

## Open Source

This talk is mostly code, so it's licensed under the [BSD-3-Clause]. Feel free to
do whatever you like with it!

[deck-mode]: https://github.com/deathbeds/jupyterlab-deck/#deck-mode
[bsd-3-clause]: https://github.com/deathbeds/building-quality/blob/main/LICENSE.txt
[mambaforge]: https://conda-forge.org/miniforge/
[binder-badge]: https://mybinder.org/badge_logo.svg
[binder]: https://mybinder.org/v2/gh/deathbeds/building-quality/main?urlpath=lab%2Ftree%2Ftalk%2F00-intro.ipynb
