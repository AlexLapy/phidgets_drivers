1. OVERVIEW:

Drivers for the Phidgets devices. The stack includes:

 * phidgets_c_api: a meta-package which downloads the Phidgets C API 
   from phidgets.com and installs it locally within the package's directory.

 * phidgets_api: a C++ wrapper of the C API which provides a base Phidget
   class and various inherited classes for the different phidget devices.

 * various packages exposing the functionality of specific phidgets using
   the ROS API.

2. INSTALLING:

To compile, simply run:

rosmake phidgets_api

To set up your udev rules for the phidgets USB devices, execute

phidgets_c_api/setup-udev.sh

You will be prompted for a sudo password.

