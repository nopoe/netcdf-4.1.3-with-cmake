# CMakeList file for cxx component of NetCDF

set ( SOURCES
    netcdf.cpp netcdfcpp.h netcdf.hh
    ncvalues.cpp ncvalues.h
    )

add_library( netcdf_c++ ${SOURCES} )

target_link_libraries( netcdf_c++ netcdf )
