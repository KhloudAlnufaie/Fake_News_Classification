# Fake News Classification using BERT


---
This is a college project required for a Deep Learning course.<br>
It is done as teamwork by Khloud Alnufaie, Raghad Albosais and Weaam Alghaith.

---

### Project overview

In recent years, the growth of online social media has greatly facilitated communication among
people. Online social media allows users to share information, connect with others, and stay
updated on current news. The news can be presented in different formats in social media, such as
articles. In the articles, the information is provided in a more formal way, which makes it more
suitable for world, politics, and government news. While these articles are being shared on social
media every day, it is not always credible, and some of it has been designed to mislead. Fake
news is often used to describe such content. Fake news “is fabricated information that mimics
news media content in form but…lack(s) the news media’s editorial norms and processes for
ensuring the accuracy and credibility of information”. It overlaps with misinformation (false or
misleading information) and disinformation (false information purposely spread to mislead
people). One example of sophisticated fake news is “deepfakes”. Deepfakes are fictional videos
or images or text with either well-known or made-up people doing, or saying, things that are not
real. This is created using artificial intelligence and machine learning.

The presence of large amounts of fake news online can have a serious impact on individuals and
society. fake news can have devastating effects on democracy if people can no longer distinguish
between what information is real and what is fake, and what sources are legitimate or not. This
makes it easier to feed people with propaganda, discredit and undermine the truth and create
chaos. Thus, in this project, we aim to build an accurate DL-model to detect and classify articles as fake and news. 

---

### Data description

ISOT Fake News Dataset includes both fake and real news articles. This dataset is collected and
provided in this IOST research lab [here] (https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/) . Articles were retrieved by crawling Reuters.com (News
website) for truthful articles. Several sources were used to collect the fake news articles. It is
important to note that the fake news articles were gathered from unreliable websites that were
flagged by Politifact (a fact-checking organization in the United States) and Wikipedia. Various
types of articles are included in the dataset. Nevertheless, most articles cover political and world
news topics.

---

### Proposed architecture

![Model architecture]()

We use the title and content of the articles as input to our model, instead of using only the title or only the content. Because we want to preserve the
important terms that help to make the final decision. For preprocessing step, we perform a
cleaning processing (punctuation marks removal) for fake sets only in order to remove unhelpful
parts of the data, or noise and keep only the words. In addition, we perform linguistics processing
(tokenization) for both sets in order to make it in suitable format for the feature extractor (BERT). 

---

### Tools

- Libraries: 

![Pandas](https://img.shields.io/badge/pandas-330F63??style=flat&logo=pandas&logoColor=white)
![openCV](https://img.shields.io/badge/openCV-%23F7931E.svg??style=flat&logo=openCV&logoColor=black&color=9cf)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg??style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg??style=flat&logo=scikit-learn&logoColor=white)
![keras](https://img.shields.io/badge/keras-%23000.svg??style=flat&logo=keras&logoColor=white&color=red)
![tensorflow](https://img.shields.io/badge/tensorflow-%23000.svg??style=flat&logo=tensorflow&logoColor=white&color=green)
![seaborn](https://img.shields.io/badge/seaborn-%2006600.svg??style=flat&color=blue)
![matplotlib](https://img.shields.io/badge/matplotlib-%233F4F75.svg??style=flat&&logo=matplotlib&color=yellow)


- Softwares: 

![Google colab](https://img.shields.io/badge/Googlel%20Colab-0078d7.svg??style=flat&logo=google-colab&logoColor=orang)

---

### Running the project
The whole project is located in the jupyter notebook file ``` BERT_Classification_model_for_classifiy_Fake_News.ipynb ``` and , you can use the Anaconda environment to open the Jupyter Notebook and install the requirement.


---

### Contributors

[@hkh7897](https://github.com/hkh7897)

[@RaghadKhaled](https://github.com/RaghadKhaled)

[@Weaam20](https://github.com/Weaam20)
