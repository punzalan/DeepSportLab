# DeepSportLab


> DeepSportLab: a Unified Framework for BallDetection, Player Instance Segmentationand Pose Estimation in Team Sports Scenes
>
> This paper presents a unified framework to(i)locate the ball,(ii)predict the pose, and(iii)segment the instance mask of players in team sports scenes.  Those problems are ofhigh interest in automated sports analytics, production, and broadcast. A common prac-tice is to individually solve each problem by exploiting universal state-of-the-art models,e.g., Panoptic-DeepLab for player segmentation. In addition to the increased complexityresulting from the multiplication of single-task models, the use of the off-the-shelf mod-els also impedes the performance due to the complexity and specificity of the team sportsscenes, such as strong occlusion and motion blur.  To circumvent those limitations, ourpaper proposes to train a single model that simultaneously predicts the ball and the playermask and pose by combining the part intensity fields and the spatial embeddings princi-ples. Part intensity fields provide the ball and player location, as well as player joints lo-cation. Spatial embeddings are then exploited to associate player instance pixels to theirrespective player center, but also to group player joints into skeletons.  We demonstratethe effectiveness of the proposed model on the DeepSport basketball dataset, achievingcomparable performance to the SoA models addressing each individual task separately.

# Commercial License

Part of this software is available for licensing via the EPFL Technology Transfer
Office (https://tto.epfl.ch/, info.tto@epfl.ch).

The rest is available for licensing via the UCLouvain Technology Transfer
Office (https://uclouvain.be/en/research/ltto, LTTO@uclouvain.be).
