---
content_type: page
title: Labs
uid: b22eac7a-52c9-f8fa-4222-a9b565dbd459
---

Computers and Software
----------------------

Part of working with quantitative data is becoming comfortable using computers for data analysis. In this class and in the readings you will learn the theories and methods behind statistical analysis, and we will demonstrate how one can do these computations "by hand" with small samples; in an actual planning, policy, and social science situations, these computations—even the creation of simple tables and exploratory plots, to say nothing of statistical tests and regression analysis—would be extremely time consuming without the use of a computer and a statistical software package. As part of the class—although not the primary focus—you are expected to become familiar with the use of a statistical software package.

Our objective in requiring you to use a statistical package stems from the hands-on nature of the class (and the Master of City Planning program in general). By the time you finish the class, you should be able to manage large and small datasets, import them into a software package, and produce descriptive summaries, plots, and inferential analyses (including regression). Beyond this, I hope you will apply and hone the more general purpose skills of a planner in regard to computing: striving to be resourceful in identifying both data and technical assistance; becoming comfortable across platforms and settings; understanding and questioning the assumptions inherent in any analysis you encounter or conduct; and interpreting and presenting the results of your work to a general audience.

In order to encourage and reward this resourcefulness, creativity, and skills for critical assessment, we are giving you a choice as to which statistical package to use. Choosing a statistical program is similar to choosing an operating system or word processor (or bicycle, or other tool): it is as much a matter of personal preference as an evaluation of technical merit. You may choose from the following three options:

Stata
-----

For the past couple years, the Department of Urban Studies and Planning has used Stata in this class (before that it was SPSS). Stata provides a good package to learn on without sacrificing the more powerful tools required by advanced users. Nearly everything can be done either through pull-down menus and dialog boxes (helpful for beginners) or through the command line (good for scripting and advanced users who care about setting different options). Graphics and output are good, import in generally straightforward (with a few quirks around missing values). The package is well-documented and well-supported, two real strengths for beginners. (For more information, visit ![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[Data Analysis and Statistical Software (PDF - 5.4MB)](http://www.stata.com/order/federal-supply-service/GS35F0108W-Rel15.pdf).)

If you decide to use Stata, you will probably want to look at the online documentation, as well as the manual it comes with (Stata Corporation. _Getting Started with Stata for Windows_. Stata Press, 2007). For a more comprehensive introduction, try:

Acock, Alan C. _A Gentle Introduction to Stata_. College Station, TX: Stata Press, 2008. ISBN: 9781597180436.

R
-

R is the open source version of the commercial S and S+ programming language used by many professional statisticians and applied scientists. It is available under the GNU license, with hundreds of additional packages and extensions for free download via the [CRAN Web site](http://cran.r-project.org/). It provides a fully-featured statistical package for data management and manipulation, statistical analysis, scripting, simulation, and graphing (the latter being a real strength). The interface is a little different if you are not used to using the command line for this sort of thing, although there are graphical user interfaces available as well ("GUIs"—windows with menus and that sort of thing).

If you decide to use R, you will probably want to look at the online documentation. For a more thorough introduction, ideal for our context, look at:

Verzani, John. _Using R for introductory Statistics_. Boca Raton, FL: CRC Press, 2005. ISBN: 9781584884507.

Something Else
--------------

Many social scientists do not use either Stata or R—these have been selected as good (and affordable) options to learn on. If you have access to SPSS or SAS, and want to try to work on that, you are free to do so. (Note that Excel is not a suitable alternative—see section below). The only caveat is that we cannot promise to support all of these options; the lab sections will only deal with Stata and R.

Why can't I just use Excel (R)?
-------------------------------

This question always comes up. Excel is a great program for assembling, viewing, and limited manipulation of spreadsheets. Where Excel fails is where it is pushed too far; this tends to be Microsoft's biggest mistake, in my book: they want to make a single giant tool that does everything for everyone and controls 100% of your time (and the market). In contrast, statistical packages (such as those listed above) have been designed around functions specific to the tasks at hand: managing large data sets; conducting complex statistical analyses (with options to control for different assumptions and technical corrections); producing high quality graphical and tabular output; and logging all inputs, commands, options, settings, manipulations, and outputs (necessary to replicate results for true scientific peer review, as well as useful for scripting and "batch" processing of routine projects).

In the same way that most of you would probably choke if asked to use Word to create websites or Publisher to create GIS maps, trying to use a spreadsheet for statistical analysis is overextending the technology, resulting in more work for you and a worse product in the end. You came here to expose yourself to new things and learn about planning technology; here is your chance.

Tutorials
---------

[Resources to help you learn and use Stata](https://www.stata.com/links/resources-for-learning-stata/) - UCLA Academic Technology Services maintains a very good site with tutorials, datasets, and other resources to help you learn Stata.

[Carolina Population Center Stata Tutorial](http://www.cpc.unc.edu/research/tools/data_analysis/statatutorial) - An online tutorial with downloadable dataset to help you learn Stata. One nice thing about this tutorial (as opposed to the hundreds of others out there) is its attention to issues of data management (cleaning datasets, dealing with missing values, transforming data, subsets, renaming variables, etc.).

[Using Excel for Statistical Data Analysis - Caveats](http://people.umass.edu/evagold/excel.html) \- This is a report from the UMass data center evaluating whether or not Excel is up to the task of statistical analysis (they conclude that it is not).

Computer Labs
-------------

| SES # | LAB | SUPPORTING FILES |
| --- | --- | --- |
| Lab 1 | ([PDF]({{< baseurl >}}/resources/mit11_220s09_lab01)) | DATA\_LAB ([ZIP]({{< baseurl >}}/resources/statadata)) (The Zip file contains 3 .raw files, 1 .do file, 20 .dta files, 1 .fix file, 2 .csv files, and 2 .txt files) |
| Lab 2 | ([PDF]({{< baseurl >}}/resources/mit11_220s09_lab2_mar6)) |
| Lab 3 | ([PDF]({{< baseurl >}}/resources/mit11_220s09_lab03_apr3)) | hedonic ([DTA]({{< baseurl >}}/resources/hedonic)) |
| Lab 4 | ([PDF]({{< baseurl >}}/resources/mit11_220s09_lab04_apr24)) |  {{< br >}}{{< br >}} nbawage ([DTA]({{< baseurl >}}/resources/nbawage)) {{< br >}}{{< br >}} nbawage\_dofile ([DO](/courses/urban-studies-and-planning/11-220-quantitative-reasoning-statistical-methods-for-planners-i-spring-2009/labs/nbawage.do)) {{< br >}}{{< br >}}