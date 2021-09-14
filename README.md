# Biomolecular Structure and Function Group (BioSFGroup) website

The research work in Biomolecular Structure and Function Group is centered on DNA methylation and Alzheimer’s disease. See [the website](https://svedruziclab.github.io/) for more info.

Editing the website contents requires at least [the basic knowledge of reStructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html).

## Preparing the enviroment

The website is built using [Sphinx](https://www.sphinx-doc.org/en/master/) and [Material for Sphinx](https://bashtage.github.io/sphinx-material/). Make sure you have [Python](https://www.python.org/) and [pip](https://pip.pypa.io/) installed on your system. The required packages can be installed via your OS package manager or using pip like:

``` shell
$ pip install sphinx sphinx_material
```

## Obtaining the sources

Clone the repository:

``` shell
$ https://github.com/svedruziclab/svedruziclab.github.io
```

## Editing the contents

Make the edits you want using any text editor you like (e.g. [Visual Studio Code](https://code.visualstudio.com/) and [reStructuredText extension](https://www.restructuredtext.net/)). When you are done, add them and commit the changes:

``` shell
$ git add *.rst */*.rst
$ git commit
```

## Publishing the edits

To publish your edits in source form, push them to GitHub:

``` shell
$ git push
```

## Building the website

Clean the previous build, if any:

``` shell
$ make clean
```

Build the website:

``` shell
$ make dirhtml
```

If the build was unsuccessful, fix the errors and repeat the building process.

## Publishing the website

Once the build is successful, prepare the built contents for pushing to GitHub:

``` shell
$ make gh-prepare
```

Add the built files, commit the changes, and push them to GitHub:

``` shell
$ git add docs
$ git commit
$ git push
```

Wait a few minutes until [GitHub Pages](https://pages.github.com/) had time to publish the new files and then visit [svedruziclab.github.io](https://svedruziclab.github.io/) to make sure your changes are visible.
