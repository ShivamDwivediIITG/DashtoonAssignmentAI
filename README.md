# DashtoonAssignmentAI
Development of an Adaptable Deep Learning Model for Artistic Style Transfer
The aim of this assignment is to create a deep learning model capable of adapting an existing work to resemble the aesthetic of any art. The model should be able to analyze the artistic style of the selected art and apply similar stylistic features to a new, original artwork, creating a piece that seems as though it could have been created by the artist themselves.

Task Description:

Model Architecture:
Design a neural network that can learn features representative of an artist's style. Consider using a convolutional neural network (CNN) as the basis for this model.
Implement a style transfer algorithm that leverages learned features to stylize input images.
Training:
Train your model using the collected dataset(Find a dataset of your choice). Ensure to use a training-validation-test split to evaluate the model’s performance properly.
Use appropriate loss functions to measure both content preservation and style emulation.
Style Adaptation:
Develop a method to adapt the learned style features to new works while maintaining the original content and integrity of the artwork.
Evaluation:
Create a set of criteria to evaluate the effectiveness of the style transfer, such as stylistic accuracy, content preservation, and visual appeal.
# Transfer Learning
Neural Style Transfer (NST) uses a previously trained convolutional network, and builds on top of that. The idea of using a network trained on a different task and applying it to a new task is called transfer learning.
![2000](https://github.com/ShivamDwivediIITG/DashtoonAssignmentAI/assets/142148841/c1291085-af8f-46a4-8a8e-40e034ad3058)
# Neural Style Transfer (NST) algorithm in three steps
 build the content cost function,build the style cost function and put it all together 
 # We use VGG-19, a 19-layer version of the VGG network
