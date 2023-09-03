# Novel Analysis to Identify Kurt Vonnegut's "Shape of Stories" Theory and Analyze the Correlation Between Old and New Novels and A.I Generated Novels to Reform the Current A.I Models

This research delves into the realm of narrative analysis, examining the alignment of narratives from different centuries and AI-generated stories with Kurt Vonnegut's renowned "shape of stories" theory. Through the comprehensive analysis of over 120 human-written narratives spanning the 19th, 20th, and 21st centuries, as well as AI-generated novels, this study offers a unique and thorough exploration. Employing sentiment analysis methods, the research scrutinizes the emotional trajectories of these narratives, revealing intriguing insights into their conformity with Vonnegut's narrative patterns. The findings were illuminating. They revealed that Vonnegut's theory holds substantial validity of the narratives analyzed aligning with his proposed shapes of stories. Additionally, AI-generated narratives displayed a considerable degree of conformity to Vonnegut's patterns, but with occasional inconsistencies in emotional trajectories. The research not only contributes to the understanding of narrative structures but also establishes a foundation for training AI to craft advanced and distinct narratives. In this context, AI-generated narratives reveal an ongoing need for human intervention to infuse emotional depth and consistency. This research's findings hold significant implications for literary analysis, storytelling, AI development, and creative writing education, benefiting researchers, writers, educators, and AI developers alike.


## About The content 
--------------------
1. Run the dependency Installation.ipynb which will install all the related libraries and packages for you
2. A simple explanatory analysis of the books has been carried out in EDA.ipynb
3. In each century sentiment analysis has been carried out using NLTK and TextBlob libraries and then the Rolling mean and the Lowes techniques have been used to smooth the sentiment fluctuations. (Analysis with TEXTBLOB2.ipynb , Analysis with TEXTBLOB2.ipynb)
4. A comparison of TextBlob and NLTK can be found in (comparison of Text blob vs NLTK.ipynb)
5. Finally the comparison with Shapes of stories is carried out in Final Analysis Outputs.ipynb


All the Book related to this project has been extracted from https://www.gutenberg.org/

I've used https://github.com/garethbjohnson/gutendex ( a simple, self-hosted web API for serving book catalog information from Project Gutenberg, an online library of free ebooks)
to extract book data from project gutenberg.org

How does it work?
-----------------

Gutendex uses [Django](https://www.djangoproject.com) to download catalog data and serve it in a
simple [JSON](http://json.org) [REST](https://en.wikipedia.org/wiki/Representational_state_transfer)
API.

API
---

When your server is up and running, you should see a home page that says "Gutendex" at the root URL
(e.g. `http://localhost:8000` by default when using `manage.py` to serve on your local machine).

You should run your own server, but you can test queries at [`gutendex.com`](http://gutendex.com).


Project Gutenberg has no such public API of its own, but it publishes nightly archives of
complicated XML files. Gutendex downloads these files, stores their data in a database, and
publishes the data in a simpler format.


## Summary
----------
The lecture linked below Kurt Vonnegut, describes graphing the shapes of stories along two axes.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/oP3c1h8v2ZQ/0.jpg)](https://www.youtube.com/watch?v=oP3c1h8v2ZQ)


<figure>
  ![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/f653195c-b068-479f-860f-624892eec938)
  <figcaption>Cinderella’s Shape of Story </figcaption>
</figure>

<figure>
  ![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/444d6ab5-a968-4244-9820-e2d1059ed26b)
  <figcaption>Boy Meets Girl’s Shape of Story</figcaption>
</figure>

<figure>
 ![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/f3477cfc-1611-454a-b6f8-91f776f48d8d)
  <figcaption>Man in a Hole’s Shape of Story </figcaption>
</figure>

<figure>
 ![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/60809c2a-8938-4d12-9e11-71c7d7a97140)
  <figcaption>New Testament’s Shape of Story </figcaption>
</figure>


## This project has two objectives as mentioned below.
----
**Objective 1- Comparing Old and Modern Novels to Find Similarities:**
Conduct a comprehensive analysis of a diverse range of novels across genres, authors, and historical periods, to extract narrative structures. Kurt Vonnegut's "shape of stories" theory serves as a framework to categorize these diverse story shapes. The comparison between older and modern works aims to identify shifts and patterns in human preferences and storytelling trends. 

**Objective 2 -Analyzing AI-Generated Novels to Perceive Story Shapes:**
Compile a comprehensive dataset of AI-generated novels, including narratives generated by advanced language models like chatGPT to analyze these structures. The goal is to assess how AI-generated narratives align with established story shapes and explore their creative potential. 

## Analyzing the Sentimental Scores in Narratives and Smoothing using Rolling Mean:

![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/03f139fb-a019-4302-be96-ab42dafbd6e7)

![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/78d16896-07a1-4cce-bf76-1a0c29e926f2)

## Analyzing the Sentimental Scores in Narratives and Smoothing using Lowess Technique:

![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/7bfa9f7c-b968-40c4-9712-62946c434b30)

![image](https://github.com/thenukathenabadu/Novel-Analysis-to-Identify-Kurt-Vonnegut-s-Shape-of-Stories-Theory-/assets/18042336/12c40b75-0898-4422-8fe6-50c74afe67e7)







