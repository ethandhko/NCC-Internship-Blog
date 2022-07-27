---
toc: true
layout: post
description: Overview of my five week experience in the NCC Internship program.
categories: [markdown]
title: Five Week Experience
image: images/ncc.jpeg
---

## About

This blog post provides a brief overview of my five week experience in the NCC Internship program.
I provide details of what I achieved each week, and overall takeaways from the experience as a whole.

{% include info.html text="Each week has a seperate presentation to go with it. You can click the title of each week to be redirected to the presentation." %}


## [Week 1](https://docs.google.com/presentation/d/1B1If5Bvh-s6tBPojnhCGpyM8s_lRUj-QWLMT5C5Rnds/edit?usp=sharing)

Now more than ever, `multi-omics data` has become imperative to understanding cancer and its mechanisms. 
Therefore, week 1 was generally spent getting comfortable with the idea of proteomics and multi-omics data along with its implications on modern science.

I spent a majority of my time attempting to understand what this type of data looked like, as I had never been exposed to it before.
It involved a lot of researaching, scrolling through data, and attempting to understand visualizations.

![]({{ site.baseurl }}/images/one.png "cBioPortal Visualization")

---

## [Week 2](https://docs.google.com/presentation/d/1f1P7xcVEUgjvskjVmk88OkLYYI7-0to4qn3xFUEnHmc/edit?usp=sharing)

Week 2 was when I really began diving deeper into data analysis.
Through trial and error, I downloaded the `OmiEmbed` software onto my computer. This software assists with multi-task deep learning of datasets.

