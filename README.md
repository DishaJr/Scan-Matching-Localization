# Scan-Matching-Localization
## **Task :**
* Filter scan using voxel filter
* Find pose transform by using ICP or NDT matching
* Transform the scan so it aligns with ego's actual pose and render that scan
##
**3D ICP** algorithm is chosen to be used in this project. The **'Res'** value in voxel filter is set to **'0.7'** and the number of itterations is set to **'10'**. The new transform scan is named **'newscanCloud'**. The following image displays the result of implementing the above steps where the car was able to drive a distance of 170 meters without the pose error rising above 1.2 meters, at an at least medium speed.
