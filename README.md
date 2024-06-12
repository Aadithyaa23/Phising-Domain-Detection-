The proposed system is implemented as a web browser extension that monitors user browsing activity and visited URLs.
When a new webpage is loaded, the extension extracts relevant features from the URL and page content that could indicate phishing, such as the presence of IP addresses in the URL, age of the domain, and suspicious HTML markup. 
These features are passed to an ensemble of multiple machine learning classifier models like logistic regression and decision trees. 
If phishing is detected, the extension alerts the user about the potential threat


Internet users across various age groups, technical proficiency levels
Both personal and professional/enterprise users
Users accessing the internet via desktop and mobile browsers
Privacy-conscious users concerned about online security

The key functional characteristics for the phishing detection browser extension

URL Page Monitoring
Feature Extraction
Phishing Classification
Alerting the User
Reporting Feedback
Configuration
Continuous Updating 


Web Browser Extensions or API’s 
Machine Learning Libraries Scikit-learn
Data Preprocessing (Numpy, Pandas, External API’s, etc,..)
Javascript for Url Extraction from user webpages
Vizualizations Tools for Wordcloud 
Third party libraries for data extraxtion from  URL 


The URL must be parsed and the features need to be extracted and given as input to the machine learning model to classify the state of the url.


There are 30 features needed to be extracted from the url using third party api’s to check whether it is google indexed, Age of Domain, Page rank, Iframe Redirection, etc,..


The time taken to get the result of the model is reduced instead of manually copying the link and pasting in another site to check the type of url.
