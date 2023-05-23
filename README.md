# Diet-Recommendation-System

The goal of application is to provide a platform where users find their Nutritious food according to their personal health preferences according to their BMI and recommend food separately for weight loss and gain categories and build a behavior of living healthy life and I have also build the recommendation system wherein it helps to identify the suitable drug names that can be recommended for the diseases respectively.

The flow of the project :

Data collection - data is collected by web scraping (projects works on demo data).

Data processing - data is processed and required attributes are added to make demo datasets.

User's profile generation by taking input from them .

Initial recommendation on the basis of user's profile (Content-based,implemented by k-nearest neighbors).
Recommendation based on similar profiles to users.
Recommendation on the basis of users past/recent activity (Collaborative Memory based approach,implemented by K-nearest neighbors).

Technology used -
Python and its libraries
For Web scraping - Beautifulsoup, requests
For Maintaing/handeling data and Data processing- Pandas,numpy,time,datetime,random,nltk
For Recommendation - sklearn

Being healthy and eating better is something the vast majority of the population wants and doing so usually requires great effort. The working prototype accomplishes a Personalized Diet Recommendation System with the integration of Machine Learning Algorithms to recommend the right food at right time and with the right nutrition, calories, fat, etc.

The existing system struggles to provide a weight gain/loss scheme to a user based on his long-term food habits.

Here the system is build with help of food.csv and nutrition_distribution.csv and thereby it calculates the BMI with help of manual entry and calculates if the person is healthy / over weight / underweight and recommendes the food that can be taken in breakfast / lunch / dinner so that a person can achieve weight loss / weight gain accordingly.

A working prototype of a Diet Recommendation System is established. The module works on the basis of K-Means Clustering and Random Forest Classification Algorithms. Tkinter-based GUI is implemented.
METHODS : Tkinter
Recommendation System
Random Forest
K-Mean Clustering

Future Scope for personalized meal and diet recommendation system
Matrix factorisation methods of collaborative filtering can be applied, further Single Value Decomposition can be applied. The module can be implemented as a cloud-based application. Packaged as a single entity, ready for production environment deployment.
