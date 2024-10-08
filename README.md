# mechanical-2










Report
 
Table of Contents
Question 1	4
Question 1. A	4
Question 1. B	9
Part A	9
Part B	10
Part C	12
Question 1. C	14
Question 1. D	14
Question 2	16
Question 3	16
References	19




 
List of Figures
Figure 1.1: Geometry of the first Part as Part A	4
Figure 1.2: Geometry of the second Part as Part B	4
Figure 1.3: Geometry of the second Part as Part C	5
Figure 1.4: Generated Mesh for the Part A	6
Figure 1.6: Generated Mesh for the Part C	7
Figure 1.7: Designed Material for the Plate	8
Figure 1.8: Applied Boundary Conditions for the Analysis	8
Figure 1.9: Total Deformation at Hole for Part A	9
Figure 1.10: Developed stress at Hole for Part A	10
Figure 1.11: Total Deformation at Hole for Part B	10
Figure 1.12: Developed stress at Hole for Part B	11
Figure 1.13: Total Deformation at Hole for Part C	12
Figure 1.14: Developed stress at Hole for Part C	13
Figure 1.15: Maximum Deformation bar plot	14
Figure 1.16: Maximum stress bar plot	15
Figure 3.1: Mode shape result from natural frequency 1	16
Figure 3.2: Mode shape result from natural frequency 2	17
Figure 3.3: Modal analysis	17
 
Question 1
Question 1. A
 
Figure 1.1: Geometry of the first Part as Part A
(Source: Ansys)
This figure shows the geometry of Part A including a rectangular plate that has a length of 2m; and a height of 1.5m while having a thickness of 0.2m. There is a central circular aperture with a diameter of 0.5 meters in diameter. On its own, this circular cutout plays a major role in defining the stress distribution and deformation under different applied boundary conditions as useful for evaluating structural behaviour (Konieczny et al. 2021).
 
Figure 1.2: Geometry of the second Part as Part B
(Source: Ansys)
Figure 1.2 shows the geometry of Part B: the structure consists of a rectangular plate, 2 meters long, 1.5 meters high, and a thickness of 0.2 meters. In the middle of the plate, there is a rectangular pit with measures of 1.5 meters and a height of one meter. Any such larger rectangular cutout changes the stress distribution and deformation shapes, especially close to the sharp corners, so useful for structural response analysis under the applied loads. 
 
Figure 1.3: Geometry of the second Part as Part C
(Source: Ansys)
Figure 1.3 shows the geometry of Part C which is a rectangular plate of dimension 2m in length, 1.5 m in height and 0.2 m in thickness. The middle larger circular aperture with a diameter of 1.5 meters is positioned at the centre of the plate while a smaller aperture is rectangular and measures 1.5 metres wide by 0.5 metres high. 
 
Figure 1.4: Generated Mesh for the Part A
(Source: Ansys)
The picture below shows the finite element mesh obtained for Part A. The meshing appropriately depicts the circular hole around which stress concentration analysis around the periphery is required. 
Object Name	Mesh
State	Solved
Element Order	Program Controlled
Element Size	0.1 m
Sizing
Bounding Box Diagonal	2.508 m
Average Surface Area	1.0462 m²
Minimum Edge Length	0.2 m
Inflation
Use Automatic Inflation	None
Inflation Option	Smooth Transition
Transition Ratio	0.272
Maximum Layers	5
Growth Rate	1.2
Inflation Algorithm	Pre
View Advanced Options	No
Statistics
Nodes	4707
Elements	849

 
Figure 1.5: Generated Mesh for the Part B
(Source: Ansys)
This figure also shows the generated mesh of Part B with a rectangular hole cut into it. The arrangements around the cut or the rectangular sharp corners are woven closely, and this makes it possible for stress analysis. 
 
