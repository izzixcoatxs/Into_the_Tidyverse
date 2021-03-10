Navigation:

* [FAQs](#faqs)
* [About This Repository](#about-this-repository)
* [About the Course](#about-the-course)
* [Getting Started](#about-the-course)
* [Quick Access to Resources](#quick-access-to-resources)
* [Help](#help)

***

**Shameless Plug Warning**

This course has been modified for AZ code club from the 'into the tidyverse' course written by [Tim Hardgreaves](https://www.linkedin.com/in/tim-hargreaves/). These resources took over one hundred hours to develop. If you find them useful, please consider connecting with him on [LinkedIn](https://www.linkedin.com/in/tim-hargreaves/) and endorsing him for R, Teaching, and Communication.

## FAQs

### The Tidy-what?

The tidyverse is a collection of tools for the programming language R used for working with data. It was designed from the ground up to have a clear and consistent design philosophy, making it as easy as possible to learn how to work with data. From data importing, to cleaning, and visualisation to modelling, the tidyverse has you covered. If you are looking for a way to step up from tools such as Excel, Tableau, and PowerBI with as little difficulty as possible, the tidyverse welcomes you.

### What are the prerequisites for the course?

Nothing but a passion to learn!

### How do I report a mistake?

Spotted a mistake, dead link, or have suggestions for improvements? Report these [here](https://github.com/izzie1234i/Into_the_Tidyverse/issues/new)

## About This Repository

This repository contains slides, exercise sheets, and solution sheets for my course, 'Into the Tidyverse'. This was first taught at Alsager Sixth Form during the Autumn term of 2019 and has since been adapted for use at the AstraZeneca Code Club and Data Science Academy. The repository is designed to be completely self-contained, with any images and data used in the presentations or exercises included in each session's data folder. You can use the navigation links below to find relevant resources and below that, a few words of guidance can be found.

## About the Course

'Into the Tidyverse' does exactly what it says on the tin. This is an intensive 10-week course which aims to take someone from a coding-zero to tidyverse-hero in as little time as possible. Each session is composed of a rapid-fire presentation introducing different elements of the tidyverse as well as an exercise sheet to help consolidate the ideas presented in the slideshow.

The contents of presentation are designed to be dense so don't worry if everything seems a bit intimidating. It takes far too long to memorise the exact function calls and parameter names of a new programming language, and so I don't make any attempt to teach this. Instead, the goal of this course is to have a scan through the tidyverse landscape and point out some of the key landmarks. Since the contents of the presentations are so dense, they become a good reference guide. Then, all you need to do is remember where to find those landmarks and look up the specifics of what you are trying to do as you go. This is often how real junior programmers work and you shouldn't be ashamed of doing so too; in fact I'd argue that it is one of the best ways to learn.

My main word of guidance is 'practice'. Practice, practice, practice. You can read through these slides as many times as your heart disires and it is likely most of it will soon be forgotten. Instead, scan through the presentations so you know what tools are available and where to find them and then get straight onto the exercise sheets. If you reach a hurdle, have a look back through the slides. Wash, rinse, repeat and soon you'll by a tidyverse star!

## Getting Started

This course will use an editor called RStudio. You have two options:

1. Download and install first [R](https://www.r-project.org/) and then [RStudio](https://rstudio.com/) on your local machine
2. Sign up for [RStudio Cloud](https://rstudio.cloud/)

I would advise the former if you have install rights on your computer. It is slightly more faffy to setup than the latter option but will be more stable in the long-run. If you have any trouble with this, [give me a shout](#general-help).

## Quick Access to Resources

Below you can find links to the content for each session. Note, that when attempting to download data for a given session, your browser may attempt to open CSVs directly. If this is the case, either right-click and select 'save as' or use `ctrl-S` to save a local copy.

### Session One

* [Presentation](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_one/izzie_session_one_a&b_presentation.pptx)

* [Exercises](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_one/session_1_exercises_izzie.nb.html)

* [Solutions](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_one/session_1_solutions_izzie.nb.html)

### Session Two

* [Presentation](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_two/izzie_session_two_a&b_presentation.pptx)

* [Exercises](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_two/session_2_exercises_izzie.nb.html)

* [Solutions](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_two/session_2_solutions_izzie.nb.html)

* [Data](https://github.com/izzie1234i/into-the-tidyverse/tree/master/resources/session_two/data)

### Session Three

* [Presentation](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_three/izzie_session_three_a&b_presentation.pptx)

* [Exercises](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_three/session_3_exercises_izzie.nb.html)

* [Solutions](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_three/session_3_solutions_izzie.nb.html)

### Session Four

* [Presentation](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_four/izzie_session_four_a&b_presentation.pptx)

* [Exercises](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_four/session_4_exercises_izzie.nb.html)

* [Solutions](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_four/session_4_solutions_izzie.nb.html)

* [Data](https://github.com/izzie1234i/into-the-tidyverse/tree/master/resources/session_four/data)

### Session Five

* [Presentation](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_five/izzie_session_five_a&b_presentation.pptx)

* [Exercises](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_five/session_5_exercises_izzie.nb.html)

* [Solutions](https://izzie1234i.github.io/Into_the_Tidyverse/sessions/session_five/session_5_solutions_izzie.nb.html)

## Help

### Importing Datasets

To import a dataset from this repository, you will first need to download it. You can do this by clicking on one of the data links above. Then select the file of interest. You should then be taken to a page showing a preview of the file. Select `raw` from the top menu. This will open a pure text version of the file. Right-click or use `crtl-S` to save the file to someone on your hard drive.

You can then import this into R by setting your working directory to either the folder containing the file or a directory containing it and then specifying the correct relative path. 

If you are use RStudio cloud, you will need to open the `Files` panel and select `upload` to add the file to your workspace.

### General Help

Please feel free to contact me [here](https://www.linkedin.com/in/isabelle-coates-774500192/) for any questions you may have. 



