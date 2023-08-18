# SAR_Image_classification
Explored the classification of Land Use and Land Cover (LULC) by employing Sentinel-1 Synthetic Aperture Radar (SAR) data, while also investigating the synergistic integration of SAR data with multispectral data from Sentinel 2 Multispectral data.
The Sentinel 1 data was downloaded using the Alaska Satellite Facility (ASF) search vertex API.
A composite 6-band image was created with the following bands
1. Sentinel 1 VV polarisation
2. Sentinel 1 VH polarisation
3. RADAR Vegetation Index ( RVI = 4*VH/(VV+VH) )
4. Sentinel 2 Green band
5. Sentinel 2 Red band
6. Sentinel 2 NIR band


