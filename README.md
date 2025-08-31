# Roadify: Road Segmentation using U-Net (TensorFlow)

Technologies and Tools Used :
- Python (TensorFlow/Keras)
- NumPy, OpenCV / Pillow
- Matplotlib for visualization
- Scikit-learn for metrics
- Git & GitHub for version control

---
Features of the Project :

- Trains a **U-Net** for **binary road segmentation** on aerial/satellite images.
- Handles **image–mask pairing**, resizing, normalization, and optional augmentation.
- Supports **Binary Cross-Entropy + Dice** loss for class imbalance.
- Tracks **Accuracy, Precision, Recall, F1, IoU** during/after training.
- Saves best model weights, training curves, and inference overlays.

---
 Architecture of Unet:

<p float="left">
  <img src="images/u-net-architecture.png" alt="Input Image" width="300"/>
  <!-- <img src="images/sample_gt_mask.png" alt="Ground Truth Mask" width="300"/>
  <img src="images/sample_pred_mask.png" alt="Predicted Mask" width="300"/> -->
</p>



---
Result Images :

<p float="left">
  <img src="images/road_seg.jpg" alt="Input Image" width="300"/>
  <!-- <img src="images/sample_gt_mask.png" alt="Ground Truth Mask" width="300"/>
  <img src="images/sample_pred_mask.png" alt="Predicted Mask" width="300"/> -->
</p>
