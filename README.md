# engr421-homework-02--na-ve-bayes-classifier-solved
**TO GET THIS SOLUTION VISIT:** [ENGR421 Homework 02- Naïve Bayes’ Classifier Solved](https://www.ankitcodinghub.com/product/engr-421-dasc-521-introduction-to-machine-learning-homework-02-naive-bayes-classifier-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113748&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ENGR421 Homework 02- Naïve Bayes’ Classifier Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this homework, you will implement a naïve Bayes’ classifier using Python. Here are the steps you need to follow:

1. Read Section 5.7 from the textbook.

2. You are given a multivariate classification data set, which contains 195 handwritten letters of size 20 pixels × 16 pixels (i.e., 320 pixels). These images are from five distinct classes, namely, A, B, C, D, and E, where we have 39 data points from each class. The figure below shows five sample figures from each class. You are given two data files:

a. hw02_data_set_images.csv: letter images,

b. hw02_data_set_labels.csv: corresponding class labels.

3. Divide the data set into two parts by assigning the first 25 images from each class to the training set and the remaining 14 images to the test set. (10 points)

print(pcd)

[[0. 0. 0. … 0.68 0.68 0.64]

[0.04 0.24 0.24 … 0.8 0.56 0.24]

[0. 0. 0. … 0.6 0.88 0.8 ]

[0.12 0.44 0.4 … 0.28 0.16 0.08]

[0. 0.12 0.12 … 0.32 0.48 0.44]]

print(class_priors) [0.2 0.2 0.2 0.2 0.2]

5. Calculate the confusion matrix for the data points in your training set using the parametric classification rule you will develop using the estimated parameters. Your confusion matrix should be like the following matrix. (30 points)

print(confusion_matrix) y_truth 1 2 3 4 5 y_pred 1 25 0 0 0 0

2 0 24 1 0 1

3 0 0 24 0 0

4 0 0 0 25 0

5 0 0 0 0 24

6. Calculate the confusion matrix for the data points in your test set using the parametric classification rule you will develop using the estimated parameters. Your confusion matrix should be like the following matrix. (30 points)

print(confusion_matrix) y_truth 1 2 3 4 5 y_pred 1 7 0 0 0 0

2 0 11 3 2 4

3 0 0 7 0 0

4 7 3 3 12 0

5 0 0 1 0 10

What to submit: You need to submit your source code in a single file (.py file) named as STUDENTID.py, where STUDENTID should be replaced with your 7-digit student number.

How to submit: Submit the file you created to Blackboard. Please follow the exact style mentioned and do not send a file named as STUDENTID.py. Submissions that do not follow these guidelines will not be graded.

Cheating policy: Very similar submissions will not be graded.
