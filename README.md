# GraphCMR
Repository for the paper "Convolutional Mesh Regression for Single-Image Human Shape Reconstruction"

# Discussion
# two-scale experiments on datasets3(with h36m_whole): localhost:6029
	NOTE: 
	1.not_share + cat + pre_fusion, not_share +  cat + post_fusion, not_share + cat + add failed. Need to run again.
	2.From the previous experiments, not_share + cat + pre_fusion, not_share +  cat + post_fusion performs better than their "share" correspondants.
	3.Anyway, "cat" looks better than "add". 
	4.For share + add + post_fusion, MPJPE(nonParam) is much higher than its Reconstruct_Error. Why? Maybe because 3D_joints and 3D_mesh gt of h36m are inconsistent. 
		try to remove loss_3D_joints, loss_2d_joints after 3D_vertices. 
	5.All the performance gain by the architecture will decrease with more training H36M datasets. 
	6. 

# 
	
