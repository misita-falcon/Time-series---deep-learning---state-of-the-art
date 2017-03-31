
# Deep Learning and Time Series

## Deef Belief Network with Restricted Boltzmann Machine

### 2017 

- [Ryu, S., Noh, J., & Kim, H. (2017). Deep neural network based demand side short term load forecasting. Energies, 10(1), 3.](https://www.scopus.com/record/display.uri?eid=2-s2.0-85009236706&origin=resultslist&sort=plf-f&src=s&st1=deep+learning+time+series&nlo=&nlr=&nls=&sid=306771ADB79C2181330A84526BFB4363.wsnAw8kcdt7IPYLO0V48gA%3a210&sot=b&sdt=cl&cluster=scosubtype%2c%22ar%22%2ct&sl=40&s=TITLE-ABS-KEY%28deep+learning+time+series%29&relpos=4&citeCnt=0&searchTerm=)

  Summary: The paper proposes deep neural network (DNN)-based load forecasting models and apply them to a demand side empirical load database. DNNs are trained in two different ways: a pre-training restricted Boltzmann machine and using ReLu without pre-training.
   
  Notes:
   - Model 1 train -> greedy layer-wise manner
   - Model 1 Fine-tuning connection weights -> Back-propagation 
   - Model 2 train -> ReLu 
   - Model Sizes -> trial and error 

- [Qiu, X., Ren, Y., Suganthan, P. N., & Amaratunga, G. A. (2017). Empirical Mode Decomposition based ensemble deep learning for load demand time series forecasting. Applied Soft Computing, 54, pages 246-255.](https://www.scopus.com/record/display.uri?eid=2-s2.0-85011866839&origin=resultslist&sort=plf-f&src=s&st1=deep+learning+time+series&st2=&sid=306771ADB79C2181330A84526BFB4363.wsnAw8kcdt7IPYLO0V48gA%3a10&sot=b&sdt=b&sl=40&s=TITLE-ABS-KEY%28deep+learning+time+series%29&relpos=0&citeCnt=0&searchTerm=)

  Summary: In this paper a Deep Belief Network (DBN) including two restricted Boltzmann machines (RBMs) was used to model load demand series.

### 2016

- [Hirata, T.a, Kuremoto, T.a, Obayashi, M.a, Mabu, S.a, Kobayashi, K.b (2016). A novel approach to time series forecasting using deep learning and linear model. IEEJ Transactions on Electronics, Information and Systems, 136(3), pages 348-356.](https://www.scopus.com/record/display.uri?eid=2-s2.0-84960451045&origin=resultslist&sort=r-f&src=s&st1=deep+learning+time+series&nlo=&nlr=&nls=&sid=306771ADB79C2181330A84526BFB4363.wsnAw8kcdt7IPYLO0V48gA%3a210&sot=b&sdt=cl&cluster=scosubtype%2c%22ar%22%2ct&sl=40&s=TITLE-ABS-KEY%28deep+learning+time+series%29&relpos=3&citeCnt=0&searchTerm=) 

  Summary: This paper presents a hybrid prediction method using DBNs (deep Belief Network) and ARIMA. *(without access to full paper)*

- [Takaomi Hirata, Takashi Kuremoto, Masanao Obayashi, Shingo Mabu, Kunikazu Kobayashi (2016).Deep Belief Network Using Reinforcement Learning and Its Applications to Time Series Forecasting. International Conference on Neural Information Processing ](http://link.springer.com/chapter/10.1007/978-3-319-46675-0_4)

  Summary: This paper introduces a reinforcement learning method named stochastic gradient ascent (SGA) to the DBN with RBMs instead conventional BackPropagation to predict a benchmark named CATS data.

- [Peng Jiang, Cheng Chen, Xiao Liu (2016). Time series prediction for evolutions of complex systems: A deep learning approach. Control and Robotics Engineering (ICCRE), 2016 IEEE International Conference on](http://ieeexplore.ieee.org/document/7476150/) 

  Summary: The paper proposes a deep learning approach, which hybridizes a deep belief networks (DBNs) and a nonlinear kernel-based parallel evolutionary SVM (ESVM), to predict evolution states of complex systems in a classification manner.

  Notes:
   - Top layer -> SVM
   - Fine-tuning connection weights -> Back-propagation 
  
- [Yuhan Jia; Jianping Wu; Yiman Du (2016). Traffic speed prediction using deep learning method. Intelligent Transportation Systems (ITSC), 2016 IEEE 19th International Conference on](http://ieeexplore.ieee.org/document/7795712/)

  Summary: In this paper, a deep learning method, the Deep Belief Network (DBN) model, is proposed for short-term traffic speed information prediction.

  Notes:
   - Model train -> greedy layer-wise manner
   - Fine-tuning connection weights -> Back-propagation
   - Model Sizes -> several ccombinations

### 2015

- [Xueheng Qiu; Le Zhang; Ye Ren; P. N. Suganthan; Gehan Amaratunga (2015). Ensemble deep learning for regression and time series forecasting. Computational Intelligence in Ensemble Learning (CIEL), 2014 IEEE Symposium on](http://ieeexplore.ieee.org/abstract/document/7015739/)

  Summary: This paper proposes an ensemble of deep learning belief networks (DBN) for regression and time series forecasting on electricity load demand datasets. Another contribution is to aggregate the outputs from various DBNs by a support vector regression (SVR) model.

  Notes:
   - Top layer -> support vector regression (SVR)

### 2014

- [Takashi Kuremotoa, Shinsuke Kimuraa, Kunikazu Kobayashib, Masanao Obayashia (2014).Time series forecasting using a deep belief network with restricted Boltzmann machines. Neurocomputing, 137(5), pages 47–56](http://www.sciencedirect.com/science/article/pii/S0925231213007388)

  Summary: This papers proposes a method for time series prediction using deep belief nets (DBN) (with 3-layer of RBMs to capture the feature of input space of time series data).
  
  Notes:
   - Mode Train -> greedy layer-wise manner
   - Fine-tuning connection weights -> Back-propagation
   - Mode sizes and learning rates -> PSO

## Long short-term memory

### 2017 

- [Zheng Zhao; Weihai Chen; Xingming Wu; Peter C. Y. Chen; Jingmeng Liu (2017). LSTM network: a deep learning approach for short-term traffic forecast. IET Intelligent Transport Systems, 11(2), 3, pages 68 - 75](http://ieeexplore.ieee.org/document/7874313/)

  Summary: This paper pses a traffic forecast model based on long short-term memory (LSTM) network, that considers temporal-spatial correlation in traffic system via a two-dimensional network which is composed of many memory units. 

### 2016

- [Yujin Tang; Jianfeng Xu; Kazunori Matsumoto; Chihiro Ono (2016). Sequence-to-Sequence Model with Attention for Time Series Classification. Data Mining Workshops (ICDMW), 2016 IEEE 16th International Conference on](http://ieeexplore.ieee.org/document/7836709/)

  Summary: The paper proposes a model incorporating a sequence-to-sequence model that consists two LSTMs, one encoder and one decoder. The encoder LSTM accepts input time series, extracts information and based on which the decoder LSTM constructs fixed length sequences that can be regarded as discriminatory features. The paper also introduces the attention mechanism.
  
2016 -> [Deep learning for stock prediction using numerical and textual information](http://ieeexplore.ieee.org/document/7550882/) <br>  
  
2016 -> [Travel time prediction with LSTM neural network](http://ieeexplore.ieee.org/document/7795686/) <br>  
  
2016 -> [Building energy load forecasting using Deep Neural Networks](http://ieeexplore.ieee.org/document/7793413/) <br>
Model train -> Backpropagation <br>

2016 -> [Traffic flow prediction with Long Short-Term Memory Networks (LSTMs)](http://ieeexplore.ieee.org/document/7848593/) <br>
  
2016 -> [Deep neural network architectures for forecasting analgesic response](http://ieeexplore.ieee.org/document/7591352/) <br>

2016 -> [Long short-term memory model for traffic congestion prediction with online open data](http://ieeexplore.ieee.org/document/7795543/) <br>
Sizes and learning rates -> several ccombinations <br>
 
## Auto-Encoders

2016 -> [Deep learning architecture for air quality predictions](https://www.scopus.com/record/display.uri?eid=2-s2.0-84991071427&origin=resultslist&sort=plf-f&src=s&st1=deep+learning+time+series&nlo=&nlr=&nls=&sid=306771ADB79C2181330A84526BFB4363.wsnAw8kcdt7IPYLO0V48gA%3a210&sot=b&sdt=cl&cluster=scosubtype%2c%22ar%22%2ct&sl=40&s=TITLE-ABS-KEY%28deep+learning+time+series%29&relpos=9&citeCnt=0&searchTerm=) <br>
Train -> greedy layer-wise manner <br>
Top layer -> logistic regression <br>
Fine-tuning connection weights -> Back-propagation <br>
Sizes -> several ccombinations <br>

2016 -> [Rainfall Prediction: A Deep Learning Approach](http://link.springer.com/chapter/10.1007/978-3-319-32034-2_13) <br>
Top layer -> multilayer perceptron <br>
Sizes and learning rates -> several combinations <br>
  
2016 -> [Optimized Structure of the Traffic Flow Forecasting Model With a Deep Learning Approach](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7517319) <br>
Fine-tuning connection weights -> Levenberg-Marquadt <br>
  
2015 -> [Forecasting the weather of Nevada: A deep learning approach](http://ieeexplore.ieee.org/document/7280812/) <br>
Top layer -> feed-forward neural network  <br>

2013 -> Time-Series Forecasting of Indoor Temperature Using Pre-trained Deep Neural Network](http://link.springer.com/chapter/10.1007/978-3-642-40728-4_57) <br> 
 
## Deef Belief Network with Restricted Boltzmann Machine - Auto-Encoders

2016 -> [Deep Learning for Wind Speed Forecasting in Northeastern Region of Brazil](http://ieeexplore.ieee.org/document/7424040/) <br>
Train -> greedy layer-wise manner <br>
Fine-tuning connection weights -> Levenberg-Marquadt <br>
Sizes -> several combinations <br>

## Long Short-Term Memory - Deef Belief Network with Restricted Boltzmann Machine - AutoEncoders Long Short-Term Memory

2016 -> [Deep Learning for solar power forecasting — An approach using AutoEncoder and LSTM Neural Networks]( http://ieeexplore.ieee.org/document/7844673/) <br>

## Others

2017 -> [Convolutional neural networks for time series classification](http://ieeexplore.ieee.org/document/7870510/) <br>
Type -> Convolutional neural network <br>

2017 -> [Short term power load forecasting using Deep Neural Networks](http://ieeexplore.ieee.org/document/7876196/) <br>
Type -> Recurrent neural network <br>

2016 -> [Deep Convolutional Factor Analyser for Multivariate Time Series Modeling](http://ieeexplore.ieee.org/document/7837993/) <br>
Type -> Convolutional neural network <br>

2016 -> [A Deep Learning Approach for the Prediction of Retail Store Sales](http://ieeexplore.ieee.org/document/7836713/) <br>
Type -> Not specified <br>

2016 -> [Optimization of decentralized renewable energy system by weather forecasting and deep machine learning techniques](http://ieeexplore.ieee.org/document/7796524/) <br>
Type -> a novel optimization tool platform using Boltzmann machine algorithm for NMIP <br>

2015 -> [Weather forecasting using deep learning techniques](http://ieeexplore.ieee.org/document/7415154/) <br>
Type -> Recurrent neural network, convolutional neural network <br>
  
2014 -> [Time Series Classification Using Multi-Channels Deep Convolutional Neural Networks](http://link.springer.com/chapter/10.1007/978-3-319-08010-9_33) <br>
Type -> Multi-Channels Deep Convolution Neural Networks <br>
  
  
## Reviews
  
2017 -> [Deep Learning for Time-Series Analysis](https://arxiv.org/abs/1701.01887) <br>
  
2014 -> [A review of unsupervised feature learning and deep learning for time-series modeling](http://www.sciencedirect.com/science/article/pii/S0167865514000221) <br>

2012 -> [Deep Learning for Time Series Modeling](https://pdfs.semanticscholar.org/a241/a7e26d6baf2c068601813216d3cc09e845ff.pdf) <br>
