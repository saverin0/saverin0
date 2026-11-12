# Abhishek Singh

I am a machine learning engineer working on Earth observation and remote sensing, in Berlin.

Everything else, all nine projects with their results, is on **[saverin0.github.io](https://saverin0.github.io)**.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/saverin0/sar-transfer-glaciers"><img src="media/sar-columbia-front.gif" alt="Columbia glacier calving front, SAR, model front against real front"></a><br>
<b><a href="https://github.com/saverin0/sar-transfer-glaciers">sar-transfer-glaciers</a></b><br>
A 0.57 M-parameter decoder on frozen C-RADIO features matches the 7.8 M-parameter U-Net on front error on the test glaciers (979 ± 31 m vs 979 m).
</td>
<td width="50%" valign="top">
<a href="https://github.com/saverin0/uav-lidar-vs-satellite"><img src="media/uav-lidar-valley.gif" alt="A drone flight over a river valley in Armenia, the drone DSM, DTM and land cover at 0.5 m, then the Copernicus DEM, ESA WorldCover, a canopy height map, Sentinel-2 and OpenStreetMap on the same map"></a><br>
<b><a href="https://github.com/saverin0/uav-lidar-vs-satellite">uav-lidar-vs-satellite</a></b><br>
GLO-30 meets the drone DSM to 0.80 m RMSE on bare ground in the valley and 0.45 m in the town.
</td>
</tr>
<tr>
<td valign="top">
<a href="https://github.com/saverin0/sar-transfer-domains"><img src="media/sar-domains-four.gif" alt="One Sentinel-1 test chip each from glacial lakes, snow, forest types and alpine glaciers, with the labels and the frozen satellite DINOv3 output"></a><br>
<b><a href="https://github.com/saverin0/sar-transfer-domains">sar-transfer-domains</a></b><br>
With a small decoder, the satellite-pretrained DINOv3 is ahead of C-RADIOv4-H on every dataset and test split (snow IoU 0.735 vs 0.602), the reverse of the glacier study.
</td>
<td valign="top">
<a href="https://github.com/saverin0/vggt-omega-drone-lidar"><img src="media/vggt-drone-town-2m.gif" alt="A drone stretch over a town in 3D, its LiDAR points coloured by the depth error of VGGT-Omega alone, a hybrid with COLMAP and full COLMAP, and by the hybrid's change against the model"></a><br>
<b><a href="https://github.com/saverin0/vggt-omega-drone-lidar">vggt-omega-drone-lidar</a></b><br>
COLMAP with the known camera is more accurate on all 6 test stretches but takes 15 to 17 minutes per stretch, the model 5 to 8 seconds.
</td>
</tr>
</table>

<sub>Figure data from CaFFe (Gourmelon et al. 2022, CC BY 4.0), Glacial-Lake-Bench (CC BY 4.0), SnowSAR replication data (Etalab Open Licence 2.0), ForTy v1 (CC BY-SA 4.0), the GlaViTU tile dataset (CC BY 4.0), and MARS-LVIG and UAVScenes (CC BY-NC-SA 4.0) with Copernicus GLO-30, ESA WorldCover, the Meta and WRI canopy height map, Sentinel-2 and OpenStreetMap contributors (ODbL).</sub>
