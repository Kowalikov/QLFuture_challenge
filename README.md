# QLFuture 2025 Capgemini challenge

Repository for second challenge data from Capgemini and City of Konin for QLFuture 2025 challenge.

> Remember to download data and assets binaries and unpack! [Link to data](https://github.com/Kowalikov/QLFuture_challenge/releases/tag/v1.0).

### Strucutre:

```
├───assets                  #
│   ├───data_preview        # Simple png files of tifs in low resolution
│   └───visualizations      # Nice visuals for the potential electric plant
├───data                    # data folder for tifs files
└───tutorials               # jupyter notebook tutorials
```



### Files legend:

In the `./data` dir the tif files are:
- transparent mosaic group1 - main file with channels `[r,g,b,alpha mask]`
- DSM - digitally corrected file with single channel - grayscale
- DTM - digitally corrected file with single channel - grayscale, with removed plants
