---
content_type: page
parent_title: Projects
parent_uid: 8388cfe3-4b2f-b7e7-0060-faf27a65e652
title: Defect Nucleation in Crystalline Metals - Problem Set 5
uid: 70049e7d-dc51-6444-051a-d2a4d929ff2d
---

_(b) The papers you have chosen focus on the initial stages of plastic deformation, or incipient plasticity, in ductile metals. Consider Fig. 9 in paper 3 \[[1](#ref)\], illustrating a dislocation loop passing through a single crystal of Al under indentation pressure. Consider a bulk metal vs. a thin film of the same material on a rigid substrate, explain how you would expect the load required to keep plastically deforming the material t a depth of 1 micron would differ._

The load required to plastically deform the thin film of Aluminum and the bulk metal at a depth of 1 micron below the free surface would differ considerably. The stress required in the case of the aluminum film would be much greater as compared to the bulk metal. This is because plastic deformation is facilitated by dislocation movement and it would be obstructed more in the thin film than in the bulk metal. This is attributed to the fact that when a stress is applied the dislocation loop would tend to move but would not be able to move easily as it would be repelled by the hard substrate as it has a higher modulus than aluminum so a higher stress is needed to move the dislocation loop close to the substrate.

The energy of a dislocation goes as (Gb2)/2 so it would be more in the hard substrate and so also would be repelled by the hard substrate as the dislocation energy increases. We can also draw analogy to the fact that the dislocation would tend to be attracted to a free surface whose G = 0 because the dislocation energy becomes 0. Going on the same lines it would be repelled by a substrate whose G is greater than the G of the metal.

In the case of the bulk metal a dislocation finds itself in the vicinity of the bulk metal only at a depth of 1 micron so it would move with no additional resistance.

_(c) Compute the fracture stress of this Al according to the Griffith criterion, assuming an initial crack size at the resolution of the TEM used in Minor's indentation experiments \[[2](#ref)\]. Compare this to the published fracture strength of single crystal Al, and discuss._

Here we assume an initial crack the size of the resolution of the microscope used by Minor in this study \[[2](#ref)\]. From the NCEM website \[[3](#ref)\], we find the minimum point-to-point resolution of the JEOL 3010 to be 1.7 _Å_, which we set equal to a crack of width 2_a_. The surface energy of aluminum was found to be 0.057 eV _Å_2 \[[4](#ref)\]. The Young's Modulus for aluminum is 68 GPa \[[5](#ref)\]. We now have all the necessary parameters to calculate the required fracture stress for a crack of this size.

![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_1.jpg)

This is a very high fracture stress, being near the theoretical fracture stress given for aluminum in class (20 GPa). A molecular dynamics simulation of a single crystal of aluminum gives a yield stress of 2 GPa, corresponding to the initiation of a plastic event in the material \[[6](#ref)\]. No direct experimental data of fracture stress could be found, but it should be even lower than this due to the presence of preexisting defects such as cracks and pores. Prof. Van Vliet gave the fracture stress of aluminum to be 0.7 GPa in class.

The high fracture stress for a crack at the TEM resolution limit points tells us that this is not a very reasonable explanation for failure in this system. Either the theoretical shear stress will be reached and a dislocation will be initiated or preexisting macroscopic defects will propagate cracks within the material before a crack on the Angstrom level would propagate.

_(d) Delamination of films can also be treated as fracture, but this time at an interface between two dissimilar materials. Using Griffith again, compute the tensile stress required to delaminate an Al film from a Si substrate, if there is an initial blister at the film/substrate interface of width 1 micron. Then state whether you'd expect the film to first fracture due to opening of initial cracks within the film (of initial size stated in c), or to delaminate from the substrate when loaded in tension normal to the film/substrate interface._

Griffith's criterion: ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_2.jpg)

Griffith's criterion considers crack propagation in single material. To apply Griffith's equation to thin film/substrate system, we need to consider both Al film and Si substrate.

1.  Surface energy: In the thin film case, the change of surface energy (Γ) because of the crack is the sum of increased surface energy of Al (γAl) and Si (γSi) and the decrease of interface energy (γAl/Si) between thin film and substrate.
    
    |  {{< br >}}{{< br >}} ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_3.jpg) {{< br >}}{{< br >}}  | \= 8 N/m (from \[[5](#ref)\]) 
    
    This value corresponds to 2γ in the Griffith's equation.
    
2.  Young's modulus: In a delamination problem, Young's modulus (_E_) should also be modified by using effective Young's modulus (_Eeff_) since the release of elastic energy comes from both the thin film and substrate.
    
3.  The effective energy release rate is given in \[[7](#ref)\], ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_4.jpg)
    
    where D1 is given as ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_5.jpg) and ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_6.jpg) is the plane strain modulus for the film and substrate.
    
    ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_7.jpg) = 80 GPa. (_Ef_ is 70 GPa and _νf_ is 0.35)  
    ![defec_nuclea_5_8.jpg](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_8.jpg) = 141 GPa. (E\_s is 130 GPa and _ν_s is 0.28)  
    D1 value for our Al/Si system is therefore -0.28.  
      
    ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nuclea_5_9.jpg)
    
4.  Combining 1) and 2), we can get the tensile stress required to delaminate an Al film on Si substrate with 1 µm blister,
    
    ![](/courses/materials-science-and-engineering/3-22-mechanical-behavior-of-materials-spring-2008/projects/defec_nucle_5_10.jpg)
    
5.  From problem (c), we know that the fracture stress for 0.17 nm crack is 21.5 GPa. Since the fracture stress for fracture is much higher than that for delamination, we would expect the film to delaminate first.

{{< anchor "ref" >}}{{< /anchor >}}References
---------------------------------------------

\[1\] Van Vliet, Krystyn J., et al. "Quantifying the Early Stage of Plasticity Through Nanoscale Experiments and Simulations." _Physical Review_ B 67 (2003): 104105.

\[2\] Minor, Andrew M., et al. "A New View of the Onset of Plasticity During the Nanoindentation of Aluminum." _Nature Materials_ 5 (2006): 697-702.

\[3\] [National Center for Electron Microscopy](http://foundry.lbl.gov/facilities/ncem/).

\[4\] Needs, Richard J. "Calculations of the Surface Stress Tensor at Aluminum (111) and (110) Surfaces." _Physical Review Letters_ 58 (1987): 53-56.

\[5\] [MatWeb](http://www.matweb.com/).

\[6\] Yuan, Lin, et al. "Molecular Dynamics Simulation of Tensile Deformation of Nano-single Crystal Aluminum." _Journal of Materials Processing Technology_ 184 (2007): 1-5.

\[7\] Freund, L. B., and S. Suresh. "Delamination and Fracture." Chapter 4 in _Thin Film Materials_. New York, NY: Cambridge University Press, 2004. ISBN: 9780521822817.

  
  
 

[Plasticity and fracture of microelectronic thin films/lines]({{< baseurl >}}/pages/projects/thinfilms_home)  
[Effects of multidimensional defects on III-V semiconductor mechanics]({{< baseurl >}}/pages/projects/iii_v_home)  
[Defect nucleation in crystalline metals]({{< baseurl >}}/pages/projects/defec_nuclea_hom) | [Problem Set 2]({{< baseurl >}}/pages/projects/defect_nucleat_2) | [Problem Set 3]({{< baseurl >}}/pages/projects/defect_nucleat_3) | Problem Set 5  
[Role of water in accelerated fracture of fiber optic glass]({{< baseurl >}}/pages/projects/fiber_optics_hom)  
[Carbon nanotube mechanics]({{< baseurl >}}/pages/projects/cnt_mech_home)  
[Superelastic and superplastic alloys]({{< baseurl >}}/pages/projects/superelasti_home)  
[Mechanical behavior of a virus]({{< baseurl >}}/pages/projects/virus_home)  
[Effects of radiation on mechanical behavior of crystalline materials]({{< baseurl >}}/pages/projects/radiation_home)