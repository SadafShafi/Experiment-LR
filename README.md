This is the Source Code for my Researh paper called EXPLORING THE RELATIONSHIP BETWEEN LEARNING RATE, BATCH SIZE AND EPOCHS IN DEEP LEARNING. 
AN EXPERIMENTAL STUDY



A series of Experiments to find the effects of changing learning rate and batch size (during training) on generalization by the neural networks


**Abstract**

Deep learning has promised us great outcomes when enough data are fed to it. Deep learning is a branch of artificial intelligence which employs artificial neural networks to learn. The quality of the performance of these ANNs majorly depends on the data fed to it, architecture of the ANN and hyperparameters. The hyperparameters are the parameters whose values control the process of learning, which in turn controls the performance of ANNs. These hyperparameters are assigned different values usually using hit and trial methods. Hyperparameters such as learning rate, batch size, and epochs are assigned some values independent of each other before training the ANN model. In this study, we introduce a novel method of allowing the learning rate to be a function of batch size and epoch, thereby reducing the number of hyperparameters to be tuned. We later on introduce some randomness to the learning rate to see the effects on accuracy. It was found that the proposed strategy helped increase accuracy by more than 2% in certain cases, when compared to the existing methods.


https://link.springer.com/chapter/10.1007/978-981-19-6525-8_16


**Experiment 2.0 ** : LR = (BS/(epoch+1)^(3/2) * 80)/8


**Experiment 3.0 ** : once using LR = BS* random() and in other epoch LR = epoch*random()


**Experiment 4.0A ** : LR = BS*random()    -> LR is increasing as BS is increasing

**Experiment 4.0B ** : reverse(BS*random())   -> LR is decresing as BS is increasing

**Experiment 4.0C ** : (LR = 1/epoch) * random()
