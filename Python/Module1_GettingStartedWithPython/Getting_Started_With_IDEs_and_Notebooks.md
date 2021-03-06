---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.1'
      jupytext_version: 1.1.0-rc0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

```raw_mimetype="text/restructuredtext"
.. meta::
   :description: Topic: Integrated Development Environments, Difficulty: Easy, Category: Tools
   :keywords: python, introduction, IDE, PyCharm, VSCode, Jupyter, recommendation, tools
```

# Setting Up a Development Environment
## What You Will Learn

- An IDE is a sophisticated text editor that allows you edit, run, and debug code. 
- The Python shell is an interface for typing Python code and executing it directly in your computer's terminal.
- The IPython shell is a much nicer version of the Python shell - it provides syntax highlighting, autocompletion, and other features.
- The Jupyter Notebook is a powerful tool for prototyping and experimenting with code, as well as visualizing data and writing nicely-formatted text. We will be using this throughout the course.


## Integrated Development Environments
In Section 1 of this module, we learned that a Python script is simply a text file that contains Python code. Aside from using a `.py` suffix for the filename, there is nothing that differentiates this sort of file from any other text file. That being said, it is not a good idea to use a simple text editor to write Python code (and it is a big mistake use word-processing software, like Microsoft Word, to do so). Instead we want an "integrated development environment" (IDE) that will facilitate our code-writing. 

First and foremost, a good IDE will provide a text editor that will:

- check your code for syntax errors (a misspelled function name, a reference to an undefined variable, etc)
- colorize your code so that it is easy to distinguish, for instance, numbers from character strings.
- enable you to easily look up documentation and definitions for functions that you are using.
- autocomplete the names of variables and functions as you are typing them.

An IDE also often provides debugging tools so that you can test your code; it will also typically interface with version-control software, like Git, so that you can keep track of versions of your code as you modify it. We will not discuss these useful, but more advanced features here.

### Recommended IDEs
There are many excellent IDEs that can be configured to work well with Python. Two IDEs that we endorse are:
 
[PyCharm](https://www.jetbrains.com/pycharm/download): A powerful IDE dedicated to Python.

**Pros**

- works well out-of-the-box
- long-supported by professionals and thus is very reliable
- highly configurable
- fully-featured

**Cons**

 - can be resource-heavy, especially for a laptop
 - may be overwhelming to new users (but has good documentation and tutorials)
 
[Visual Studio Code](https://code.visualstudio.com/) with the [Python extension](https://code.visualstudio.com/docs/languages/python): A lightweight, highly customizable IDE.

**Pros**

- lightweight and elegant 
- works with many different languages, so you only need to familiarize yourself with one IDE
- a huge number of extensions can be downloaded to add functionality to the editor; these are created by a large community of open-source developers.

**Cons**

- currently less polished and less powerful than PyCharm, although Microsoft is now formally supporting the Python extension
- can require some tinkering to get features working


<div class="alert alert-info">

**Takeaway**:

Integrated Development Environments (IDEs) provide powerful tools for helping you write well-formatted and typo-free code. We recommend using PyCharm Community Edition or Visual Studio Code (with the Python extension installed) for your Python IDE. 
</div>


<div class="alert alert-warning">

**Jupyter Lab**:

[Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) is a new IDE that is being developed by the same team that develops the Jupyter Notebook. It aims to mix the polish and power of a traditional IDE, along with the convenience and great utility of the notebook environment. As of writing this, Jupyter Lab is still in the beta release phase. Given the massive popularity of Jupyter Notebook, Jupyter Lab will likely become a widely used IDE, quickly. 

</div>
