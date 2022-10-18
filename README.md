# Naive Bayes Classifier

## Task
Create a naive model for binary classification for fake news datasets (fake/credible).
Datasets are provided in `data/2-fake_news`

## Implementation
```
1. Cleaned data(removed stopwords, punctuations e.t.c). Create 'bag of words' out of texts and visualize data.
2. Fit our model with data, and calculate conditional probabilities for words and fake/credible cases.
3. Implemented predict function to get prediction for one entry based on words conditional probabilities
4. Get results for the whole dataset. Evaluate result metrics
```
## Results and Visuals

Our model works really well with provided datasets. We get a high results(with different metrics) even on the test set. 

As we can see we got high values both for the recall and precision metrics

### Test set results
![image](https://user-images.githubusercontent.com/91615606/196554077-b867cf16-97c9-4de7-85d1-30bb762baad3.png)

### WordsCloud
Also we can see whick words occures the most in all texts, fake or credible ones. (Example for fake news)
![image](https://user-images.githubusercontent.com/91615606/196551461-43bffc95-4115-49e6-8bc8-df8768baa0e6.png)

See more in `visualization.Rmd`

## Cons and Pros

```
Cons:
    Easy and fast to implement
    Fast evaluations for predictions
    Good results in a short time
    
Pros:
    It is naive, so it can miss important features.
    Very sensetive to class variance.
    We have to assume that features are independent
```
