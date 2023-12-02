# Paddy Quality Estimation for the Government of Telangana
Our team with Anika Roy, Ujjwal Shekhar, Siddharth Singh, Radhikesh Agrawal and Mayank Goel won the first place in Megathon, the largest 24hr student-run hackathon in Hyderabad with 700+ participants from 30+ colleges across India.
<center> 
<img src= "https://github.com/Anika-Roy/Rice_Estimation_using_Satellite_Images/assets/102136135/07c007af-92e8-4f87-ba0c-602ae5f6a80e" height = "400">
</center>


https://github.com/Anika-Roy/Rice_Estimation_using_Satellite_Images/assets/102136135/ea5c6072-983a-482e-88e8-d5f1b9436f33


# Abstract

## Clustering Region into Parts

In the following project, we employ a clustering algorithm to partition a given region into 'k' distinct segments based on two essential parameters:

- **VH** (Vertical Horizontal): VH is a radar remote sensing parameter. It represents the signal's polarization in the vertical-horizontal plane and is used for land cover analysis.

- **NDVI** (Normalized Difference Vegetation Index): NDVI is a common vegetation index that quantifies the presence and health of vegetation in an area based on the difference between the near-infrared and red bands of remote sensing data.

Subsequently, we apply the Fast Fourier Transform (FFT) to the averaged VH and NDVI data to identify periodic patterns, which often correspond to the growth cycles of paddy fields. This analysis allows us to measure the extent of paddy cultivation in the region by calculating the area of these identified clusters relative to the total area.

## Calculating Water Quality

To assess water quality, we employ two key indices:

- **NDWI** (Normalized Difference Water Index): NDWI is a remote sensing index that focuses on the presence of water bodies, which is essential for monitoring water quality and aquatic ecosystems.

- **NDCI** (Normalized Difference Chlorophyll Index): NDCI is used to estimate the chlorophyll content in plants, indicating the health and vitality of vegetation.

The method for calculating water quality involves the use of NDWI and NDCI. NDWI typically quantifies the water content, while NDCI assesses chlorophyll content in plants. By combining these indices and analyzing their values, we can make inferences about the quality of water resources in a given area, particularly in relation to vegetation and aquatic ecosystems.

More details in our presentation, hope you found it insightful!
