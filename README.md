# ML OPS Assignment 4 

1) Add a functionality to use "DecisionTree" classifier https://scikit-learn.org/stable/modules/tree.html#classification
2) Have 5 different splits of train/test/valid, and will report performance of existing SVM and the new DecisionTree classifier. Make sure you are doing  hyper-parameter turning for both the classifiers.
3) Compute the mean and standard deviations of both the classifier's performances.
4) Interpret the numbers. Write an observation.
5) Identify if there is more to the classifier comparison than just the numbers? -- Can you somehow compare the predicted labels, instead of the metrics.
6) Push the code to your repo. Provide the branch link
7. write the performance metrics from step 3 in the readme.md. in following format
 run svm decision_tree
 1 x x
 2 x x
 3 x x
 4 x x
 5 x x
 mean x x
 std x x


# answer for #7 
                                                  svm                                      decision_tree
0  {'accuracy_score': 0.9832402234636871, 'f1_sco...  {'accuracy_score': 0.8659217877094972, 'f1_sco...
1  {'accuracy_score': 0.994413407821229, 'f1_scor...  {'accuracy_score': 0.7988826815642458, 'f1_sco...
2  {'accuracy_score': 0.994413407821229, 'f1_scor...  {'accuracy_score': 0.88268156424581, 'f1_scori...
3  {'accuracy_score': 0.9832402234636871, 'f1_sco...  {'accuracy_score': 0.8603351955307262, 'f1_sco...
4  {'accuracy_score': 0.994413407821229, 'f1_scor...  {'accuracy_score': 0.8547486033519553, 'f1_sco...

SVM Accuracy Mean
0.9899
SVM Standard Deviation
0.0061
DECISION TREE Accuracy Mean
0.8525
DECISION TREE Standard Deviation
0.0318
