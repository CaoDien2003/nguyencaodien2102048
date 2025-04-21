# Alice in Wonderland

## Problem Statement for Students
You're tasked with analyzing the text of Alice in Wonderland to understand the structure and meaning of its words using natural language processing (NLP) and data visualization techniques.

## Objectives:
- Clean and preprocess the text
- Visualize word frequencies using a word cloud
- Plot the top frequent words using a bar chart
- Explore semantic relationships between words using GloVe embeddings + PCA
- Display word similarity as a heatmap

## Data Source: 
[Alice’s Adventures in Wonderland – Lewis Carrol](https://www.gutenberg.org/files/11/11-0.txt?fbclid=IwY2xjawJyqEVleHRuA2FlbQIxMAABHiSEtVv0QAY3PtyPmYhYiuRQ_QhUSArL6Tq225phgivxTfR3N4xFEw3JdRIT_aem_d_TYRPYx_3xqgIAJ6A42VQ)

## Technologies & Libraries:
- Python
- nltk – for text tokenization and stopword removal
- collections.Counter – for counting word frequency
- matplotlib and seaborn – for plotting
- wordcloud – for generating the word cloud
- sklearn.metrics.pairwise.cosine_similarity – for computing similarity
- gensim.downloader – to load GloVe embeddings
- sklearn.decomposition.PCA – for dimensionality reduction

## Sample Visuals

1. Word Cloud
![Word Cloud](/AliceinWonderland/public/WordCloud.png)

2. Bar chart
![Bar chart](/AliceinWonderland/public/barchart.png)

3. PCA of Word Embeddings
![PCA of Word Embeddings](/AliceinWonderland/public/PCAofWordEmbeddings_01.png)

4. Heat Map
![Heat Map](/AliceinWonderland/public/heatmap.png)

**Install the required libraries:**

<div align="center">

```bash
pip install -r /AliceinWonderland/requirements.txt
```

</div>

## Run the Jupyter Notebook

```bash
jupyter notebook AliceinWonderland/Alice_in_Wonderland_NLP_&_Visualization.ipynb
```

---

## 📬 Contact

For any inquiries or contributions, feel free to reach out:

- **Email:** nguyencaodien2003@gmail.com
- **GitHub:** [CaoDien2003](https://github.com/YourGitHubUsername)
- **LinkedIn:** [Điền Cao](https://www.linkedin.com/in/nguyencaodien/)
