

## [PapARt](https://github.com/poqudrof/PapARt) - Paper Augmented Reality Toolkit

PapARt is in active development, and it will evolve to better fit its uses. For now 
it handles many different tasks: 

* Marker detection and tracking, with markers and natural features. [Help Needed to tend the tracking capabilites]. 
* Augmented reality rendering, in Processing. 
* Camera and projector calibration. 
* Touch detection and tracking from depth cameras. 
* «Touch» detection and tracking from color cameras. 
* 3D Scanner with structured light (in addition to depth cameras).
* Camera «drivers»: Processing, OpenCV, Kinect, Realsense and more...


The library is available on github and available for free, distributed under the 
LGPL and CeCILL-C licences. 

* Community forum. [Coming  soon]
* Github page for the [core](https://github.com/poqudrof/PapARt) and [examples](https://github.com/poqudrof/PapARt-examples).


PapARt was initially a reseach project from [Bordeaux University](https://www.u-bordeaux.fr/) and [Inria](https://www.inria.fr/en/centre/bordeaux).


## Processing libraries


### [Skatolo](https://rea-lity-tech.github.io/Skatolo/) GUI library.

Skatolo is a **fork of ControlP5**. We repackaged the code and reworked the pointer system to enable multi-touch inputs. We add dedicated widgets and 
controllers for our apps and for Augmented Reality. 

Skatolo also comes with [JRubyArt](https://ruby-processing.github.io/JRubyArt/) bindings and as a [ruby gem](https://rubygems.org/gems/skatolo/versions/0.7.1.0). The great work done in ControlP5 can be experienced in a more interactive way in ruby. With this it is possible to create GUI elements in presentations in Soby.


### [SVGExtended](https://rea-lity-tech.github.io/SVGExtended/), font and embedded support for SVG in Processing.

Processing is capable to display `.svg` images. However its support 
is limited in performance and capabilities. We did not work on 
performance but we extendend the support to enable the rendering 
of text and embedded images in svg files. 

This is notably used to render svg presentations in Soby described below. 

## Experimental programs

This is a list of experimental projects, mostly made as personal
projects

###  Presention software: [Soby](https://github.com/poqudrof/Soby)

Soby was inspired by Prezi and Sozi. It is a planar (pan/zoom) presentation software. 
The presentations are created with Inkscape, animated with a plugin from Sozi and displayed through Processing. 

It is an experimental project which enables to mix creative coding and presention softwares. 

Soby is in Ruby, and uses [JRubyArt](https://github.com/ruby-processing/JRubyArt).  


# Contributions

## Java bindings in [JavaCPP Presets](https://github.com/bytedeco/javacpp-presets)

We created java bindings for C++ libraries.

Stable presets: 
* We proposed some extensions to [Libfreenect](https://github.com/bytedeco/javacpp-presets/tree/master/libfreenect).
* Intel provides open source drivers for their Realsense devices. We created java bindings and compilation tools for Arch linux. [Librealsense in java](https://github.com/bytedeco/javacpp-presets/tree/master/librealsense). *An update to version 2.0 is not planned yet*. 

Unstable presets
* We worked with the Kinect for Xbox One and thus created a java binding for it. However it is not stable yet and requires additional work. [Libfreenect2 source](https://github.com/bytedeco/javacpp-presets/tree/master/libfreenect2).



## [Robus](https://github.com/Rea-lity-Tech/RobusRuby) in ruby.

[Robus](https://github.com/pollen/pyrobus) is a robotics framework from [Pollen Robotics](http://pollen-robotics.com/). 
We created an experimental version of Robus in Ruby to make it work in JRubyArt. 

