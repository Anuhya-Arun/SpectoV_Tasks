**Unsupervised Learning: Clustering and Segmentation**
This project demonstrates foundational unsupervised learning techniques in Python using scikit-learn and OpenCV, focusing on clustering, image segmentation, dimensionality reduction, and contour-based region detection.

Tasks Completed
**1. Clustering on Synthetic Data**
Generated 2D datasets using make_blobs and make_moons. Applied KMeans and DBSCAN clustering to visualize how each algorithm handles different cluster shapes. Observed KMeans performing well on globular data, while DBSCAN captured more complex structures and noise.

**2. Image Segmentation with KMeans**
Loaded and processed a sample image using OpenCV. Reshaped pixel data and applied KMeans clustering on RGB values to create segmented images. Explored the effect of varying k values on segmentation granularity.

**3. Dimensionality Reduction with PCA and t-SNE**
Applied PCA and t-SNE to reduce the Iris dataset to two dimensions. Plotted and compared how each method preserves class structure visually. Experimented with t-SNE parameters such as perplexity and learning rate to observe changes in separation.

**4. Region Detection and Overlay with OpenCV**
Post-processed clustered image to identify distinct regions using contour detection. Drew polygons and bounding boxes over original images to highlight segments. Implemented a real-time AR-style overlay using webcam feed and live KMeans clustering.

