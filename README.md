#QTL Text Analysis Project 2 - COMS_579

This project extends the work from Project 1 by applying advanced language models to analyze animal QTL-related texts. It explores and compares different embedding techniques including:

BERT Embeddings with Cosine Similarity (bert_nd_grove_2.ipynb)

GloVe Embedding with Similarity Metrics (GloVe_T1.ipynb)

Manual Rule-based Phrase Matching (M1.4.ipynb)

Each method aims to extract and match QTL-relevant traits from the text using different NLP techniques.

🔧 Setup
Make sure Python 3.8+ is installed, along with Jupyter and the required libraries:

git clone https://github.com/yourusername/qtl_text_analysis_project2.git
cd qtl_text_analysis_project2
pip install -r requirements.txt
🚀 Execution Instructions
1. BERT-based Embedding and Similarity Matching
   
jupyter notebook bert_nd_grove_2.ipynb
This notebook uses pre-trained BERT to compute sentence embeddings and evaluates similarity between extracted phrases and dictionary terms.

3. GloVe-based Trait Matching

jupyter notebook GloVe_T1.ipynb
This method uses pre-trained GloVe vectors to represent text and compute cosine similarity with trait terms.

4. Manual Trait Phrase Matching

jupyter notebook M1.4.ipynb
This rule-based approach manually searches for trait phrases within the text corpus using string patterns and keyword matching.

📊 Results
The comparative analysis of trait extraction methods and their performance is documented in 579_Project_2_Report.pdf.