Figure 1.6: Generated Mesh for the Part C
(Source: Ansys)
This again is the finite element mesh generated, for Part C with a rectangular hole of smaller dimensions of 1.5 m x 0.5 m. As in Part B, the mesh is denser around the corners and edges of the hole, but due to the smaller size of the cut, stress concentration behaviour varies. 
Statistics
Nodes	3548
Elements	584

 
Figure 1.7: Designed Material for the Plate 
(Source: Ansys)
In the Ansys simulation, this figure refers to the material properties given to the plate. The material has Young’s modulus of elasticity of 7×10^10 N/m and Poisson’s ratio of 0.3. 
 
Figure 1.8: Applied Boundary Conditions for the Analysis
(Source: Ansys)
The attractor figure below represents the boundary conditions that were used when simulating the plate. On the left boundaries of the plate, the displacements are restrained, and a uniformly distributed load of 27×10^7N/m2 is acting on the upper boundaries of the plate (Toor, 2020). 
Question 1. B
Part A
 
Figure 1.9: Total Deformation at Hole for Part A
(Source: Ansys)
The figure below demonstrates the total deformation values of Part A with a circular hole under the applied pressure of 27×10^7N/m2. The maximum value of deformation is found to be 9.23×10^−3m near the hole as shown earlier and the minimum value is 3.48×10^−3m. The deformed area depends heavily on the circular hole, exhibiting huge displacement that arises from stress.
 
Figure 1.10: Developed stress at Hole for Part A
(Source: Ansys)
This figure presents the stress in Part A where the values vary between 0 and 4.58×10^8Pa with stress concentrations near the circular hole. The minimum stress is 4,880,000,000 Pa. Hole creates stress concentration around the perimeter of the hole where stress is rectangular, around the boundary near the fixed boundary and the area where the pressure is applied.
Part B
 
Figure 1.11: Total Deformation at Hole for Part B
(Source: Ansys)
Total deformation is indicated in this figure for Part B with a rectangular hole. When the load is considered, the maximum deformation is 1.03×10^−2m and the minimum is 3.28×10^−3m. Deformation is greater during the second part relative to the first part because of the increase in the size of the rectangular aperture (Jule et al. 2021).
 
Figure 1.12: Developed stress at Hole for Part B
(Source: Ansys)
From this figure, the stress distribution is presented for Part B; the maximum mechanical stress is 5.14×10^8 Pa and the area is the sharp corner of the rectangular hole. The minimum stress achieved during the analysis in this simulation is 5.23×10^6 Pa. 
Part C
 
Figure 1.13: Total Deformation at Hole for Part C
(Source: Ansys)
Overall deformation for Part C is shown in this figure and it has a relatively small rectangular opening of 1.5m×0.5 m. The maximum deformation obtained is 7.82×10^ -3m and the minimum deformation is 4.29×10^-3 m on in Part B, which features a rectangular hole. Under the same loading conditions, the maximum deformation is 1.03×10^−2m, and the minimum is 3.28×10^−3m. 
Object Name	Mesh
State	Solved
Defaults
Physics Preference	Mechanical
Element Order	Program Controlled
Element Size	0.1 m
Sizing
Use Adaptive Sizing	Yes
Resolution	Default (2)
Mesh Defeaturing	Yes
Defeature Size	Default
Transition	Fast
Span Angle Center	Coarse
Initial Size Seed	Assembly
Bounding Box Diagonal	2.508 m
Average Surface Area	0.748 m²
Minimum Edge Length	0.2 m
Inflation
Use Automatic Inflation	None
Inflation Option	Smooth Transition
Transition Ratio	0.272
Maximum Layers	5
Growth Rate	1.2
Inflation Algorithm	Pre
View Advanced Options	No
Statistics
Nodes	3526
Elements	580

 
Figure 1.14: Developed stress at Hole for Part C
(Source: Ansys)
This figure shows the stress distribution for Part B, where the maximum stress is 5.14×10^8Pa, occurring near the sharp corners of the rectangular hole. The minimum stress recorded is 5.23×10^6Pa. 
Question 1. C
The bar chart compares the peak deformation sustained at three distinct parts (A, B, C) that both have different shaped and sized holes when subject to the same boundary loads. Where the x-axis is labelled as the parts (A, B and C) and the y-axis is marked in m, showing the maximum deformation. In Part A with a circular hole, a maximum deformation of 9.23m was observed. In Part B, the one with a large rectangle-shaped opening, the maximum deformation of 10.3 m is recorded. In Part C where the rectangular hole is small sizes 7.82m of deformity is recorded. The chart serves as a good example showing how hole size and shape influence deformation for the same loading (Al-Shammari et al. 2022).
 
