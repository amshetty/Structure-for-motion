# Structure-for-motion

I have implemented Structure for motion using training and query images. Once Sift matches were calculated, the RANSAC test helped to eliminate redundancies in
matched pairs and the resulting mask from the essential matrix helped produce better SIFT matching points. Results for images were used to produce a point cloud. It is observed that iimages produce the most densely populated 3D point cloud because of the highest number of SIFT matching pair points between the two images.
