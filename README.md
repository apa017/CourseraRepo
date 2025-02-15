# Deep Learning Exam

## Deploying a Convolutional Neural Network for Image Classification with Watsonx.AI¶

### Abstract

This notebook demonstrates the end-to-end development of a Convolutional Neural Network (CNN), from model design and training to cloud deployment and real-time inference. <br>The process begins with an introduction to CNNs, their use cases, and an exploration of the MNIST dataset, a widely used benchmark for image classification.

The first CNN model is built using convolutional layers, pooling, dropout, and dense layers, but its performance is suboptimal, leading to the development of an improved architecture. <br>Key enhancements include batch normalization, additional convolutional layers, increased depth, dropout regularization, and padding adjustments to improve generalization and reduce overfitting. <br>The revised model achieves better accuracy and stability, making it suitable for deployment.

The deployment phase covers saving the trained model in a compatible format and integrating it with IBM watsonx.ai for scalable cloud deployment. <br>Using a programmatic approach via SDK, the model is stored, deployed, and tested through API calls, demonstrating its ability to generate real-time predictions. <br>The notebook concludes with an evaluation of potential pitfalls and alternative strategies such as transfer learning to further enhance model performance.

Despite its improvements, the new model still presents challenges. Training a deeper network requires more computational resources, increasing training time and complexity. <br>Overfitting can still occur if hyperparameters are not carefully tuned, and performance may degrade when applied to datasets with different distributions. <br>Furthermore, real-time inference on cloud environments may introduce latency, which can be a concern for time-sensitive applications.

To address these challenges, alternative approaches are explored, including transfer learning by leveraging pre-trained models to improve accuracy with fewer training samples.
