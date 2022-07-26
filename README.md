# lrose-topaz

<img align="left" width="175" height="175" src="./docs/images/LROSE_logo_small.png">
<img align="right" width="175" height="175" src="./docs/images/CYCLONE.jpeg">

## **LROSE Topaz** - The Lidar Radar Open Software Environment "Cyclone" Release

[![DOI](https://zenodo.org/badge/339518592.svg)](https://zenodo.org/badge/latestdoi/339518592)

The fourth LROSE release is called **"Topaz"** and encompasses six key toolsets that define a core lidar/radar workflow: *Convert, Display, QC, Grid, Echo, and Winds*

Topaz can be installed with pre-compiled binaries or compiled from source in C++ for native apps on Linux or Mac. Preliminary support is available for some tools on Windows.

Full documentation for Topaz is available on the [LROSE website](https://wiki.lrose.net)

We encourage users to [register](https://lrose.net/software.html) in order to receive critical software updates, and sign up for the mailing list to help build the LROSE community.

[Help](https://lrose.net/help.html) can be obtained by posting issues directly to the lrose-core Github repository, via our help mailing list, or Discourse user forum.

LROSE is a co-operative project between:

  * [Dept. of Atmospheric Science at Colorado State University (CSU)](http://www.atmos.colostate.edu/) and the
  * [The Earth Observing Lab at the National Center for Atmospheric Research (NCAR)](https://www.eol.ucar.edu/content/lidar-radar-open-software-environment).

LROSE is funded by the [National Science Foundation](https://www.nsf.gov).

**Topaz** focuses on high-quality, well-tested, well-maintained and well-documented key applications as ‘building blocks’, allowing users to assemble trusted, reproducible workflows to accomplish more complex scientific tasks.

In the current release, the following tools are available:

## Convert
  * **RadxPrint** - Query files to determine properties and support by the Radx engine
  * **RadxConvert** - Convert 24 different lidar and radar formats to CfRadial NetCDF format
  * **RadxBufr** - Convert Bufr format to CfRadial NetCDF format

## Display
  * **HawkEye** - Real-time and archive display suitable for both scanning and vertically pointing radars.

## Quality Control

  * **RadxDiffFields** - Compare two fields in different CfRadial files
  * **RadxDiffVol** - Compare two volumes in different CfRadial files
  * **RadxMergeFields** - Merge fields from different CfRadial files
  * **RadxFilter** - Perform simple filtering operations
  * **RadxPersistentClutter** - Create a mask for persistent ground clutter

## Grid
  * **Radx2Grid** - Gridding and interpolation of ground-based radar data
    * 3-D Cartesian gridding (x, y, z)
    * Cartesian PPIs (x, y, elevation)
    * Regular polar grid (range, azimuth, elevation)

## Echo
  * **RadxKdp** - KDP and Attenuation calculations
  * **RadxPid** - KDP, Attenuation, and Particle Identification
  * **RadxRate** - KDP, Attenuation, PID, and Rain Rate
  * **RadxQpe** - Accumulated Quantitative Precipitation Estimation

## Wind
  * **RadxEvad** - Extended Velocity Azimuth Display single-Doppler retrieval
  * **FRACTL** - Fast Reorder and CEDRIC Technique in LROSE multi-Doppler retrieval
  * **SAMURAI** - Variational multi-Doppler retrieval and analysis package
  * **VORTRAC** - Single-Doppler wind retrieval for vortices using the GBVTD or GVTD algorithms

### Future Release Plans

Topaz is considered an 'stable' release.
