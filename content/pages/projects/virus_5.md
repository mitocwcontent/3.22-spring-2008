---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Mechanical Behavior of a Virus - Problem Set 5
uid: d5ac3e4c-e98f-a66d-535e-a241535e0491
---

_(b) One of the cool things about a virus is that after the prohead shoots in the genetic material into the host cell (say, a bacterium), the genetic material is replicated until there is so much pressure that the host cell fractures. Assuming this is an E. coli bacterium with an initial crack size equal to the width of the prohead, find the Griffith fracture strength of the E. coli. You'll have to assume some properties to do this, so cite and justify these._

Assumptions (from literature):

*   crack size, a = 70 nm \[[1](#References)\]  
      
     
*   Elastic modulus, E = 0.4 GPa \[[2](#References), [3](#References)\]  
      
     
*   Surface energy, γ = 52 mN/m \[[4](#References), [5](#References)\]  
      
     

Computation:

σ = (2Eγ/πa)(1/2) = 13.8 MPa

_(c) Ivanovska, et al. \[[1](#References)\] says the virus capsids are tough, but we said in class that this is the strain energy density up to the point of fracture. Assuming the fracture strength of a virus is 3 times the computed yield strength from PS3, and that the virus deforms in a linear elastic-linear strain hardening plastic mode up to the point of fracture, compute the toughness UT. Discussion on p. 7604 of their paper is also helpful._

From PS3 we calculated the yield stress to be 2.2 MPA and thus we can assume the fracture stress to be 3 times this value or 6.6 MPA.

From the following figures, taken from Ivanovska, et al., we see that the prohead dimension along the axis of stress/strain is 38 nm (Fig. 1). From Fig. 3, we see that the total strain distance the AFM tip moved from contact to fracture to be 62 nm - 29 nm = 33 nm. Thus the strain experienced by the prohead at fracture (rupture) is 33 nm/38 nm = .85.

Applying these values and the assumption of linear elastic and linear strain hardening we get a stress/strain curve as shown below.

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/virus_5_1.jpg)  
Courtesy of National Academy of Sciences, USA. Used with permission.  
Source: Ivanovska, I. L., P. J. Pablo, B. Ibarra, G. Sgalari, F. C. MacKintosh, J. L. Carrascosa, C. F. Schmidt, and G. J. L. Wuite. "Bacteriophage capsids: Tough nanoshells with complex elastic properties." PNAS 101 (2004): 7600-7605. Copyright 2004 National Academy of Sciences, USA.

  
 

The toughness can be computed from the figure below by finding the area under the stress/strain curve.

1/2\*.29\*2.2 MPa + (.85 - .29)2.2 MPa + 1/2(.85 - .29)(6.6 MPa - 2.2 MPa) = **2.783 MPa**

  
 

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/virus_5_2.jpg)

  
 

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Ivanovska, I. L., P. J. Pablo, B. Ibarra, G. Sgalari, F. C. MacKintosh, J. L. Carrascosa, C. F. Schmidt, and G. J. L. Wuite. "Bacteriophage Capsids: Tough Nanoshells with Complex Elastic Properties." _PNAS_ 101 (2004): 7600-7605.

\[2\] Ramos, Daniel, et al. "Measurement of the Mass and Rigidity of Adsorbates on a Microcantilever Sensor." _Sensors_ 7 (2007): 1834-1845.

\[3\] Yao, X., et al. "Thickness and Elasticity of Gram-Negative Murein Sacculi Measured by Atomic Force Microscopy." _Journal of Bacteriology_ 181 (November 1999): 6865-6875.

\[4\] Lopez-Montero, Ivan, et al. "High Fluidity and Soft Elasticity of the Inner Membrane of Escherischia coli Revealed by the Surface Rheology of Model Langmuir Monolayers." _Langmuir_ 24 (2008): 4065-4076.

\[5\] van Oss, C. J., A. Docoslis, and R. F. Giese. "Role of the Water-air Interface in Determining the Surface Tension of Aqueous Solutions of Sugars, Polysaccharides, Proteins, and Surfactants." _Contact Angle, Wettability, and Adhesion_ 2 (2002): 3-12.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home) | [Problem Set 2]({{< baseurl >}}/pages/projects/virus_2) | [Problem Set 3]({{< baseurl >}}/pages/projects/virus_3) | Problem Set 5  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)