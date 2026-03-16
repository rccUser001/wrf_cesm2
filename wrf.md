
# WRF Installation Instructions

This guide provides step-by-step instrucitons for installing WRF, based on the official documentaiton [1]. 
Please refer to [1] for detailed system environment checks. For example, after downloading [2], test your Fortran 
compiler as described. Additional tests are listed in [1], ensure you also perform all library compatibility checks
using [3].

Below are the summarized steps to build WRF exactly as outlined in [1].

1. Download your desired WRF version from [4].
2. Run ```./configure```
3. Run, e.g., ```./compile em_scm_xy```
4. Locate the ```.exe``` files in the main directory


### References

[1] [WRF Official Compilation Tutorial](https://www2.mmm.ucar.edu/wrf/OnLineTutorial/compilation_tutorial.php)
[2] [Fortran Compiler Test Files](https://www2.mmm.ucar.edu/wrf/OnLineTutorial/compile_tutorial/tar_files/Fortran_C_tests.tar)
[3] [Library Compatibility Test Files](https://www2.mmm.ucar.edu/wrf/OnLineTutorial/compile_tutorial/tar_files/Fortran_C_NETCDF_MPI_tests.tar)
[4] [WRF Releases on GitHub](https://github.com/wrf-model/WRF/releases)
