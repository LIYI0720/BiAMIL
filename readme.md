##BiAMIL
Welcome to the BiAMIL Github repository!

BiAMIL is a tool that predicts gene mutations through pathological images. It is built on bi-directed self-attention multi-instance learning.
This repository contains all the relevant files related to the paper [“BiAMIL: Bi-directed self-attention multi-instance learning for BRCA1/2 gene mutations detection of breast cancer”].

Warning: BiAMIL is currently in a pre-development phase and may contain many bugs. It is recommended that you make copies of all datasets before using this application.

1.###ROI_SegByTiles = Automatic ROI segmentation model
--Train_roi_model.ipynb = Train the automatically segmentation model.
--Segment_roi.py = Generate ROI regions based on the automatic segmentation model.
Preprocess_full_tiles.ipynb = ROI regions were divided into tiles.

2.## ColorNorm =Color normalization 
get_snmf.py =Generate non-negative sparse matrix of the WSI.
color_norm_multi.py =Normalize the tiles to the target tile. 

3.## Mutaion =Classification using attentionMIL.
--5fold_train_breast.py=5-fold cross-validation.
--Slide_Validation =Validation at the slide level.
