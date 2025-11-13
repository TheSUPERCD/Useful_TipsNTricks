## FOR SETTING UP MANIMGL (3b1b-version):

 - Need to install using `pip install manimgl`, after creating a conda virtual environment (mgl).
 - Need to install `libstdcxx-ng` from `conda-forge` after installing manimgl to get rid of the `pyglet`-window error.

## For setting up scrcpy (To use android-phone camera as a webcam):

 - Need to install `scrcpy` from `extra/scrcpy`.
 - Need to install `v4l2loopback-dkms`, `linux-headers`, and `v4l2loopback-utils`.
 - Run `sudo modprobe v4l2loopback` to create the virtual webcam and `v4l2-ctl --list-devices` to see the list of available video inputs.
 - Run the script in this repo `start_android_webcam` and see the magic happen!
