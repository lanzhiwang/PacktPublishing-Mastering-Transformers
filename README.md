


# Mastering Transformers

<a href="https://www.packtpub.com/product/mastering-transformers/9781801077651"><img src="mt.jpg" alt="Book Name" height="256px" align="right"></a>

This is the code repository for [Mastering Transformers](https://www.amazon.com/Mastering-Transformers-state-art-processing/dp/1801077657), published by Packt.

**Build state-of-the-art models from scratch with advanced natural language processing techniques**

## What is this book about?
Transformer-based language models have dominated natural language processing (NLP) studies and have now become a new paradigm. With this book, you'll learn how to build various transformer-based NLP applications using the Python Transformers library.

This book covers the following exciting features: 
* Explore state-of-the-art NLP solutions with the Transformers library
* Train a language model in any language with any transformer architecture
* Fine-tune a pre-trained language model to perform several downstream tasks
* Select the right framework for the training, evaluation, and production of an end-to-end solution
* Get hands-on experience in using TensorBoard and Weights & Biases
* Visualize the internal representation of transformer models for interpretability

If you feel this book is for you, get your [copy](https://www.amazon.com/Mastering-Transformers-advanced-processing-techniques/dp/1801077657) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Table of Contents

1. From Bag-of-Words to the Transformers
   从词袋模型到 Transformers

2. A Hands-On Introduction to the Subject
   主题的动手介绍

3. Autoencoding Language Models
   自动编码语言模型

4. Autoregressive and Other Language Models
   自回归和其他语言模型

5. Fine-Tuning Language Models for Text Classification
   用于文本分类的微调语言模型

6. Fine-Tuning Language Models for Token Classification
   用于标记分类的微调语言模型

7. Text Representation
   文本表示

8. Working with Efficient Transformers
   使用高效的 Transformers

9.  Cross-Lingual and Multilingual Language Modeling
    跨语言和多语言语言建模

10. Serving Transformer Models
    服务 Transformer 模型

11. Attention Visualization and Experiment Tracking
    注意力可视化和实验跟踪

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter03.

The code will look like the following:

```
import pandas as pd
imdb_df = pd.read_csv("IMDB Dataset.csv")
reviews = imdb_df.review.to_string(index=None)
with open("corpus.txt", "w") as f:
      f.writelines(reviews)

```

**Following is what you need for this book:**
This book is for deep learning researchers, hands-on NLP practitioners, as well as ML/NLP educators and students who want to start their journey with Transformers. Beginner-level machine learning knowledge and a good command of Python will help you get the best out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

### Software and Hardware List

| Chapter | Software required                                                            | OS required                        |
| ------- | ---------------------------------------------------------------------------- | ---------------------------------- |
| 1-11    | Python 3.6x, Transformers, Google Colaboratory, Jupyter Notebook, TensorFlow | Windows, Mac OS X, and Linux (Any) |
| 10      | Docker, Locust.io                                                            | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it]( https://static.packt-cdn.com/downloads/9781801077651_ColorImages.pdf).

## Code in Action

Click on the following link to see the Code in Action:

https://bit.ly/3i4vFzJ

### Related products <Other books you may enjoy>
* Getting Started with Google BERT [[Packt]](https://www.packtpub.com/product/getting-started-with-google-bert/9781838821593) [[Amazon]](https://www.amazon.in/Getting-Started-Google-BERT-state-ebook/dp/B08LLDF377)

* Snowflake Cookbook [[Packt]](https://www.packtpub.com/product/snowflake-cookbook/9781800560611) [[Amazon]](https://www.amazon.in/Snowflake-Cookbook-Techniques-warehousing-solutions-ebook/dp/B08PDJ7CTX)

## Get to Know the Author
**Savaş Yıldırım**
He graduated from the Istanbul Technical University Department of Computer Engineering and holds a Ph.D. degree in Natural Language Processing (NLP). Currently, he is an associate professor at the Istanbul Bilgi University, Turkey, and is a visiting researcher at the Ryerson University, Canada. He is a proactive lecturer and researcher with more than 20 years of experience teaching courses on machine learning, deep learning, and NLP.

**Meysam Asgari-Chenaghlu**
He is an AI manager at Carbon Consulting and is also a Ph.D. candidate at the University of Tabriz. He has been a consultant for Turkey's leading telecommunication and banking companies. He has also worked on various projects, including natural language understanding and semantic search.

### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781801077651">https://packt.link/free-ebook/9781801077651 </a> </p>


```bash
docker run -it --rm -p 10000:8888 \
-v ~/work/code/go_code/ai/huggingface/PacktPublishing-Mastering-Transformers:/home/jovyan/work \
jupyter/minimal-notebook:x86_64-python-3.11.6

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple black[jupyter] scikit-learn==1.6.1

find . -name "*.ipynb" -exec black {} \;
find . -name "*.py" -exec black {} \;

find . -name "*ipynb_checkpoints*" -exec rm -rf {} \;

```
