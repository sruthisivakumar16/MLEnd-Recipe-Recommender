# Recipe Recommender - MLEnd Yummy
In everyday life, meal planning can be very challenging, particularly when dealing with a variety of dietary requirements, health concerns, and a small number of available ingredients. Considering how people have different dietary and health concerns, it can be challenging to put together a meal everyday that satisfies these requirements even with a well-stocked pantry. This real-world problem emphasises the need for a solution that simplifies this decision-making process and enables people to quickly find dishes that satisfy their dietary needs, support their health goals by making the best use of the ingredients available.

By using the <a href = "https://mlenddatasets.github.io/yummy/" >MLEnd Yummy Dataset</a>, the main objective is to develop a robust machine learning model that suggests healthier dishes based on the ingredients available and dietary restrictions by combining NLP and ML techniques.

The MLEnd Yummy Dataset is a collection of more than 3,000 enriched images created by students at the School of Electronic Engineering and Computer Science, Queen Mary University of London, including contributions from myself. For more information about the dataset, checkout <a href = "https://mlenddatasets.github.io/yummy/" >MLEnd Yummy Dataset</a>. 

### Installing the dataset
```pip install mlend```

Currently, the recipe recommender system relies solely on textual data such as ingredient lists, nutritional information, and dietary labels to generate recommendations. However, By leveraging Convolutional Neural Network (CNN) models to extract features from recipe images, we can compare the effectiveness of incorporating visual information alongside textual data in recipe recommendations and see how it affects the performance.
