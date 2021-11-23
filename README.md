# handwritten_digit_recognization

==


                 
                
                suresh Kumar :-    19EJICS149

+ MNIST is a collection of handwritten digits ranging from the number 0 to 9.
+ It has a training set of 60,000 images, and 10,000 test images that are classified into corresponding categories or labels.
+ It is a subset of a larger set available from NIST. 
+ Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

# Libraries Required
- Tensorflow
- Keras
- Matplotlib
- Pandas
- Numpy

# Model
- To create the model, we first initialize a sequential model then we compile and train Model
- We need to use a sparse_categorical_crossentropy loss function in case we have an integer-dependent variable. For a vector-based dependent variable like a ten-size array as the output of each test case, use categorical_crossentropy.
- In this model we use Adam Optimizer
- Then we train the model using .fit() method and also  specify an epoch and batch size when training the model.

# Result
   - Total params: 101,770
   - Trainable params: 101,770
   - Non-trainable params: 0

 * Training Accuracy :- 100 %
 * Testing Accuracy :-  97.75 %
