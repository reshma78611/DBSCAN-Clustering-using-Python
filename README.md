# DBSCAN-Clustering-using-Python
 
 In **Unsupervised Learning** we have different type of algorithms such as:
 
1. Clustering
2. Association Rules
3. Recommendation Engine
4. PCA
5. Text mining
6. NLP


In **Clustering** we have :
1. Hierarchial Clustering
2. K-Means Clustering
3. DBSCAN Clustering

In this repository we will discuss mainly about *DBSCAN Clustering*

   There are some disadvantages in Hierarchial clustering and K - means Clustering, among them main disadvantages are that they doesnt perform well with non-spherical shapes of clusters and sensitive to noise or outliers. 
   
   To deal with this we have *Density Based Spatial Clustering (DBSCAN)* :
   
        -It is mainly used to find outliers and merge them and to deal with non-spherical data
        -Clustering is mainly done based on density of data points (where more number of data points are present).
        
        
   step 1: Mainly we have 2 parameters:
   
            1. eps
            2. Min points
            
   step 2: eps >0 => compulsary
   
            Suppose eps=2 which means it randomly chooses a point x from that point it draws a circle with radius=2 that is nothing but cluster with eps=2
   step 3: Min points, to know neighbourhood is dense enough or not we use min points.
   
            Suppose minpoints = 8, which means neighbourhood has atleast >= 8 data points then it is denser and forms cluster, if < 8 data points then not denser and outliers.
            
   step 4: Border points
   
            In eps neighbourhood that contains less than min points but it belongs to eps neighbourhood of another core point
            
   **Note:**\
      *If not core point and not border point then it is noise or outliers*


## Data Used:
          wholesale customers data: depending on their priorities clusters of customers are formed
          
## Programming:
          Python


## **The Codes regarding this DBSCAN Clustering with different business problem *Clustoring of customers deprnding on their priorities* with its dataset is present in this Repository in detail**
