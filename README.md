Download Link: https://assignmentchef.com/product/solved-bitsf464-assignment-1a-fischers-linear-discriminant
<br>



<ol>

 <li>In this problem, you will implement Fischer’s Linear Discriminant from scratch as learnt in class, i.e. given the higher dimensional data reduce the data to one dimension while maximizing difference of means and minimizing sum of variances of the clusters. Finally, calculate the intersection point of both the normal distributions corresponding to the collapsed clusters and find the discriminant vector in 1-D and 3-D.</li>

 <li>Note that, for this question, you need not make any train-test split and you can use the entire data for the procedure.</li>

 <li>Try to vectorize your code as much as possible to make your computations faster and efficient. Do not hard code any parts of the implementation unless it is absolutely necessary.</li>

</ol>

Plot of the higher dimensional data. (you can use Matplotlib’s 3D plotting feature for this)

Plots of the reduced clusters and their corresponding normal distribution in two separate plots. It is recommended that you use two different colors <em>(say red and blue) </em>to represent the two classes. Also, do visualize the discriminant line in your plots.

<ol start="4">

 <li>The intersection point of both the normal distributions and unit vector along the discriminant line in 1-D and 3-D.</li>

</ol>

Assignment-1B: Naive Bayes Classifier

Deadline: TBD

<h1>1       General Instructions</h1>

<ol>

 <li>This assignment is a coding project and is expected to done in groups. Each group can contain at most <strong>three </strong> Make sure that all members in the group are registered to this course and please try to maintain the same group for all the assignments.</li>

 <li>This assignment is expected to be done in Python using standard libraries like NumPy, Matplotlib and Pandas. You can use Jupyter Notebook and any other python in-built data structure or library. No other ML libraries like scikit/sklearn, TensorFlow, Torch etc. should be used.</li>

 <li>Refrain from directly copying codes/snippets from other groups or the internet as all codes will be put through a plagiarism check.</li>

 <li>All deliverable items (.py files, .ipynb files, report, images) should be put together in a single .zip Rename this file as NB hid-of-first-memberi (preferably ID number of the student submitting) before submission.</li>

 <li>Submit the zip file on CMS/GForms on or before the aforementioned deadline. Please note that this is a hard deadline and no extensions or exemptions will be given. The demos for this assignment will be held on a later date which shall be conveyed to you by the IC. All group members are expected to be present during the demo.</li>

 <li>Dataset for this assignment can be found <a href="https://drive.google.com/file/d/1Cvrm5fR1EXytEVF3OelHK4EZu6t3FOZe/view?usp=sharing">here</a><a href="https://drive.google.com/file/d/1Cvrm5fR1EXytEVF3OelHK4EZu6t3FOZe/view?usp=sharing">.</a></li>

</ol>

<h1>2       Problem Statement</h1>

<ol>

 <li>In this problem, you will implement a simple Naive Bayes classifier to classifiy mails as spam or not. You will need to create a 7-fold cross validation to train and test your model. You may choose to discard various stop words, commas, fullstops, numbers, hyphens, brackets, exclamation marks and any other single/double letter words (such as a, an, the, be etc) which do not contribute to the sentiment of the text.</li>

 <li>Use laplace smoothening to avoid the problem of divison by zero.</li>

 <li>Try to vectorize your code as much as possible to make your computations faster and efficient. Do not hard code any parts of the implementation unless it is absolutely necessary.</li>

</ol>

Accuracy of your model over each fold and the overall average accuracy.

Major limitations of the Naive Bayes classifier.

<ol>

 <li></li>

</ol>

<h1>2       Problem Statement</h1>

<ol>

 <li>In this problem, you will implement a linear perceptron as discussed in class. You have two different datasets for this assignment on which you need to train and test your model independently. Create 70:30 train-test splits on both the datasets and train the model for a maximum of 10<sup>6 </sup>iterations in case the model does not converge on the given dataset.</li>

 <li>Try to vectorize your code as much as possible to make your computations faster and efficient. Do not hard code any parts of the implementation unless it is absolutely necessary.</li>

</ol>

Accuracy of your model on both the datasets.

Dataset which was more linearly separable.

<ol start="4">

 <li>Major limitations of the Perceptron classifier.</li>

</ol>