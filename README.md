# Flower-recognition
Experimentation with Few shot learning and Vision transformers


### Baseline: ResNet-18 Model

To simplify the comparison of performance for all the different methods implemented, we have used a pretrained Resnet-18 Model as the baseline and downstreamed it for the classification task. All performance comparisons will be made in terms of the training and testing accuracy.

Accuracy and Loss plots obtained for Baseline Model

<img width="648" alt="Screenshot 2024-12-03 at 9 55 32 AM" src="https://github.com/user-attachments/assets/d6f41656-9798-4fa0-acc5-f71f941a806d">

### Prototypical networks with Triplet marginal loss

Accuracy and Loss plots for Prototypical Triplet Loss model

<img width="647" alt="Screenshot 2024-12-03 at 10 02 49 AM" src="https://github.com/user-attachments/assets/0477dd7b-775e-4f9b-aa72-837fac25c419">



### Prototypical networks with Triplet Semi-Hard Loss

Top results for best parameter settings for few shot learning with Prototypical networks with Triplet Semi-Hard Loss

<img width="668" alt="Screenshot 2024-12-03 at 9 51 39 AM" src="https://github.com/user-attachments/assets/06043b18-373f-41da-a871-1a26762cb145">

K-NN Modified Prototypical Network with Triplet Semi-Hard Loss

Tried different backbone models, optimizers, and hyperparameters. Using K=10, α=2, μ=1 (based on random tuning results), we noted following results: 



