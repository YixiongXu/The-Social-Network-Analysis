# The-Social-Network-Analysis

The purpose of the project is to generate a basic sociogram and interpret centrality measures and clustering procedures from it. SNA resolves relational information as additional fields that can be included in the model. These exported key performance indicators measure an individual's social characteristics. Combining these social attributes with individual-based measurements provides a better overview of the individual, thus improving the predictive accuracy of the model.

![image](https://user-images.githubusercontent.com/70576346/121510691-7a9cf800-ca1a-11eb-954b-bfd6c21da5ee.png)

It depicts the network structure of nodes and bonds, edges, or connections to them to investigate social structures. It allows us to find some of the most characteristic origins (nodes).

#Practical Use
  
  -Accurately market people and recommend personalized goods and services.
  
  -cutting off the key nodes in the network can effectively stop the spread of infectious diseases.
  
  -Identify fraud groups in the Internet financial industry and make anti-fraud predictions.

After dividing social networks, you can accurately market people and recommend personalized goods and services, such as JD.com;
The spread of disease is also spread outward by a central point, cutting off the key nodes in the network can effectively stop the spread of infectious diseases;
Identify fraud groups in the Internet financial industry and make anti-fraud predictions;

![image](https://user-images.githubusercontent.com/70576346/121362326-99db4d00-c968-11eb-8444-097b99286f10.png)

In the project, I will build a variety of different social networks that focus on different feature. Then visually find out the connection between closeness, betweeness centralities, mutual connections, vertices, groups(cliques) and graphical analysis objects.

https://user-images.githubusercontent.com/70576346/121371009-ca72b500-c96f-11eb-9fb2-ccdb9e906782.mp4

#Centrality Measures

![image](https://user-images.githubusercontent.com/70576346/121510336-1b3ee800-ca1a-11eb-95a3-fd955bcea22e.png)

  Degree Centrality
  
Degree centrality is defined as the number of links to events on a node. For "best friends ", more central students were more popular. So according to these figures shown in the video, we can intuitively find out the students who have the highest Closeness value. Based on the number list shown in the video, we can see that student 8 has a high sort position among students.

The first three csv files are obtained that list the students' digital evaluation forms of their relationships. I can model the composition of these data with 'plot.igraph'. And they can get a straight classification of sort based on degree. It is important to note that the algorithm of the standardized score is 18/(29-1)=0.64 for student 8 in my calculation.
  
  -Closeness Centrality
  
Student 21 has the highest closeness centrality in "bestfriends" network. Student 14 and 16 have the highest closeness centrality in the "geton" measure. Student 21 has the highest closeness centrality in "workwith" network. 

I found some duplicate numbers while looking at the data tables of the outputs. This shows that some students have very similar social networks -- they are people in the same circle.

  -Betweeness Centrality
  
represents how essential a vertice is in the network. Vertices with high degrees of betweeness can have considerable impact in the network because they control the transmission of information between other vertices. On the other hand, "degree centrality" suggests how popular a node is within the social network.

# Visualization

![image](https://user-images.githubusercontent.com/70576346/121697250-74347c00-caff-11eb-8e7c-ef91d2db7a92.png)

As I notice in the picture, except for the marginal student25, student18, most of the students have close internal connections. They can be called a cluster. Unlike csv file "bestfriends", in the field of "geton", most students are in a whole cluster.

# Data Wrangling

![image](https://user-images.githubusercontent.com/70576346/121693096-6250da00-cafb-11eb-88a0-65aef86baf06.png)

Find the right data set on the ICON website, model it with spot.igraph, and then derive intuitive high-frequency words and center words by dyad_census and cliques instructions, and more.

# Limitations

- There are not enough data samples.

- The social connections given by students are somewhat subjective.


  -Citation:

Christakis, N. A., Fowler, J. H., Imbens, G. W., & Kalyanaraman, K. (2010). An empirical model for strategic network formation (No. w16039).

Uetake, K. (2014). Estimating a model of strategic network formation and its effects on performance: An application to the US venture capital markets.Unpublished manuscript, Yale School of Management.

Sheng, S. (2020). A structural econometric analysis of network formation games through subnetworks.Econometrica,88(5), 1829-1858.Molinari, F. (2020). 

Microeconometrics with Partial Identification.arXiv preprint arXiv:2004.11751.
