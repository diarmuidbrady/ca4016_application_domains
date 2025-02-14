# CA4016 Personal Data Analysis
As part of my final year module Application Domains 2, I carried out a data science project. I gathered my own data and created meaningful insights from it.

## Key Insights
- I predicted my self-reported Mood (binary variable, Happy/Sad) using exercise, lifestyle, and sleep factors. I found *“Time with Friends”* to be the highest predictor of happiness and *“Time on Phone”* to be the key predictor of sadness.
- During analysis, I **found significant differences** in sleep measurements between SleepScore and Fitbit.
- I predicted the “SleepScore” metric from the SleepScore App using Fitbit Sleep data with high accuracy **(within 2.23 points on a 100-point SleepScore scale)**.

## Data Sources
I gathered data from several sources including:

- SleepScore data
- Fitbit data
- CBT Thought Diary data

### SleepScore Data
This data was requested from the Data Science team at SleepScore Labs 30/09/2022 to 25/11/2022 and was sent through email.
It includes both sleep metrics (Total Sleep Time, Sleep Onset Latency etc.) and sleep related factors logged eg. Caffeine, Alcohol, Sleepiness, Mood and Stress.

### Fitbit Data
This data was exported from Fitbit from 30/09/2022 to 25/11/2022 and saved locally.
It includes both activity (Steps, Heart rate, Activity Minutes etc.) and Sleep tracking data (Total Sleep Time, Wakefulness After Sleep Onset).

### CBT Thought Diary Data
This was exported in bulk as a text file from the phone app and saved to iCloud storage.

Data is not present on GitHub for data privacy.

## Directories
There are a number of directories, each with a specific purpose.

### Deliverables
Contains the LaTex report documenting the project along with the bibtex file containing citations to support the document.

### Environments
This includes a yml environment file and is used to set up the environment with all relevant libraries and packages.

### Models
Includes several models used in the analysis for prediction tasks.

### Notebooks
All the notebooks used for data importing, cleaning, processing, engineering, analysing, modelling, and visualising are stored here.

### Specification
Contains the specification for the project assigned by our lecturer Dr.Cathal Gurrin.

### Visuals
All visuals outputted from Jupyter Notebook have been saved here.
