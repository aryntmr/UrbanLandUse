# Tutorial to work on the repo

-	Use the `project_env.yml` to create the environment
-  While working on the file `core_acquire-imagery.ipynb` and `core_prepare-ground-truth.ipynb`, in the Load and inspect study area snippet. Check that it uses the file `_studyAreaEPSG4326.shp` which is not the part of the initial download file of the city. 
-   To obtain it, use the `studyArea.shp` file and change it's projection (by going into the properties) to EP4326 instead of UTM (which is selected by default).
-   Changed the `load_shape()` function in the `util_vectors.py`