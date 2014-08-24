# STAT 545A Exploratory Data Analysis and STAT 547M Basic Training for Data Science

## Basic facts

|          | STAT 545A                       | STAT547M                        |
|----------|---------------------------------|---------------------------------|
| title    | Exploratory Data Analysis       | Basic Training for Data Science |
| SSC link | [STAT 545A][SSC 545A]           | [STAT 547M][SSC 547M]           |
| credits  | 1.5                             | 1.5                             |
| dates    | Sep 02, 2014 to Oct 19, 2014    | Oct 20, 2014 to Nov 28, 2014    |
| meets    | Mon Wed 9:30 - 11am             | Mon Wed 9:30 - 11am             |
| where    | [GEOG 200][geog200] (new!)      | [GEOG 200][geog200] (new!)      |
| pre-req  | none (but see below)            | STAT 545A                       |

[esb1042]: http://www.maps.ubc.ca/?225
[geog200]: http://www.students.ubc.ca/classroomservices/buildings-and-classrooms/?code=GEOG&room=200
[SSC 545A]: https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=5&dept=STAT&course=545A&section=101
[SSC 547M]: https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=5&dept=STAT&course=547M&section=101

Instructor: [Jennifer (Jenny) Bryan][jb], <jenny@stat.ubc.ca>  
TA: Dean Attali (STAT 545A)  
Other assistance from Shaun Jackman, Bernhard Konrad, Julia Gustavsen

[jb]: http://www.stat.ubc.ca/~jenny/

## What's up with the two half courses?

For several years, I have taught STAT 545A as a 1.5 credit course. I -- and many students -- have felt there was alot of great, relevant content that could go into an additional 1.5 credits.

Therefore, in 2014/2015, we will pilot a full semester on data exploration, visualization, and all-around data wrangling. It is structured as two half courses for various reasons, such as allowing STAT 545A alums to register for STAT 547M and get the "missing half" of the course!

### FAQ re: two half courses

  * I have taken STAT 545A for 1.5 credits in the past. Can I take STAT 547M?
    - YES. But you will want to follow along during STAT 545A (at least online), so you get some new content. Examples: the use of Git for version control, GitHub for collaboration, `knitr` and R Markdown for dynamic documents, `ggplot2` for graphics, `plyr` and `dplyr` for data aggregation.
  * Can I just take the second half, i.e. STAT 547M?
    - NO, not unless you have taken STAT 545A previously.
  * Can I take just the first half, i.e. STAT 545A?
    - YES. But development is proceeding with the ultimate goal of creating a full 3 credit course. I will try to make each half stand alone reasonably well, but that is not my top priority.
  * What do you advise I do?
    - Take STAT 545A and STAT 547M.

## Course description

This course has three intertwined goals;

