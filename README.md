# Convolutional-Sliding-Windows

This repository contains the implementation of an object detection pipeline using a sliding window approach built on top of a convolutional neural network. The model is designed to handle object classification and localization (bounding box prediction) using a custom Three-head network architecture. The solution is developed and trained using the Caltech101 dataset.

#Results
- Train: Objectness Loss 0.1091, Class Loss 0.0821, Bbox Loss 0.0097
- Valid: Objectness Loss 0.1765, Class Loss 0.3934, Bbox Loss 0.0125
- Test: Objectness Loss 0.1697, Class Loss 0.4829, Bbox Loss 0.0096

# Future Work
- Improve bounding box accuracy with more advanced localization techniques.
- Implement non-maximum suppression (NMS) for better bounding box selection.
- Extend to more complex datasets like COCO.
