The purpose of this analysis is to examine whether the Linear Regression Model is suitable for assessing the creditworthiness of borrowers. We're going to dig into a bunch of data from a peer-to-peer lending company. It's got loads of records—about 77,536 things covering: 
	-Loan_size
	-Interest_rate
	-Burrower_income
	-Debt_to_income
	-Number_of_accounts
	-Derogatory_marks
	-Total_debt
	-Loan_status

Results: Logistic Regression Model
-Accuracy: [99.241%] - With this high accuracy score, it's evident that the model performs admirably overall, correctly predicting 99% of the instances in the dataset.
-Precision (0 class): [1] - This impressive precision score suggests a minimal false positive rate, indicating the model's exceptional accuracy in identifying healthy loans.
-Recall (0 class): [1] - A high recall score here indicates a low false negative rate, highlighting the model's proficiency in capturing healthy loans.
-Precision (1 class): [.87] - Though not perfect, this precision score of 87% still underscores the model's effectiveness in identifying high-risk loans, with a majority of instances correctly predicted.
-Recall (1 class): [.89] - This recall score of 89% showcases the model's ability to accurately flag 89% of high-risk loans within the dataset.

Summary:
The logistic regression model does a great job predicting both healthy and high-risk loans, with high accuracy, precision, and recall scores for both. Even though high-risk loan recall is more crucial, the model's balance between precision and recall overall makes it the top choice for predicting loan status. In general, it performs really well, especially in spotting healthy loans. While it's not perfect for high-risk loans, it still does a good job and should be taken seriously.
