Files for evaluation:
  - Evaluate.ipynb: loads pretrained model and precomputed embeddings and compute the matching of the original dataset phishing pages 
  
  - Evaluate_new_phishing.ipynb: loads pretrained model and precomputed and compute the matching of the newly crawled phishing data
  
  - Compute_CNN_embeddings.ipynb: Compute and save the off-the-shelf-cnns embeddigs (i.e. VGG-16). The computed embeddings can be used in 'Evaluate.ipynb' and 'Evaluate_new_phishing.ipynb'
  
  - Perturbations_attacks.ipynb: applies the defined random perturbation attacks on the phishing test set and calculate and save the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb' and 'Evaluate_new_phishing.ipynb'
  
  - Whitebox_attacks.ipynb: applies whitebox adv perturbations on the phishing test set and calculates and saves the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb' and 'Evaluate_new_phishing.ipynb'
  
  - Whitebox_attacks_closest.ipynb: applies adv perturbations by sampling the closest example as the positive image, calculate and save the new embeddings of the perturbed images. The computed embeddings can be used in 'Evaluate.ipynb' and 'Evaluate_new_phishing.ipynb'
