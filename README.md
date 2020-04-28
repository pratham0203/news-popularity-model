# news-popularity-model
## Contents of the Project:-

### 1)Classification Model:
This model has various algos like Logistics Regression,Random Forest Classifier,SVM but the one actively used is RandomForestClassifier due to its best results.


The Output shows Essentials of the model using RandomForestClassifier after being trained and tested.
![Capture](https://user-images.githubusercontent.com/20925116/80414298-708b6900-88ee-11ea-8dd9-c969dfb97668.PNG)



The Output shows the labels before and after standardization.
It also shows the accuracy of this model.
![Capture1](https://user-images.githubusercontent.com/20925116/80414301-72552c80-88ee-11ea-8caa-4f6729c155dd.PNG)


### 2)Regression Model:
This model uses Bayesian Linear Regression to solve the problem and give us the required accuracy of the model. 
### 3)News Aggregator(made using Django by scraping popular websites like Times of India etc):

I also made a website using Django that can be later used to project the popular news on a single site only.
![website](https://user-images.githubusercontent.com/20925116/80413115-944daf80-88ec-11ea-83ed-a0e037194788.PNG)


Web Scraping of Times Of India:
![webscraptoi](https://user-images.githubusercontent.com/20925116/80413138-9b74bd80-88ec-11ea-86b9-c2931bb6e418.PNG)


Web Scraping Of Hindustan TImes:
![webscrapht](https://user-images.githubusercontent.com/20925116/80413137-9adc2700-88ec-11ea-90c6-c4be970a6f72.PNG)


Web Scraping of The Economist:
![webscrapet](https://user-images.githubusercontent.com/20925116/80413131-99126380-88ec-11ea-92ba-0f263fb3ff5e.PNG)

### 3)Integrated scraped data and ML model to predict virality:
Here using Regression model that uses a dataset Newspopularity.csv to train itself and then check the virality of the scraped data.The virality is checked on the basis of various information that has been scraped from Times of India website.The text includes these data for evaluation:

![Capture3](https://user-images.githubusercontent.com/20925116/80467515-87b47000-895b-11ea-99d0-a0c82f419391.PNG)
The dataset choosen for evaluation.





## Future of the Project:
A much proper integration of model and NewsAggregator which could predict the virality of the news and display the link to the site on my website asap.
## License
The project is available as open source under the terms of the MIT License.
