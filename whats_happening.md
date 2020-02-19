# number_classifier
 This is a basic number classifier which learns number from various writing styles.
 
 
 we use the data set mnist which avaible in tensorflow itself. 
 
 then we load the data in x,y_train and x,y_test.
 
 the use a simple nueral net model which has:-

 1)One Flatten layer

 2)Three fully connected layers with a (relu) activation function.
 
 3)Output layer with a (sigmoid) activation function.
 
 the model was fitted by using optimizer='adam' and  loss_function='sparse_categorical_crossentropy'and Epoch=10.
 
 then saved it by using model.save("name_of_model.model")
 
 this model has 
     
     
               acc=0.9929
               
               loss=0.0212
           
           val_acc=0.9772
           
           val_loss=0.0531



For more info checkout my code at ("https://github.com/rustombhesania/number_classifier").

Thnx for watching.



the reference was taken from ("https://pythonprogramming.net/introduction-deep-learning-python-tensorflow-keras/")
