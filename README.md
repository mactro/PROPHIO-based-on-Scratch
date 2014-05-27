PROPHIO based on Scratch
===========
This is the Prophio source package README file.

Prophio (Programming of Physical Objects) is a modification of Scratch, a programming language for beginners. It allows controlling and programming a M-System robot via Bluetooth. 

Prophio is written in Squeak, and depends on a Squeak virtual machine. For more information about squeak, see: http://www.squeak.org/. 

Prophio is based on Scratch 1.4 from MIT Media Labs, so most of guides applicable to Scratch will apply to Prophio as well. You will find original Scratch 1.4 sources in /src/ directory.

The Squeak source code for Prophio ( PROPHIO.image ) is set to open in "User Mode" by default. If you'd like to enter "Dev" mode to make changes to the source code, you can do so by following these steps: 

Download and uncompress the Squeak v2 Sources file, and place it in the Prophio directory. See this page for more info: http://www.squeak.org/Download/?version=2  Currently, the Squeak v2 sources file is downloadable from this url: http://ftp.squeak.org/2.0/SqueakV2.sources.gz

Then open Prophio and follow these steps:

1. Shift-click the Edit menu.
2. Click "Turn fill screen off".
3. Click the white area that appears at the right and bottom of the window.
4. Click open....
5. Click browser
6. The System Browser appears — this is where you can edit the code.

Since Prophio runs as an image on a Squeak virtual machine, all that needs to be compiled when packaging Scratch are the necessary plugins, which can be done  on Linux using the included makefile. The following libraries are necessary to build the plugins:
libcairo2-dev (>= 1.8.6), libpango1.0-dev (>= 1.20.5), libglib2.0-dev (>= 2.20.1)

Note: the Camera plug-in will make use of libv4l2 (>= 0.5.8) at run-time if found.

On Windows, you can use plugins from regular distribution of Prohio or Scratch 1.4.


