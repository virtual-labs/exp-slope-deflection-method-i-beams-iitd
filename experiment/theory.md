### Theory

The slope deflection method is a classical displacement-based structural analysis technique used to determine the displacements and member end forces in a beam/ frame subjected to external loads. Especially for which DSI > DKI. 
1. Assumptions: 
•	The beam is made of a linear – elastic material (Hooke’s law is valid).
•	The beam undergoes small deformations, and its geometry remains unchanged. 
•	The cross-sections of the beam remain plane and perpendicular to the longitudinal axis. 
•	The loads applied the beam are static (do not vary with time). 
2. Structural Idealization: 
•	The beam is discretized into individual members (segments) between consecutive supports and points of loading. 
•	Each member is onsides as a simple beam with two degrees of freedom: rotation(Ɵ) and vertical displacement (δ). 
3. Determination of Fixed Moments (FEM):
•	The first step is to calculate the fixed end moments for each member, which represent the moments that would develop at the ends of the member if it were fully fixed (rotationally and translationally) and subjected to the applied loads. 
•	For each member, the fixed end moments are computed using the known loads and the geometry of the beam, taking into account the support conditions at the ends, using well-known standard formulas. 
<br>
<br>
<div align="center"><img src="images/f1.png"></div>
<br>
<br>
Formation of Slope-Deflection Equations: 
•	The slope-deflection equations relates the rotation (Ɵ) and the relative vertical displacement (δ) with the bending moments at the ends.
•	These equations are derived based on the relationship between bending moment, curvature, and the material properties of the beam (Elastic Modulus and Moment of Inertia). 
<br>
<div align="center"><img src="images/f2.png"></div>
<br>
Where: M<sup>F</sup><sub>AB</sub> and M<sup>F</sup><sub>BA</sub> = Fixed ended moments, Ɵ<sub>A</sub> and Ɵ<sub>B</sub> = Beam end rotations, δ<sub>AB</sub> = δ<sub>B</sub> - δ<sub>A</sub> = Relative vertical displacement between end A and B
•	Ɵ<sub>A</sub> and Ɵ<sub>B</sub> - anticlockwise (+ve).
•	δ<sub>AB</sub> - Considered positive if member rotates anticlockwise as a whole.
5. Application of Compatibility  Equation:
•	Moment equilibrium are applied to form equations, whose solution leads to obtaining the unknown displacements (MBA + MBC = MC = 0) . After displacement & rotation are obtained, the member and moments obtained using the slope deflection equations (1 & 2).
6. Verification of Results:
•	The computed bending moments and rotations should satisfy the equilibrium conditions for the entire structure. 
