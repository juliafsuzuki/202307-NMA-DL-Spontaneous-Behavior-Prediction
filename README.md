# Team Project

Megapod: cotopaxi

Pod: othnielia_Zydeco

Team: The Amit-Golnaz-Arman-Julia (AGAJ) Team 

Motivation: Neuroscience is a field of study that examines the structure and function of the human brain and nervous system. The field of neuroscience is growing at an exponential rate thanks to the new advances in imaging technology.

Abstract: I recently worked on a Deep Learning project where a group of 4 team members investigated the activity evoked in the primary visual cortex (V1) of a mouse while it is running on a floating ball in the complete darkness. We use the Stringer dataset (2019) that consists of neural recordings (i.e. calcium imaging of ~12,000 neurons in V1 of an awake mouse) using a method called multi-plane two-photon. The question we pose was if there is a correlation between the neural activity and spontaneous behaviors such as running speed and whether we can deploy deep learning algorithms to predict such behavior from neural activity. To reduce the complexity of analysis, we worked with a small subset of neurons by applying the Conventional Principal Component Analysis (PCA) technique and reduced the dimensions of the neural data to 500. The dataset was further divided into two parts: training (7) and testing (3) subsets in a ratio of 7 to 3. We experimented with different architectures of a linear deep learning model (by changing the number of layers and the number of neurons in each hidden layer and employing different activation functions such as ReLU, Sigmoid and TanH) to determine the best performing model. Mean Square Error (MSE) and Root Mean Square Error (RMSE) are used as loss functions and Adam optimization algorithm is used as an optimizer. Preliminary results show that running speed can be predicted from the V1 with a high degree of precision with one architecture constructed with 3 hidden layers with the ReLU activation function and another architecture with 1 hidden layer with the Sigmoid activation function. 

Dataset Name: Stringer

Dataset Location: https://github.com/gbaghdadi/NeuromatchDeepLearningProject/blob/main/projects/neurons/load_stringer_spontaneous.ipynb

Dataset Information: https://compneuro.neuromatch.io/projects/docs/projects_2020/neurons.html

