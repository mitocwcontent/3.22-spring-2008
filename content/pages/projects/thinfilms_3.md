---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Plasticity and Fracture of Microelectronic Thin Films/Lines - Problem Set 3
uid: 1cc6e515-e08d-3ae8-5946-4bd60d338299
---

_(b) Nejhad, et al. \[[1](#ref)\] present an analysis of retained internal stresses, and an associated elastic analysis in Eq. (8). Justify the form of Eq. (8) in terms of crystal structure of the two film materials of interest, and the origin of the strain terms._

  
 

Image removed due to copyright restrictions. Please see Fig. 7 in \[[1](#ref)\].

  
 

Let us consider the two-film structure model above; we can refer to ZnO as material 1, and Si3N4 as material 2.

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_1.jpg)

And as shown by the paper, we have the table below:

  
 

Table removed due to copyright restrictions. Please see Table 1 in \[[1](#ref)\].

  
 

We can separate the compliance matrix to two parts: the first one is related to the 1, 2, 3 dimension, and the other is related to the 4, 5, 6 dimension below:

For Si3N4 as material 2,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_2.jpg)

For ZnO as material 1,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_3.jpg)

For the two-layer composite, we can predict that the matrix has the below form,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_4.jpg)

Now we need to determine P, Q, J, L, K and M from the matrices of materials 1 and 2. Let us determine them one by one.

We set the volume fraction of material 1 as a and the volume fraction of material 2 as b.The equation is shown below,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_5.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_6.jpg)

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_7.jpg) = extrinsic strain = thermal strain in this work

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_8.jpg) = intrinsic strain =

1.  dopants
2.  "atomic peening" which causes compressive stress
3.  microvoids which cause tensile stress
4.  gas entrapment which causes compressive stress
5.  shrinkage during process which causes tensile stress
6.  grain boundaries

_(c) After Eq. (10) \[[1](#ref)\], the authors state that there are so many contributors of intrinsic strain that it is difficult to consider them quantitatively. Rank-order the sources they list in terms of relative amount of stress contribution for this system, and justify your answer._

The contributors of intrinsic strain mentioned in the literature are:

1.  dopants
2.  "atomic peening" which causes compressive stress
3.  microvoids which cause tensile stress
4.  gas entrapment which causes compressive stress
5.  shrinkage during process which causes tensile stress
6.  grain boundaries

For this system, the Si3N4 and ZnO films are deposited through PECVD.

Among the 6 contributors above;

1.  No dopants are introduced in the process of PECVD method, so this effect is very small.
2.  The "atomic peening" mechanism refers to the reflected neutral atoms bombarding the growing film at low sputtering pressures. The paper does not use sputtering method, so this effect is also small.
3.  Microvoids are caused by poor quality of film during process, which depends on the material, the environment, and the growth rate during PECVD.
4.  Since plasma (Ar, for example) is used in PECVD, it is very possible that gas will be entrapped in the film. Therefore this contribution is relatively significant.
5.  Shrinkage often happens in ceramics during sintering. There is no sintering in the process, so this contributor is small.
6.  For Si3N4, it is an amorphous film, so there are no grain boundaries. For ZnO, this effect is possible.

Integrating and rank-ordering all the effects, I get the conclusion below:

4 > 3 > 6 > 5 > 1 > 2

_(d) Determine the % of residual stress in terms of the tensile and compressive failure strength of these two film materials. In other words, how closely does the residual stress in films or lines approach the failure stress of the bulk forms of these same materials?_

Use the material properties give in Table I,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_9.jpg)

Given that residual strain is 10\-12

Substituting S matrix and residual strain into the residual stress tensor equation given above, we have residual stress,

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/thinfilms_3_10.jpg)

Provided yield stress of silicon nitride and zinc oxide is 900 and 412 MPa respectively.

Therefore, the residual stress is very small compared to the yield stress of silicon nitride or zinc oxide.

{{< anchor "ref" >}}{{< /anchor >}}Reference
--------------------------------------------

\[1\] Ghasemi-Nejhad, Mehrdad N., Chiling Pan, and Hongwei Feng. "Intrinsic Strain Modeling and Residual Stress Analysis for Thin-Film Processing of Layered Structures." _Journal of Electronic Packaging_ 125 (March 2003): 4-17.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home) | [Problem Set 2]({{< baseurl >}}/pages/projects/thinfilms_2) | Problem Set 3 | [Problem Set 5]({{< baseurl >}}/pages/projects/thinfilms_5)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)