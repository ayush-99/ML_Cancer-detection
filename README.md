# ML_Cancer-detection
We try to contribute to the problem of cancer diagnosis today.
This problem is a multi-class classification problem. There are 9 classes that have to be predicted here. 
There are 4 features here namely: ID, Gene, Variation, text and the feature we're predicting on is the class
THE PROBLEM OVERVIEW WE ARE TRYING TO SOLVE:
Once sequenced, a cancer tumor can have thousands of genetic mutations. Mutations are the onces which can corroupt the genes which cause cancer. Note. Not all mutations are cancer causing. SO based on these genes and mutations(or variations), they can be classified into 9 different categories. Some of these classes correspond to some forms of cancer.
So in the real world rite now, a domain expert or a medical professional selects one of these genes and it's variation and picks up the literature on it. After giving a huge amount of man hours to this literature, they are able to classify these gene+variation into one of these 9 classes.
Our goal here is to replace the last part by a ML model. This model would accept the Gene, Variation and based on it's training on a huge amount of literature, it will classify this gene+variation into one of the classes of cancer. THis will help save thousands of man hours for a medical professional in classifying the same

SOME CONSTRAINS: 1. Interpretability is important. With the probability output, we also need to give some text based on why the model thinks this is the correct class. This gives                            confidence to the model and we can know based on what exact text is the model predicting the class
                 2. Errors can be very costly.
                 3. No low latency requirement
                 4. Probability of a datapoint belonging to each class is needed.
