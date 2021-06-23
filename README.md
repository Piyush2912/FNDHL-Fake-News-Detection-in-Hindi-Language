# FNDHL-Fake-News-Detection-in-Hindi-Language

## FNDHL
Fake news detection in the Hindi language is an NLP based model developed for the detection of whether a Hindi news headline is fake or real.

## Web Portal:
<p align="center">
  Presently available at local host
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123117753-a75fff00-d45f-11eb-8566-d5a3fd515d6b.png" />
</p>

### How to use?
1. Copy Hindi news article from any source.
2. Paste the Hindi news article in the box as shown above.
3. Click on predict to check whether the Hindi news is true or fake. 


## Table of Contents: 
1. Motivation
2. Problem Statement
3. Introduction
4. Hindi Dataset Creation
5. Generic Methodology
6. Comparison of Results
7. Summary and Conclusion
8. Limitations
9. Future Scope
10. References
11. Credits

## 1. Motivation
- Everyone deserve to know the truth. 
- Fake news destroys the credibility of people.
- Fake news can hurt some people and Real news can benefit everyone.
- Methods are largely developed for English whereas low resource languages remain out of the focus.

## 2. Problem Statement
- The goal of this project is to find an efficient algorithm which identifies fake news in Hindi language. 
- Due to the lack of resources on Indian regional languages the goal is also to assemble labelled Hindi dataset for automatic fake news detection.
<p align=center> 
Fake news tackled with facts!
</p>    
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123094687-d0c26000-d44a-11eb-9376-9605eef241ad.png" />
</p>
  
## 3. Introduction
- Ensuring that everyone gets the right information is crucial.
- False information or misleading details can be disastrous in many aspects.
- About 57.09% of the total population of India are native Hindi speakers. 
- Lots of fake and manipulative news are posing a huge risk in regional languages.
- An analysis of Hindi fake news on a manually created dataset using various Machine learning -classification algorithms as well as using Deep learning.

## 4. Hindi Dataset Creation
### Sources of Hindi Dataset Creation
1. Danik Bhaskar      www.bhaskar.com/
2. Hindustan Times    www.hindustantimes.com/
3. Dainik Jagran      www.jagran.com/

### Dataset Description
- The data set consist of 24,000 news article out of which 80 percent of data is used for training  data set, and the rest 20 percent have been used for testing.

<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123099762-1cc3d380-d450-11eb-9ee2-a72e8155d8b5.png" />
</p>

- The following figure shows dataset description as follows:
  - 'id' representing unique numberical value.
  - 'title' representing hindi news headline in newspaper.
  - 'text' representing body text under the hindi news article.
  - 'author' representing the author/writer of that news article.
  - 'label' indicating numeric value '0' for fake news and '1' for true news.

<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123100032-5eed1500-d450-11eb-9191-dab860481c7e.png" />
</p>

- There is equal distribution of dataset.
- The following figure shows the bar graph which represents a total of 24,000 news articles distribution between two classes, fake news and real news.

## 5. Generic Methodology
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123103198-682bb100-d453-11eb-902e-1916932993e8.png" />
</p>

- The following figure represents sequential steps performed in order to reach to end goal.

## 6. Comparison of Results
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123104184-5d255080-d454-11eb-948d-11dc323a1714.png" />
</p>

- The following table represents comparison of result after evaluating with different machine learning and deep learning algorithms.
- It can be noted that B-LSTM (Bidirectional Long Short Term Memory) algorithm as compared with other algorithms gave the best results with an accuracy of 95.01% and precision of 90%.

### Architecture used in our model
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123116562-a37fad00-d45e-11eb-9b8e-db4e85dfb1d7.png" />
</p>
<p align="center">
  Bidirectional LSTM Architecture retrieved from https://paperswithcode.com/method/bilstm
</p>

- It is a two way process.
- A Bidirectional LSTM is a sequence processing model that consists of two LSTMs: one taking the input in a forward direction, and the other in a backwards direction. 
### Example of B-LSTM:
<p align="center">
  <img src="https://user-images.githubusercontent.com/47279598/123117182-299bf380-d45f-11eb-8ee4-b278f5c8d8b8.png" />
</p>

- The LSTM model reads the input text in one direction from left to right.
- The B-LSTM model reads the input text from both directions from left to right and right to left.

## 7. Summary and Conclusion
- Automatic fake news detection is a very promising area of research.
- Due to drastic consequences detection of fake news becomes very significant. 
- The Hindi dataset created can be a contribution to other research work. 
- The project proposes a model that can easily absorb other features of news and has a very strong extensibility. 
- B-LSTM was preferred since higher accuracies were achieved of about 95.01%.


## 8. Limitations/ Challenges faced during the project
- Lack of labelled data availability in Indian regional languages.
- The amount of data on social media is massive but unlabeled and hence could not be used for training.
- Also preprocessing of Hindi data was a challenge.
- Due to above limitations remaining available dataset will lead to underfitting of the model.

## 9. Future Scope
- To increase the size of Hindi dataset and make it more robust.
- Testing the model using URL to validate headlines and other parameters.
- To make system adaptive to other languages and detect region specific biases.
- To investigate new features to flag fake news.




## Installation: 
Installation is the next section in an effective README. Tell other users how to install your project locally. Optionally, include a gif to make the process even more clear for other people.

## Usage: 
The next section is usage, in which you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action.

## Contributing: 
Larger projects often have sections on contributing to their project, in which contribution instructions are outlined. Sometimes, this is a separate file. If you have specific contribution preferences, explain them so that other developers know how to best contribute to your work. To learn more about how to help others contribute, check out the guide for setting guidelines for repository contributors.

## Credits: 
Include a section for credits in order to highlight and link to the authors of your project.

## License: 
Finally, include a section for the license of your project. For more information on choosing a license, check out GitHub’s licensing guide! 
