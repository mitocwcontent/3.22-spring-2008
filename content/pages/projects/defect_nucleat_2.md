---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Defect Nucleation in Crystalline Metals - Problem Set 2
uid: 6ab0d9bf-3df7-cba9-3348-74c6c3b67d39
---

  
 

  
 

_(a) What is the average Young's elastic modulus of the Au nanopillar in Fig. 1A of Li \[[1](#ref)\]? From comparison of these data with E of Au reported in the literature, do you infer that elastic properties of Au are size-dependent down to these sample diameters?_

The average Young's elastic modulus of the Au nanopillar is the slope of the unloading curve which is equal to 48.5 GPa. The E of Au reported in literature is around 43 GPa along the direction which is the same direction in which the compression was done on the Au nanopillar. We conclude that the elastic modulus is not dependent on specimen size as it is a property that is related to the internal energy change associated with bond stretching or compression and thus does not depend on the size of the sample.

_(b) Derive the expression used several times by Li \[[1](#ref)\] relating the maximum shear stress generated within an indented material as a function of applied load, Young's elastic modulus, and indenter radius. You may wish to consult K. Johnson's Contact Mechanics \[[2](#ref)\]._

We are interested in modeling the maximum shear stress a material experiences when being indented. This is done by considering the elastic contact of two smooth surfaces. Among other things, we need to know how contact area changes with increased applied load. Contact mechanics allows us to do this so that we can also predict the deformation (stress, strain) in the region of the material affected by the contact.

We begin by describing the geometry of two surfaces being brought into contact. This allows us to define our problem in terms of critical variables.

Consider 2 surfaces in contact described by Eq. 1 and Eq. 2 below. Here, we assume that we have two smooth surfaces with surfaces which can be described by an equation which must be continuous up to the second derivative.

  
 

| Surface 1: |  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_1.jpg) {{< br >}}{{< br >}}  | Eq. 1 |
| Surface 2: |  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_2.jpg) {{< br >}}{{< br >}}  | Eq. 2 

  
 

Therefore, the separation is _h = z1 - z2_. However, this separation currently requires two different coordinate systems for its definition.

Switching to common set of axes: _x and y_

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_3.jpg) {{< br >}}{{< br >}}  | Eq. 3 

  
 

Since these axes are arbitrary, we can pick them intelligently to make our description of the problem easier. Here, we choose our axes such that C = 0,

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_4.jpg) {{< br >}}{{< br >}}  | Eq. 4 

  
 

where _A and B_ are positive constant; _R' and R"_ are the principal relative radii of curvature.

