Changelog
=========

### Next release: 

- DS for economists: <https://donskerclass.github.io/Forecasting.html>,
  [Data Science for Economists](https://github.com/tyleransom/DScourseS18).
  maybe there should be a review of this type of classes trend. 
- Antiexamples (draft)  

[blogs]: https://trics.me/blogs.html
[textbook]: https://trics.me/textbook/
[tweets]: https://trics.me/tweets.html

#### v.0.0.7 (January 2020)

- [Textbooks][textbook]: @HarryDCrane on [Probability and statistics books](https://trics.me/textbook/preliminaries.html#probability-and-statistics), mml-book by @mpd37, @AnalogAldo, @ChengSoonOng.
- [Blogs][blogs]: @StatModeling [statmodeling](https://statmodeling.stat.columbia.edu/) blog and [videos](https://trics.me/textbook/statistics.html#video)
- ['Teaching at...?'](https://epogrebnyak.github.io/econometrics-navigator/how-to-teach.html#teaching-at): @DinaPomeranz on seminar attitudes
- [Timeless tweets][tweets] by @TedPetrou, @FrnkNlsn, @bencasselman, @JazzArtemis, @stephenaguilar and others.


#### v.0.0.6 (late evening at the very, very end of November 2019):

- Econometrics: [rms by @f2harrell](https://epogrebnyak.github.io/econometrics-navigator/textbook/econometrics.html#biostatistics), @Verbeek
- [Blogs](https://epogrebnyak.github.io/econometrics-navigator/blogs.html): @kaz_yos on clinical/biostat papers 
- Topics: [OLS baby dragons](https://epogrebnyak.github.io/econometrics-navigator/gh-pages/topics/ols.html) by @EpiEllie, @nickchk [LOST](https://epogrebnyak.github.io/econometrics-navigator/gh-pages/topics/index.html), @ahmaurya comment on [ANOVA](https://epogrebnyak.github.io/econometrics-navigator/gh-pages/topics/anova.html), Tesla truck [derivatives](https://epogrebnyak.github.io/econometrics-navigator/topics/derivatives.html)
- ['Teaching at...?'](https://epogrebnyak.github.io/econometrics-navigator/how-to-teach.html#teaching-at): @voxeu on top5 journals and @saragoldrickrab on equity in American education 
- [Math preliniaries](https://epogrebnyak.github.io/econometrics-navigator/textbook/preliminaries.html): Gilbert Strang lin alg lectures (HT @ryxcommar), neural-network math by A.C.C. - Coolen, matrix calculus by @jeremyphoward and Terence Parr (HT @iamtrask)
- [ML/DL](https://epogrebnyak.github.io/econometrics-navigator/textbook/ml-dl.html): puzzles by Boaz Barak and textbook by @michael_nielsen
- [Software-as-a-textbook](https://epogrebnyak.github.io/econometrics-navigator/textbook/ways-into-econometrics.html#econometric-software-manuals): @JASPStats manual

#### v.0.0.5 (November 2019):

- new TOC and flatter stucture
- generated a `rough
pdf <https://github.com/epogrebnyak/econometrics-navigator/blob/master/latex/EconometricsNavigator.pdf>`__
- minimised errors for sphinx builds
- tasks.py for invoke renewed


#### v.0.0.4 (May 2019):   

- Science of teaching: quoting @gvwilson, @nickchk, @AllenDowney, @RochelleTerman at https://tinyurl.com/em-nav-teach
- Data: added data from @stlouisfed/@quandl/@DBnomics along with several R data sources by @nickchk at https://tinyurl.com/em-nav-da
- Books: 

   - `WM Venables. Exegeses on Linear Models <software.html#sas-and-terminology>`__
   - Walpole, Myers, Myers, Ye. Probability and Statistics for Engineers and Scientists


#### v.0.0.3 (April 2019)

Scraps several unfinished articles, including 
a section on applications (hard to fill it quickly). Three main parts
in content established (own articles, textbook annotations and how to 
teach resources).

#### v.0.0.2 (November 2018) 

Original version of EN nobody understood what it is good for,
had sample articles on max likelihood, bootstrap, ANOVA.

Roadmap 
-------

## November 09, 2019

- drafts for cases and excercises
- add more tweets
- add from twitter personalities - links to them
- Section 4 History may go somewhere else
- logit models, tweets about them
- add presentation about reproducibility
- Statistical inference section is still a draft

## May 13, 2019

### General 

-  draw a mindmap for econometrics (as described in text) 
-  put key textbooks on a roadmap
-  pay more attention to bayesian / causality

### Data science textbooks

- [Data Science for Economists](https://github.com/tyleransom/DScourseS18)

### Articles and code

- write more articles and code for the main section
- translate some RATS/MATLAB code to open source (especially time series)

Specific tasks:
- clean ols
- run pca example

### Reproducibility

Add resources on reproducible research and why it has such a poor traction in economics

-  [this - 1](https://github.com/epogrebnyak/notes-pandoc/blob/master/paper.md)
-  [this - 2](https://github.com/epogrebnyak/notes-pandoc) 

DAG tools:

-  waf.io
-  invoke

### How to publish a textbook

Need an opensource textbook with interactive code examples, translation into Russian desired. 
Hard to see a combination of a static site generator, good theme and PDf export working smoothly.

- Allen Downey on Medium
- jupyter-book
- bookdown

### Our publishing process

- things mentioned in [todo.txt](https://github.com/epogrebnyak/econometrics-navigator/blob/master/todo.txt)


### Other goals

- review 'depreciated' folder, and 'history' page
- 'vednorize' [LessOLS.jl](https://github.com/epogrebnyak/LessOLS.jl)