Files for training: 
  - phase1: starts training, computes and saves embeddings at the end of training
  - phase2: fine tunes phase1 by hard subsets, should load the previously trained model, computes and saves embeddings at the end of training
  - adv: fine tunes on adv examples, should load the previously trained model, computes and saves embeddings at the end of training
  - adversarial training and evaluation require tensorflow v1
  
  
  - New Jan. 2022: More details have been added to reproduce the results in the paper: the train/test split, exact model architecture, and some other hyperparameters.
