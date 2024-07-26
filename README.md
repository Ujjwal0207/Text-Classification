<h3>Importing Important Libraries</h3>
<ul>
    <li>I have imported the stopwords from nltk and copied more of them from internet</li>
    <li>Instead of split() function, I am using the tokenizer which makes the job much easier.</li>
    <li>Instead of manually downloading the data from the internet, I have downloaded it using sklearn.datasets.fetch_20newsgroups</li>
</ul>
<h1>Observations</h1>
<p><b>
It seems like recall of some of the classes is excellent while for some other is moderate this is most probably because of selection of features. More accurately we select features, more will be the f1-score, precision and recall values. although from the confusion matrix we can determine that our algorithm is not that bad. Infact it seems to be working very precisely for some classes. And an accuracy of nearly 86% is not that bad. The accuracy is coming out to be equal to the one we got from the inbuilt multinomial naive bayes algorithm. And a better accuracy could be obtained by working on the selection of features. the accuracy can be increased up to 90 percent max by increasing the number of features in the 13th cell to 50,000. but it will not be worthy because as we keep on increasing the number of features the "increase in the accuracy" will keep on decreasing. So it would be more computationally viable to take upto just 10k or 20 k features in our vocabulary for such a dataset.
</b></p>
