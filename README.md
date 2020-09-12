# Knowledge-Distillation-in-Keras
Demonstrates knowledge distillation (kd) for image-based models in Keras. To know more check out my blog post [Distilling Knowledge in Neural Networks](https://app.wandb.ai/authors/knowledge-distillation/reports/Distilling-Knowledge-in-Deep-Neural-Networks--VmlldzoyMjkxODk) that accompanies this repository. The blog post covers the following points - 

- What is softmax telling us?
- Using the softmax information for teaching - Knowledge distillation
- Loss functions in knowledge distillation
- A few training recipes
- Experimental results
- Conclusion

## About the notebooks
- `Distillation_Toy_Example.ipynb` - kd on the MNIST dataset
- `Distillation_with_Transfer_Learning.ipynb` - kd (with the typical KD loss) on the Flowers dataset with a fine-tuned model
- `Distillation_with_Transfer_Learning_MSE.ipynb` - kd (with an MSE loss) on the Flowers dataset with a fine-tuned model
- `Effect_of_Data_Augmentation.ipynb` - studies the effect of data augmentation on kd

## Results
Interact with the all the results [here](https://app.wandb.ai/authors/knowledge-distillation).

## Acknowledgements
I am grateful to [Aakash Kumar Nain](https://twitter.com/A_K_Nain) for providing valuable feedback on the code. 
