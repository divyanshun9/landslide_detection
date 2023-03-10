
## Challenge Description

The aim of the competition is to promote innovative algorithms for automatic landslide detection using remote sensing images around the globe, and to provide objective and fair comparisons among different methods. The competition ranking is based on a quantitative accuracy metric (F1 score) computed with respect to undisclosed test samples. Participants will be given a limited time to submit their landslide detection results after the competition starts. The winners will be selected from the top three solutions in the competition ranking.

Special prizes will be awarded to creative and innovative solutions selected by the competition's scientific committee based on originality, generality, and scalability.

## Data Description

The Landslide4Sense dataset has three splits, training/validation/test, consisting of 3799, 245, and 800 image patches, respectively. Each image patch is a composite of 14 bands that include:

- **Multispectral data** from [Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2): B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12.

- **Slope data** from [ALOS PALSAR](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-radar-alos-palsar-radar-processing-system): B13.

- **Digital elevation model (DEM)** from [ALOS PALSAR](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-radar-alos-palsar-radar-processing-system): B14.

All bands in the competition dataset are resized to the resolution of ~10m per pixel. The image patches have the size of 128 x 128 pixels and are labeled pixel-wise.

