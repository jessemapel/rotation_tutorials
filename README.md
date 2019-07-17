# Rotation Tutorials
Jupyter notebook tutorials for how reference frames and rotations work.

Most of the style and layout has been lifted from Eric Ma's excellent
[Network Analysis Made Easy](https://github.com/ericmjl/Network-Analysis-Made-Simple).


## Getting Started
You can use a Python 3 install of [Anaconda](http://docs.anaconda.com/anaconda/install/)
to easily setup the run the notebooks. Once you have Anaconda install run the
following commands from the root directory of this repo to setup your environment
and start your notebook server:

1. `conda env create -f environment.yml`
1. `conda activate rotations`
1. `jupyter lab`

This will open up a jupyter lab instance in your browser. From there, you can
select the notebook to work on from the left-hand menu.

## Resources

* [quaternion applet](https://quaternions.online/) - A good online applet for visualizing quaternions
* [wolfram alpha](https://www.wolframalpha.com/input/?i=quaternion+(0.5,+0.5,+0.5,+0.5)) - wolfram alpha will give you almost every representation of a rotation and some handy visualizations
* [NAIF Rotations Required Reading](https://naif.jpl.nasa.gov/pub/naif/toolkit_docs/C/req/rotation.html)
* [NAIF Reference Frames Required Reading](https://naif.jpl.nasa.gov/pub/naif/toolkit_docs/C/req/frames.html)
* [Rotations and Quaternions](https://en.wikipedia.org/wiki/Quaternions_and_spatial_rotation) - In depth explanation of how quaternions relate to rotations