Figure 1.15: Maximum Deformation bar plot
(Source: Excel)
Question 1. D
The bar chart above shows the maximum stress (in Pascal) for Part A, B and C with the same boundary conditions. Rather, the type of car model which is A, B or C is represented at the x-axis and the maximum stress value in Pascals is represented on the y-axis. The maximum stress is obtained to be 4.58x10^8 pa for Part A which has a circular shaped hole, Part B which has a larger rectangular shape has a maximum stress of 5.14x10^8 pa while the smallest rectangular shape of Part C has a minimum stress of 3.70x10^8 pa.
 
Figure 1.16: Maximum stress bar plot
(Source: Excel) 
Question 2
Using FEM here the first two natural frequencies of the bar, first discretize the bar into two elements First. The bar has an underline length of 2 meters and each of the elements is 1 meter long. From the above material properties, Young’s modulus is 200GPa, the density is 8000kg/m, and the cross-sectional area is 500mm2. For each element, the stiffness matrix is 100×10^6N/m and the mass matrix is 0.6667 kg. These matrices are assembled into global stiffness and mass matrices, with the first node constrained, to obtain corresponding 2×2 matrices.
The natural frequencies are determined from the generalized eigenvalue problem. 
(K−ω2M)ϕ=0. When the eigenvalue problem is solved, the first two natural frequencies are obtained. The obtained values are equal to f1=250Hz and f2=710 Hz. bar using the Finite Element Method (FEM), here, first discretize the bar into two elements (Pandey et al. 2020). 
Question 3
 
Figure 3.1: Mode shape result from natural frequency 1
(Source: Ansys)
 
Figure 3.2: Mode shape result from natural frequency 2
(Source: Ansys)
 
Figure 3.3: Modal analysis 
(Source: Ansys)
The results obtained from ANSYS software include the modal analysis results including natural frequencies of 40.358 Hz and 50.18 Hz for the first two modes of the system as depicted in the above images. These frequencies are the natural frequencies of the system under free vibration, deflection increasing from zero at the fixed end to a maximum at the free end as indicated by the gradient from blue to red.

These results are compared with the analytical solution which gave predicted frequency of 250 Hz and 710 Hz; a marked difference is observed. These differences could be contributed to a number of reasons, including possible assumptions in the analytical method where for instance lumped mass or stiffness has been used. However, the ANSYS probably made a somewhat more accurate calculation in comparison to an equivalent model taking into account the actual geometry distribution of mass and stiffness. The results of deformation mode shapes in ANSYS software are of typical cantilever beam nature, where largest deformation is at the free end and smallest deformation is at the fixed end.
 
References
Al-Shammari, M.A., Husain, M.A. and Al-Waily, M., 2022, January. Free vibration analysis of rectangular plates with cracked holes. In AIP Conference Proceedings (Vol. 2386, No. 1). AIP Publishing.
Jule, L.T., Ramaswamy, K., Nagaprasad, N., Shanmugam, V. and Vignesh, V., 2021. Design and analysis of serial drilled hole in composite material. Materials Today: Proceedings, 45, pp.5759-5763.
Konieczny, M., Gasiak, G. and Achtelik, H., 2020. The FEA and experimental stress analysis in circular perforated plates loaded with concentrated force. Frattura ed Integrità Strutturale, 14(51), pp.164-173.
Pandey, M., Patel, A., Jaiswal, K., Kirola, L. and Sharma, S.K., 2020. Investigation of variation in stress concentration factor with the change in orientation of central hole on a rectangular plate. In Recent Advances in Mechanical Engineering: Select Proceedings of ITME 2019 (pp. 629-635). Singapore: Springer Singapore.
Toor, Z.S., 2020. Finite element method for numerical stress analysis of aluminum plate. Journal of Space Technology, 10(1), pp.1-6.

