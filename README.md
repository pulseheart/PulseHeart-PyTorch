# PulseHeart-PyTorch
![image](https://github.com/pulseheart/PulseHeart-PyTorch/assets/29145045/a59fc3f5-a186-43f5-8c9b-d5944d35028e)

## create datasets
  - rename void-movienet_50f directory as movienet_50f
  - rename void-npef_movienet_50f directory as npef_movienet_50f
  - use "create_dataset" notebooks
  - delete  "delete_me_after loading _videos.txt" files in last-level subdirectories
## run training notebooks
  - a csv file per notebook will be created: take care to give it a suitable experiment name   
## obtain loss and accuray train/val curves 
  - open loss_curves.xlsx
  - duplicate one of the folder, give it the experiment name
  - copy/paste the printed training output in the first cell, and that's all!
## calculate metrics and plot graphs of ROC / PR curves
- use echocg_video_metrics_and_graphs notebook
- load the csv files that were created
- adapt the model dictionnary to take into account your choice of experiments
- run remaining cells 
