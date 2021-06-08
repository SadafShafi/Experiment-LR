A series of Experiments to find the effects of changing learning rate and batch size (during training) on generalization by the neural networks


**Experiment 2.0 ** : LR = (BS/(epoch+1)^(3/2) * 80)/8


**Experiment 3.0 ** : once using LR = BS* random() and in other epoch LR = epoch*random()


**Experiment 4.0A ** : LR = BS*random()    -> LR is increasing as BS is increasing

**Experiment 4.0B ** : reverse(BS*random())   -> LR is decresing as BS is increasing

**Experiment 4.0C ** : (LR = 1/epoch) * random()
