# Deep-Learning
Training LeNet5 on MNIST with SGD and ADAM
	a)LeNet5 on MNIST with SGD:
  		-->Effect of training loss vs. Batch size for a fixed learning rate
 	 	-->Effect of training loss vs. Learning rate for a fixed Batch size
 	b)LeNet5 on MNIST with ADAM
		-->Effect of training loss vs. Batch size for a fixed learning rate
		-->Effect of training loss vs. Learning rate for a fixed Batch size

Result:
a)Using SGD

Testing accuracy (Batch size=256, lr=0.1 =  11.35
Testing accuracy (Batch size=1024, lr=0.1) =  11.35
Testing accuracy (Batch size=256, lr=.01) =  38.6


b)using ADAMs

Testing accuracy (Batch size=256, lr=0.1 =  96.61
Testing accuracy (Batch size=256, lr=.01) =  89.66
Testing accuracy (Batch size=1024, lr=0.1) =  97.37
