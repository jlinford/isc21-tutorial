# Schedule and Logistics

The event starts at **5:00am PST / 8:00am EST / 1:00pm BST** with cluster login 
instructions and an introduction to the Fujitsu A64FX.  

![Schedule](/schedule.png)
 
 * **Slides**: [Download slides](/slides.zip)
          
 * **Hands-on Materials**: https://gitlab.com/arm-hpc/training/arm-sve-tools/

 * **Registration**: ISC 2021 registration is required to attend this tutorial.  Please [register for ISC 2021 tutorials.](https://www.isc-hpc.com/registration-2021.html)

 * **Communication**: A Zoom meeting link will be provided to the registered attendees. *Please make sure that you have updated to the latest version of Zoom.*  [See this help article for instructions](https://support.zoom.us/hc/en-us/articles/201362233-Upgrade-update-to-the-latest-version).

 * **System Access**: Login details will be provided on the day of the event. This event is generously supported by the University of Bristol with access to
the [HPE Apollo 80](https://buy.hpe.com/us/en/servers/apollo-systems/apollo-80-system/apollo-80-system/hpe-apollo-80-system/p/1012970957) partition of [Isambard 2, the largest Arm-based supercomputer in Europe](https://insidehpc.com/2020/02/isambard-2-at-uk-met-office-to-be-largest-arm-supercomputer-in-europe/).  


# Tutorial Abstract

The Scalable Vector Extension (SVE) is the next-generation SIMD instruction set 
for Armv8-A. SVE does not specify a vector length and it uses predicates to 
dynamically select vector lanes. For many developers, this presents an entirely 
new way of thinking about vectorization. This tutorial will introduce tools from 
the Arm community for SVE programming and performance analysis, i.e. compilers, 
scientific libraries, profilers, and debuggers. *Remote access to SVE-enabled CPUs 
(Fujistu A64FX) will be provided.* The hands-on exercises will explore the unique 
features of SVE and demonstrate their applicability to a range of common 
programing motifs. This tutorial will demonstrate how to capture high-utility 
information and present it in meaningful ways, i.e. how much time is spent in 
application routines, where these routines are called in the source code, and 
how well the routines vectorize. Attendees will complete the tutorial with a 
working understanding of SVE and knowledge of how SVE may be used in their 
applications.

This hands-on, non-NDA event will introduce vector length agnostic programming 
and jumpstart developers targeting the the first CPU to implement SVE, the 
Fujitsu A64FX.  Hands-on exercises will introduce SVE compilers, libraries, and 
tools from Fujitsu, Cray, Arm, and GNU, and show how popular HPC codes can take 
advantage of SVE.  Don't miss out!  Remote access details will be provided to 
all registered attendees.

# Contact

 * John Linford <john.linford@arm.com>

# Acknowledgements

Many thanks to all our partners and teams within Arm who contributed content including, but not limited to, Dani Ruiz-Munoz, Miguel Tairum-Cruz, Olly Perks, Francesco Petrogalli, Alex Rico, Roxana Rusitoru, and Jelena Milanovic.

