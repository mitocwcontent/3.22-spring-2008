---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Mechanical Behavior of a Virus - Problem Set 2
uid: 17fb7a5b-c938-5875-d1ff-a27e6dd55da8
---

_(b) Zandi, et al. \[[1](#References)\] note that virus capsid behavior can be considered as a competition between bending and strain energies at the continuum level. State the magnitude of these two mechanical energy components on a flat plate of thickness equal to the viral capsid wall, of width and length equal to the CCMV capsid facet, and under a state of hydrostatic stress (pressure) plus a superposed normal point load at the center of the capsid facet._

*   The **strain** and **bending** energy are directly proportional to the elastic modulus and the bending rigidity respectively.  
      
     
*   Thus by calculating the moduli we can determine the **relative contributions to stress from strain and bending energies**.

Assumptions: (from cited paper)

> \- Filled CCMV capsid with internal pressure of approximately 1 atm
> 
> \- Capsid modeled as a thin shelled sphere with an applied point load stress
> 
> \- CCMV: radius ~ 12 nm
> 
> \- Föppl-von Kármán number (γ) describes the elastic properties of thin shelled spheres. γ ≡ R²(Ke/Kb), where R is the equatorial radius of the virus, Ke is the elastic modulus, and Kb is the bending rigidity. (It has been shown that γ ~ 300 for CCMV)
> 
> \- Internal pressure of a filled CCMV is approximated by the following: π = 0.01 \* Ke/R ~ 1 atm

Calculations:

> \- Ke = (1 atm\*12 nm) / (0.01) = **.122 N/m²**
> 
> \- Kb = (R²\*Ke) / γ = **5.84E-20 Nm²**
> 
> \- Ke/Kb proportional to γ by γ ≡ R²(Ke/Kb)
> 
> \- γ = 300, thus strain energy contributes 300 times more to the stress than the bending energy

As shown in Fig. 1 of \[[2](#References)\], the elastic response of the capsid to the deformation strongly depends on the ratio of bending and elastic energy characterized by the FvK number.

_(c) The authors \[[1](#References)\] rely on a thermodynamic definition of stresses and a Lennard-Jones inter-capsomer potential to predict the dependence of stress on capsid size. State their definition of the LJ potential in terms of the symbols we used in class, and explain why the radial and tangential stresses they compute from this potential (under the defined stress state) monotonically decrease with increasing capsid radius._

ε0 = 4\*ALJ

σij = B1

(2)(1/6)\*σij = B2

The convention used in the paper \[[1](#References)\] is for compressive stress to be positive and tensile stress to be negative. Thus, as the capsid radius, R, increases (and likewise, the center-to-center separation between two capsomers in the capsid shell), the capsomers experience less and less compressive stress until the virus reaches an optimal radius, past which the capsomers begin to experience tensile stress. The stress monotonically decreases with increasing R. As you decrease the center-to-center capsomer separation (and virus radius) below the equilibrium value, a compressive stress is required to keep them from going back to their equilibrium. Likewise, if you increase the center-to-center capsomer separation beyond the equilibrium value, a tensile stress is required to hold them there. This is supported by the LJ potential, which describes that a repulsive force dominates at small separations (below some equilibrium separation) and an attractive force dominates beyond the equilibrium separation. Therefore at center-to-center capsomer distances below the equilibrium value, the aforementioned compressive stress is required to balance this repulsive force between capsomers while at separations beyond the equilibrium value, an attractive force is required to balance the tensile stress. Because the repulsive and attractive contributions to the LJ potential have different dependencies on R, the energy minimum is asymmetric. At low R below the equilibrium value, the repulsive potential rises faster than the attractive potential does at high R. Thus, the compressive stress at low center-to-center capsomer separations decreases with R faster than the tensile stress does at separations beyond the equilibrium value. This has implications on virus mechanical behavior as described below. (Please see attached graphs).

  
 

Images removed due to copyright restrictions. Please see \[[3](#References)\] and Fig. 5 and 6 in \[[2](#References)\].

  
 

_(d) Briefly summarize the implications of this trend in terms of virus behavior._

This trend indicates that because there exists an equilibrium separation between capsomer centers (as shown by the minimum in the LJ potential), there is an optimal value for virus capsid radius for a given number of capsomers. Additionally, the asymmetry in the LJ potential indicates that the tensile stress required to stretch a virus capsid by a given ΔR is much less than the compressive stress required to compress the capsid by the same ΔR. As a result, viruses more easily fail by bursting or rupture due to swelling than they do by compression.

{{< anchor "References" >}}{{< /anchor >}}References
----------------------------------------------------

\[1\] Zandi, R., and D. Reguera. "Mechanical Properties of Viral Capsids." _Physical Review_ 72 (2005): 021917.

\[2\] Buenemann, M., and P. Lenz. "Mechanical Limits of Viral Capsids." _PNAS_ 104 (2007): 9925-9930.

\[3\] [Wikimedia Commons](http://upload.wikimedia.org/wikipedia/commons/9/93/Argon_dimer_potential_and_Lennard-Jones.png).

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom)  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home) | Problem Set 2 | [Problem Set 3]({{< baseurl >}}/pages/projects/virus_3) | [Problem Set 5]({{< baseurl >}}/pages/projects/virus_5)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)