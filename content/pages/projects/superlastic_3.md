---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Superelastic and Superplastic Alloys - Problem Set 3
uid: 930bd449-6d42-b095-aae2-1811720720e4
---

_(b) Taillard, et al. \[[1](#ref)\] summarize Bouvet, et al.'s \[[2](#ref)\] attempt at a yield surface for superelastic alloys; this is a modification of the von Mises equivalent stress and criterion that we have discussed. Restate this criterion and its components in terms of the symbols used in class._

von Mises
---------

von Mises' (maximum distortion energy) criterion is "when the effective stress, defined as

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_1.jpg)

exceeds the uniaxial yield stress, then the material will plastically flow." The criterion was stated by von Mises without a physical interpretation, but it is now accepted that it demonstrates the critical value of the distortion (or shear) component of the deformation energy of a body. Based on this understanding, a body flows plastically in a complex state of stress when the distortional deformation energy is equal to the distortional deformation energy in uniaxial stress (tension or compression). This criterion is also known as the J2 plasticity criterion because it is the second invariant of the stress deviator.

Mathematically, the yield function for the von Mises condition is written as

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_2.jpg)

or alternatively,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_3.jpg)

where _k_ is a critical value. Substituting the value of J2 into this equation, we obtain the von Mises yield criterion as a function of the principal stresses:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_4.jpg)

Or as a function of the stress tensor components

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_5.jpg)

This equation defines the yield surface as a circular cylinder whose yield curve, or intersection with the deviatoric plane, is a circle with radius ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_6.jpg). This implies that the yield condition is independent of hydrostatic stresses, as is implied by the fact that it was derived from the deviatoric stress tensor.

In the case of uniaxial stress or simple tension, ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_7.jpg), so the von Mises criterion becomes ![superlastic_3_8.jpg](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_8.jpg). Using this equation, which gives the relation between the uniaxial yield stress,![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_10.jpg), and the pure shear yield stress, _k_, the von Mises criterion can also be expressed as a function of ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_10.jpg):

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_11.jpg)

For this equation, the radius of the yield curve is ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_12.jpg). The yield stress ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_10.jpg) is also called equivalent stress or von Mises stress, ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_14.jpg), which is used to predict yielding of materials under triaxial loading from results of simple uniaxial tensile tests. Thus,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_15.jpg)

where ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_16.jpg) are the components of the stress deviator tensor. Projected into the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_7.jpg) plane, the von Mises criterion is shown in the figure below.

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic1.jpg)

  
 

Projected into the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane, the Von Mises criterion is shown in the figure below.

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic2.jpg)

  
 

Taillard
--------

The Taillard plasticity criterion was stated as:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_21.jpg)

where

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_22.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_23.jpg)

and _a_ is a material constant that is determined empirically, and ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_24.jpg) is the effective stress described in the section above. In order for the above criterion to be expressed in notation consistant with the course materials, the term ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_25.jpg) must be expanded in terms of the component scalars. First, the stress deviator is defined as:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_26.jpg)

The determinant of that tensor is therefore:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_27.jpg)

Therefore, the Taillard condition can be expressed in expanded form by substituting the above expressions for ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_24.jpg) and ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_25.jpg) back into the original three equations that define it. I will refrain from that trivial substitution because it would be quite cumbersome for both author and reader.

Note that the projection onto the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) plane results in the simplifications:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_32.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_33.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_34.jpg)

Note that the projection onto the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane results in the simplifications:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_37.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_38.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_39.jpg)

_(c) Taillard, et al.'s Fig. 1 and 2 \[1\] demonstrate the yield surface in biaxial tension/compression and torsion for xCu-yAl-cBe, respectively. They claim Fig. 3 shows a difference between this response and that of NiTi. Graph the biaxially stressed yield surface for NiTi._

An arbitrary state of stress on the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane can be uniquely transformed into a position on the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) plane. This can be seen on the Mohr's circle, in which any conceivable state of stress can necessarily has two points with a principal stress and zero shear stress. However, there are states of stress on the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) plane that do not produce states of stress that fall on the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane. This can be seen on a Mohr's circle in which both principal stresses have the same sign, as shown below. This clearly means that data presented in the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) can be transformed onto the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane if and only if ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) has a different sign from ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg).

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic3.jpg)

  
 

