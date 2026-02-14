# Lab 5: Spring Semester 2026
## Name : Farhan Hussain
## Id : U20240196

## Aim 
The aim of this lab is to detect faces in a group photograph using haar Cascade Classifier , extract color-based features like Hue and Saturation from detected faces and pply k-Means clustering to group faces based on similarity and in the end do the cluster assignment for the template image.

## Methodology
1. Face detection : Applied haar cascade face detection. Bounding boxes around the face.
2. Features extraction : mean hue and saturation values for each face
3. KMeans clustering : cluster labels and centroid position
4. Template classification : According to the hue and saturation assign the template image to the cluster.

## Key Findings
1. Face detection results : Haar Cascade classifier effectively identified frontal faces with consistent lighting
2. Clustering analysis : cluster 0 : red color, 
                         cluster 1 : green color
3. Template image classification : The template image is correctly assigned to the respective cluster.

## Visualizations

1. Face detection : <img width="1599" height="993" alt="image" src="https://github.com/user-attachments/assets/7c8cb085-0727-4c50-adaa-af004d060f39" />

2. Feature space with faces: <img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/ad0f5a79-8714-48a2-a008-c5b0def1f6b7" />

3. Clustering faces based  on Hue and Saturation : <img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/2b85c6c5-ed9b-428c-bf48-53db4433bad4" />

4. Template image with detected face: <img width="494" height="497" alt="image" src="https://github.com/user-attachments/assets/bf92c77e-e69b-41c5-9bf0-2eca39232d00" />

6. clustering faces based on hue and saturation with Dr Shashi Tharoor: <img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/0e4993f8-da95-4dd5-9a9f-b300a5adc24e" />



7. clustering faces based on hue and saturation with dr shashi tharoor : <img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/8984e063-91a0-473a-9f54-5002a8c7175d" />


## Conclusions

1. Effective face detection is done by haar cascade classifier.
2. Color based classification using HSV provides useful features for grouping faces.
3. K-Means clustering successfully seperated faces into two distinct clusters based on hue and saturation.
4. The trained model successfully clasified the template image to the respective cluster.
 
