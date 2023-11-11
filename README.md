# Twitter-Sentiments-Classification
Using Natural Language Processing to classify an individual's belief in climate change based on their tweets.

# Context:
In the face of increasing skepticism towards climate change, companies positioning themselves as environmentally conscious or offering eco-friendly products face challenges without robust market research. To complement ongoing efforts, a Machine Learning model is needed to classify individuals' belief in climate change based on their unique tweet data.

Dataset Description
The collection of this data was funded by a Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo. The dataset aggregates tweets pertaining to climate change collected between Apr 27, 2015 and Feb 21, 2018. In total, 43,943 tweets were collected. Each tweet is labelled as one of 4 classes, which are described below.

# Class Description of the Dataset
[2] News: the tweet links to factual news about climate change

[1] Pro: the tweet supports the belief of man-made climate change

[0] Neutral: the tweet neither supports nor refutes the belief of man-made climate change

[-1] Anti: the tweet does not believe in man-made climate change Variable definitions

# Features
- sentiment: Which class a tweet belongs in (refer to Class Description above)
- message: Tweet body
- tweetid: Twitter unique id

# Expected Outcomes:

- Identify patterns and trends within tweet data.
- Develop a model capable of classifying sentiment towards climate change.
- Construct a user-friendly app for seamless model utilization.
- Present key findings to stakeholders for informed decision-making.

# Tools Utilized:
- Python
- Streamlit
- scikit-learn
- nltk
- Comet
- GitHub
- AWS EC2

# Output:
A comprehensive demonstration of the app, showcasing the developed sentiment classification model and its application to analyze climate change beliefs based on tweet data.
# Demo Video
[![Demo Video](https://img.youtube.com/vi/GlCtb9WSD9U/0.jpg)](https://youtu.be/GlCtb9WSD9U)

Barchart showing the count of sentiments towards climate change in the dataset.
![21](https://github.com/OsinachiEzemba/Twitter-Sentiments-Classification/assets/127313959/91308b88-9e8b-490c-ae44-b17b9cc67a97)

WordCloud for word count of each class
![MATEO Analytics Presentation](https://github.com/OsinachiEzemba/Twitter-Sentiments-Classification/assets/127313959/76bf000c-1cbc-413d-9b2e-837b9217a043)

# Conclusions:
- Overwhelmingly, the majority of Tweets express support for climate change.
- An intriguing observation from the word cloud analysis is the prominence of terms like "climate change" and "global warming," indicating their frequent mention in tweet messages.

# Recommendations:
- Focus on Climate Change Supporters
- Trend-Dependent Word Differentiation:
- Develop a tool to automatically discern words used by climate change believers and skeptics based on current trends.
- Recognize that differences may be trend-dependent and may not persist over longer periods.
- Enable marketers to identify key terms dynamically for targeted messaging to their specific audience.

# Acknowledgements
I would like to thank my team members for their participation and contributions:
- Almoaruf Ajasa 
- Maggie Kalembo
- Opuere Ponuwei
- Esther Akinniyi
- Tise Onadipe






