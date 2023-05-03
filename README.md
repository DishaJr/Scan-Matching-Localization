# Scan-Matching-Localization
## **Task :**
* Filter scan using voxel filter
* Find pose transform by using ICP or NDT matching
* Transform the scan so it aligns with ego's actual pose and render that scan
##
**3D ICP** algorithm is chosen to be used in this project. The **'Res'** value in voxel filter is set to **'0.7'** and the number of itterations is set to **'10'**. The new transform scan is named **'newscanCloud'**.
