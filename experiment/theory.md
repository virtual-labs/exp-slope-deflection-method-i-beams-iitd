### Theory

The slope deflection method is a classical structural analysis technique used to calculate the displacements and moments in a beam subjected to external loads. It is a stiffness-based method that takes into account the flexibility of the beam members to determine the bending moments and rotations at various points along the beam's length. The method is particularly useful for analyzing statically indeterminate structures, where the number of unknown reactions exceeds the number of available equilibrium equations.

1. Assumptions:
   - The beam is made of a linear-elastic material (Hooke's law is valid).
   - The beam undergoes small deformations, and its geometry remains unchanged.
   - The cross-sections of the beam remain plane and perpendicular to the longitudinal axis.
   - The loads applied to the beam are static (do not vary with time).

2. Structural Idealization:
   - The beam is discretized into individual members (segments) between consecutive supports and points of loading.
   - Each member is considered as a simple beam with two degrees of freedom: rotation (θ) and lateral displacement (δ).

3. Determination of Fixed End Moments (FEM):
   - The first step is to calculate the fixed end moments for each member, which represent the moments that would develop at the ends of the member if it were fully fixed (rotationally and translationally) and subjected to the applied loads.
   - For each member, the fixed end moments are computed using the known loads and the geometry of the beam, taking into account the support conditions at the ends.

   FEM formulas for common support conditions:

Simply Supported Beam with Uniform Load (w) and Length (L):
M1 = M2 = wL²/8

Cantilever Beam with Uniform Load (w) and Length (L):
M1 = M2 = wL²/2

Fixed-Fixed Beam with Uniform Load (w) and Length (L):
M1 = M2 = wL²/12

Fixed-Fixed Beam with Point Load (P) at the Mid-Span:
M1 = M2 = PL/8

4. Formation of Slope-Deflection Equations:
   - The slope-deflection equation relates the rotation (θ) at one end of a member to the lateral displacement (δ) at the same end.
   - These equations are derived based on the relationship between bending moment, curvature, and the material properties of the beam (Elastic Modulus and Moment of Inertia).

   EI * d²θ/dx² = M

where:

M is the bending moment at the considered section of the member.
EI is the flexural rigidity of the member.
θ is the rotation at the considered section.
x is the position along the length of the member.

5. Application of Compatibility Equations:
   - Compatibility conditions are applied to ensure that the rotations and displacements at the common ends of adjacent members are the same.
   - These conditions are essential for ensuring continuity of the beam's deformation.

6. Solving the Simultaneous Equations:
   - The slope-deflection equations and compatibility conditions result in a system of simultaneous equations.
   - These equations are solved to obtain the values of rotations and displacements at each end of the members.

7. Calculation of Bending Moments:
   - Using the computed rotations and displacements, the bending moments at various points along the beam's length can be determined.

   M = EI * d²θ/dx²

where:

M is the bending moment at a specific point along the beam's length.
EI is the flexural rigidity of the beam (product of Young's modulus and moment of inertia).
θ is the rotation (angular displacement) at the point.
x is the position along the beam's length.

8. Verification of Results:
   - The computed bending moments and rotations should satisfy the equilibrium conditions and compatibility equations for the entire structure.

The process is repeated iteratively, refining the results until convergence is achieved. The method becomes more complex for structures with higher degrees of indeterminacy, but it remains an effective technique for analyzing continuous beams and frames.

