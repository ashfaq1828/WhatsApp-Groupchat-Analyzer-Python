App Link: https://whatsapp-groupchat-analyzer-py.herokuapp.com/


Introduction:

•	WhatsApp it is one of the favorite social media platforms among all of us because of its attractive features. It has more than 2B users worldwide and “According to one survey an average user spends more than 195 minutes per week on WhatsApp”. How terrible the above statement is. Leave all these things and let’s understand what actually WhatsApp analyzer means?
•	WhatsApp Analyzer means we are analyzing our WhatsApp group activities. It tracks our conversation and analyses how much time we are spending or saying it as “wasting” on WhatsApp. The aim of this article is to provide step by step guide to build our own WhatsApp analyzer using python. Here I used different python libraries which help me to extract useful information from raw data.

Required libraries:

•	Regex
•	Pandas
•	Matplotlib
•	Seaborn
•	Date time
•	Emoji
•	Wordcloud
•	Heatmap

Disadvantages of Existing System:

1. Raw data.
2. Time consuming.
3. Difficult to Analyze.
4. Analysis are not accurate.

Proposed System:

•	The “WhatsApp Chat Analyzer” provides a platform to the user which enables user to analyze WhatsApp chats
•	Online on Heroku link. This application allows user to browse WhatsApp exported (.txt) file and import it to
•	WhatsApp chat analyzer and get analysis according to that txt file. And user can analyze by clicking Show
•	Analysis button.

Advantages of WhatsApp Chat Analyzer:

•	Runs on all devices.
•	Shows based on WhatsApp chat file.
•	Shows different visualizations.
•	Total Messages.
•	Total words.
•	Media shared.
•	Link shared.
•	Monthly timeline.
•	Most busy day.
•	Most busy month.
•	Weekly activity.
•	Most busy users.
•	Most used words
•	Emoji analysis.

III. METHODOLOGIES USING TECHNICAL THINKING:

Python:

•	It is a general-purpose programming language. It provide different types of libraries which provides different functionality to project. Python is used for predictions and pattern using test and data. Python consist many libraries which provide mathematical, statistical functions and help to find insights from data.

Pandas:

•	This is an open-source Python libraries which is mainly used in Data Science and machine learning subjects.
•	This library provides analysis tool for data manipulation, using its data structures this are used for analyzing data for manipulating time series analysis and numerical data.

Numpy:

•	Numpy can be name come from Numeric Python, it is a data analysis library for Python that contains various numerical functions and methods for numerical analysis and also having multi-dimensional array objects and to process these arrays contains collection of routines.

IV. ANALYZE METHODOLOGIES BASED UPON MEASURES OR PERFORMANCE:

Matplotlib:

•	Matplotlib is easy to use and an amazing visualizing library in Python. It is built on NumPy arrays and it work with the broader SciPy stack and consists of several plots like pie, line, bar, graph, scatter, histogram, etc. In this project, Matplotlib is used for various visualizations for analysis of WhatsApp chats. Visualizations like bar charts, line charts, pie charts are used.
Seaborn

•	Seaborn is a library mostly used for statistical plotting in Python. To make statistical plots more attractive it provides beautiful color palettes and default styles. In this project, Seaborn is used for heatmap visualization for showing 24 hours with 7 day with different scale of color for getting hour with max to min messages.

Streamlit:

•	In this project, this library is used for creating beautiful web items and objects for representing WhatsApp chat analysis with different types of charts and visualizations on Streamlit.

NLP:

•	In this project, Features of NLP are used like Parsing Text, Eliminating stop words and Analyzing Text. Parsing text is used for splitting messages into words for analysis like total words and mostly used words. A file is used that contains all stop words which is given to the python program to show meaningful words only by eliminating all stop words. Text analysis is used to identify how many media are shared, how many links are shared.
