# isochrones
The repository contains a library pf isochrone spectra
At this site, there are several types of files/directories:

- the TAB directory, which contains a table of parameters of each isochrone
in the library as taken or derived from the Geneva isochrones. 

- several gzipped tar directories for the 30 isochrones, labeled by the name of the
isochrone. Each contains the full spectrum of each mass-point of the isochrone,
e.g. 51 spectra comprising the Z004t6.0. The file names of individual spectra
give the stellar mass and have the extension, .spec, e.g. *Z004t6.0m3.658.spec*. 

–- analogous isochrone directories, with the name giving the isochrone
and stellar mass, so that a user can access individual spec files, rather than
downloading the whole, large set of spectra for the given age and metallicity;

- the IMFSALP directory containing the gzipped IMF-integrated spectrum
for all 30 isochrones, with the Salpeter power-low exponent alpha=-2.35. The
individual files have names of the isochrone with the extension, *.imfsalp*,
e.g. *Z002t6.7R.imfsalp*. 

- the IMF1.35 directory, which contains the gzipped IMF-integrated spectrum
of each isochrone assuming a top-heavy IMF with alpha=-1.35.

- directory *docs*: 
contains file *manual.pdf*, the paper (Hubeny & Heap, 2023, arXiv:2309.01024)),
serving as a detailed user's guide to the presented spectral libraries
