# PulseHeart-PyTorch
![image](https://github.com/pulseheart/PulseHeart-PyTorch/assets/29145045/0da4deb9-986b-41fb-be3d-c74cf83d0e27)

## create datasets
  - download and rename void-movienet_50f directory as movienet_50f
  - download and rename void-npef_movienet_50f directory as npef_movienet_50f
  - delete  "delete_me_after loading _videos.txt" files in last-level subdirectories
  - download and use "create_dataset" notebooks
## download and run training notebooks
  - a csv file per notebook will be created: take care to give it a suitable experiment name   
## obtain loss and accuray train/val curves 
  - download and open movinet_loss_curves.xlsx
  - duplicate one of the folder, give it the experiment name
  - copy/paste the printed training output in the first cell, and that's all!
## calculate metrics and plot graphs of ROC / PR curves
- download echocg_video_metrics_and_graphs notebook
- modifying the adhoc cells, downlad as pandas data files the csv files that were created by traning notebooks
- adapt the model dictionnaries to take into account your choice of experiments
- run remaining cells 
