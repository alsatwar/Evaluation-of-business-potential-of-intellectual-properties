# Feed-Forward-Neural-Network-approach-for-evaluating-business-potential-of-intellectual-properties

Artificial Neural Networks (ANN) has been phenomenal in predictive analytics of business problems. This study paved to compute business potential of individual patents using Feed-Forward-Neural Network algorithm to predict the likelihood of a patent to survive until its maximum expiration date. The binary classification is named as Core-Business-Patents (CBPs) and Non-Core-Business-Patents (Non-CBPs). This project aimed to aid businesses identifying their business potential of intellectual properties, because patents are retained when profits created are larger than the maintenance fee, finding emerging technologies of competitive firms. A total of 31 indicators and maintenance fee data was used for learning a FFNN model. 

![CHC](https://github.com/alsatwar/Feed-Forward-Neural-Network-approach-for-evaluating-business-potential-of-intellectual-properties/blob/master/Images/Untitled-1.png)

# Evaluation metric

It should be noted that this approach attempted to increase the F2-measure owing to its goal of identifying CBPs that have the potential to create a business value through retainment. That is, the recall value is considered more important than the precision value because a false negative rate is more critical than a false discovery rate in a practical business environment

# Performance Evaluation

In the confusion matrix of the test set, there are 22,188 patents in the true-positive (TP) category, meaning that they were retained until their maximum lifetime. In terms of the false-positive (FP) category, there are 14,087 patents that were not maintained but were expected to be retained until their maximum lifetime, whereas the false-negative (FN) category includes 3,125 patents that were not held for their maximum lifetime but were determined by the model to be non-CBPs. The true-negative (TN) category refers to patents that were abandoned before they reached their maximum lifetime but were deemed to be CBPs.
 
 # Graph shows the variance of the precision recall and F2-Measure.

The business potential of a patent was evaluated based on the prediction result regarding the likelihood that a patent survives until its maximum expiration date. this approach adjusted the threshold t of the patent’s business potential value to address the business potential from various viewpoints. Indeed, the performance of a decision system can be analyzed from multiple viewpoints by adjusting the threshold for determining the positive/negative state of a predicted value.
![sc](https://github.com/alsatwar/Feed-Forward-Neural-Network-approach-for-evaluating-business-potential-of-intellectual-properties/blob/master/Images/download%20(1).png)

# Confusion Matrix :
![i](https://github.com/alsatwar/Feed-Forward-Neural-Network-approach-for-evaluating-business-potential-of-intellectual-properties/blob/master/Images/0.7.png)

# References :
1.	Guellec, D. & de la Potterie, B.v.P. (2000). Applications, grants and the value of patent. Economics letters, 69(1), 109–114.

2.	Pakes, A. (1984). Patents as options: Some estimates of the value of holding European patent stocks. In: National Bureau of Economic Research Cambridge, Mass., USA.

3.	Lemley, M. A., & Shapiro, C. (2006). Patent holdup and royalty stacking. Tex. L. Rev. 85, 1991.

4.	Bader, M. A., Gassmann, O., Ziegler, N., & Ruether, F. (2012). Getting the most out of your IP–patent management along its life cycle. Drug Discovery Today, 17(7–8), 281–284.

5.	Jaewoong Choia , Byeongki Jeonga , Janghyeok Yoona, , Byoung-Youl Cohb , Jae-Min Leeb(2020). A novel approach to evaluating the business potential of intellectual properties: A machine learning-based predictive analysis of patent lifetime. Expert Systems with Applications.

6.	Lai, Y.-H., & Che, H.-C. (2009). Modeling patent legal value by extension neural network. Expert Systems with Applications, 36(7), 10520–10528.

7.	Trappey, A. J., Trappey, C. V., Wu, C.-Y., & Lin, C.-W. (2012). A patent quality analysis for innovative technology and product development. 
