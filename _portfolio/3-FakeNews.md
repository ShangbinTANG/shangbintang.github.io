---
title: "Are We Reading Fake News?"
excerpt: "Social media information classification during 2020, the year of COVID-19 and election"
layout: single
#classes: wide
header:
  overlay_image: /assets/images/project_collection/fakenews/header_photo_dark2_demo.jpg
  teaser: /assets/images/project_collection/fakenews/TRUE-WC.png
  #overlay_filter: rgba(0, 0, 0, .8)
sidebar:
  - title: "Author"
    text: "Shangbin Tang - Department of Geology and Environmental Science, University of Pittsburgh, Pittsburgh, Pennsylvania, USA" 
  - text: "Chengchen Wang - Joseph M. Katz Graduate School of Business, University of Pittsburgh, Pittsburgh, Pennsylvania, USA"
  - text: "Taylor Herb - School of Computing and Information, University of Pittsburgh, Pittsburgh, Pennsylvania, USA"
  - title: "Role"
    text: "Team Leader, Designer, Data Analyst"
  - title: "Responsibilities"
    text: "Co-developing the project title, technical approach, and workflow. Scrapping the data used in this analysis and performing preliminary data analysis."
gallery1: # Hot words in new titles.
  - url: /assets/images/project_collection/fakenews/dtmclean_1.jpg
    image_path: /assets/images/project_collection/fakenews/dtmclean_1.jpg
    alt: "Hot words in new titles."
gallery2: # Authenticity statistics of the top 10 news sources
  - url: /assets/images/project_collection/fakenews/top10original.jpeg
    image_path: /assets/images/project_collection/fakenews/top10original.jpeg
    alt: "Top 10 news sources (original categories)"
  - url: /assets/images/project_collection/fakenews/top10merge.jpeg
    image_path: assets/images/project_collection/fakenews/top10merge.jpeg
    alt: "Top 10 news sources (merged categories)"
gallery3: #Top 20 sources of true, half-true, and false news
  - url: /assets/images/project_collection/fakenews/Top20TrueAuthor.jpeg
    image_path: /assets/images/project_collection/fakenews/Top20TrueAuthor.jpeg
    alt: "Top 20 true news sources"
  - url: /assets/images/project_collection/fakenews/Top20HalfTrueAuthor.jpeg
    image_path: /assets/images/project_collection/fakenews/Top20HalfTrueAuthor.jpeg
    alt: "Top 20 half-true news sources"
  - url: /assets/images/project_collection/fakenews/Top20FalseAuthor.jpeg
    image_path: /assets/images/project_collection/fakenews/Top20FalseAuthor.jpeg
    alt: "Top 20 false news sources"
gallery4: # Sentiment distribution/trend of hot words in true, half-true, and false news titles
  - url: /assets/images/project_collection/fakenews/Top Hot Words in True Information-Sentiment Analysis3.jpeg
    image_path: /assets/images/project_collection/fakenews/Top Hot Words in True Information-Sentiment Analysis3.jpeg
    alt: "Sentiment analysis - true information"
  - url: /assets/images/project_collection/fakenews/Top Hot Words in Half-true Information-Sentiment Analysis3.jpeg
    image_path: /assets/images/project_collection/fakenews/Top Hot Words in Half-true Information-Sentiment Analysis3.jpeg
    alt: "Sentiment analysis - half-true information"
  - url: /assets/images/project_collection/fakenews/Top Hot Words in False Information-Sentiment Analysis3.jpeg
    image_path: /assets/images/project_collection/fakenews/Top Hot Words in False Information-Sentiment Analysis3.jpeg
    alt: "Sentiment analysis - false information"
gallery5:
  - url: /assets/images/project_collection/fakenews/MarksCountLevel.jpeg
    image_path: /assets/images/project_collection/fakenews/MarksCountLevel.jpeg
    alt: 
  # - url:
  #   image_path:
  #   alt:

---
<p style="color:grey;"><em>Key words: Data Mining, Web Scraping, Machine Learning, Classification, Data Visualization</em></p>
<br>
<br>
Without any doubt, "Fake News" is absolutely one of the hottest high-frequency words on all kinds of social media, especially in 2020, the year of the COVID-19 outbreak, the U.S. presidential election, and a series of hot social events. We scrapped all 2123 fact-checked news on <a href="https://www.politifact.com/"> PolitiFact.com</a> from January to November, 2020. By analyzing the headlines, authors and platforms/occations of these news, we got some interesting findings.

<figure >
	<img src="/assets/images/project_collection/fakenews/DataSource.png"  style="width:75%;margin-left:auto;margin-right:auto" alt="PolitiFact screenshot">
	<figcaption>Data source: <a href="https://www.politifact.com/"> PolitiFact.com</a>.</figcaption>
</figure>


## Coronavirus, people, president...
We built a <a href = "https://en.wikipedia.org/wiki/Document-term_matrix">document term matrix</a> analyze the news title we gathered statistically. The unigrams (one-word sequence) and bigrams (two-word sequence of words) among all collected titles are COVID-19, Joe Biden, Donald Trump, Kamala Harris, people, president... These hot words reflect the topics that received the most attention from the media and the general public in 2020 (January to November).

<!-- <figure>
	<img src="/assets/images/project_collection/fakenews/dtmclean_1.jpg">
	<figcaption>Barplot: Bigrams with the highest frequency; Word clouds: Unigrams with the highest frequency.</figcaption>
</figure> -->
{% include gallery id="gallery1" caption="Hot words in new titles. <br>(barplot: bigrams with the highest frequency; word clouds: unigrams with the highest frequency)" %}

## Which media platforms and individuals are more reliable?
{% include gallery id="gallery2" caption="Authenticity statistics of the top 10 news sources" %}
{% include gallery id="gallery3" caption="Top 20 sources of true, half-true, and false news" %}

## Emotions in news
{% include gallery id="gallery4" caption="Sentiment distribution/trend of hot words in true, half-true, and false news titles" %}