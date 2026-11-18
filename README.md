# isochrones
The repository contains a library pf isochrone spectra
At this site, there are several types of files/directories:

- directory SPEC that contains several subdirectories, each for a given
metallicity, age, and rotational status. For instance, directory
*iso_Z0004t6.7R* contain spectra for all mass-points of the isochrone
with metallicity Z=0.004, log age=6.7 yrs, and with rotation. <br>
So far, only two ages are included, t=6.0 and 6.7, but it is planned to
add more.

- the TABS directory, which contains a table of parameters of each isochrone
in the library as taken or derived from the Geneva isochrones. 

- the IMFSALP directory containing the gzipped IMF-integrated spectrum
for all 30 isochrones, with the Salpeter power-low exponent alpha=-2.35. The
individual files have names of the isochrone with the extension, *.imfsalp*,
e.g. *Z002t6.7R.imfsalp*. 

- the IMF1.35 directory, which contains the gzipped IMF-integrated spectrum
of each isochrone assuming a top-heavy IMF with alpha=-1.35.

- directory *docs*: 
contains file *manual.pdf*, the paper (Hubeny & Heap, 2023, arXiv:2309.01024)),
serving as a detailed user's guide to the presented spectral libraries