Through Mohr's circle, Taillard's figures 2 and 3 can be transformed into the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) plane, and the data from the second quadrant of Taillard's figure 1 can be transformed onto the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane. All of this data was normalized by the uniaxial yield stress ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_58.jpg) so that it produced similar magnitudes for all materials and tested temperatures. The plot below shows the all three figures normalized and plotted in the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg) plane. Interestingly, The NiTi data from figure 3 agrees quite well with the Cu-Al-Be data from figure 1, but the Cu-Al-Be data from figure 2 agrees with neither.

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic4.jpg)

  
 

To confirm that the transformations were done correctly, the same data (except for the Cu-Al-Be primary data, for reasons stated previously) was also normalized and plotted in the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) plane. Although the trend is less clear, it is still there; the NiTi data agrees better with the Cu-Al-Be data tested at 32°C than the Cu-Al-Be data tested at 60°C.

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic5.jpg)

  
 

The change in yield surface between the two different temperatures for Cu-Al-Be could be explained if 60°C is above the Af temperature for Cu-Al-Be while 32°C is below the Mf temperature for Cu-Al-Be and the testing temperature for the NiTi was below that materials Mf. The changes between the two different temperatures of Cu-Al-Be would therefore represent two different phases of the material. This would indicate that the proposed yield surface would be appropriate for materials in their martensitic state but not for materials in their austenitic state. The agreement between the NiTi data and the Cu-Al-Be data taken at 32°C would indicate that the yield surface, when scaled properly, would characterize both the NiTi and Cu-Al-Be quite well.

_(d) Contrast the Bouvet yield surface with the other non-asymmetric yield surfaces considered in PS3. Is this equivalent to one of them or different, and how? What is the atomistic origin of the asymmetry justifying the Bouvet yield criteria?_

The yield surface presented in the papers is merely the Von Mises yield surface modified by the scalar, g:

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_21.jpg)

Therefore, the yield surface is the Von Mises yield surface when _g_\=1. This happens when _a_(1-_y_σ)=1. However, _y_σ is a complex function of the stress state, so there is no single parameter that causes this yield surface to degenerate to the Von Mises condition.

The yield condition presented in the papers is a curve fit of the data. Therefore, plotting the normalized source data along with the Mises and Tresca yield conditions will highlight the differences. This comparison is shown in both the ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_19.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_20.jpg) and ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_17.jpg) vs. ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/superlastic_3_18.jpg).

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic6.jpg)

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/suprlastic3_pic7.jpg)

  
 

What these plots highlight is the considerable difference between the symmetrical yield conditions, which have similar behavior in the compression and tension regimes while the superlastic yield surfaces has considerably different behavior in compression (negative normal stresses).

What is the atomistic origin of the asymmetry justifying the Bouvet yield criteria? The asymmetry justifying the Bouvet yield criteria is caused by a different behavior in compression regime or in tension regime. There is a tension-compression asymmetry (or strength-differential effect) in the yield stress. Through the atomistic aspect, first of all, the different behavior in compression regime and in tension regime can be explained by atomistic bonding energy. Exceeding the Bouvet yield criteria means that the material starts yielding, that is, plastic deformation. And plastic deformation is related to bond breaking and proportional to bonding energy.

Image removed due to copyright restrictions. Please see Fig. 1 in Sleight, Arthur. "Materials Science: Zero-expansion Plan." _Nature_ 425 (October 16, 2003): 676-676.

Compression is the regime of r < r0 and tension is the regime of r > r0. They are obviously different by intuition.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Taillard, K. et al. "Phase Transformation Yield Surface of Anisotropic Shape Memory Alloys." _Materials Science and Engineering A_ 438-440 (2006): 436-440.

\[2\] Bouvet, Cristophe, Sylvain Calloch, and Christian Lexcellent. "A Phenomenological Model for Pseudoelasticity of Shape Memory Alloys Under Multiaxial Proportional and Nonproportional Loadings." _European Journal of Mechanics - A/Solids_ 23 (January/February 2004): 37-61.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home) | [Problem Set 2]({{< baseurl >}}/pages/projects/superelastic_2) | Problem Set 3 | [Problem Set 5]({{< baseurl >}}/pages/projects/superelastic_5)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)