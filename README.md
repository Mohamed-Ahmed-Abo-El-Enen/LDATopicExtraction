<div align="center">
  <h3 align="center">LDA Topic Extraction</h3>
  <p align="center">
    NLP Topic Extraction Task using LDA
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#Running">Running</a>
    </li>
    <li>
      <a href="#Future Work">Future Work</a>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

NLP Task With 3 Notebook To Define topics from list of docs and try to find top 3 topic and top nearest docs, as the problem is unsupervised one we will try to tune our prameters. <br>

Here will see:
* Simple Notebook with LSA, LDA with sklearn, LDA with Gensim
* Cleaninig and preprocessing the text(Lemmetazation, CountVector, ...) 
* Word cloud for each topic
* Each doc topic score
* using TSNE, TruncatedSVD to visualize in 3D space
* Using kmeans to find similar topics
* Inference the a new text

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

Python on using Basic packages Numpy, Pandas, matplotlib <br> Plus:

* [Sklearn](https://scikit-learn.org/stable/)
* [Wordcloud](https://pypi.org/project/wordcloud/)
* [NLTK](https://www.nltk.org/install.html)
* [Gensim](https://pypi.org/project/gensim/)
* [Spacy](https://spacy.io/usage)

<p align="right">(<a href="#top">back to top</a>)</p>


### Installation

To run the source code 

1. Clone the repo
   ```sh
   git clone https://github.com/Mohamed-Ahmed-Abo-El-Enen/LDATopicExtraction.git
   ```
2. Install Previous packages
5. Run Notebook eack notebook have the commands to install it from pip

<p align="right">(<a href="#top">back to top</a>)</p>

### Running

Code Run on Python 3.6.9 <br>
Some Notebook will save some results on the harddick for later process and tuning 
<p align="right">(<a href="#top">back to top</a>)</p>

### Future Work
* Will try to make simple Flask API, just like this <br>
https://github.com/Mohamed-Ahmed-Abo-El-Enen/AIMChallenge/tree/main/Code/app
* We could try more techniques like {Latent Semantic Analysis, pLSA, ...}
* Or Dive To DeepLearning, Neural Networks, including Word Embedding, Variational Auto-Encoders, Generative Adversarial Networks, and some complements of the LDA such as reranking words and document representations.
<br>
<br> 
https://medium.com/data-folks-indonesia/recent-works-in-topic-modeling-56c38da8dfc4
<p align="right">(<a href="#top">back to top</a>)</p>
 
