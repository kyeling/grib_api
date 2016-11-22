# grib_api
<pre>
GRIB API is the ECMWF encoding/decoding software for GRIB edition 1 and 2.

Documentation can be found here:
    https://software.ecmwf.int/wiki/display/GRIB/Home


INSTALLATION
-------------

1. Download GRIB API from https://software.ecmwf.int/wiki/display/GRIB/Releases

2. Unpack distribution:
   > tar -xzf grib_api-x.y.z-Source.tar.gz

3. Create a separate directory for the build:
   > mkdir build
   > cd build

4. Run cmake pointing to the source and specify the installation location:
   > cmake  ../grib_api-x.y.z-Source -DCMAKE_INSTALL_PREFIX=/path/to/where/you/install/gribapi

5. Compile, test and install:
   > make
   > ctest
   > make install


For more details, please see:
https://software.ecmwf.int/wiki/display/GRIB/GRIB+API+CMake+installation



COPYRIGHT AND LICENSE
------------------------

Copyright 2005-2016 ECMWF.

This software is licensed under the terms of the Apache Licence Version 2.0
which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

In applying this licence, ECMWF does not waive the privileges and immunities granted to it by
virtue of its status as an intergovernmental organisation nor does it submit to any jurisdiction.
</pre>
