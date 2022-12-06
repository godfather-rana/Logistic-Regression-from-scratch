# Logistic-Regression-from-scratch-on-Andrew-ng-s-problem
Here I have implemented logistic regression along with the analysis of cost function associated with each epoch.

# Dataset
The data used here has been taken from Andrew Ng’s Machine Learning course on Coursera. The data consists of marks of two exams for 100 applicants. The target value takes on binary values 1,0. 1 means the applicant was admitted to the university whereas 0 means the applicant didn't get an admission. The objective is to build a classifier that can predict whether an application will be admitted to the university or not.

Here I loaded the data into pandas Dataframe using the read_csv function. I also splitted the data into admitted and non-admitted to visualize the data.

![Screenshot from 2019-07-22 02-03-27](https://user-images.githubusercontent.com/31368133/61596747-148c0980-ac25-11e9-8cb2-15332fd5c7dd.png)

Below shows the decision boundary made by logistic regression implementation.

![Screenshot from 2019-07-22 02-09-56](https://user-images.githubusercontent.com/31368133/61596819-dfcc8200-ac25-11e9-84cb-9dfd8652a956.png)

And finally we have the change in cost with completion of each epoch.

![Screenshot from 2019-07-22 02-12-44](https://user-images.githubusercontent.com/31368133/61596845-3df96500-ac26-11e9-94a2-a3bb29b4b22a.png)
