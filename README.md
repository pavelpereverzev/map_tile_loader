# MapTileLoader

QGIS plugin which download and stitch XYZ imagery.
This tool allows QGIS users to download stitched chunks of tile map services provided in plugin.

### Quickstart guide

1. Open QGIS, find a location which XYZ fragment you would like to get and launch a MapTileLoader plugin.
Select a `Source` from combobox, then set the download zoom level.

>[!NOTE]
>The more zoom is, the more detailed picture will be in output and the more time it takes to download.

2. Press `Draw frame` <img style="pointer-events: none;" src="https://raw.githubusercontent.com/qgis/QGIS/refs/heads/master/images/themes/default/mActionMapIdentification.svg"> button to draw a bounding box of downloading area. This box can be also saved and loaded (buttons `Save frame` and `Load frame`) as custom files for further downloads of another sources. 
3. Point the save path. It is recommended to be an empty folder in order to keep your data safe.
4. Check a tick `Add image on load` if downloaded image should be added to project right after it is ready.
5. Finally press `Download` button to start downloading process.

## Options:
+ Option `Optimize image` will create overviews (pyramids) for faster rendering of raster layer in QGIS
+ You can also add modify XYZ sources by editing list of them. Press button `Edit sources` <img style="pointer-events: none;" src="https://raw.githubusercontent.com/qgis/QGIS/refs/heads/master/images/themes/default/mActionEditTable.svg"> to view current sources. In this window you can add new, modify and delete existing XYZ sources. Adding new source allows you to import existing XYZ sources from QGIS settings or you can add custom one.

Video guide:

https://github.com/user-attachments/assets/b67d4bb5-5309-4821-a840-06220d59b511
