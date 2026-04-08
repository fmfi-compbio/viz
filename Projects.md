---
title: Projects
---

{% if false %}
Project guidelines will be published later. Basic information can be found in the [course rules](./Rules.html). 
{% endif %}

{% if true %}
* TOC
{:toc}

If any of these guidelines present problems for your project, please consult possible solutions with the instructors.

## Project goals

The project is a key part of this course.

* Unlike homework assignments, where you have a precisely defined task and often hints on how to proceed, in the project you will practice more independent work on data analysis, where you will have to come up with goals and ways to achieve them.
* You will work in groups, so you can learn from each other. 
* You will also practice various aspects of teamwork, such as communication and coordination, creating documentation and so on.
* An important aspect of the project is communicating results in the form of a presentation, a written report and a technical document (notebook), which are also important skills.
* Your progress on the project will be monitored by the instructors, who will be happy to advise you in case of problems.

## Project topics

Below we offer five project topics. You can choose one of them, or propose your own.
For each topic, we list questions that you can explore. These are just ideas, you don't have to explore all of them and you can also come up with others. Connecting data from the listed sources with other data sources is highly encouraged, but focus primarily on the listed tables.

### Beaches

The European Environment Agency publishes a table of bathing water quality at beaches in the European Union ([data](https://sdi.eea.europa.eu/data/30e5d599-6bc1-408d-9e65-a10e433b81ef)). Process this data either at the EU level or for selected countries you are familiar with. You can visualize water quality on maps, track its changes over time, compare different countries or their regions. Does water quality relate to the wealth of a country, the number of tourists visiting it, the density of settlement around a particular location and so on? You can also be inspired by the [official European report](https://www.eea.europa.eu/en/analysis/publications/european-bathing-water-quality-in-2024) and replicate some of its analyses (don't forget to mention the inspiration in your report).


### Streets

The Ministry of the Interior of Slovakia publishes a list of addresses in Slovakia, from which data about all streets can be obtained. What are the most popular street names in Slovakia? Does the popularity of some names differ by region or district? How many different house numbers are there on streets (this might be related to street length)? Do street lengths vary in different cities? Optionally, you can gather and join data about the population of individual cities and examine their relationship with the number and length of streets and the total number of addresses. Popular street names can also be divided into groups, such as Slovak personalities, foreign personalities, dates, cities and others, and their popularity can be examined. The street names can also be analyzed as text and the length of the name or frequently occurring words in the names can be studied. Addresses also include coordinates, so it is possible to calculate and visualize density of addresses in certain areas. <https://data.slovensko.sk/datasety/f2b3af7a-b4d4-45d7-9605-29fa5d7ad115>


### Universities

The Ministry of Education, Research, Development and Youth of Slovakia publishes a register of employees at universities, which contains names of university teachers, their titles, positions at individual faculties and participation in guaranteeing study programs. You can look at the number of teachers at different faculties, their changes over time, teachers who currently work at multiple universities or those who have changed employers.
[Data for download](https://data.slovensko.sk/datasety/f05a7371-420e-4381-99da-a63d50303124), interactive [portal](https://www.portalvs.sk/regzam/) for better orientation in the data.

### Religions

Website Our World in Data has several [analyses of religion](https://ourworldindata.org/religion) for which they provide data for download. You can try to replicate some of their analyses and add your own. Do not forget to mention inspiration for your analyses in your report. Concentrate on the following two data sets: different religions in countries ([data](https://ourworldindata.org/grapher/number-of-people-by-religion.csv?v=1&csvType=full&useColumnShortNames=true), [metadata](https://ourworldindata.org/grapher/number-of-people-by-religion.metadata.json?v=1&csvType=full&useColumnShortNames=true)), importance of religion in countries: ([data](https://ourworldindata.org/grapher/how-important-religion-is-in-your-life.csv?v=1&csvType=full&useColumnShortNames=true), [metadata](https://ourworldindata.org/grapher/how-important-religion-is-in-your-life.metadata.json?v=1&csvType=full&useColumnShortNames=true)). You can combine these with other country indicators such as GDP and fertility. 

### Microbes

The American Gut Project provides data on the presence of various microbes in the human gut and their relationship to various factors such as diet, health, and lifestyle. You can explore the distribution of microbes in different individuals, their co-occurrence, and how they relate to factors such as diet and health. You can try to do simpler versions of the analyses presented in the listed papers (do not forget to mention the inspiration in your report) or come up with your own. This project can be done by both Bioinformatics and Data Science students. 

[Data and their more detailed description](./data/microbes/)


## Project phases

* **Group creation:** Agree on groups of size 3-4 by Wednesday, March 25. One group member will list the group members and the group name in the table published in [Moodle](https://moodle.uniba.sk/mod/url/view.php?id=149879). The name should be short and easy to remember. Students without a group will be distributed into groups by instructors.
* **Topic selection:** Each group will choose a topic by Friday March 27, 9:40. One group member will write the topic name in the [group table](https://moodle.uniba.sk/mod/url/view.php?id=149879). At most 5 groups can work on the same topic, so if 5 other groups have already chosen and signed up for your favorite topic, you must choose another (therefore record the topic in the table as soon as possible). If you want to propose your own topic, you must send a brief description of the topic and available data by email to B. Brejová by Wednesday March 25 so that we can tell you whether the topic is suitable.
* **Group organization:** Agree on how you will communicate within the group, divide tasks, share files and so on. Create a document with project log. Submit a link that allows comments to be added to the log to the appropriate task in [Moodle](https://moodle.uniba.sk/mod/assign/view.php?id=151600) (we will write our progress evaluation there).
* **Progress evaluation:** At each Friday class from April 10 to May 8, there will be a brief meeting of each group with instructors regarding progress on the project. More details see [below](#progress-meetings). Group tasks will no longer be assigned after March 27. We recommend you to work on the project during the remaining class time on Friday.

* **First steps:** Downloading data, their preprocessing to a suitable form, exploring basic characteristics, correcting or removing errors. During the class on April 10, you should already have these activities completed or at least substantial work done.
* **Next stages:** Set a question that can be analyzed in your data and try to answer it with appropriate graphs and tables. Try to find the most suitable visualization and examine visible trends or their exceptions. Gradually work on several such questions. Individual members of the group or subgroups can work in parallel on different questions. Gradually compile materials that you will submit.
* **Project presentations:** Presentations will be held in the week of May 11-15 during the classes on Wednesday and Friday or in another agreed time.
* **Project submission:** The deadline is on Wednesday May 20, 22:00.

### Progress meetings

* Each Friday class from April 10 to May 8, there will be a brief meeting of each group with instructors regarding progress on the project.
* The group has prepared brief notes in their log document regarding the current state (who did what, what are the next plans and whether there are any problems).
* At the beginning of the meeting, open this section of the log and briefly report it. One or more group members can do the report.
* The meeting continues with a discussion with the instructors.
* Have additional files ready so you can quickly show completed or problematic visualizations and tables.
* Be prepared for the meeting so we don't waste time waiting for you to find and open the appropriate files.
* The goal of the meeting is to monitor and evaluate the level of your progress, motivate you in your work and advise you in case of problems.

## Technical requirements

* The project should be written in the Python language. It should work under the Colab environment and primarily use libraries covered in the lectures, although you may use other libraries to a lesser degree.
* Create your own copy of the processed data so that you are not at risk if the data from the source website disappears or changes. If the data requires extensive preprocessing, save also the preprocessed data to a file and continue working with it.
* It will be easy to load the data if you place it on a website, for example, on the faculty server [daVinci](http://davinci.fmph.uniba.sk/) ([guide](http://davinci.fmph.uniba.sk/dokuwiki/howtos/personal-web)) or on GitHub.
* Make as few manual interventions in the data as possible.
* Move repetitive parts of the code into functions that you will use multiple times with different parameters. Similarly, complex calculations should be moved into a function. It is not ideal if several members of the group write similar code and it remains in the final project. You should communicate to prevent such duplications or remove them.
* Colab does not function ideally if multiple users edit the same notebook at once, which can lead to data loss. You can try using a different platform or work on your temporary copies of the notebook and move completed parts of the code to the shared notebook on Colab.

## Using resources

* Keep track of the resources you use (websites, articles, books, etc.) and cite them in your final project. You can find inspiration in existing analyses of your data and replicate or extend these analyses, but you must acknowledge the sources of your inspiration. Also clearly indicate if you have taken large portions of code from any source.
* It is allowed to use editors that support automatic code generation using artificial intelligence. However, the automatically generated code must be thoroughly reviewed, understood, checked and corrected. You are responsible for its quality and correctness. Moreover, during the oral exam we will check whether you can explain and modify your code without using artificial intelligence. If you use AI tools, mention this in your log and among the sources in the notebook.

## Submitting the final project

As the final project, one member of the group submits two files listed below. You shoould continue to make your project log available to us and you should not make any changes to it after the submission date.

### Report

Report is a document that you would submit to the "customer" assigning you the project, explaining your results. It should contain the following sections:

* Header with the project title, list of authors and date
* Table of contents with a list of chapters and links or page numbers (if possible generated automatically)
* Introduction briefly introducing the project topic
* Description of where you obtained the data, how you processed it (whether it was necessary to filter or otherwise modify it) and basic characteristics of the data (for individual used tables, specify the meaning of each column and the number of rows, possibly also other summary statistics). Based on your description, the reader should have a good understanding of what the data looks like without having to download and examine it.
* Results of further analyses (divided into several chapters). For each analysis, briefly describe what you did with the data, include graphs or tables with results, explain what trends and other conclusions you see. When drawing conclusions, be careful not to assume causation from correlation. The text should make it clear which are actual observations and which are your hypotheses. You can compare your results with those from other sources (though this is not required).
* Conclusion with a brief summary of main findings and possibilities for further work.

The report should be written in a formal technical style without grammatical errors, written in Slovak or English. Figures and tables should have captions explaining what is shown in the plot or in the table and should be numbered (figure 1, table 1 etc.). Furthermore, reference each figure and table in the main text ("as shown in figure 1"). If you used any sources during your work, list them in the bibliography at the end of the report (data sources, literature on the subject area). Do not include code or describe technical aspects of the project (how you programmed it) and you do not need to include links to sources directly related to programming. The report is submitted as a pdf file. You can create it as a Google doc or in another system (for example Latex).

If you want to see examples of a formal technical text with numbered figures and tables, you can look at the [proceedings of the Students' Science Conference](https://zona.fmph.uniba.sk/fileadmin/fmfi/studentska_vedecka_konferencia/zbierka2025/svk2025_zbornik.pdf). However, your reports probably won't have so much mathematics, you will likely cite websites rather than scientific publications, and you also don't have to format the report into two columns.

We also provide a sample [report template](https://docs.google.com/document/d/1BKmmjGd8X594S5bK9uMwl3LV271EH0UOjone0eWMTzY/edit?usp=sharing) as a Google doc, from which you can start if you wish.

The report text should be written by you. Do not generate text with artificial intelligence or copy it from other sources. You can use AI tools for grammar and style checking. Always carefully review any suggested changes to ensure they don't alter the intended meaning of the text.


### Source code

You should [submit](https://moodle.uniba.sk/mod/assign/view.php?id=151604) the source code of your projct in the form of a Jupyter notebook, containing the entire analysis including  data loading, their preprocessing to the rendering of final graphs used in the report. The entire code should be executable in Colab. If some part of the data preprocessing is not practical to do in the notebook, state this in the notebook and describe the preprocessing process there, or submit relevant code in a separate file. The notebook should contain headers characterizing individual parts of the analysis and brief descriptions of individual parts of the code. Also include links (URL) to used sources, especially if you copied code from them (including AI tools).

Notebook should load data from some URL, where you will store it either in the original or preprocessed form, see [Technical requirements](#technical-requirements). On the oral exam, it will be necessary for you to be able to run and modify the notebook on a computer in I-H6 or another classroom.

### Project log

Write the project log in the document provided in [Moodle](https://moodle.uniba.sk/mod/assign/view.php?id=151600), from which you will create a copy.

At the beginning of the log, specify the group name, list of members, and the project topic.

The log should be updated regularly and divided into chapters, each with a brief description of the goal, participants, and dates when the analysis was performed. In the body of each chapter, briefly describe what you did, how you did it, any problems that arose, and whether they were resolved. Also include a description of work that ultimately did not lead to successful graphs used in the report.

The log should also contain preparation for progress meetings with instructors and  summaries from such meetings. Also write notes from additional group meetings - what steps and task division was agreed upon.

The project log serves for instructors to monitor your progress. But it also serves for you. It will help you to keep track of what is happening in the group, what was agreed upon at meetings and refresh your memory when writing the final report.

It is a good practice to maintain such notes, especially for larger data analysis projects, as you may not remember all the details from the beginning by the end of the project. This also helps with coordination within the group.

At the end of the log, write a brief overview of contributions of each member of the group.

## Presentation

* Each group will create a single common presentation, which should last at most **12 minutes** for 3-person groups and at most **15 minutes** for 4-person groups.
* In the presentation, all members of the group will take turns. Each member will present for **at least 2 minutes**.
* Your presentation should have the following sections:
  * Introduction to the topic, description of the data
  * Summary of main results appropriate for the "customer" (examples of graphs and their descriptions)
  * Examples of interesting technical aspects of the project appropriate for fellow programmers, what you learned, what was difficult.
* Practice your presentation in advance, especially the transitions between speakers and the overall duration.
* The entire presentation must be in a **single pdf file**, with one member of the group submitting it to [Moodle](https://moodle.uniba.sk/mod/assign/view.php?id=151608) at least 30 minutes before the start of presentations on a given day, from where the instructors will upload it to the presentation computer.
  * If you need animations or other elements that don't work in pdf, you can present from your own computer. In this case you must meet the following conditions:
    * The entire group must present from one file and computer to eliminate delays.
    * Check the connection of your computer to the projector in advance in the appropriate classroom (F1-108 or I-H6).
    * Submit a pdf with at least partial functionality as a backup for the case of technical problems. 
* Each group will also attend as an audience at all presentations on the given day (Wednesday or Friday), but if you want, you can come to see all presentations.
* After each presentation there will be a short discussion, and we welcome your questions.

## Evaluation

According to the [course rules](./Rules.html), you can earn up to 55% of the grade from activities related to the project.
* After each progress meeting, points will be awarded for ongoing work on the project, totaling 12%.
  * Each member of the group should participate in some work on the project during the week, even if it is not completed. In case of special circumstances, please let us know.
* The final presentation is worth 8%.
* The final evaluation of the submitted project is worth 20%.
* Individual oral exam related to the project is 15%, you need to score at least half the points.

{% endif %}
