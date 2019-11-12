# 分析の種類
## supervised leaning
Machine learning algorithms that learn from input/output pairs arecalled supervised learning algorithms because a “teacher” providessupervision to the algorithms in the form of the desired outputs foreach example that they learn from.

* Identifying the zip code from handwritten digits on an envelope
* Determining whether a tumor is benign based on a medical image 
* Detecting fraudulent activity in credit card transactions 

## unsupervised leaning
In unsupervised learning, only the input data is known, and no known output data is given to the algorithm. 

* Identifying topics in a set of blog posts
* Segmenting customers into groups with similar preferences
* Detecting abnormal access patterns to a website

----

# ツール
## anaconda
[インストール](https://www.anaconda.com/distribution/#download-section)

```
// バージョン確認
anaconda --version

// pythonのバージョンも3に上がっているのを確認できる
python --version

// anacondaでインストールされているパッケージを確認
conda list
```

## scikit-learn
* anacondaインストール時に自動でインストールされる
* 学習データなども含むパッケージ
[公式ドキュメント](https://scikit-learn.org)

## jupyter
```
// 対象のディレクトリに移動して、以下を実行
// ipynb
jupyter notebook
```

## numpy
NumPy is one of the fundamental packages for scientific computing inPython. It contains functionality for multidimensional arrays,
high-level mathematical functions such as linear algebra operations and
the Fourier transform, and pseudorandom number generators. 

## SciPy
It provides, among other functionality, advanced linear algebra routines, mathematical function optimization, signal processing, special mathematical functions, and statistical distributions. 

## matplotlib
グラフを表示する

## pandas
* データテーブルを作成できる
* SQLやエクセルなど様々なデータソースからデータを取得できる
* クエリを投げることができる

## mglearn
```

```

----

# Terms
## data point(column), row(feature)
Each data point that you want to reason about (each email, each customer, each transaction) is a row, and each property that describes that data point(say, the age of a customer or the amount or location of a transaction)is a column. You might describe users by their age, their gender, whenthey created an account, and how often they have bought from your online shop. You might describe the image of a tumor by the gray scale values of each pixel, or maybe by using the size, shape, and color of the tumor. Each entity or row here is known as a sample (or data point) in machine learning, while the columns the properties that describe these entities are called features .

## Classification and Regression
* In classification, the goal is to predict a class label , which is a choice from a predefined list of possibilities.
* For regression tasks, the goal is to predict a continuous number.

## Binary Classification
You can think of binary classification as trying to answer a yes/no question. Classifying emails as either spam or not spam is an example of a binary classification problem. 
