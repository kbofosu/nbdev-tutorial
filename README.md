# nbdev-linear-regression-tutorial

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

Behold, the NBDEV Linear Regression Tutorial for students of CSCI 435!

### Requirements

------------------------------------------------------------------------

1.  Install JupyterLab
    - conda install -c conda-forge -y jupyterlab **OR** pip install
      jupyterlab
2.  Install nbdev
    - **Mac and Linux**:
      - conda install -c fastai -y nbdev **OR** pip install nbdev
    - **Windows**:
      - pip install nbdev==2.3.7
3.  Install quarto
    - nvdev_install_quarto
      - Windows will redirect you to install it at the Quarto website
      - **Make sure to restart your terminal afterwards**
    - pip install jupyterlab-quarto
4.  Install the required modules if you don’t have them already
    - Use either pip or conda
    - matplotlib and numpy
    - Python has csv and datetime already

### Tutorial Steps

------------------------------------------------------------------------

1.  Create a new repository and clone it to your computer
2.  Go to the terminal and make sure you’re in your repo’s directory
3.  Run `nbdev_new` to generate necessary files
4.  Replace `nbs/00_core.ipynb` and `nbs/index.ipynb` with the ones in
    this repository, and add `shampoo.csv` into the `nbs` folder
5.  Run `nbdev_readme` to generate a README.md that should look like
    this one
6.  Run `jupyter lab` in the repository
7.  Program `nbs/00_core.ipynb` such that everything works properly and
    save your PDF
8.  Run `nbdev_install_hooks`
9.  Push your changes to your Github
10. Run `nbdev_preview` and make sure it looks right
11. Go to your Github Settings, click `Deploy from a branch`, and select
    `gh-pages`.
12. Return to Github Code, click the gear on About, and set the website
    to Github Pages
13. Send the PDF and your Github Pages website to Alejandro and CC
    Prof. Poshyvanyk!

### Resources Utilized

------------------------------------------------------------------------

- https://nbdev.fast.ai/tutorials/tutorial.html
- https://jmp75.github.io/work-blog/posts/20221007-nbdev-windows/
  - nbdev isn’t actually designed for Windows but this madlad somehow
    made it work anyways

P.S. I wrote this entire tutorial in one night.