# Clustering-K-Means :page_facing_up:
A k means algorithm implementation in Java .Clustering numbers from functions .
UOI-Project for computational intelligence course.

# Create dataset putting noise in it :file_folder:

- If (x1 – 0.5)2 + (x2 – 0.5)2 <0.16, then (x1,x2) is classified in the category C1,

- If (x1 + 0.5)2 + (x2 + 0.5)2 <0.16, then (x1,x2) is classified in the category C1,

- If (x1 – 0.5)2 + (x2 + 0.5)2 <0.16, then (x1,x2) is classified in the category C2,

- If (x1 + 0.5)2 + (x2 – 0.5)2 <0.16, then (x1,x2) is classified in the category C2,
- 
- If (x1,x2) belongs tο 1st or in the 3rd quarter then is classified in the category C3,

- If (x1,x2) belongs to 2nd or in the 4th quarter then is classified in the category C4.

We then add noise only to the training set as follows: for each instance of
training set with a **probability of 0.1** we change its category and assign it to some random one
another category



# Create K-Means algorithm 
