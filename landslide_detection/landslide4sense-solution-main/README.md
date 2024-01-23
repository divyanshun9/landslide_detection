

## Data Description

The Landslide4Sense dataset has three splits, training/validation/test, consisting of 3799, 245, and 800 image patches, respectively. Each image patch is a composite of 14 bands that include:

- **Multispectral data** from [Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2): B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12.

- **Slope data** from [ALOS PALSAR](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-radar-alos-palsar-radar-processing-system): B13.

- **Digital elevation model (DEM)** from [ALOS PALSAR](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-radar-alos-palsar-radar-processing-system): B14.

All bands in the competition dataset are resized to the resolution of ~10m per pixel. The image patches have the size of 128 x 128 pixels and are labeled pixel-wise.

