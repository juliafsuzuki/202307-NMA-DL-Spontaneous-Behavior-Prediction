# Research Project 

Project Name: "Spontaneous Behavior Prediction based on Neural Activity" in visual cortex of awake mice
 
Team Name: The Amit-Golnaz-Arman-Julia (AGAJ) Team

Team Members: Amit Kumar, Golnaz Baghdadi, Arman Charan, Julia Suzuki

Megapod: cotopaxi

Pod: othnielia_Zydeco

Motivation: Neuroscience is a field of study that examines the structure and function of the human brain and nervous system. The field of neuroscience is growing at an exponential rate thanks to the new advances in imaging technology.

Abstract: A team comprised of 4 individuals (Amit, Golnaz, Arman, and myself) investigated the activity evoked in the primary visual cortex (V1) of mice while they were running on a floating ball in the complete darkness. We use the Stringer dataset (2019) that consists of neural recordings (i.e. calcium imaging of 10,000+ neurons in visual cortex of awake mice) using a method called multi-plane two-photon. The question we pose is if there is a correlation between the neural activity and spontaneous behaviors such as running speed and whether we can deploy deep learning algorithms to predict such behavior from neural activity. To reduce the complexity of analysis, we worked with a small subset of neurons by applying the Conventional Principal Component Analysis (PCA) technique and reduced the dimensions of the neural data to 500. The dataset was further divided into two parts: training (7) and testing (3) subsets in a ratio of 7 to 3. We experimented with different architectures of a linear deep learning model (by changing the number of layers and the number of neurons in each hidden layer and employing different activation functions such as ReLU, Sigmoid and TanH) to determine the best performing model. Mean Square Error (MSE) and Root Mean Square Error (RMSE) are used as loss functions and Adam optimization algorithm is used as an optimizer. Preliminary results showed that running speed can be predicted from the visual cortex with a high degree of precision with a neural network architecture constructed with 3 hidden layers with the ReLU activation function and another architecture with 1 hidden layer with the Sigmoid activation function.

Dataset Name: Stringer Spontaneous Data

Dataset Location: 

- https://github.com/NeuromatchAcademy/course-content/blob/main/projects/neurons/load_stringer_spontaneous.ipynb
- https://colab.research.google.com/github/NeuromatchAcademy/course-content/blob/main/projects/neurons/load_stringer_spontaneous.ipynb

Dataset Information: 

- https://www.youtube.com/watch?v=78GSgf6Dkkk
- https://compneuro.neuromatch.io/projects/docs/projects_2020/neurons.html

