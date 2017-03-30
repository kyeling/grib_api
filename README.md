# grib_api
<pre>
+------------------+
| IMPORTANT NOTICE |
+------------------+
Please note that 'ecCodes' is now the primary GRIB encoding/decoding package used at ECMWF.
Nevertheless GRIB API will be maintained and new releases made publicly available to support
decoding of ECMWF model output.
Replacing GRIB API with ecCodes is expected to be transparent for current GRIB API users.
In particular the "grib_" functions are included in the ecCodes library.
Users are strongly advised to start the migration process.

For more details, please see:
https://software.ecmwf.int/wiki/display/ECC/ecCodes+Home


GRIB API
-------------
GRIB API is the encoding/decoding software for GRIB edition 1 and 2 developed at ECMWF.

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

Copyright 2005-2017 ECMWF.

This software is licensed under the terms of the Apache Licence Version 2.0
which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

In applying this licence, ECMWF does not waive the privileges and immunities granted to it by
virtue of its status as an intergovernmental organisation nor does it submit to any jurisdiction.
</pre>
