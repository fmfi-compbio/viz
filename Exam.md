---
title: Exam
---

{% if false %}
Pokyny ku skúške upresníme neskôr. Základné informácie viď [pravidlá predmetu](./Rules.html). 
{% endif %}

{% if true %}
* TOC
{:toc}

## Oral exam

* **Suggested dates - any conflicts?**
  * Tuesday June 2 and Thursday June 4, morning and afternoon
  * Each half-day has a limit of 10 students, total duration approximately 2.5 hours, the approximate schedule will be known
  * Sign up in AIS from Thursday April 30 18:00
  
* Upon arrival in the computer room, open your group's project on the school computer (Windows or Linux), ensure you can run it, and make a copy that you will modify. Turn off AI assistants.
* We will discuss your project, and you will be given a task to improve or change something in it.
* You can search in lectures and tasks, in online documentation or existing discussions on the internet, you can also bring paper materials.
* It is forbidden to communicate with other people and use artificial intelligence tools, as well as other hardware except the school computer (as a backup for the case of major technical problems, we recommend bringing your own laptop).
* Used resources should remain open in the browser.
* We may also ask you about your homeworks or group tasks.
* The weight of the exam is 15%, but you must at least achieve half of the points, otherwise Fx. Based on the oral exam, we may also change your points from the project/tasks, if we find out that your contribution to the group work was not sufficient or that you do not understand the submitted work.
* Remedial exams will be scheduled later, after discussion with those who need them. There will be at most two additional dates.


## Final test

* The only regular test date **Friday June 5, 9:30**. Some conflicts with other exams?
  * Remedial exams will be scheduled later, after discussion with those who need them. There will be at most two additional dates.
* Bring your pens/pencils and ISIC.
* It is not allowed: any papers, electronic devices, communication with other people except the instructors
* Write in the space reserved for each question, request additional paper if needed
* Write clearly, illegible answers will be graded with 0 points
* Test duration 60-90 minutes (will be announced at the beginning of the test)
* Questions will be in Slovak, some terms will be given also in English for clarity
  * You can request questions in English before may 22 10pm using this form: <https://forms.office.com/e/SV3A4xth2E>
  * You can write your answers in Slovak or English
* To pass this course, you must score at least 50% of the points from the test
* The list below contains the terms you should know (for each term: definition, if given, intuitive meaning, advantages/disadvantages etc.)
* There is also a list of commands from the pandas/matplotlib/seaborn libraries and their parameters that you should know
* If we use other commands from these libraries, they will be explained in the question text
* Examples of question types:
  * simple questions on knowledge/comprehension (similar to some quiz questions)
  * what would this code output for this input? 
  * how to complete the code so that it does xyz? (for example adding a few commands, not writing a whole longer code)
  * discuss the plot with regard to some aspects covered in the course
  * propose how you would visualize a certain type of data

## Test syllabus

### L01b Matplotlib

* `figure,axes = plt.subplots(nrows, ncols, sharex, sharey)`
* `axes.plot(x, y, fmt, label)` (`fmt` options `'.'`, `'-'`, `'.-'`)

### L02 Pandas

* `df = pd.DataFrame({'col1_name':col1_data,...})`
* `df.iloc[1,2]`
* `df.iloc[[0, 2, 3], 0:2]`
* `df.iloc[[True, False, True, True], :)`
* `df.sort_values(column, inplace)`
* `df.copy()`
* `df.set_index()`
* `df.reset_index()`
* `df.loc[]`
* `series1 + series2`, `series + number`, similarly `-`, `/`, `*`, `>` etc.
* `df.query(...)`
* wide vs. long table

### L03 Plot types, matplotlib, seaborn

* Types of variables: categorical / qualitative vs numerical / quantitative; nominal, ordinal, discrete, continuous, ratio, interval
* Different plot types (what types variables to use it for, advantages, disadvantages)
  * scatterplot (additional variable as color, size, shape; use of log axes)
  * line graph
  * area graph
  * small multiples
  * bar graph (horizontal/vertical, additional variable as color, stacked)
  * dot plot
  * heatmap
  * pie chart
  * strip plot
  * histogram
  * parallel coordinates
  * parallel categories
  * radar chart
