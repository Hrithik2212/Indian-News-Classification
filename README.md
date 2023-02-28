# Indian-News-Classification


## Objective 

The objective of this project is to develop a model that can accurately classify news articles as fake or real using Machine Learning and Deep Learning techniques.The project also aims to evaluate the performance of various machine learning models such as Naive Bayes, Artificial Neural Networks (ANN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) using metrics such as accuracy, precision, F1 Score, and Confusion Matrix. The outcome of the project is to provide a tool that can be used by news agencies, social media platforms, and governments to identify and prevent the spread of fake news articles.


## Introduction

Fake or Real News Classification using Machine Learning and Deep Learning Techniques is a project that aims to develop a model that can distinguish between fake and real news articles. In recent years, the rise of social media and online news sources has led to an increase in the spread of misinformation and fake news. It is important to develop methods to detect fake news as it can have serious consequences on society, politics, and public opinion.
The project uses Machine Learning and Deep Learning techniques to analyze news articles and classify them as fake or real. The project involves collecting a diverse dataset of news articles, preprocessing the data, and using various text vectorization techniques to convert the text data into numerical data.
The project uses various machine learning models such as Naive Bayes, Artificial Neural Networks (ANN), Recurrent Neural Networks (RNN), and Long Short-Term Memory (LSTM) to classify the news articles as fake or real. The project also evaluates the performance of the models using metrics such as accuracy, precision, F1 Score, and Confusion Matrix.
The outcome of this project can have significant implications on identifying and preventing the spread of fake news. This project can be used by news agencies, social media platforms, and governments to identify fake news articles and prevent their spread.


# Metrics

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precission</th>
      <th>F1 Score</th>
      <th>Recall</th>
      <th>ROC_AUC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Naive Bayes</td>
      <td>0.978552</td>
      <td>0.994083</td>
      <td>0.976744</td>
      <td>0.960000</td>
      <td>0.977475</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ANN - TwoLayers</td>
      <td>0.990617</td>
      <td>0.985836</td>
      <td>0.990043</td>
      <td>0.994286</td>
      <td>0.990830</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Simple RNN</td>
      <td>0.943700</td>
      <td>0.918478</td>
      <td>0.941504</td>
      <td>0.965714</td>
      <td>0.944978</td>
    </tr>
    <tr>
      <th>3</th>
      <td>LSTM</td>
      <td>0.962466</td>
      <td>0.939891</td>
      <td>0.960894</td>
      <td>0.982857</td>
      <td>0.963651</td>
    </tr>
  </tbody>
</table>
