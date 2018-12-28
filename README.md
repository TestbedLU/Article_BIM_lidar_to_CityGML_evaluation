# Article_BIM_lidar_to_CityGML_evaluation

This repository contains FME workbenches from the submitted manuscript "Evaluating geometric aspects of integrating BIM models into city models". The FME workbenches convert Building Information Models (BIM) in IFC format to CityGML geometires. Since the aim of the study is to compare the geometries of CityGML building models created from BIM models with CityGML building models created from lidar data the transformation is on geometry level only; no attributes are mapped to create valid CityGML models. 

The CityGML building models are created in LOD1.2, LOD1.3 and LOD2.3 according to the detailed LOD definitions suggested by:
Biljecki, F., Ledoux, H., Stoter, J., 2016a. An improved LOD specification for 3D building models. Computers, Environment, and Urban Systems, vol. 59, pp. 25-37. https://doi.org/10.3390/ijgi4042842

__Content__:
1. revit2kanaan_LOD1.fmw - Transforming Kanaan Garden Cafe to LOD1.2 and LOD1.3
2. revit2kanaan_LOD23.fmw - Transforming Kanaan Garden Cafe to LOD2.3
3. revit2kristallen_LOD1_LOD2.fmw - Transforming Lund City Hall to LOD1.2, LOD1.3 and LOD2.3
4. revit2undervisningshuset.fmw - Transforming KTH Educational Building to LOD1.2, LOD1.3 and LOD2.3

The workbencehes are published without IFC models due to lack of permission.

For KTH Educational Building the script also adds a terrain intersection line to the CityGML building model if the BIM model is placed in a Digital Elevation Model (DEM).

## Built with
[FME](https://www.safe.com/) - Safe Software


## License

*BSD 3-Clause License*

*Copyright (c) 2018, TestbedLU*
*All rights reserved.*

See the [LICENSE.md](https://github.com/TestbedLU/Testbed_BIM_GIS/blob/master/LICENSE) file for details.