* `sns.scatterplot(data, x, y, hue, size, col)`
* `sns.barplot(data, x, y, hue)`

### L04 Summary statistic

* For each statistic: definition, intuive meaning, properties
* Measures of central tendency: mean, median, mode
* Quantiles, percentiles and quartiles
* Measures of variability: minimum, maximum, interquartile range, variance and standard deviation
* Tukey's definition of outliers using IQR
* Boxplot
* Summary statistics under linear transformation of the variable
* Pearson correlation coefficient
* Spearman’s rank correlation coeﬀicient
* Correlation does not imply causation
* Computation in Pandas:
  * `series.mean()`, `series.median()`, `series.mode()`
  * `series.quantile([p0,...,pn])`, linear interpolation
  * `series.min()`, `series.max()`, `series.std()`
  
### L05 Pandas 2

* `pd.merge(df1, df2, on)` (with default inner join)
* split-apply-combine strategy, apply as aggregation, transformation, filtering
* `df.groupby(column)[column_selection].aggregation_function()` with aggregation functions `size()`, `count()`, `sum()`, `mean()`, `median()`, `min()`, `max()`, `describe()`
* `df.groupby(column)[column_selection].transform(function)`
* `df.groupby(column)[column_selection].filter(function)`
* Missing values as `np.nan`

### L06 Maps, graphs, time series

* Map projections: conformal / equal-area
* Thematic maps
* Data as points or lines in a map
* Isarithmic maps / isoline maps / heatmaps
* Choropleth maps, spatially extensive/intensive variables
* Graph terminology (vertices, edges, tree), basics of graph drawing
* Time series: smoothing with aggregation and sliding window, overlapping timescales, uncertainty and missing values

### L07 More statistics

* Histograms (which properties of data they show, choice of bins, comparing several distributions)
* Probability density function (and its relation to histograms)
* Kernel density estimation (how it is constructed, how it is used, bandwidth)
* Violin plot
* Two-dimensional histograms / KDE
* Cumulative distribution function (definition, properties)
* Empirical cumulative distribution function (definition, properties, use for visualization)
* Clustering (intuitive meaning, use for improving heatmaps)
* Dimensionality reduction (intuitive meaning, use for visualizing high-dimensional data)

### L08 Visual perception and colors

* Light as a mixture of wavelengths
* Human eye: retina, photoreceptors, cones and rods, cones with three wavelengths
* Foveal vs peripheral vision
* Metamers, LMS color space
* Additive color models, RGB, HSL, HSV
* Subtractive color models, CMY(K)
* Color wheel, RYB model, primary and secondary colors, complementary color scheme
* Issues to consider in visualization (color blindess, technical limitations, use for highlighting)
* Palettes in visualization: qualitative, quantitative sequential, quantitative diverging
* Raster vs vector image formats
* Data analysis project phases, exploratory vs explanatory visualization

### L09 Text, visual perception (2)

* Text visualization: word clouds vs other techniques for showing word frequencies
* Pre-attentive attributes and their use in visualization
* Hierarchy of graph elements for quantitative reasoning
* Gestalt principles of proximity, similarity, connection, enclosure, closure, continuity and their use in visualization
* Illusions
* Working memory
* Chart junk

### L10 Presentation of results

* Context of a presentation
* Storytelling in a presentation
* Cognitive biases, patternicity bias, storytelling bias, conformation bias
* Aspects of visualization: basic setup, data transformations and other settings, focus and explatation
* Table vs plot
* Interactivity, which aspects of a plot can be interactive
* Dashboard (what it is)

### L11 Interactivity, other types of plots

* Infographics vs data visualization
* Other types of graphs: waterfall chart, funnel chart, Gannt chart, candlestick chart

{% endif %}