The installation process was a lot more difficult than I had expected, as there were many supplementary softwares I needed to download, as well as errors that I ran into. Therefore, to help others in their future OmiEmbed installation endeavors, I created a step-by-step guide on how to install the software on my [Google Site](https://sites.google.com/view/ncc-blog-ethan-ko/home).

After installation, I tested out running the train_test files on my computer, which I was able to produce some visualizations with on TensorBoard.
Mr.Kim was able to teach me more about the importance of train and test files, and its importance for machine learning.
![]({{ site.baseurl }}/images/omi.png "OmiEmbed train_test Visualizations")


I also began to branch out into my own reserach topic which surrounded cancer metastasis in thyroid cancer.
I am currently writing and publishing a research paper on the effect of radiotherapy on distant metastsis in papillary thyroid cancer. 
To connect my internship experience and my writing together, I decided that by engaging in multi-omics data analysis around cancer metastsis in thyroid cancer would be helpful to my research.

---

## [Week 3](https://docs.google.com/presentation/d/10OcXNKOwkRgpm4Dtl4W-p-_doRcUtU3KTCY_ki_K_Cw/edit?usp=sharing)

During Week 3, Mr.Kim gave us the task to engage in exploratory data anlysis for datasets from the PDC and a [Nature article](https://www.nature.com/articles/s41467-022-30342-3).
Firstly, I began to research what exploratory data anlysis was. I learned that it meant to expose yourself to unfamiliar data and attempt to understand it through investigating patterns, anomalies, and testing hypotheses.

To carry out this task, I began to learn how to use `Pandas`. Pandas is an application that assists with data cleaning and manipulation. It also provides efficient visualizations of data.
![]({{ site.baseurl }}/images/visual.png "Pandas Visualizations")

In order to learn and get comfortable with Pandas' numerous commands, I created a Pandas command list that I uploaded in my previous blog, and on my [Google Site](https://sites.google.com/view/ncc-blog-ethan-ko/home).
By learning how to use pandas to analyze data, I was able to spot patterns in data that I presented in my week 3 presentation. Though the analysis wasn't very deep or intricate, it was still a great introduction for me to learn more about exploratory data anlysis and its importance.

## [Week 4](https://docs.google.com/presentation/d/1_Qnu0JGPnFFiXBcDsDZxGLfdcLUV_Oy4YZzJiUuO7dY/edit?usp=sharing)

Mr.Kim gave us the task of uploading datasets from `CPTAC` onto `Omics Playground`.
Omics Playground is a software that creates and displays efficient and clear visualizations for data analysts. 
However, the upload process for Omics Playground is rigorous, requiring sample and counts data in the form of .csv. 
Majority of this week was spent attempting to upload CPTAC datasets to Omics Playground. Eventually, after several forms of data cleaning and editing, I was able to upload the CPTAC Glioblastoma dataset to Omics Playground (see screenshot below).

In addition to uploading the data to Omics Playground, I documented my progress and provided a step-by-step guide to uploading the data on my week 4 presentation and in my [Google Site](https://sites.google.com/view/ncc-blog-ethan-ko/home).

![]({{ site.baseurl }}/images/omics.png "Omics Playground Data")

---

## Week 5

The final week of this internship was arguably the most difficult of all. 

The first task I was given based on Mr.Kim's feedback of week 4's progress was to edit the glioblastoma data to only include positive values, and to upload it to `Omics Playground`. Originally, the mean of the data was set to zero, therefore the data included many negative values.
After changing the values to all be positive, and analyzing the visuals on Omics Playground, I found that the clustered heatmaps of each exhibited drastically different visuals.

![]({{ site.baseurl }}/images/gbm.png "Clustered Heatmaps of Glioblastoma Data")

I noticed that the updated data was much smoother in contrast between the original data that displays jagged changes in blue and red. After doing additional reserach, I was able to find that it is better to have all data values positive, as in some cases it provides more accurate visualizations.

The second task I had was to combine all the CPTAC datasets together and run them through OmiEmbed. This is where I sadly ran into my one and only error of the week: concatenation error.

![]({{ site.baseurl }}/images/error.png "Concatenation Error")

Despite searching through numerous Stack Overflow forums and online tutorials, I wasnt' able to find a solution to this.
Although the internship is ending, I am still determined to get the datasets working and be able to run them through OmiEmbed.

The last and most grueling task I faced was this blog post.
Before this week, I had no idea that blog posts in data science were this complicated to create. 

I am currently using `fastpages` to create this blog. For this post, I am using a markdown format so that I can easily add text and images.
For my Pandas Commands post, I used Jupyter Notebook so that I could display the input and output of the commands for readers. To make the post look cleaner, I used the collapse-output feature so that readers could choose to view the output of the commands if they wished to.

Through numerous tutorials, trial and errors, and hours of confusion, I feel comfortale using fastpages to upload blog posts.
I will definitely be using this template once again if I make another data science blog in the future.

---

## [Overall](https://docs.google.com/presentation/d/1RVoEcTvRu7Cc0Y63KmuHVtyYzm2Cd28j0QBeL_4fhYA/edit?usp=sharing)

Throughout this internship, I have learned numerous new skills that I can translate into other areas of my academics.

## What I learned

Multi-Omics (Week 1)
- I learned the importance of multi-omics in cancer research, and how to read its data.

OmiEmbed (Week 2 ~)
- Importance for machine learning

Exploratory Data Analysis & Pandas (Week 3 ~)
- Practice engaging in exploratory data analysis
- Getting comfortable with Pandas
- Creating my own blog post with Pandas commands using Jupyter Notebook

Omics Playground (Week 4 ~)
- How to upload files to Omics Playground.
- Navigating and understanding visualizations.

Fastpages (Week 5)
- How to create my own repository on Github
- reating my own blog post using markdown and jupyter notebook files.
- Add images, notes, heading, links.

## Key Takeaways

Data Analysis
- Using pandas to edit dataframes
- Using Omics Playground to provide visualizations
- Using OmiEmbed to display train test 

Multi-Omics Understanding
- Reading and understanding research papers and datasets around multi-omics
- Will help me in my quantitative data analysis for my research paper.
- Exposure to lots of different types of data.
- Attempting to understand the data through exploratory analysis.
- Assistance with applications such as Pandas and Omics Playground

## Future Goals

Research Paper
- Engage in quantitative data analysis in my research paper.
- Add visualizations to my paper.
- Will strengthen my claims and findings.

OmiEmbed Running
- Solve roadblock I faced in week 5
- Concatenation of dataframes and upload to OmiEmbed

Machine Learning
- Attempt to understand machine learning at a deeper level.
- Will help me better navigate OmiEmbed for the future.


