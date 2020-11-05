Files for evaluation, needs to be adjusted according to the dataset path, model file names and precomputed embeddings files names:
  - Evaluate.ipynb: loads pretrained model and precomputed embeddings and compute the matching of the original dataset phishing pages. Can be used to compute the matching of the attacks by loading the computed perturbed features of the test set.
  
  - Evaluate_new_phishing.ipynb: loads pretrained model and precomputed embeddings and compute the matching of the newly crawled phishing data.
  
  - Compute_CNN_embeddings.ipynb: Compute and save the off-the-shelf-cnns embeddigs (i.e. VGG-16 and ResNet50). The computed embeddings can be used in 'Evaluate.ipynb' and 'Evaluate_new_phishing.ipynb'
  
  - Perturbations_attacks.ipynb: applies the defined random perturbation attacks on the phishing test set and calculate and save the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb'. You can specify the attack type and parameters.
  
  - Whitebox_attacks.ipynb: applies whitebox adv perturbations on the phishing test set and calculates and saves the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb'.
  
  - Whitebox_attacks_closest.ipynb: applies adv perturbations by sampling the closest example as the positive image, calculate and save the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb'.
