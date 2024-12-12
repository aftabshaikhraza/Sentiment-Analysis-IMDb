# Sentiment-Analysis-IMDb
This project implements Sentiment Analysis on the IMDb Large Movie Review Dataset using various machine learning models. The goal is to classify movie reviews as positive or negative based on their textual content. The project involves data preprocessing, feature extraction using TF-IDF, and evaluation of multiple supervised learning algorithms to determine the best-performing model.
Features
	•	Dataset: IMDb Large Movie Review Dataset (50,000 labeled reviews).
	•	Preprocessing:
	  Text cleaning (removal of stop words, punctuation, etc.).
	 	Lemmatization for standardizing words.
		Feature extraction using TF-IDF vectorization.
	•	Algorithms:
		Logistic Regression
		Support Vector Machine (SVM)
		Naïve Bayes
		Random Forest
		Gradient Boosting
	•	Performance Metrics:
		Accuracy, Precision, Recall, and F1-Score for both positive and negative classes.
	•	Comparison:
		Detailed evaluation and comparison of all models with visualizations and insights.

Results
	•	Best Model: Support Vector Machine (SVM) achieved the highest accuracy of 87.6% with balanced precision and recall for both classes.
 How to Run (in bash)
	1.	Clone the repository:
 
 git clone https://github.com/aftabshaikhraza/Sentiment-Analysis-IMDb.git
 cd Sentiment-Analysis-IMDb

Dataset

The IMDb Large Movie Review Dataset is provided in the repositary in zip format.
Update:- I am having trouble uploading all the whole dataset in the repo so I'll just leave the link where you can download the dataset and ZIP it using any online ZIP tool 
https://ai.stanford.edu/~amaas/data/sentiment/

Credits for this dataset 
@InProceedings{maas-EtAl:2011:ACL-HLT2011,
  author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
  title     = {Learning Word Vectors for Sentiment Analysis},
  booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
  month     = {June},
  year      = {2011},
  address   = {Portland, Oregon, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {142--150},
  url       = {http://www.aclweb.org/anthology/P11-1015}
}

References
	1.	Maas, A. L., Daly, R. E., Pham, P. T., Huang, D., Ng, A. Y., & Potts, C. (2011). Learning Word Vectors for Sentiment Analysis. ACL 2011.
	2.	Pang, B., & Lee, L. (2008). Opinion Mining and Sentiment Analysis. Foundations and Trends in Information Retrieval, 2(1–2), 1–135.
	3.	Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.
