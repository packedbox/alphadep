Alphadep Toolkit
----------------

A set of utility programs and plugins to integrate Syphon/FFGL capable video applications (e.g. Resolume) with Kinect effects and CK lights.

* CKVideoDriver: Route pixels from a Syphon server to Philips Color Kinetics light fixtures
    * Currently supports routing single color values to RGB light fixtures ony by one.
    * Zone averaging, light arrays and 12x12 video tiles are coming next.
* ADServer: Pipe Kinect RGB and depth information to Syphon clients by storing depth in the alpha channel
* coming next: FFGL plugins designed to operate on alpha-as-depth video input.

