Amazon User Segmentation
Project Overview

      This project focuses on segmenting Amazon users into distinct groups based on their purchasing behavior and preferences using the K-Means Clustering algorithm. By analyzing user data such as annual income and product ratings & product ratings and age, the project helps identify meaningful customer segments that can be leveraged for targeted marketing and personalized recommendations.
      Amazon-like platforms personalize user experiences by analyzing past interactions. This project simulates that concept using clustering techniques to group similar users together.

Objectives

*  Perform customer segmentation using K-Means clustering
*  Identify patterns in user behavior
*  Enable targeted marketing strategies
*  Improve recommendation systems

Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

Key Features

* K-Means Clustering Implementation for user segmentation
* Elbow Method Visualization to determine optimal number of clusters
* Interactive Charts for better data understanding

Methodology

Step 1: Finding Optimal K (Elbow Method)
   Compute WCSS (Within-Cluster Sum of Squares)
   Plot WCSS vs number of clusters
   Identify the "elbow point" where the decrease slows

Step 2: Initialize Centroids
      Randomly select K centroids

 Step 3: Assign Data Points
     Assign each user to the nearest centroid

Step 4: Update Centroids
    Compute new centroid as the mean of assigned points

Step 5: Repeat Until Convergence
    Reassign points
    Stop when no changes occur

Dataset
The dataset includes:
      Age
      Annual Income
      User Ratings

Results
      Users were successfully grouped into distinct clusters
      Each cluster represents a different type of customer behavior
     Insights can be used for:
          Personalized recommendations
          Customer targeting
        Marketing optimization

Conclusion
       This project demonstrates how clustering techniques like K-Means can be effectively used to segment users and generate actionable insights. Such segmentation plays a key role in improving user experience and driving business growth in e-commerce platforms.

Author
    Gopika Sanjeevini
