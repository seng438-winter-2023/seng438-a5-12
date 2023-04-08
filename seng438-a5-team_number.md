**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group 12:            |               |
|-----------------     |---------------|
| Student Names:       |      UCID     |
| Esohe Aideyan        |    30135560   |
| Jack Barrie          |    30088832   |
| Tamunomiete Brown    |    30130009   |
| Dyenaan Dapoet       |    30126758   |

# Introduction

# 
This assignment was an opportunity for the group to familiarize ourselves with Software Testing and Reliability as well as Software Testing and Reliabilty assessment tools. The assignment allowed us to fully understand software testing and reliability by selecting a set of models that will provide the best fit for project data using model ranking. It also provided a visual representation that made it easy to check whether the target failure rate or MTTF was met. 

# Assessment Using Reliability Growth Testing 
Failure Count for failure report 9 using SRTAT:\
![image](https://user-images.githubusercontent.com/85323597/230689760-34ee4d0e-8d76-464d-9fad-50756c905675.png)

Time between failures 1 for failure report 10 using SRTAT:\
![geometric](https://user-images.githubusercontent.com/85323597/230697857-877ad988-a164-404a-8f2a-1a257eb5f056.png)\
This graph was generated using the Geometric model. It is clear from the graph that this model doesnt work with this dataset, so this model was discarded.

Time between failures 2 for failure report 10 using SRTAT:\
![image](https://user-images.githubusercontent.com/85323597/230689849-1bda4ac3-b294-45ea-b4b4-cddc83d9e18e.png)\
This graph was generated using the Littlewood and Varral's Baysian Reliability model. The prediction line fits the data points well. The model also isnt influenced significantly by the outliers in the graph. Both the low and high MTTF's are modeled with reasonable accuracy.


# Assessment Using Reliability Demonstration Chart 
We used DATASET3.dat for the RDC. The largest failure count was 16, and the time it took was 153, so calculating the MTTF we got 153/16 = 9.56, which we rounded to 10 for simplicity. Using the RDC-11 Excel sheet, we graphed the data which resulted in the following: \
![mttf](https://user-images.githubusercontent.com/85323597/230688329-254ded9f-fc7e-4fdf-8bc4-a6d65e078832.png)\
Based on the graph, we can see that the systems reliability begins in the continue test area, while proceeding to the accept area. This tells us that the system reliability is within the acceptable range. 

RDC for double the MTTF:\
![double_mttf](https://user-images.githubusercontent.com/85323597/230689332-535bb24a-a77c-4847-88a9-d3f91a6738b9.png)\
This plot is of double the MTTF, which results in a trend in the continue zone of the RDC. The data is moving towards the reject zone, so we can say that the system is somewhat reliable.   

RDC for half the MTTF:\
![half_mttf](https://user-images.githubusercontent.com/85323597/230689348-1f99ccfa-b16f-48b7-aa92-d0bb7bb7a7cf.png)\
This plot is of half the MTTF, which results in a trend beginning in the continue zone, and moving into the accept zone. Therefore we can conclude that the system is reliable based on this plot being within the acceptable range. 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned
A major difficulty we encountered as a group was getting the right dataset to run on our selected assessment tool (SRTAT).

# Comments/feedback on the lab itself
This lab was a bit more frustating compared to the previous labs, as the instructions were quite vague and the applications needed to complete the assignment were not neccessarily responsive. However, the lab helped to bridge the gap between what had been taught in class and the actual uses of Software Testing and Reliability. It also gave the group a feel of actual tools and applications that are used to test software and reliability which would be useful as we advance in our Software Engineering careers.
