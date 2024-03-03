# Dave's Portfolio

## [Project 1: Use of Neural Networks to Solve the Inverse Kinetics Problem of a Robot Manipulator](https://github.com/Dee-ui/Neural-IK-Robotics)
Neural-IK-Robotics/NN.jpg
- The dataset used in this project is generated using the Denavit-Hartenberg forward kinematics method with 100,000 samples for training and testing.
- The analysis was first done on five 6dof industry-standard robots; ABB IRB 1600, Fanuc LR Mate 200iD, Universal Robots UR10, KUKA KR AGILUS, Yasakawa Motoman GP series. The it was implemented on a live 4 dof model.
- Two Tensorflow models were used. Both having a 7 input layer and a 3 output layer. The first model predicts the first three joint parameters while the second model predicts the last three joint parameters.
- The models were optimized using the Adam's optimizer and an earlystoppingcallback was also incorporated to combat overfitting.
