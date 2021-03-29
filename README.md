# Interpretable Machine Learning with Python

<a href="https://www.packtpub.com/product/interpretable-machine-learning-with-python/9781800203907"><img src="https://static.packt-cdn.com/products/9781800203907/cover/smaller" alt="Interpretable Machine Learning with Pythone" height="256px" align="right"></a>

This is the code repository for [Interpretable Machine Learning with Python](https://www.packtpub.com/product/interpretable-machine-learning-with-python/9781800203907), published by Packt.

**Learn to build interpretable high-performance models with hands-on real-world examples**

## What is this book about?
Do you want to understand your models and mitigate the risks associated with poor predictions using practical machine learning (ML) interpretation? Interpretable Machine Learning with Python can help you overcome these challenges, using interpretation methods to build fairer and safer ML models.

This book covers the following exciting features: 
* Recognize the importance of interpretability in business
* Study models that are intrinsically interpretable such as linear models, decision trees, and Naïve Bayes
* Become well-versed in interpreting models with model-agnostic methods
* Visualize how an image classifier works and what it learns
* Understand how to mitigate the influence of bias in datasets

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/180020390X) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
base_classifier = KerasClassifier(model=base_model,\
                                  clip_values=(min_, max_))
y_test_mdsample_prob = np.max(y_test_prob[sampl_md_idxs],\
                                                       axis=1)
y_test_smsample_prob = np.max(y_test_prob[sampl_sm_idxs],\
                                                       axis=1)
