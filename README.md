# PulseHeart-PyTorch
![image](https://github.com/pulseheart/PulseHeart-PyTorch/assets/29145045/53c1da80-f386-4a07-b9be-93a5daa5dbaa)


## create datasets
  - download and rename void-movienet_50f directory as movienet_50f
  - download and rename void-npef_movienet_50f directory as npef_movienet_50f
  - delete  "delete_me_after loading _videos.txt" files in last-level subdirectories
  - download and use "create_dataset" notebooks
## download and run training notebooks
  - a csv file per notebook will be created: take care to give it a suitable experiment name   
## obtain loss and accuracy train/val curves 
  - download and open movinet_loss_curves.xlsx
  - duplicate one of the folder, give it the experiment name
  - copy/paste the printed training output in the first cell, and that's all!
## calculate metrics and plot graphs of ROC / PR curves
- download echocg_video_metrics_and_graphs notebook
- modifying the adhoc cells, downlad as pandas dataframes the csv files that were created by traning notebooks
- adapt the model dictionnaries to take into account your choice of experiments
- run remaining cells 
