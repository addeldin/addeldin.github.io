---
layout: page
title: how to use these activities
description: if you get confused about how to make use of the materials in this section, read this first
img: assets/img/how-to-use.png
importance: 1
category: instructional activities
---

Each of the activities in this section leads to a page that describes the activity overall. However, the main materials will be published on GitHub or, in some occasions, linked elsewhere, e.g. the [Genre Generators activity](https://addeldin.github.io/projects/genre-generators/), which has an introduction that was published as part of an open collection.

## Using GitHub
If you have never used GitHub before, you can still make use of any activities here that consist only of Markdown (`.md`) files, e.g. the [Personal Writing with AI activity](https://addeldin.github.io/projects/personal-writing-with-ai/). Simply click on the `README.md` file in a given repository (the collection of files on the linked GitHub page) and then click through the other relevant `.md` files as described in the `README`.

However, if you want to download these files (to, say, edit or print them), you will need to create a free GitHub account. You can do so via the [account creation page](https://github.com/signup).

Once you have created an account, return to the repository. To the top-right of the list of files and to the left of the `About` section, select the green `Code` button, which will result in a dropdown menu. From there, you can download all of the relevant files as a ZIP.

## Editing and Printing Markdown
You can edit any of the markdown files by opening them in any text editor, e.g. Notepad or TextEdit. Scroll down to the text section you want to edit and save your changes. If you want to rework the structure, including headings, you can reference the [Markdown Guide](https://www.markdownguide.org/basic-syntax/) or even complete [a tutorial]](https://www.markdowntutorial.com/) to learn how to work with Markdown.

However, the text editor will not *render* the Markdown into something that is easy to read (for example, instead of having different sized headers, all text will be the same size but prefaced by different numbers of `#`). And, as a result, you won't be able to print it out in a way that looks good. You can use an online tool such as [Markdown, Humanized](https://markdowner.github.io/) to both preview and print your newly edited Markdown.

Another option is to go to the relevant `.md` file on GitHub. You can copy+paste the text into a word processor, and it should maintain its formatting. Then you can edit and print as you would any other word processing document.

## Using Jupyter Notebooks
Some activities, such as the [Genre Generators activity](https://addeldin.github.io/projects/genre-generators/), include Jupyter Notebooks or `.ipynb` files. This format is useful because it enables the presentation of both rendered Markdown text along with executable code. Because the Genre Generators activity involves the running of code, `.ipynb` files are useful, as they can be more user-friendly than figuring out how to run a file of, say, Python code. If you are completely unfamiliar with coding languages and executing code, these activities might be worth skipping, but if you feel confident in your ability to make any necessary edits and execute the code in a Jupyter Notebook, this section will help you set up the software you need and make basic use of it.

However, there is still some setup required to actually make use of these files, rather than just preview them on GitHub. To do so, you will want to download an [Anaconda distribution](https://www.anaconda.com/products/distribution). Anaconda allows you to run Jupyter notebooks and includes with it the installation of Python, which is the coding language I use for my instructional activities, and is generally considered to be more beginner friendly.

Install Anaconda using default settings via the distribution installer linked above. You should be able to run `Anaconda Navigator` by searching it via Windows search in your desktop taskbar, or the MacOS Launchpad. Make sure to launch `Anaconda Navigator` and not `Anaconda Prompt`. Once it has opened, launch `Notebook`, which has an icon that reads `jupyter`, rather than `JupyterLab`.

A window should open in your web browser. Navigate to the folder where you have stored the files from the GitHub repository and select the .ipynb file. You should be able to see text in Markdown along with blocks of code, which you can edit directly and execute by clicking in a code block and pressing the `Run` button at the top of the page or pressing `Shift+Enter`.