* Introduce students to
  [R, a free software environment for statistical computing and graphics](http://www.r-project.org/),
  and put them on the fast track to becoming power useRs!

* Develop students' *practical* skills in exploring, grooming, visualizing, and analyzing datasets. Cultivate complementary skills in making analyses reproducible, reusable, and shareable. *Heavy emphasis* on data manipulation, making figures, and report generation, especially for the web.

* Expose students to data analytical approaches that exemplify modern statistical practice. Expose students to statistical methods ranging from core techniques (description and exploration, linear models) to more modern and flexible techniques (resampling / bootstrap, smoothing, robust statistics).

Knowledge and skills from this course may be useful to incoming graduate students as preparation for Research Assistant work and for MSc/PhD thesis projects.

To see content from 2013, go here:

  * [Clean index](http://www.stat.ubc.ca/~jenny/STAT545A/quick-index.html) into topics covered in 2013
  * [Full course website](http://www.stat.ubc.ca/~jenny/STAT545A/current.html) from 2013
  * [GitHub repository](https://github.com/jennybc/STAT545A_2013) for 2013 course materials

__AUDIENCE__. This course is open to any graduate student at UBC. Students from other departments generally outnumber those from Statistics.

__TEXTBOOK__.  None. We will use online resources and eBooks available through the UBC site licenses. See influential books in the references below.

__PREREQUISITE__.  None. However, most students will have had at least one prior statistics course. __If you have never programmed or worked at the command line before, prepare for a shock.__ This will be a powerful, positive experience for you but it's a big adjustment. The most successful students are often grad students from other fields who need to analyze and visualize data for a thesis. They are highly motivated and excel.

__COMPUTER__. Class meetings will be a mix of lecture, discussion, and live coding. Students will get the most out of this if they can bring their own laptop to class every day. If we stick with ESB 1042 as our location, students can use the computers in this lab. But the room is quite small and we may try to change.

__EVALUATION__

*Under development. The plan is to have small-to-medium units of work spread out fairly evenly. The end result may still resemble a "final project", but one that has been built up gradually over the term. Expect some peer evaluation.*

## Syllabus

*2014-07-15: Under active development!*

Topics traditionally covered in STAT 545A, with light updating:

  * Introduction to R and the [RStudio IDE](http://www.rstudio.com/products/rstudio/)
  * R scripts and workspaces, RStudio Projects; how to get your work done
  * Creating reports from R scripts and [R Markdown](http://rmarkdown.rstudio.com), using [`knitr`](http://yihui.name/knitr/)
  * Deep thoughts about data analytic work
  * Care and feeding of data in R; data frames
  * R objects -- beyond data frames
  * Indexing, subsetting
  * Data aggregation; "apply" functions, [`plyr`](http://plyr.had.co.nz), [`dplyr`](https://github.com/hadley/dplyr)
  * How to help yourself, how to ask questions to get useful answers
  * How to get data in and out of R, staying as "open" as possible
  * How to get figures out of R
  * Be the boss of your factors, i.e. categorical variables
  * Use of color in R
  * Single quantitative variable: visualizations and descriptive statistics
  * Two quantitative variables: visualizations and descriptive statistics
  * Categorical variables: visualizations and descriptive statistics
  * Multivariate visualizations
  * Visualizing and summarizing data when "grouped"
  * Coding style and project organization
  
New topics for STAT 545A and/or STAT 547M will be selected from here:

  * Bash shell / unix basics, personal system administration.
  * Version control with Git, collaboration via [GitHub](https://github.com)
  * The tabular data mentality, "tidy" data, data reshaping
  * Regular expressions, programmatic transformation and searching of character data
  * Writing R functions
  * `ggplot2` will be used instead of `lattice` for visualization
  * Creating interactive pages, apps, and graphics via [Shiny](http://shiny.rstudio.com) and (maybe) [`ggvis`](http://ggvis.rstudio.com)
  * Unit testing, at least as a mentality. Maybe will cover formal unit testing, e.g. `testthat`
  * Stats particularly useful in exploration (and often neglected in standard intro stats courses)
    - robust summary statistics
    - robust regression
    - smoothing
    - density estimation
    - cluster analysis, PCA, SVD, MDS
  * Embrace the web:
    - getting data from the web, e.g. using an API or via scraping
    - exposing your hard work on the web (data, code, results)
  * Distributing data and code to the world via an R package
  * Automating an analytical pipeline, e.g. via `Make`.

## Indicative and influential resources

  * [Bad Data Handbook](http://shop.oreilly.com/product/0636920024422.do) by By Q. Ethan McCallum, published by O'Reilly. *"In short, Bad Data is data that gets in the way."*
  * [Creating More Effective Graphs](http://www.amazon.com/Creating-Effective-Graphs-Naomi-Robbins/dp/0985911123) by Naomi B. Robbins
  * Grammar of graphics, as implemented in R by Hadley Wickham, Winston Chang, and others.
    - [`ggplot2` package web home](http://ggplot2.org) | [online docs](http://docs.ggplot2.org/current/) especially nice
    - `ggplot2`: Elegant Graphics for Data Analysis [book available via SpringerLink](http://ezproxy.library.ubc.ca/login?url=http://link.springer.com.ezproxy.library.ubc.ca/book/10.1007/978-0-387-98141-3/page/1) by Hadley Wickham, Springer (2009) | [author's website for the book](http://ggplot2.org/book/), including all the code
    - [`ggvis` package](http://ggvis.rstudio.com) | [on GitHub](https://github.com/rstudio/ggvis)
  * [Dynamic documents with R and knitr](http://www.crcpress.com/product/isbn/9781482203530) by Yihui Xie, part of the CRC Press / Chapman & Hall R Series (2013). ISBN: 9781482203530. *No online access (yet?).*
  * [Reproducible Research with R & RStudio](http://www.crcpress.com/product/isbn/9781466572843) by Christopher Gandrud, part of the CRC Press / Chapman & Hall R Series (2013). ISBN: 978-1466572843 | [Book website](http://christophergandrud.github.io/RepResR-RStudio/) | [Examples and code](https://github.com/christophergandrud/Rep-Res-Examples) | [Book source](https://github.com/christophergandrud/Rep-Res-Book). *No online access (yet?).*
  * [Rmarkdown](http://rmarkdown.rstudio.com) is "an authoring format that enables easy creation of dynamic documents, presentations, and reports from R."
  * [Practical Data Science With R](http://www.manning.com/zumel/) by Nina Zumel and John Mount, published by Manning.
  * Tidy data
    - Nine simple ways to make it easier to (re)use your data by EP White, E Baldridge, ZT Brym, KJ Locey, DJ McGlinn, SR Supp. *Ideas in Ecology and Evolution* 6(2): 1–10, 2013. doi:10.4033/iee.2013.6b.6.f <http://library.queensu.ca/ojs/index.php/IEE/article/view/4608>
    - Tidy data by Hadley Wickham. Preprint available <http://vita.had.co.nz/papers/tidy-data.pdf>.  [`tidyr`](https://github.com/hadley/tidyr) is an emerging R package that help to tidy data.


