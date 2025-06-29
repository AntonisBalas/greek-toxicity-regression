# greek-toxicity-regression
Fine-tuning transformer models for offensive language detection in Greek using regression-based scoring on the 
AIKIA dataset
This project focuses on detecting and scoring offensive language in Greek using regression-based approaches built on top of transformer language models (e.g., BERT).
Unlike binary classification, this method outputs continuous values representing degrees of offensiveness, offering more nuanced control for downstream tasks.
The models are trained and evaluated using the AIKIA dataset, a Greek corpus annotated with Best-Worst Scaling (BWS) scores, containing texts from:
	•	Tweets
	•	Blogs
	•	Fiction
