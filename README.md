# GNR-640---Mini-Project
**Figshare DOI**: https://doi.org/10.6084/m9.figshare.32228568

**Report Doc Name:** GNR_640_MiniProject.pdf
----------------------------------------------------------------------------------------------------------------------------------------------------------------
ERA5_data_processing.ipynb - The downloading and preprocessing of data. 

**STEPS:** Data Downloading > Clipping to USA shapefile > Gridding in 2 degree

interpolation_models.ipynb - The main code for interpolating the given data. 
Methods used for interpolation: 
1) Linear Kriging
2) Spherical Kriging
3) Gaussian Kriging
4) Exponential Kriging

**STEPS:** Clipping the data using USA shapefile > Converting in 2 degree spatial resolution using same spatial configuration as used for gridding ERA5 data. 

Statistical_Assessment.ipynb - Test of central tendency, dispersion and distribution characteristics

stationary_analysis.ipynb - Test for stationary using 1st and 2nd moment. 

