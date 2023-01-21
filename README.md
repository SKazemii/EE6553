# Implementing some algorithms for image registration

## Project of EE6553 (2020/12/22)


### Image registration, SIFT, BRISK, BRIEF, FREAK, ORB.


Abstract—These days, object registration and tracking in a sequence of images play a significant role in various areas. One of the methods in image registration is featurebased algorithms that in two steps were accomplished. The first step includes finding features of scene and object images. In this step, for reducing the sensitivity of detected features to the scale changes, scale-space is used. Afterward, we attribute feature points obtained in the first step, a description using brightness value around the feature points. In this project, five algorithms such as Binary Robust Invariant Scalable Keypoints (BRISK) and Scale Invariant Feature Transform (SIFT) are implemented in python. These algorithms could use in object detection and tracking.