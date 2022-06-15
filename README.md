# Lunar-Lander
1. Please note that these files are Google Colab specific and hence it requires modifications if running locally. 

2. Please create the necessary folders in your Google Drive under Colab Notebook folder before running the code. 
   Specifically 'lunarlander dqn' for DQN agent under Colab Notebook.
   Please refer to the appendix for detailed instructions on the new folders required in the Google Drive.

3. Please accept the permission to access your Google Drive folder to run the code and save the trained model,training 
   video and test video.



********DQN***********

DQN_LunarLander.ipynb
This is the main DQN code which we implemented and achieved good performance.   

DQN_LunarLander_Fixed_Target_Network.ipynb
This is DQN with Fixed Target Network which did not perform well and hence shared just for reference.


**********Policy Gradient*************

Lunar_Lander_Policy_Gradient_REINFORCE.ipynb
This is the main Policy Gradient code which we implemented and achieved good performance.



************** Notes *******************
The results can vary during different runs and the average reward for last 100 might not reach >210 in 10,000 episodes. Please restart and run the code to
train the model again from the start.

Please change the total no.of episodes from 10,000 to any other number if you wish to do so in the train loop cell.

Please change the total no.of episodes from 100 to any other number if you wish to do so in the test loop cell.

The learning rate,gamma and the no of neurons in the dense layers can be changed manually in the Agent class,however the results might not be the same.





https://user-images.githubusercontent.com/94230074/173899144-06714664-54da-4b1b-857d-62555509729d.mp4


