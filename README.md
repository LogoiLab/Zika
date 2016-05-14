This is an analysis of existing Zika data
=
All analysis is done in [KNIME](knime.org) and [ArcGIS](esri.com).

If there is a data source for Zika that you come across that is not in this repository please create an issue or submit a pull request.

Data Wishlist:
-

- [X] Microcephaly Data
- [X] Zika Case Data
- [X] Mosquito Population Data
- [X] Global Adminstrative Area Data
- [ ] Zika Infection Rate Data
- [ ] Global Human Population Data

---
If you would like to add you own analysis please fork this repo and submit a pull request.

Important Note!
-

For ArcGIS Users:

ArcGIS uses full paths(cause it's proprietary and **WEIRD**). In order for the data to work with the [`Global_Infection_History.mxd`](https://github.com/LogoiLab/Zika/tree/master/ArcGIS/Global_Infection_History.mxd) file you must first add the [`Zika.gdb`](https://github.com/LogoiLab/Zika/tree/master/ArcGIS/Zika.gdb) geodatabase under the [`ArcGIS`](https://github.com/LogoiLab/Zika/tree/master/ArcGIS/) folder and then import the necessary shapefiles from the geodatabase.

Also, any geodatabase shapefile within [`Zika.gdb`](https://github.com/LogoiLab/Zika/tree/master/ArcGIS/Zika.gdb) can be added to any ArcGIS session to be viewed and interpreted.

Contributors
-

LogoiLab *(Chad Baxter)*

montecodei *(Montgomery Webb)*
