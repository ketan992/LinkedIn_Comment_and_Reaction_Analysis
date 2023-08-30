Contributors:
Abhinaw Tiwari
Vaibhav Srivastava
Ketan Anil Patil
Asish Prasad Rath
Amogh Anil Rao
Harshal Patil
Haneesh Solasa
Karan Dua

Files:
Cleaned_data.csv
EDA_da.ipynb
ExploratoryDataAnalysis_Comments.ipynb
ExploratoryDataAnalysis_Reactions.ipynb
combined_data.csv
DA_scrapping.ipynb
profile_to_comment.csv
Linkedin.ipynb
LinkedinReactionsv3.csv
processed_batch.csv
DA code_final.twb
reactions.html
linkedinReactions.ipynb
da_grtaphs.pbix

Steps to replicate the work:
- Initial scraping was done using "DA_scrapping.ipynb" to produce "profile_to_comment.csv"
- Profile data was collected using Phantom Buster and merged with existing profile data to get "combined_data.csv"
- Reactions were collected using "linkedinReactions.ipynb" over "reactions.html"
- Sentiment analysis for comments and reactions was done. Results of comments' sentiment analysis are stored in "processed_batch.csv" and for reactions' sentiment analysis are stored in "LinkedinReactionsv3.csv".
- "Linkedin.ipynb" was used to analyze comments and reactions
- EDA was performed over "Cleaned_data.csv", which was produced from the "processed_batch.csv" after cleaning it.
- Further EDA was performed as using tableau (DA code_final.twb) and powerBI (da_grtaphs.pbix)
- Data Analysis was also performed on comments and reactions data in "ExploratoryDataAnalysis_Comments.ipynb" and "ExploratoryDataAnalysis_Reactions.ipynb" files.