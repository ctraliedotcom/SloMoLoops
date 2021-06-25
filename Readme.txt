a) DESCRIPTION:
This supplementary data contains an original set of videos and a corresponding set of "slow motion" videos that are the output of our pipeline.  We also show the 3 synthesized ground truth videos we use in our quantitative analysis of circular coordinates, which have each been corrupted by a different type of noise (camera shake, Gaussian, occlusion).

b) Size: 19.8MB

c) PLAYER INFORMATION: Standard video player


------------------------------------------
d) PACKING LIST:
*JumpingJacks_Occlusions.avi: A video of two men doing jumping jacks (creative commons, obtained from https://www.youtube.com/watch?v=sHRw7yIgNKE), with a square taking a random walk and occluding the video frames
*JumpingJacks_Occlusions_SimpleReordered.avi: A slow motion template obtained by simply reordering the first frames of each window by the circular coordinates
*JumpingJacks_Occlusions_MedianReordered.avi: A much cleaner slow motion template of the above video obtained via median reordering with our code

*Fan_Original.avi: A video of a fan spinning quickly, creative commons, obtained from https://www.youtube.com/watch?v=ror_LhUh8kY
*Fan_MedianReordered_Close4.avi: A clean slow motion template using an "F" of 4

*Exercise_Original.mp4: A video of a man doing rows with a kettle ball (obtained from reference [36])
*Exercise_MedianReordered.avi: A slow motion template of the above video obtained from our code

*FaceHeartbeat_Original.mp4: A video from the Eulerian video magnification paper of a man's face filling with blood as his heart beats (obtained from reference [3])
*FaceHeartbeat_MedianReordered_60FPS.avi: A slow motion template of the above video obtained from our code

*ThroatMagnified_Original.avi: A video from the phase-based Eulerian video amplification paper of a man's neck beating with his heart (obtained from reference [4])
*ThroatMagnified_MedianReordered.avi_80FPS.avi: A slow motion template of the above video obtained from our code

*GroundTruth_Simple_OcclusionSquare50.avi: A few cycles of the "simple" video used in our quantitative experiments, with a drifting occlusion square
*GroundTruth_Harmonic_Shake20x20.avi: A few cycles of the "harmonic" video with a 20x20 motion blur kernel
*GroundTruth_Crowd_Noise0.5.avi: A few cycles of the "crowd" video with 0.5 standard deviation Gaussian noise
------------------------------------------

e) CONTACT INFORMATION:
Christopher Tralie
ctralie@alumni.princeton.edu
http://www.ctralie.com
