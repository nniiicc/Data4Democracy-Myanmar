**Data for Democracy Project **

Data for Decision Making Training

*Annotated Instructor Guide *

**Module 4:** Introduction to the Data Lifecycle – Analyzing and Sharing
Data

**Total expected time:** 3 hours

**Objectives: **

-   Understand basic concepts of data lifecycle - including the
    collection, analysis, and sharing of data for decision making

-   Understand key parts of the data analysis process, such as methods,
    cleaning data, coding data, and visualizing data

-   Learn data visualization best practices

-   Learn how to question your data and its integrity

-   Understand how coding data can improve your analysis

-   Learn different ways to share data

-   Learn how to share data with metadata

-   Be able to identify different open-sourced resources for data
    analysis

**Materials: **

-   **Projector**

-   **Computer**

-   **Blackboard/whiteboard (ideally) **

-   **Paper**

-   **Pencils **

-   **Printout of images used **

-   **Activity packet 4.1 **

-   **Activity packet 4.2**

-   **Myanmar election data **

-   **Sample data and metadata from aiddata.org**

-   []{#_gjdgxs .anchor}**Visualization print outs from**
    [*http://paldhous.github.io/ucb/2016/dataviz/week2.html*](http://paldhous.github.io/ucb/2016/dataviz/week2.html)

  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Time           Action                                                                        Instructor Notes
  -------------- ----------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  *10 minutes*   Review                                                                        Welcome the participants back. Review the following concepts. As before, have the participants give their own definitions before providing definitions for the following:
                                                                                               
                                                                                               -   Data life cycle
                                                                                               
                                                                                               -   Data collection
                                                                                               
                                                                                               -   Data analysis
                                                                                               
                                                                                               -   Data sharing
                                                                                               
                                                                                               -   Metadata
                                                                                               
                                                                                               -   Primary data
                                                                                               
                                                                                               -   Secondary data
                                                                                               
                                                                                               -   Methods of data collection
                                                                                               

  *25 minutes*   Activity 4.1: Questioning Your Data                                           See annotated instructor guide for Activity 4.1 for detailed instructions.

  *15 minutes*   Introducing Key Concepts                                                      Reintroduce the following image to the participants by passing it around or projecting it on the screen.
                                                                                               
                                                                                               ![4D-LinearModel.jpg](media/image1.jpg){width="4.181590113735783in" height="1.474278215223097in"}
                                                                                               
                                                                                               After gathering your data (module 3), you unfortunately don’t have a brilliant flash of insight and understand how to solve the problem or answer your original question. In order to make meaning out of your data, you need to analyze your data, which is the next step in the data lifecycle after data collection.
                                                                                               
                                                                                               Remind the class of the following definition for data analysis:
                                                                                               
                                                                                               -   Data analysis: the process of inspecting, cleansing, transforming, and visualizing data with the goal of discovering its useful information, suggesting conclusions, and supporting decision making. *(Exploring Data Analysis, 2017)*
                                                                                               
                                                                                               The following are steps to follow in beginning any data analysis.
                                                                                               
                                                                                               1\. Choosing method for analysis.
                                                                                               
                                                                                               -   This can be thought of as making meaning of the data, or how you will use the data to answer your question or solve your problem.
                                                                                               
                                                                                               -   We want to choose a method that helps us answer our question or our overall goal.
                                                                                               
                                                                                               -   If we want to know, for example, which parties are most represented in state and region parliaments? To answer this we need election results data (including location information), and we probably want to produce this on a map.
                                                                                               
                                                                                               2\. Preparing data for analysis
                                                                                               
                                                                                               -   The next step is to prepare your data for analysis. Often, “raw data” straight from surveys, sensor data, or voter data can be “messy”, meaning it is not ready for analysis. To fix this, you often need to “clean” your data. Ask the participants what they think data cleaning might be. Then, provide the following definition:
                                                                                               
                                                                                               -   Data Cleaning means making sure that data are ready for analysis.
                                                                                               
                                                                                               Data cleaning depends on data type, and the method of analysis. In general, we should consider whether or not they are ready for analysis (e.g. are the values standard?) We can do an initial check on the data by picking some random values, and comparing them. We can also begin to “sort” the data by looking for minimum and maximum values, lists of values. If possible, use a dataset to demonstrate how to sort your data in excel or Google sheets.
                                                                                               
                                                                                               3\. Data Normalization
                                                                                               
                                                                                               -   After cleaning, the next step is data normalization, which means making all values consistent.
                                                                                               
                                                                                               -   This includes ‘0’ vs ‘NA’, using similar scales, using similar decimal points, dates, words, etc. For location data, we also want to initially make sure that all of our data are within the right map and all locations are uniformly named.
                                                                                               

  *20 minutes*   Understanding how to make meaning out of your data – descriptive statistics   Now that the data have been prepared, cleaned, and normalized, the next steps in data analysis is to make meaning out of our data by applying the method of analysis that has already been chosen in order to reach a conclusion. In many ways this is finding and accepting (or rejecting) an answer to our question.
                                                                                               
                                                                                               We will cover three ways of making meaning with data in this workshop:
                                                                                               
                                                                                               -   Descriptive Statistics
                                                                                               
                                                                                               -   Coding qualitative data
                                                                                               
                                                                                               -   Visualization
                                                                                               
                                                                                               First, we’ll begin with descriptive statistics. Ask the class if they have heard of descriptive statistics, or ask if they can think of a definition for descriptive statistics. Then, provide the class with the following definition:
                                                                                               
                                                                                               -   Descriptive statistics are statistics that quantitatively describe or summarize features of a dataset.
                                                                                               
                                                                                               The following are descriptive statistics:
                                                                                               
                                                                                               -   Mean: the average or the norm
                                                                                               
                                                                                               -   Median: the middle value
                                                                                               
                                                                                               -   Mode: the most frequent value
                                                                                               
                                                                                               -   Range: the highest and lowest values in a dataset
                                                                                               
                                                                                               Project these images on the screen or pass it around to the class.
                                                                                               
                                                                                               ![](media/image2.png){width="4.292361111111111in" height="2.988888888888889in"}![](media/image3.png){width="4.303472222222222in" height="3.0in"}
                                                                                               
                                                                                               ![](media/image4.png){width="4.303472222222222in" height="2.9659722222222222in"}
                                                                                               
                                                                                               ![](media/image5.png){width="4.292361111111111in" height="2.954861111111111in"}
                                                                                               
                                                                                               These descriptive statistics act of measure of centrality and can tell us what is typical in our dataset. For example, ask for volunteers to report their age. Write the ages on the board, if possible, and then walk the participants through finding the mean, median, and mode.
                                                                                               
                                                                                               Explain to the participants that these measures of centrality can offer a quick snapshot into the data without having to look at every single value. Pass the following image around or project it on the screen.
                                                                                               
                                                                                                 Question                                                              Statistical Tool
                                                                                                 --------------------------------------------------------------------- --------------------
                                                                                                 Do you want to know how many individuals checked each answer?         Frequency
                                                                                                                                                                       
                                                                                                 Do you want the proportion of people who answered in a certain way?   Percentage
                                                                                                 Do you want the average number or average score?                      Mean
                                                                                                 Do you want the middle value in a range of values or scores?          Median
                                                                                                 Do you want to compare one group to another?                          Cross tab
                                                                                                 Do you want to show how far a value is from the mean?                 Standard deviation
                                                                                               
                                                                                               (Source: [*http://www.uio.no/studier/emner/matnat/ifi/INF4260/h10/undervisningsmateriale/DataAnalysis.pdf*](http://www.uio.no/studier/emner/matnat/ifi/INF4260/h10/undervisningsmateriale/DataAnalysis.pdf))
                                                                                               
                                                                                               The above image represents different tools that you can use to answer questions you may have about your data. This table might be useful in the future as you make meaning of data at your own organizations. Note that we did not discuss all of the tools that are in this table, but these tools are something that you could explore on your own with your own data in the future.
                                                                                               
                                                                                               The next way to make meaning out of your data is to code the data. Ask participants if they have coded data before. Also ask participants if they have an idea what coding is and could provide a definition. Then, provide the following definition:
                                                                                               
                                                                                               -   Coding: a process in which data, in both quantitative form (such as questionnaire results) or qualitative (such as interview transcripts) are categorized to make analysis easier.
                                                                                               
                                                                                               There are several ways coding could be approached.
                                                                                               
                                                                                               -   Iterative Coding (looking for common themes, and patterns in which to group the data)
                                                                                               
                                                                                               -   Card Sorting - show data columns to stakeholders, develop common understanding of data, and select appropriate data to communicate to public
                                                                                               
                                                                                               \*If the above “coding” section is too advanced, there could be a description here that would give more advanced classes the opportunity to go in more depth about iterative coding and card sorting. If a class is less advanced or less familiar with this concept, then the above section can be skipped.\*
                                                                                               
                                                                                               As an example, ask the participants a question such as for what they had for lunch today. Try to get as many answers as possible. Then, let the participants guide “coding” their answers into groups.
                                                                                               
                                                                                               The final step in making meaning out of your data is visualization. Ask the participants why data visualization is important. How can it help in communicating and understanding your data? Underscore to the participants that visualization does not always have to be for an external audience. Often, visualizing your data will also help you as analyst gain a great understanding of the descriptive statistics of the data and how coding can be implemented or improved to make the analysis is easier.
                                                                                               
                                                                                               As an example, using the Myanmar election data set provided, make an in initial chart. Choose an independent (political party) variable for the x-axis and a dependent variable (number of coverage in state and region parliaments) for the y-axis. Does the data look correct? Are we surprised? How can the data be transformed for easier analysis?

  *10 minutes*   Key considerations                                                            Introduce to the participants that there are a few things they should keep in mind throughout the data analysis process. These include:
                                                                                               
                                                                                               There are often many questions that a dataset can answer, and often you will think of more to ask as you continue to analyze your data.
                                                                                               
                                                                                               -   Choose one initial question. Write it down. As new questions emerge, continue to write these down, and only after you’ve answered the initial question should you come back to the “new” questions
                                                                                               
                                                                                               Do I have enough data?
                                                                                               
                                                                                               -   This gets into notions of significance and representativeness of the data. For example, in looking at the age data that were collected in the descriptive statistics example, ask the students, were enough data collected? Do they provide an accurate enough picture of the class? What about of Myanmar as a whole? There are not always correct answers in questioning if you have enough data for it to be significant or representative. However, there are correct ways to report the limitations of any analysis, which can be included in the way the results are reported are shared.
                                                                                               
                                                                                               Do I trust the data that I have?
                                                                                               
                                                                                               -   Who collected these data? How? When were they collected? Is the sample size big enough?
                                                                                               
                                                                                               -   Always communicate how much data or what kind of data were used
                                                                                               
                                                                                               -   Always communicate how you arrived at an answer, and what were the limitations of the data that were used.
                                                                                               

  *35 minutes*   Activity 4.2: Making Meaning with your Data                                   See annotated instructor guide for more information.
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

BREAK 10 MINUTES

  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  *25 minutes*   Providing future resources                                                 The following section of this module provides participants with sample resources surrounding data analysis that they can return to in the future. If using a projector, take time to go to each website and click around, providing commentary with participants about the website’s purpose and how they can use the website in the future. If not, provide screen shots of each source that can be passed around to the participants as the instructor describes each data resource.
                                                                                            
                                                                                            Sample Resources:
                                                                                            
                                                                                            Making Meaning: Quantitative
                                                                                            
                                                                                            -   Easy to use template for Google Sheets: [*https://docs.google.com/spreadsheets/d/1GwAGqhipP6CdeyGuk3dZEl004H8C24JkSMki50lu5kI/template/preview?usp=drive\_web\#*](https://docs.google.com/spreadsheets/d/1GwAGqhipP6CdeyGuk3dZEl004H8C24JkSMki50lu5kI/template/preview?usp=drive_web)
                                                                                            
                                                                                            Making Meaning: Qualitative
                                                                                            
                                                                                            -   Card Sorting Templates: [*http://uxmastery.com/store/card-sorting-analysis-spreadsheet/*](http://uxmastery.com/store/card-sorting-analysis-spreadsheet/)
                                                                                            
                                                                                            -   Qualitative data coding [*http://onlineqda.hud.ac.uk/Intro\_QDA/how\_what\_to\_code.php*](http://onlineqda.hud.ac.uk/Intro_QDA/how_what_to_code.php)
                                                                                            
                                                                                            -   Online (free) tool for coding: [*http://www.dedoose.com/*](http://www.dedoose.com/)
                                                                                            
                                                                                            Making Meaning: Visualization
                                                                                            
                                                                                            -   Basic Principles: [*http://paldhous.github.io/ucb/2016/dataviz/week2.html*](http://paldhous.github.io/ucb/2016/dataviz/week2.html)
                                                                                            
                                                                                            -   Combine Google Sheets and Google Charts: [*https://developers.google.com/chart/*](https://developers.google.com/chart/)   
                                                                                            
                                                                                            -   Tableau Public (free tool) [*https://public.tableau.com/s/*](https://public.tableau.com/s/)
                                                                                            
  -------------- -------------------------------------------------------------------------- ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  *15 minutes*   Understanding key concepts: file types                                     The next part of the module explains how to share data. Remind participants about the importance of sharing data, as discussed in Module 2.
                                                                                            
                                                                                            Knowledge sharing: an activity through which information, skills, expertise is exchanged between people, friends, and organizations. (Bulchandani, Linkedin, 2015)
                                                                                            
                                                                                            Emphasize to the class that knowledge sharing helps create awareness among different organizations, helps facilitate faster solutions and improves response rates, can increase coordination, and can also provide ways for new ideas to be accepted and shared faster.
                                                                                            
                                                                                            Engaging with other organizations allows them to learn from each other. You can share approaches, methods, tools, or instruments with each other. You should try to be as open as possible with sharing your data, your analysis, and your conclusions from that analysis.
                                                                                            
                                                                                            To share your data, you should prepare the data into digital formats that can be easily sharable across organizations. Data should always be put into “open formats”. These include:
                                                                                            
                                                                                            -   Text: .txt; docx
                                                                                            
                                                                                            -   Image: JPEG, PNG
                                                                                            
                                                                                            -   Audio: Mp3
                                                                                            
                                                                                            -   Video: MP4
                                                                                            
                                                                                            Ask the participants if they have used any formats of these files before. If possible, open files on the computer and explore their extensions on a projector.

  *15 minutes*   Understanding key concepts: metadata, publishing, and communicating data   Remind participants about metadata. As before, ask if they can give their own definition of metadata before providing the following:
                                                                                            
                                                                                            -   Metadata: structured information that describes, explains, locates, or otherwise makes it easier to retrieve, use, or manage data. Metadata can also be call data about data, or information about information. (National Information Standards Organization, 2013)
                                                                                            
                                                                                            Metadata are important because it is used to add context to data. Metadata are the key for primary data to be used as secondary data. Metadata can be:
                                                                                            
                                                                                            -   Descriptive Metadata - who created the data, when, where, what kind of data are these, and what topics / subjects do they contain?
                                                                                            
                                                                                            -   Administrative Metadata - how were the data produced, using what methods of data collection, and what instruments?
                                                                                            
                                                                                            -   Rights metadata - Who can use what resource, how , and under what conditions? (how to choose a license:  [*https://choosealicense.com/*](https://choosealicense.com/))
                                                                                            
                                                                                            **Creating documentation **
                                                                                            
                                                                                            If wifi, a computer, and a projector are available, walk the participants through some of the replication data on aiddata.org ([*http://aiddata.org/*](http://aiddata.org/)). If not, take the time to print out some sample datasets along with their metadata for the class to pass around and analyze. Look at each dataset and its metadata: how does he metadata describe the data? How is it administrative? How does it describe rights?
                                                                                            
                                                                                            Also take the time to explain read.me that accompanies a dataset- plain text file that describes dataset or collection of files. Look through some example read.me files as well. Then, provide a discussion for participants surrounding metadata and data within their own organizations. Sample discussion questions include: How can they create metadata so it is easily sharable? How can they use metadata to communicate the purpose of their research to other organizations? Why is metadata and its creation important?
                                                                                            
                                                                                            **Publishing Data**
                                                                                            
                                                                                            Publishing the documentation of your data is an important way to share your data with outside organizations and other governments. You should store your data into repository with long-term preservation plan. This will ensure long-term access to your data and will offer back-up locations for it should the original files become corrupted.
                                                                                            
                                                                                            Below are free services for data archiving:
                                                                                            
                                                                                            Figshare: [*https://figshare.com/*](https://figshare.com/)
                                                                                            
                                                                                            Zenodo: [*https://zenodo.org/*](https://zenodo.org/)

  *15 minutes*   Best practices: Data visualization                                         This final section about data sharing is about communicating the data to appropriate audience.
                                                                                            
                                                                                            Take the time to project the following chart, or pass the image around to participants.
                                                                                            
                                                                                            ![](media/image6.png){width="4.292361111111111in" height="3.1458333333333335in"}
                                                                                            
                                                                                            Walk the participants through the different types of charts, and how they should choose visualization types that will effectively communicate not only their data, but also the question they sought to answer with that data.
                                                                                            
                                                                                            If access to wifi is available, access the following page for more information surrounding different types of visualizations. Of note are the sections from simple comparisons: bars and columns down to composition: change over time. [*http://paldhous.github.io/ucb/2016/dataviz/week2.html*](http://paldhous.github.io/ucb/2016/dataviz/week2.html)
                                                                                            
                                                                                            Other best practices for data visualizations include:
                                                                                            
                                                                                            -   Label all axis
                                                                                            
                                                                                            -   Create a legend that tells viewers what data are being used, and any limitations (e.g.sample size)
                                                                                            
                                                                                            -   Create a descriptive title
                                                                                            
                                                                                            -   Provide a link to the original data, or contact information for the data producer.
                                                                                            

  *5 minutes*    Debrief                                                                    Review with the class that today they learned about the data lifecycle: collecting, analyzing, and sharing their data surrounding a problem or issue that they would like to solve.
                                                                                            
                                                                                            State the tomorrow they will be putting Day 1 and Day 2 together, and will be working on a capstone project that will apply everything they have learned throughout the course. Take the time to answer any questions the participants may have, then dismiss the students for the day.
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
