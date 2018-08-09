# EEOB/BCB 546X Course Website

This repository hosts the website for the graduate course "Computational Skills for Biological Data". This is a static site built by Jekyll and based on the [Millidocs Theme](https://github.com/alexander-heimbuch/millidocs).

## Editing and Building the Site

To edit this site, you must first clone this repository

```
git clone git@github.com:EEOB-BioData/EEOB-BCB-546X.git
```

Then, change directories to `EEOB-BCB-546X`.

```
cd EEOB-BCB-546X
```

To build the site, you must have [Jekyll installed](https://jekyllrb.com/docs/installation/). If you have Jekyll, you can install the Millidocs bundle:

    $ bundle

Or install it yourself as:

    $ gem install millidocs

Now you should be able to serve the website on your local machine using Jekyll:

```
jekyll serve
```

This will generate the whole site so that you can view it on your own machine at `http://127.0.0.1:4000/`.

Now if you make changes, you will be able to preview them before pushing the source to the remote host on GitHub.

### Directory Structure and Making Edits

Most of the files in the site directory determine the style and layout of the pages. This Jekyll theme only supports page, which are all composed in Markdown and should be located in the top directory. 

Additionally, there is a directory called `slides`, which is where we can post the lecture slides. We can simply link to these slides using their relative paths: `[today's lecture slides](slides/today_lecture.html)`.