# Spontaneous Behavior Prediction using Deep Learning

Project Name: "Spontaneous Behavior Prediction based on Neural Activity" in the visual cortex (V1) of awake mice

Team Name: The Amit-Golnaz-Arman-Julia (AGAJ) Team

Team Members: Amit Kumar, Golnaz Baghdadi, Arman Charan, Julia Suzuki

Megapod: cotopaxi

Pod: othnielia_zydeco

Motivation: Neuroscience is a field of study that examines the structure and function of the human brain and nervous system. The field of neuroscience is growing at an exponential rate thanks to the new advances in imaging technology.

Abstract: A team of 4 individuals living in different parts of the world met through the Neuromatch Academy in July 2023 and worked on a research project together. We used scientific methods and techniques to formulate a research question, "Can we predict spontaneous behavior such as running from neural activity in the visual cortex (V1) of awake mice?" and addressed the question using the Stringer spontaneous dataset (Stringer, 2019). The Stringer spontaneous dataset comprised of Neural recordings (i.e. neural activities of mice (calcium imaging of 10,000+ neurons in the visual cortex (V1)) while they were running on a floating ball in the complete darkness) were collected using a method called multi-plane two-photon. We defined "running speed" as a target variable or y-feature and "neural activity" as a predictor or X-feature. To reduce the complexity of analysis, we applied the dimension reduction technique called Conventional Principal Component Analysis (PCA) technique and reduced the dimensions of the neural data to 500. The dataset was further divided into two parts: training (7) and testing (3) subsets in a ratio of 7 to 3. We first built and experimented with a Linear Deep Learning model and then built and experimented the Deep Linear Neural Network models with different architectures that were constructed with different number of layers, different number of neurons in each hidden layer and different activation functions such as ReLU, Sigmoid and TanH to identify the best performing model. We used metrics such as Mean Square Error (MSE) and Root Mean Square Error (RMSE) as loss functions to evaluate the model performance. We fine-tuned the best performing models with the Adam optimization algorithm to improve the accuracy of predictions. Preliminary results showed the running speed can be predicted from the neural activity in the visual cortex (V1) of mice with a high degree of precision. The best performing models had the architecture constructed with a neural network with 3 hidden layers with the ReLU activation function and another architecture with a neural network with 1 hidden layer with the Sigmoid activation function.

Dataset Name: Stringer Spontaneous Data

Dataset Location: 

- https://github.com/NeuromatchAcademy/course-content/blob/main/projects/neurons/load_stringer_spontaneous.ipynb
- https://colab.research.google.com/github/NeuromatchAcademy/course-content/blob/main/projects/neurons/load_stringer_spontaneous.ipynb

Dataset Information: 

- https://www.youtube.com/watch?v=78GSgf6Dkkk
- https://compneuro.neuromatch.io/projects/docs/projects_2020/neurons.html

Medium Blog Post:

- https://medium.com/@julia.f.suzuki/project-spontaneous-behavior-prediction-based-on-neural-activity-in-visual-cortex-of-awake-mice-13625eef46e4
