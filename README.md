# Decision-Tree-in-Python-for-Continuous-Attributes
This code constructs a Decision Tree for a dataset with continuous Attributes. Each training instance has 16 numeric attributes (features) and a classification label, all separated by commas. In deciding which attribute to test at any point, the information gain metric is used. The node test threshold for each potential attribute is set using this same metric i.e. at each point,  all the values that exist for a particular attribute in the remaining instances are ordered, and  threshold values that are (half way) between successive attribute values are used to find the Information Gain. The threshold value that gives the highest information gain is used. The same attribute can be tested again later in the tree (with a different threshold).
