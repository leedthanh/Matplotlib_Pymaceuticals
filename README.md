Using Matplotlib to a analyze real-world situation and dataset.

I used data from Pymaceuticals, Inc to analyze the effectiveness of the drug Capomulin against the other treatments.

Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

Generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen

<img width="859" alt="Screen Shot 2023-08-29 at 2 28 41 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/c203b9d1-1013-4c83-b7f5-d841818185da">

generate a summary statistics table of mean, median, variance, standard deviation.

<img width="447" alt="Screen Shot 2023-08-29 at 2 30 44 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/979707f6-90f4-46ad-a6c4-89354a184b61">

Generate a bar plot showing the total number of rows (Mouse ID/Timepoints) for each drug regimen.

<img width="637" alt="Screen Shot 2023-08-29 at 2 32 07 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/88c3a5ef-1bc2-4f19-a40f-3d284f81ba41">

Generate a pie plot showing the distribution of female versus male mice

<img width="422" alt="Screen Shot 2023-08-29 at 2 32 57 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/d590c05f-c7fb-4cbb-8247-56b0a2f6cb1b">

The tumor volume at the last timepoint

<img width="760" alt="Screen Shot 2023-08-29 at 2 34 42 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/74b2f2c2-f309-4bb1-8f23-11cd942e4165">

box plot that shows the distrubution of the tumor volume for each treatment group.

<img width="629" alt="Screen Shot 2023-08-29 at 2 35 47 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/4e18a92f-ebd2-46db-9b0f-aeb898c51dbf">

A line plot of tumor volume vs. time point for a single mouse treated with Capomulin

<img width="634" alt="Screen Shot 2023-08-29 at 2 37 53 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/16fd934c-9d2b-451c-bd90-3d3fcc359815">

A scatter plot of mouse weight vs. the average observed tumor volume for the entire Capomulin regimen

<img width="607" alt="Screen Shot 2023-08-29 at 2 38 33 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/88ee8d1a-edf9-4b91-8822-f27467c84f95">

The correlation between mouse weight and the average tumor volume is 0.84

<img width="638" alt="Screen Shot 2023-08-29 at 2 39 53 AM" src="https://github.com/leedthanh/Matplotlib_Pymaceuticals/assets/135544908/978d1ee6-10a9-4449-b632-c34900ee82e9">

Analysis

Based on the scatter plot there is a strong correlation between weight and tumor size.  The correlation between mouse weight and the average tumor volume is 0.84.  The bigger the mouse the greater the size of the tumor.  

When running a box and whisker plot I've noticed the effectiveness of Capomulin, Ramicane against tumor volume.  To make sure the drug have the same effects on male and female I did the pie chart to show case the drug distribution among male and female mice.  

Since I noticed the effectiveness of capomulin I ran a line chart to see the progress when using capomulin and the result were reported that during the 20 timepoints to 35 timpepoints the volume of tumor in mouse l509 decrease 8mm.

Inconlusion the two drugs that were affective during this study were capomulin and ramicane with capomulin being the top and most affective drug in decreasing the volume of tumor in mice.  The purpose of this study was to compare the performance of Capomulin against the other treatment regimens and with the data pointing to the effectiveness of Capomulin in decreasing the volume of tumor in mice.

