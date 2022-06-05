# Term_Deposit_Lead_Prediction
<ul>
<li>Aim is to implement machine learning model to identify a list of customers who could be contacted via telecommunication channels to open a term deposit account with this institution. The firm wants a list of only 1000 customers for the target list to increase the number of term deposit accounts.</li>
<li>Out of 17 features present in dataset, after normalizing and cleaning data and generating new unique fields from the original features, I've selected 37 features using RandomForestClassifier with ensemble learning.</li>
<li>Then using the weighted average of each of the 37 features driven from the historic data set, i used those values to calculate the total score of new customers who we are targeting .</li>
<li>Rearranged the new customer list based on their total score and then selecting the top 1000</li>
</ul>