We can get relations for A and B using geometrical considerations. This is done in Appendix 2 of \[[2](#ref)\], but omitted here for clarity.

  
 

|  {{< br >}}{{< br >}} ![defec_nuclea_2_5.jpg](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_5.jpg) {{< br >}}{{< br >}}  | Eq. 5 |
|  {{< br >}}{{< br >}} ![defec_nuclea_2_6.jpg](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_6.jpg) {{< br >}}{{< br >}}  | Eq. 6 

  
 

where α is the angle between the axes of principal curvature of each surface (_x1 and x2_)

We will now consider two surfaces of general shape, centered at _O_, deformed with a normal load _P_ applied (Figure 1).

  
 

Image removed due to copyright restrictions. Please see Fig. 4.2 in \[[2](#ref)\].

Figure 1 Schematic showing the geometry of the problem \[[2](#ref)\].

  
 

We now must utilize Hertzian contact theory to determine displacements, which then allow us to find strains and stresses. Hertzian theory makes some assumptions which must be declared at this juncture. It is assumed that each body can be regarded as an elastic half-space which is loaded over an elliptical area on its surface plane. This is done because well-developed solutions exist for solving boundary value problems for an elastic half-space. It is also assumed that the surfaces are continuous and non-conforming. The strains experienced by the half-space area small. These last two considerations are represented by the assumptions that the contact radius is much smaller than the radius of curvature of each body. Finally, it is assumed that the surfaces are frictionless.

During compression, distant points _T1_ and _T2_ move towards O by displacements _δ1_ and _δ2_.

Due to contact pressure, the surface of each body is displaced parallel to O in the z direction by _uz1_ and _uz2_ relative to _T1_ and _T2_.

Looking at points S1 and S2, which are coincident within the elastic surface:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_7.jpg) {{< br >}}{{< br >}}  | Eq. 7 

  
 

If we write _δ = δ1 + δ2_ and use Eq. 6, we get elastic displacements:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_8.jpg) {{< br >}}{{< br >}}  | Eq. 8 

  
 

At this point, we can consider the specific geometry of our problem of interest to simplify the equations which describe the evolutions of the contacting bodies.

For this situation, we are interested in the contact of two solids of revolution. A solid of revolution is a solid body which is obtained by revolving a plane figure about some axis.

_(R1' = R1" = R1 ; R2' = R2" = R2)_

Therefore: _A = B = ½(1/R1 + 1/R2)_

The circular symmetry of the problem means that the contact area will be circular (with a radius we will call _a_).

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_2_9.jpg) {{< br >}}{{< br >}}  | Eq. 9 

  
 

Where _(1/R) = (1/R1 + 1/R2)_ is the relative curvature.

A pressure distribution which gives displacements satisfying Eq. 9 is given in Johnson Section 3.4 \[[2](#ref)\]. This gives the stress resulting from an applied pressure over a circular area for an elastic half-space (Hertzian contact).

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_10.jpg) {{< br >}}{{< br >}}  | Eq. 10 

  
 

This pressure distribution gives the displacement:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_11.jpg) {{< br >}}{{< br >}}  | Eq. 11 

  
 

Since the pressure acting on the second body is equal to the first, we can write:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_12.jpg) {{< br >}}{{< br >}}  | Eq. 12 

  
 

Substituting Eq. 11 into Eq. 9 for _uz1_ and _uz2_, we are left with:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_13.jpg) {{< br >}}{{< br >}}  | Eq. 13 

  
 

Which give us the radius of circle contact, _a_, and the mutual approach of distant points, _δ_:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_14.jpg) {{< br >}}{{< br >}}  | Eq. 14 |
|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_15.jpg) {{< br >}}{{< br >}}  | Eq. 15 

  
 

The total load compressing the solids is:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_16.jpg) {{< br >}}{{< br >}}  | Eq. 16 

  
 

Substituting this into Eq. 14 and Eq. 15, we get:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_17.jpg) {{< br >}}{{< br >}}  | Eq. 17 |
|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_18.jpg) {{< br >}}{{< br >}}  | Eq. 18 

  
 

We also get an equation for the maximum pressure, _po_, if we compare our new expressions for _a_ and _δ_ with the old ones.

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_19.jpg) {{< br >}}{{< br >}}  | Eq. 19 

  
 

We now have expressions for contact size, compression, and maximum pressure.

For this pressure distribution, the stresses beneath the surface along the z-axis are (refer to Johnson Section 3.4 \[[2](#ref)\]):

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_20.jpg) {{< br >}}{{< br >}}  | Eq. 20 |
|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_21.jpg) {{< br >}}{{< br >}}  | Eq. 21 

  
 

These are the principal stresses. Therefore, our principal shear stress is:

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_22.jpg) {{< br >}}{{< br >}}  | Eq. 22 

  
 

We now plug in the values for our principal stresses to get an expression for the maximum shear.

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_23.jpg) {{< br >}}{{< br >}}  | Eq. 23 

  
 

This principal shear stress is maximized at a depth of _z_ _\= 0.48 a (for ν = 0.3)_. This step was evaluated in Maple. Substitution gives us an expression for the maximum shear stress under an indenter.

  
 

|  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_2_24.jpg) {{< br >}}{{< br >}}  | Eq. 24 

  
 

P is the indentation load. R is the radius of curvature of the indenter tip. E\* is the effective elastic modulus.

This equation tells us that the maximum shear stress occurs below the contact surface and is equal to 0.31 times the maximum pressure. This can also be expressed in terms of variables which can be easily measured in an experimental situation. From this equation, we would expect critical plastic events to occur underneath the surface of an indented material.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Li, Ju. "The Mechanics and Physics of Defect Nucleation." _MRS Bulletin_ 32 (February 2007): 151-159.

\[2\] Johnson, K. L. _Contact Mechanics_. Cambridge, UK: Cambridge University Press, 2008. ISBN: 9780521347969.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom) | Problem Set 2 | [Problem Set 3]({{< baseurl >}}/pages/projects/defect_nucleat_3) | [Problem Set 5]({{< baseurl >}}/pages/projects/defect_nucleat_5)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)