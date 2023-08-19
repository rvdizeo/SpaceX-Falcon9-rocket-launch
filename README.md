# Determining the price of a SpaceX Falcon 9 rocket launch

SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars.​
* Falcon 9 rocket is made up of three stages: Stage One, Stage Two and The Fairings.​

Other providers cost upwards of 165 million dollars each launch.​
* Much of the savings is because SpaceX can reuse the first stage.​

Sometimes the first stage does not land. Sometimes it will crash. Other times, Space X will sacrifice the first stage due to the mission parameters like payload, orbit, and customer. ​

**If we can determine if the first stage will land, we can determine the cost of a launch.**

## Methodology
* We will be working with SpaceX launch data that is gathered from an API, specifically the SpaceX REST API.​

* We will build a machine learning pipeline to predict if the first stage of the Falcon 9 lands successfully.​

* Using the best hyperparameter values, we will determine the model with the best accuracy using the test data. We will test:​
  * Logistic Regression​
  * Support Vector machines​
  * Decision Tree Classifier​
  * K-nearest neighbors
