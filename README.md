# HY_IRS-dataset

HY_IRS dataset created by Yafei DUAN

2023-4-25

The dataset used in this study consists of continuous observed thermal infrared images in a physical test for the cooling water discharged from a coastal power plant. The power plant uses seawater as its cooling source, drawn from a nearby sea channel on the southeast side of the plant and discharged through another channel on the west side.
HY_IRS dataset: Includes 10736 thermal infrared images of cooling water discharge under different experiment conditions. These images were converted into grayscale images with a resolution of 320×240 and randomly divided into a training set (8500 images), a validation set (1236 images), and a test set (500 images). 

During the summer of 2020, prototype monitoring of the sea surface temperature (SST) in the vicinity of the power plant was conducted using ship-based measurements, unmanned aerial vehicles, and satellite remote sensing. Seventeen cloudless satellite images (after the plant operation in October 2018) were obtained from Landsat8 TIRS. The C1 Level1 data products of thermal infrared bands 10 and 11 of the TIRS sensor were selected. The SST of the TIRS data was retrieved using the atmospheric correction method based on the radiative transfer equation and the atmospheric correction parameter calculator provided by NOAA (Barsi et al. 2003), by inputting meteorological data collected from the meteorological tower at the plant site. The spatial resolution of the SST retrieval images from Landsat8 TIRS was 100 meters per pixel.

Details please refer to "Super-Resolution Reconstruction of Sea Surface Pollutant Diffusion Images Based on Deep Learning Models: A Case Study of Thermal Discharge from a Coastal Power Plant"
