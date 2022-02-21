# heartdiseasesproject
In this project, I built a machine learning system that can predict whether a person has heart disease or not.
The first step of this project is to get the heart dataset containing various health parameters that correspond to an individual’s healthiness.
In the next step, processing the dataset will be needed to make it compatible with machine learning algorithms to learn and work better. One of the significant pre-processing steps is feature normalization.
Typically, the range of values for each feature can be varied. For instance, in this dataset, the gender column is either zero or one, but the age column has a wider range of values. This diversity can cause a problem when the model tries to compare features’ importance. Therefore, feature normalization is a way to rescale every feature between 0 and 1. I use min-max normalization here.
In the next part, which is called train-test split, I need to split the data into training and testing data that will fit the machine learning models.
