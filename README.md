Hello! My name is Buyang Li, and welcome to my Data Science Portfolio, an in-depth look at the many projects I have completed. I am very passionate about using data ethically and effectively, and I hope that is conveyed through my work.

# [Project 1: IP Detective: Patent infringement detection using BERT](https://github.com/jasonli3947/IP-Detective-Patent-infringement-detection-using-BERT)
Patents play a significant part in innovation and helps individuals and companies safeguard and retain ownership of their ideas. However, patent infringement is common, and more than 2,500 patent infringement suits are filed each year. Currently, patent infringement detection is largely done manually, and companies spend approximately $600 to identify each case of infringement. Our work provides an approach to automate this process through machine learning. Our model first vectorizes patent text using a BERT model trained on patent text, and then calculates similarity scores between competing patent claims. We developed an architecture that not only identifies the similarity of two patents at an overall level, but also on each subsection and crossevaluates the similarity between these sections. This was implemented by creating a matrix of all possible subsection combinations between two patents and populating the matrix with relevant ‘similarity’ scores. The overall score is then calculated by taking a weighted average of the subsection similarities, where the weights were calculated by training a logistic regression model based on historical cases of infringement. Looking at subsection scores along with the overall score, we can identify potential infringement of two competing patent claims rather accurately.

Presented the solution at INFORMS 2022 Business Analytics Conference and Midwest 2022 Decision Sciences Conference.

More Details: [https://mwdsi2022.exordo.com/files/papers/46/paper_custom_fields/1/IP2022_Bonutti_Paper_v2.pdf](https://mwdsi2022.exordo.com/files/papers/46/paper_custom_fields/1/IP2022_Bonutti_Paper_v2.pdf)

![](/images/poster.png)

# [Project 2: Craigslist Classification of Resume](https://github.com/jasonli3947/Craigslist-Resume-Classification)
Created an automatic script using Python to pre-process high volume Craigslist unstructured data, leveraged multiply ML models (LDA, SVM, LSTM, etc.) on resume misclassification recognition and labeling, and delivered a prototype with deployment recommendations.

# [Project 3: Phishing Emails Detection](https://github.com/jasonli3947/Phishing-Emails-Detection)
Phishing email detection using NLP. Used BERT, Bi-LSTM, Naive Bayes models to learn phishing email patterns.
