# computem

These programs calculate high resolution conventional and scanning transmission electron microscope (CTEM, STEM) images of thin specimens from first principles using the multislice method for electrons in the energy range of approximately 60 keV to 1000 keV.  The fundamental theory and usage are described in "Advanced Computing in Electron Microscopy" (Springer 2020) and Acta Cryst. A72 (2016) p. 1 by Earl J. Kirkland.  Please refer to these documents for the theory of calculation and how to use these programs.

computem uses a GUI and the temsim group uses a command line interface.  The user is assumed to have some understanding of optics, Fourier transforms, electron microscopy and computer skills at the graduate or advanced undergraduate level. Click on "Files" to download Windows and Mac binary executable files or source code.

All code is AS-IS with ABSOLUTELY NO WARRANTY OR GUARANTEE of any kind to the extent permitted by law under the GNU public license (GPL).

## GPU/cuda code

The GPU enabled program autostem_cuda can be much faster but the windows executable requires the cuda library cufft64_10.dll, which is a large file. github does not easily allow large files to be uploaded, so this dll cannot be easily included here and must be obtained separately (perhaps from NVIDIA), if you wish to run this program.

## release notes 

[27] 14-aug-2022 add COM detector to STEM

[26] 26-dec-2021, 5-feb-2022 small updates to python 3.8, numba in MTFgraphing
[25] 10-sep-2021 add win10 version of autostem_cuda (GPU)
[24] 23-jul-2021 small fixes and add autoslic animation
[23] 16-nov-2020 add juliaMTFgraphing and EMprograms.html
[22] 6-oct-2019 variety of small bug fixes
[21] 7-oct-2018 add autostem_cuda (GPU, linux cmd line only)
[20] 21-may-2018 add segmented detector in STEM (cmd line only)



