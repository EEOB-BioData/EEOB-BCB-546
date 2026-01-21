# EEOB/BCB 546 Course Website

Website URL: [https://eeob-biodata.github.io/EEOB-BCB-546](https://eeob-biodata.github.io/EEOB-BCB-546)

This repository hosts the website for the graduate course "Computational Skills for Biological Data". This is a static site built by Jekyll and based on the [Millidocs Theme](https://github.com/alexander-heimbuch/millidocs).

## Editing and Building the Site

To edit this site, you must first clone this repository

```
git clone git@github.com:EEOB-BioData/EEOB-BCB-546.git
```

Then, change directories to `EEOB-BCB-546`.

```
cd EEOB-BCB-546
```

To build the site, you must have [Jekyll installed](https://jekyllrb.com/docs/installation/). If you have Jekyll, you can install the Millidocs bundle:

    $ bundle

Or install it yourself as:

    $ gem install millidocs

Now you should be able to serve the website on your local machine using Jekyll:

```
bundle exec jekyll serve
```

This will generate the whole site so that you can view it on your own machine at `http://127.0.0.1:4000/`.

Now if you make changes, you will be able to preview them before pushing the source to the remote host on GitHub.

### Troubleshooting

If you get errors when running `bundle exec jekyll serve` this may be because you need to update installed gems or Gemfile snapshot. To do this first update your gems in the Gemfile:

```
bundle update
```

Then install any missing gems:

```
bundle install
```

You should be able to serve the site now:

```
bundle exec jekyll serve
```



### Directory Structure and Making Edits

Most of the files in the site directory determine the style and layout of the pages. This Jekyll theme only supports page, which are all composed in Markdown and should be located in the top directory. 

Additionally, there is a directory called `slides`, which is where we can post the lecture slides. We can simply link to these slides using their relative paths: `[today's lecture slides](slides/today_lecture.html)`.

## Updating for a New Semester

When starting a new semester, it's necessary to make changes to the site. Here are the steps:

* create a new GitHub repository for the course data files and documents, the format for naming this is `BCB546-FallYEAR`
* create a new syllabus and place it in the repository above
* update the GitHub and Canvas links in `_includes/navigation.html`
* update the year in `_includes/sidebar.html`
* remove previous year's content in:
	* `index.md`
	* `schedule.md`
	* `assignments.md`
* correct the link to the syllabus on `index.md`
* update the link to the schedule on `schedule.md`

### Website Troubleshooting

With annual updates to jekyll and the theme, it may help to pull the `millidocs.gemspec` file from the [theme repository](https://github.com/alexander-heimbuch/millidocs/blob/master/millidocs.gemspec).

### New Look

It is typically good to give the site a new look for each semester. This can be achieved by changing the theme (a lot of work) or changing the colors of the current theme (little work). Here are the colors we have used:

#### Fall 2018 Green Theme

* `_sass/milligram.scss` button background color `#047900`
* `_sass/variables.scss` navigation background color `#C9E0C4`
* `assets/css/docs.scss` link color `#047900`

#### Fall 2019 Blue Theme

* `_sass/milligram.scss` button background color `#006878`
* `_sass/variables.scss` navigation background color `#AAD4E6`
* `assets/css/docs.scss` link color `#006878`

#### Spring 2021 Purple Theme

* `_sass/milligram.scss` button background color `#633A8E`
* `_sass/variables.scss` navigation background color `#BBACC1`
* `assets/css/docs.scss` link color `#633A8E`
* note that this semester will also include details for the virtual format that may need to be removed when updated for an in-person semester

#### Spring 2022 Pink Theme

* `_sass/milligram.scss` button background color `#821B28`
* `_sass/variables.scss` navigation background color `#E7BBC1`
* `assets/css/docs.scss` link color `#821B28`

#### Spring 2023 Blue Theme

* `_sass/milligram.scss` button background color `#006878`
* `_sass/variables.scss` navigation background color `#AAD4E6`
* `assets/css/docs.scss` link color `#006878`

#### Spring 2024 Green Theme

* `_sass/milligram.scss` button background color `#047900`
* `_sass/variables.scss` navigation background color `#C9E0C4`
* `assets/css/docs.scss` link color `#047900`

#### Spring 2025 Purple Theme

* `_sass/milligram.scss` button background color `#633A8E`
* `_sass/variables.scss` navigation background color `#BBACC1`
* `assets/css/docs.scss` link color `#633A8E`

#### Spring 2026 Blue Theme

* `_sass/milligram.scss` button background color `#006878`
* `_sass/variables.scss` navigation background color `#AAD4E6`
* `assets/css/docs.scss` link color `#006878`
