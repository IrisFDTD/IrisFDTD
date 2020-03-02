Rodrigo et al., "Metallic slit arrays filled with third-order nonlinear media: Optical Kerr effect and third harmonic generation", PRB 83, 235425 (2011)
-----------------------------------------------------------------------------


**The paper was a theoretical study on the non-linear optical properties of both gold and nickel slit arrays inlaid with a third order nonlinear dielectric medium. We investigated the Optical Kerr Effect and Third Harmonic Generation in these typical systems in Nanophotonics. In this version of the IrisFDTD program the results found in *PRB 83, 235425 (2011)* can be easily reproduced. Below the examples are listed:**

*Updated: 02/03/2020*

> **In jobs:**

+ *cexe_1*: Fig.1(b) 
+ *cexe_2-6*: Several points in Fig.2(c)-(d), calculated for a gaussian wave.
+ *cexe 7-11*: Several points in Fig.2(c), calculated for a real-valued plane wave.
+ *cexe_2_1D* and *cexe_7_1D*: 1D tests. Propagation of GW & PW in vacuum. Calculation of powers, intensities for real- complex- valued plane waves. 

> **How to run an example:**

+ Copy the IrisFDTD program in a cexe_* directory.
+ Run the IrisFDTD program. That's all. 

> **The inputFDTD.dat file:**

+ The IrisFDTD.dat files provides all neccesary inputs to IrisFDTD program. Of course, it is not straightforward to understand all at once, but most of the important information, like the geometry of the system and how the illumination is defined..., are things easily found within it. In the examples, each input value is followed by the name of the variable in the Fortran code and a brief explanation. Fully describe the inputFDTD.dat file is one of the most hard tasks of this project. 

> **Retrieve the optical properties from the output files:**

+ For the moment the inputs are built so you can reproduce many of the figures in the paper, so let's see where do we put our attention among all the files the IrisFDTD program generates in one run. 
  - *cexe_1*: Fig.1(b) shows transmission, reflection and absorption through a slit array filled with a Kerr nonlinear media in the linear regime (low powers). Reflection and transmission are saved in ref.dat and trans.dat files. Each file consists in a one column sequence of numbers. The first 400 numbers correspond to the number of wavelengths for which reflection and transmission are calculated. The number of wavelengths and the initial and final wavelength can be modified in IrisFDTD.dat. Search within the file for "nopto", "lno" and "lnf". After the wavelength list we see the character "#" followed by a number, which it is the time step. The IrisFDTD program does a on-fly Fourier Transformation and you can see how a given spectrum converges looking at these snapshots. The total simulation time can be modified in the IrisFDTD.dat file, search for "Running Options". Below you will see 200.0 fs are used for this example. The number of times reflection and transmission is saved is 50, which is introduced just above the total simulation time.

--- 

*IrisFDTD* is licensed under the AGPL and it is free to use.  However, if you are using, 
or plan to use it, specially if it is for research or academic purposes, please send an email with your name,
institution and a brief description of your interest for this program. If you use this version of *IrisFDTD* to calculate optical Kerr effects in a work that leads to a scientific or academic publication, we would appreciate it if you would kindly cite *IrisFDTD* in your manuscript as:

>S. G. Rodrigo, S. Carretero-Palacios, F. J. García-Vidal and L. Martín-Moreno, [*Metallic slit arrays filled with third order nonlinear media: Optical Kerr effect and third harmonic generation*](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.83.235425), Phys. Rev. B 83, 235425, (2011).

Commercial applications may also acquire a commercial license. Please contact Sergio G Rodrigo <sergut@unizar.es>

Copyright (C) 2005-2020 Sergio G Rodrigo <sergut@unizar.es>

*IrisFDTD* is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License,or (at your option) any later version.
  
*IrisFDTD* is distributed in the hope that it will be useful for research or/and academic purpouses, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details. You should have received a copy of the GNU Affero General Public License along with *IrisFDTD*. If not,see <http://www.gnu.org/licenses/>.

