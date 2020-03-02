*IrisFDTD*    
=========

*IrisFDTD* is a Fortran implementation of the Finite-Difference Time-Domain (FDTD) method, one of the most widely 
used Maxwell’s equation solvers in the field of computational electrodynamics for photonics and nanotechnology.

Light does funny things when interacting with structures consisting in tiny bricks of matter. These funny things show up naturally if one can solve Maxwell's equations and this is what I tried last years: to implement several numerical and analytical methods applied to Nanophotonics. Definetively, coding and seeing what's going on with EM fields in nanostructures has been one of my favorites games these years. I'm proud of most of the codes I worked on, but there is one that made feel great moments and also desperate ones. This is *IrisFDTD*, an implementation of the famous Finite-Difference Time-Domain (FDTD) method, one of the most widely used solvers of Maxwell’s equations in Nanophotonics.

<img style="float: right;" src="Z_SDL_H52.e3.bmp">

*IrisFDTD* is more than a program for me. Sometimes, I wonder what would happen if some day I will decide jumping to a different topic of research. Probably all the years of coding would be end in an old computer that nobody will never use. This is why I decided to share with others IrisFDTD and do it public. This is the motivation of this project. I hope IrisFDTD will be in the future a nice tool for researchers and students.


*IrisFDTD* is licensed under the AGPL and it is free to use.  However, if you are using, 
or plan to use it, specially if it is for research or academic purposes, please send an email with your name,
institution and a brief description of your interest for this program. If you use *IrisFDTD* in a work that leads to a 
scientific or academic publication, we would appreciate it if you would kindly cite *IrisFDTD* in your manuscript as:

> Sergio G. Rodrigo, [*Optical Properties of Nanostructured Metallic Systems: Studied with the Finite-Difference Time-Domain Method*](https://www.springer.com/gp/book/9783642230844), Springer-Verlag, Berlin, (2012).

Commercial applications may also acquire a commercial license. Please contact Sergio G Rodrigo <sergut@unizar.es>

Copyright (C) 2005-2020 Sergio G Rodrigo <sergut@unizar.es>

*IrisFDTD* is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License,or (at your option) any later version.
  
*IrisFDTD* is distributed in the hope that it will be useful for research or/and academic purpouses, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details. You should have received a copy of the GNU Affero General Public License along with *IrisFDTD*. If not,see <http://www.gnu.org/licenses/>.

***

*Finite-Difference Time-Domain method* 
---------------------------------------

The FDTD method has been applied in a great variety of engineering and physical problems since originally proposed in 1966 by K. Yee [1]. The FDTD method has been developed over the years, being one of the most spread methods in computational electromagnetism worldwide. In a nutshell, the optical properties of a given system (a living cell, an aircraft, a nanostructure…)  are obtained through calculations of the  electromagnetic field, which is propagated in discretized space and discretized time, according to both Maxwell equations and the constitutive relations (which state how materials respond to the EM field).  FDTD thus provides the whole “movie” of the electromagnetic field evolution of a given system. This information is then post-processed to obtain the EM response of the considered system.

*IrisFDTD* has been devoloped with the focus on the field of Nanoptics. Nanooptics aims at the understanding of optical phenomena at the nanoscale, beyond the realm of conventional optics and the diffraction limit of light. It is an emerging new field, which opens up new perspectives into the Nanoworld. It is motivated by the rapid growth of nanotechnology and material science. The former supplies the adequate tools and strategies for fabrication, manipulation and characterization of nanosystems, whereas the latter provides the material platforms required for the realization of specific optical effects. Undoubtedly, Nanooptics research is a very promising pathway towards the overcoming of some of the most immediate social challenges, such as the seek for novel technological grounds allowing further development of the knowledge and information   society and the search for clean, efficient energy sources. Therefore, the improvement of the numerical methods and computer technology to be applied in Nanooptics must be a goal by itself. 

*IrisFDTD* has been applied to several problems in Nanoptics [2], to name a few, it has been used to investigate the optical response of nano-structures based on 2d-atomically thin materials like Boron Nitride, with potential applications in optoelectronics in both infrared and THz regimes, and the study of non-linear effects in Nanophotonics, for their potential applications in high-resolution enhanced spectroscopies. The number of physical systems investigated with *IrisFDTD* is quite extense. Most of them gave raise to publications which can be found in the scientific literature (see Ref. [3]). Most of them...that is, there are also many never published that I'll try make available (Mie resonances, Green's functions in FDTD...).

 *References:*
 
[1] A. Taflove, S.C. Hagness, *Computational Electrodynamics: The Finite-Difference Time-Domain Method*, 3rd edn. (Artech House, Boston, 2005).

[2] Sergio G. Rodrigo, [*Optical Properties of Nanostructured Metallic Systems: Studied with the Finite-Difference Time-Domain Method*](https://www.springer.com/gp/book/9783642230844), Springer-Verlag, Berlin, (2012).

[3] https://publons.com/researcher/2827893/sergio-gutierrez-rodrigo/
 

***

*Working with *IrisFDTD**
--------------------------------


The best way (as always) to learn and use new programs is going through the examples. The table below will be updated with examples of my own research. The details are included in folders expecified in the table. 

While Windows and Linux executable versions of the program are provided (IrisFDTD_64bits_Windows & IrisFDTD_64bits_Linux), the code is not yet available. This is something I working on... The description of input files and how the information of optical properties are retrieved from the output files is on its way. 


|Available|Folder|Published (see [Publons](https://publons.com/researcher/2827893/sergio-gutierrez-rodrigo/))|
|:-----:|:-----:|:-----:|
|?  |PRB_83_235425_2011|S. G. Rodrigo, S. Carretero-Palacios, F. J. García-Vidal and L. Martín-Moreno, [*Metallic slit arrays filled with third order nonlinear media: Optical Kerr effect and third harmonic generation*](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.83.235425), Phys. Rev. B 83, 235425, (2011).|