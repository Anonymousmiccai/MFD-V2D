# MFD-V2D
![MFD-V2D Architecture](figures/overall_fig.png)
Unsupervised Cardiac Video Translation Via Motion Feature Guided Diffusion Model

## Demonstration of MFD-V2V
<p align="center">
  <img src="MFD-V2V_demos/A01_P101_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P104_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P12_evaluation.gif" width="250" />
</p>
<p align="center">
  <img src="MFD-V2V_demos/A01_P17_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P19_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P22_evaluation.gif" width="250" />
</p>
<p align="center">
  <img src="MFD-V2V_demos/A01_P25_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P34_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P35_evaluation.gif" width="250" />
</p>
<p align="center">
  <img src="MFD-V2V_demos/A01_P42_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P43_evaluation.gif" width="250" />
  <img src="MFD-V2V_demos/A01_P46_evaluation.gif" width="250" />
</p>

## Train the Registration Network
If you want to train the registration network, then go to the "Train LTMA registration Network" and run the Main.py file. The code will automatically save the last checkpoint for you, so you don't need to do anything. After training the registration network put the checkpoint in the models folder. We already provide the pretrain weights of the registration network inside the models folder.

## Train the Diffusion Model
Run the train_video_flow_diffusion.py file. 

