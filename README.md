# MLPR-lab-5

Aim
The aim of this experiment was to detect faces from a group image, extract color-based features (Hue and Saturation), cluster the faces using K-Means algorithm into two groups, and classify a template face (Dr. Shashi Tharoor) into one of the clusters.

Methodology
- The group image was processed using Haar Cascade face detection, and 30 faces were detected successfully.
- Each detected face region was converted from BGR to HSV color space.
- The mean Hue and Saturation values were extracted as features for each face.
- K-Means clustering (k = 2) was applied to group the faces into two clusters.
- The centroids of both clusters were calculated and plotted.
- The template image (Dr. Shashi Tharoor) was detected, converted to HSV, and its Hue–Saturation features were extracted.
- Using the trained K-Means model, the template face was classified into one of the existing clusters.

Key Findings
- The face detector successfully detected 29 faces in the group image and got one error.
- The faces were clearly divided into two clusters based on Hue and Saturation values.
- One cluster had generally higher Hue values, while the other had relatively lower Hue values.
- The template image (Dr. Shashi Tharoor) was classified into the cluster near Hue ≈ 65–75 and Saturation ≈ 90–95, which corresponds to Cluster 1 (blue cluster in the plot).
- The clustering visually showed separation based on color characteristics.

Conclusion

The experiment demonstrates that simple color features (Hue and Saturation) can be effectively used for clustering faces using K-Means (distance-based learning).
Although the clustering is not identity-based recognition, it successfully groups faces based on visual similarity in color space.
The template classification shows that a new image can be assigned to an existing cluster using distance-based classification


All pictures and graphs have been displayed on the bottom.
<img width="633" height="447" alt="Face detection" src="https://github.com/user-attachments/assets/babac0d1-4704-4fca-93f9-f643cb47cde1" />
<img width="1104" height="600" alt="hue and saturation" src="https://github.com/user-attachments/assets/7e59c007-310b-4580-a0aa-6f0838dee4ae" />

<img width="1104" height="600" alt="hue and saturation" src="https://github.com/us<img width="1105" height="599" alt="kmeans hue and sat" src="https://github.com/user-attachments/assets/92c552f9-42e4-4c53-9645-f03e53040e95" />

<img width="395" height="422" alt="shashi" src="https://github.com/user-attachments/assets/de8a1deb-0e86-48d8-ad97-210bf094371a" />
assets/3800c9e5-64c8-4f2f-9779-226dc572f5d3" />
<img width="1105" height="598" alt="template" src="https://github.com/user-attachments/assets/71aeb92b-05f3-4403-a12c-2e87e874b257" />
<img width="1105" height="598" alt="kmeans template" src="https://github.com/user-attachments/assets/8b1c9c95-0ba2-4796-b064-0b5c202b399a" />





