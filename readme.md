

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
