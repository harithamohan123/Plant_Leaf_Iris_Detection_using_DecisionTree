# Plant_Leaf_Iris_Detection_using_DecisionTree
________________________________________________

Plant leaf iris detection using decision tree. 

Procedure :                                                                                                                           
=> Analyse the problem that is need to be found.                                                                                                                 
=> Collect dataset  from scikit-learn Iris Dataset. where input = 4 features.                                                                               
=> Input is sepal length and width, petal length and width  and output is Iris species ( setosa, virginica, vesicolour).                                         
=> We dont have pixel , it is dimensional value.=> Analyse the problem that is need to be found.                                                        
=> Load dataset and summarize detials such as Data = (150 x 4), Target = [0 1 2....2].                                                     
=> Segregate Dataset into x and y, where x = pd.DataFrame(datset.data,columns = data.feature_name) and y = dataset.target.                              
=> Split data into test and train sets.                                                                                                                          
=> Use Decision tree with tuning parameters(max_depth, ASM (gini)).                                                                                           
=> Node = sepal length and width, petal length and width.                                                                                                  
=> Leaf node = setosa, virginica, vesicolour.                                                                                                                  
=> Find best max_depth value                                                                                                                          
=> Train the model.                                                                                                                          
=> Evaluation and Validation.                                                                                                                          
=> Observe how our model classify our new data.                                                                                                                          
