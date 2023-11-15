### Theory

The slope deflection method is a classical displacement-based structural analysis technique used to determine the displacements and member end forces in a beam/ frame subjected to external loads. Especially for which DSI > DKI where DSI is degree of static indeterminacy and DKI is degree of kinematic indeterminacy.

1. Assumptions: 
•	The beam is made of a linear – elastic material (Hooke’s law is valid).<br>
•	The beam undergoes small deformations, and its geometry remains unchanged. <br>
•	The cross-sections of the beam remain plane and perpendicular to the longitudinal axis. <br>
•	The loads applied the beam are static (do not vary with time). <br><br>
2. Structural Idealization: <br>
•	The beam is discretized into individual members (segments) between consecutive supports and points of loading. <br>
•	Each member is onsides as a simple beam with two degrees of freedom: rotation(Ɵ) and vertical displacement (δ). <br>
3. Determination of Fixed Moments (FEM):<br><br>
•	The first step is to calculate the fixed end moments for each member, which represent the moments that would develop at the ends of the member if it were fully fixed (rotationally and translationally) and subjected to the applied loads. <br>
•	For each member, the fixed end moments are computed using the known loads and the geometry of the beam, taking into account the support conditions at the ends, using well-known standard formulas. <br>

<br>
<div align="center"><img src="images/F1.png"></div>
<br>

Formation of Slope-Deflection Equations: <br>
•	The slope-deflection equations relates the rotation (Ɵ) and the relative vertical displacement (δ) with the bending moments at the ends.<br>
•	These equations are derived based on the relationship between bending moment, curvature, and the material properties of the beam (Elastic Modulus and Moment of Inertia). <br>
<br>
<div align="center"><img src="images/f2.png"></div>----------------eq<sub>(1) & (2)</sub>
<br>
Where: M<sup>F</sup><sub>AB</sub> and M<sup>F</sup><sub>BA</sub> = Fixed ended moments, Ɵ<sub>A</sub> and Ɵ<sub>B</sub> = Beam end rotations, δ<sub>AB</sub> = δ<sub>B</sub> - δ<sub>A</sub> = Relative vertical displacement between end A and B.<br>
•	Ɵ<sub>A</sub> and Ɵ<sub>B</sub> - anticlockwise (+ve).<br>
•	δ<sub>AB</sub> - Considered positive if member rotates anticlockwise as a whole.<br><br>
5. Application of Compatibility  Equation:
•	Moment equilibrium are applied to form equations, whose solution leads to obtaining the unknown displacements (M<sub>BA</sub> + M<sub>BC</sub> = M<sub>C</sub> = 0) . After displacement & rotation are obtained, the members and moments obtained using the slope deflection equations (1 & 2).
6. Verification of Results:
•	The computed bending moments and rotations should satisfy the equilibrium conditions for the entire structure. 
<br>