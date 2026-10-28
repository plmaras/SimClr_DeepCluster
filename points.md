#THree points form SimClr


We show that 

(1) composition of data augmentations plays a critical role in defining
effective predictive tasks, 

(2) introducing a learnable nonlinear transformation between the repre-
sentation and the contrastive loss substantially im-
proves the quality of the learned representations,

    
3) contrastive learning benefits from larger
batch sizes and more training steps compared to
supervised learning.





The main point while processing CIFAR Images we get 32*32*3 we get an error during bn at layer4 so in conv layer i changed stride from s =2 to 1


They are using only random crop and resize (with random flip), color distortions, and Gaussian blur in training , and evaluing on different augems



