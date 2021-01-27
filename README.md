# DeepMTA_PyTorch

This is an Officical PyTorch Implementation of "Dynamic Attention-guided Multi-TrajectoryAnalysis for Single Object Tracking", Xiao Wang, Zhe Chen, Jin Tang, Bin Luo, Yaowei Wang, Yonghong Tian, Feng Wu, IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT 2021) [[Paper]()] [[Project](https://sites.google.com/view/mt-track/home)] 


## Abstract: 
Most of the existing single object trackers track the target in a unitary local search window, making them particularly vulnerable to challenging factors such as heavy occlusions and out-of-view movements. Despite the attempts to further incorporate global search, prevailing mechanisms that cooperate local and global search are relatively static, thus are still sub-optimal for improving tracking performance. By further studying the local and global search results, we raise a question: can we allow more dynamics for cooperating both results? In this paper, we propose to introduce more dynamics by devising a dynamic attention-guided multi-trajectory tracking strategy. In particular, we construct dynamic appearance model that contains multiple target templates, each of which provides its own attention for locating the target in the new frame. Guided by different attention, we maintain diversified tracking results for the target to build multi-trajectory tracking history, allowing more candidates to represent the true target trajectory. After spanning the whole sequence, we introduce a multi-trajectory selection network to find the best trajectory that deliver improved tracking performance. Extensive experimental results show that our proposed tracking strategy achieves compelling performance on various large-scale tracking benchmarks.


