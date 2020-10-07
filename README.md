# CUSTOMER SEGMENTATION
Machine Learning project

Imagine that you are treating the grocery shop owner that you shop every day, as you treat your significant other. That can be fun at the beginning, however may cause disastrous situations too. Likewise, it can be unfavorable for a company to manage its relationships with every customer similarly.
Customer segmentation enables a company to customize its relationships with the customers, as we do in our daily lives.
When you perform customer segmentation, you find similar characteristics in each customer’s behavior and needs. Then, those are generalized into groups to satisfy demands with various strategies. Moreover, those strategies can be an input of the
Targeted marketing activities to specific groups
Launch of features aligning with the customer demand
Development of the product roadmap
There are different products/solutions available in the market from packaged software to CRM products. Today, I will apply an unsupervised machine learning algorithm with Python.
# Project idea 
Customer segmentation is a technique in which we divide the customers based on their purchase history, gender, age, interest, etc. It is useful to get this information so that the store can get help in personalize marketing and provide customers with relevant deals. With the help of this project, companies can run user-specific campaigns and provide user-specific offers rather than broadcasting same offer to all the users.
Introduction
Customer segmentation is the practice of dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests and spending habits.
Companies employing customer segmentation operate under the fact that every customer is different and that their marketing efforts would be better served if they target specific, smaller groups with messages that those consumers would find relevant and lead them to buy something. Companies also hope to gain a deeper understanding of their customers’ preferences and needs with the idea of discovering what each segment finds most valuable to more accurately tailor marketing materials toward that segment.
Customer segmentation relies on identifying key differentiators that divide customers into groups that can be targeted. Information such as a customers’ demographics (age, race, religion, gender, family size, ethnicity, income, education level), geography (where they live and work), psychographic (social class, lifestyle and personality characteristics) and behavioral (spending, consumption, usage and desired benefits) tendencies are taken into account when determining customer segmentation practices.

# Benefits of customer segmentation include:

1.Personalization
Personalization ensures that you provide exceptional customer experience.
2. Customer Retention
It is 16 times as costly to build a long-term business relationship with a new customer than simply to cultivate the loyalty of an existing customer.
3. Better ROI for marketing
Affirmations that right marketing messages are sent to the right people based on their life cycle stage.
4. Reveal new opportunities
Customer segmentation may reveal new trends about products and it may even give the first mover’s advantage in a product segment.

# Approach — Machine Learning
Unsupervised Learning is a class of Machine Learning techniques to find the patterns in data. The data given to unsupervised algorithm are not labelled, which means only the input variables(X) are given with no corresponding output variables. In unsupervised learning, the algorithms are left to themselves to discover interesting structures in the data.
There are some analytics techniques that can help you with segmenting your customers. These are useful especially when you have a large number of customers and it’s hard to discover patterns in your customer data just by looking at transactions. The two most common ones are:

# Clustering
Clustering is an exploration technique for datasets where relationships between different observations may be too hard to spot with the eye.
2. Principal Component Analysis (PCA)
PCA is a statistical procedure that uses an orthogonal transformation to convert a set of observations of possibly correlated variables (entities each of which takes on various numerical values) into a set of values of linearly uncorrelated variables called principal components.
The following code takes advantage of the Mall Customer Segmentation Data to demonstrate the ability of K-Means clustering algorithm to identify customer’s segments.

# K-Means
K-means clustering is an unsupervised machine learning algorithm for clustering ’n’ observations into ‘k’ clusters where k is predefined or user-defined constant. The main idea is to define k centroids, one for each cluster.
The K-Means algorithm involves:
Choosing the number of clusters “k”.
Randomly assign each point to a cluster
Until clusters stop changing, repeat the following:
A. For each cluster, compute the cluster centroid by taking the mean vector of points in the cluster.
B. Assign each data point to the cluster for which the centroid is the closest.
Two things are very important in K means, the first is to scale the variables before clustering the data *, and second is to look at a scatter plot or a data table to estimate the number of cluster centers to set for the k parameter in the model.
Note: Scaling is necessary when a distance between attributes is not sensible(i.e. distance between Age and Height; different metrics are important too!). On the other hand, if you have attributes with a well-defined meaning(e.g. latitude and longitude) then you should not scale your data, because this will cause distortion.
Our hypothesis and the answer we are trying to give using k-means is that there is an intuition that customers can be grouped (clustered) according to their spending score given their income. My null hypothesis (which I am trying to disprove) is that there are no groups(clusters) of customers based on these.
Cluster Analysis: Create, Visualize and Interpret Customer Segments
Exploring methods for cluster analysis, visualizing clusters through dimensionality reduction and interpreting clusters through exploring impactful features.
Although we have seen a large influx of supervised machine learning techniques being used in organizations these methods suffer from, typically, one large issue; a need for labeled data. Fortunately, many unsupervised methods exist for clustering data into previously unseen groups, thereby extracting new insights from your clientele.
This article will guide you through the ins and outs of clustering customers. Note that I will not only show you which sklearn package you can use but more importantly, how they can be used and what to look out for.
As always, the data is relatively straightforward and you can follow along with the notebook here. It contains customer information from a Telecom company and is typically used to predict churn

[Click here](https://medium.com/@bsreeja.cse/customer-segmentation-6b8f08317059) to look into my blog for more details.