```

**Following is what you need for this book:**
This book is for data scientists, machine learning developers, and data stewards who have an increasingly critical responsibility to explain how the AI systems they develop work, their impact on decision making, and how they identify and manage bias. Working knowledge of machine learning and the Python programming language is expected.

With the following software and hardware list you can run all code files present in the book (Chapter 1-14).

### Software and Hardware List

You can install the software required in any operating system by first installing [Jupyter Notebook or Jupyter Lab](https://jupyter.readthedocs.io/en/latest/install.html) with the most recent version of Python, or install [Anaconda](https://docs.anaconda.com/anaconda/) which can install everything at once. While hardware requirements for Jupyter are relatively modest, we recommend a machine with at least 4 cores of 2Ghz and 8Gb of RAM.

Alternatively, to installing the software locally, you can run the code in the cloud using Google Colab or another cloud notebook service.  

Either way, the following packages are required to run the code in all the chapters (Google Colab has all the packages denoted with a ^):

| Chapter  | Software required                     | OS required                        |
| -------- | --------------------------------------| -----------------------------------|
| 1        | ^ matplotlib 3.2.2+                   | Windows, Mac OS X, and Linux (Any) |
| 2        | ^ scikit-learn 0.22.2+                | Windows, Mac OS X, and Linux (Any) |
| 3        | ^ pandas 1.1.5+                       | Windows, Mac OS X, and Linux (Any) |
| 4        | machine-learning-datasets 0.01.16+    | Windows, Mac OS X, and Linux (Any) |
| 5        | ^ numpy 1.19.5+                       | Windows, Mac OS X, and Linux (Any) |
| 6        | ^ seaborn 0.11.1+                     | Windows, Mac OS X, and Linux (Any) |
| 7        | ^ tensorflow 2.4.1+                   | Windows, Mac OS X, and Linux (Any) |
| 8        | shap 0.38.1+                          | Windows, Mac OS X, and Linux (Any) |
| 9        | ^ scipy 1.4.1+                        | Windows, Mac OS X, and Linux (Any) |
| 10       | ^ xgboost 0.90+                       | Windows, Mac OS X, and Linux (Any) |
| 11       | ^ lightgbm 2.2.3+                     | Windows, Mac OS X, and Linux (Any) |
| 12       | alibi 0.5.5+                          | Windows, Mac OS X, and Linux (Any) |
| 13       | ^ tqdm 4.41.1+                        | Windows, Mac OS X, and Linux (Any) |
| 14       | ^ statsmodels 0.10.2+                 | Windows, Mac OS X, and Linux (Any) |
| 15       | rulefit 0.3.1+                        | Windows, Mac OS X, and Linux (Any) |
| 16       | lime 0.2.0.1+                         | Windows, Mac OS X, and Linux (Any) |
| 17       | catboost 0.24.4+                      | Windows, Mac OS X, and Linux (Any) |
| 18       | ^ Keras 2.4.3+                        | Windows, Mac OS X, and Linux (Any) |
| 19       | ^ pydot 1.3.0+                        | Windows, Mac OS X, and Linux (Any) |
| 20       | xai 0.0.4+                            | Windows, Mac OS X, and Linux (Any) |
| 21       | ^ beautifulsoup4 4.6.3+               | Windows, Mac OS X, and Linux (Any) |
| 22       | ^ requests 2.23.0+                    | Windows, Mac OS X, and Linux (Any) |
| 23       | cvae 0.0.3+                           | Windows, Mac OS X, and Linux (Any) |
| 24       | interpret 0.2.2+                      | Windows, Mac OS X, and Linux (Any) |
| 25       | ^ six 1.15.0+                         | Windows, Mac OS X, and Linux (Any) |
| 26       | skope-rules 1.0.1+                    | Windows, Mac OS X, and Linux (Any) |
| 27       | PDPbox 0.2.0+                         | Windows, Mac OS X, and Linux (Any) |
| 28       | pycebox 0.0.1+                        | Windows, Mac OS X, and Linux (Any) |
| 29       | alepython 0.1+                        | Windows, Mac OS X, and Linux (Any) |
| 30       | tensorflow-docs 0.0.02+               | Windows, Mac OS X, and Linux (Any) |
| 31       | ^ nltk 3.2.5+                         | Windows, Mac OS X, and Linux (Any) |
| 32       | witwidget 1.7.0+                      | Windows, Mac OS X, and Linux (Any) |
| 33       | ^ opencv-python 4.1.2.30+             | Windows, Mac OS X, and Linux (Any) |
| 34       | ^ scikit-image 0.16.2+                | Windows, Mac OS X, and Linux (Any) |
| 35       | tf-explain 0.2.1+                     | Windows, Mac OS X, and Linux (Any) |
| 36       | tf-keras-vis 0.5.5+                   | Windows, Mac OS X, and Linux (Any) |
| 37       | SALib 1.3.12+                         | Windows, Mac OS X, and Linux (Any) |
| 38       | distython 0.0.3+                      | Windows, Mac OS X, and Linux (Any) |
| 39       | ^ mlxtend 0.14.0+                     | Windows, Mac OS X, and Linux (Any) |
| 40       | sklearn-genetic 0.3.0+                | Windows, Mac OS X, and Linux (Any) |
| 41       | aif360 0.3.0+                         | Windows, Mac OS X, and Linux (Any) |
| 42       | dowhy 0.5.1+                          | Windows, Mac OS X, and Linux (Any) |
| 43       | econml 0.9.0+                         | Windows, Mac OS X, and Linux (Any) |
| 44       | ^ networkx 2.5+                       | Windows, Mac OS X, and Linux (Any) |
| 45       | bayesian-optimization 1.2.0+          | Windows, Mac OS X, and Linux (Any) |
| 46       | ^ graphviz 0.10.1+                    | Windows, Mac OS X, and Linux (Any) |
| 47       | tensorflow-lattice 2.0.7+             | Windows, Mac OS X, and Linux (Any) |
| 48       | adversarial-robustness-toolbox 1.5.0+ | Windows, Mac OS X, and Linux (Any) |

The exact versions of each library as tested can be found in the [requirements.txt](https://github.com/PacktPublishing/Interpretable-Machine-Learning-with-Python/blob/master/requirements.txt) file and installed like this:

`> pip install -r requirements.txt`

should you have a dedicated environment for them.

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781800203907_ColorImages.pdf).

### Related products <Other books you may enjoy>
* Automated Machine Learning [[Packt]](https://www.packtpub.com/product/automated-machine-learning/9781800567689) [[Amazon]](https://www.amazon.com/dp/1800567685)

* Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits [[Packt]](https://www.packtpub.com/product/hands-on-machine-learning-with-scikit-learn-and-scientific-python-toolkits/9781838826048) [[Amazon]](https://www.amazon.com/dp/1838826041)

## Get to Know the Authors
**Serg Masís**
has been at the confluence of the internet, application development, and analytics for the last two decades. Currently, he's a Climate and Agronomic Data Scientist at Syngenta, a leading agribusiness company with a mission to improve global food security. Before that role, he co-founded a startup, incubated by Harvard Innovation Labs, that combined the power of cloud computing and machine learning with principles in decision-making science to expose users to new places and events. Whether it pertains to leisure activities, plant diseases, or customer lifetime value, Serg is passionate about providing the often-missing link between data and decision-making — and machine learning interpretation helps bridge this gap more robustly.
