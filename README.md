 Ring Class
Properties:

outerRadius: A double value representing the outer radius of the ring (default value: 2.0).
innerRadius: A double value representing the inner radius of the ring (default value: 1.0).
Methods:

Constructors:
Default constructor: Initializes outerRadius to 2.0 and innerRadius to 1.0.
Parameterized constructor: Initializes outerRadius and innerRadius with provided values, ensuring that outerRadius is greater than innerRadius.
Getter Methods:
getOuterRadius(): Returns the outer radius.
getInnerRadius(): Returns the inner radius.
Setter Methods:
setOuterRadius(): Allows updating the outer radius, ensuring it's greater than the inner radius.
setInnerRadius(): Allows updating the inner radius, ensuring it's less than the outer radius.
Area Calculation: Computes the area of the ring using the formula:
Area
=
𝜋
×
(
outerRadius
2
−
innerRadius
2
)
Area=π×(outerRadius 
2
 −innerRadius 
2
 )
toString() Method: Provides a string representation of the Ring object.
2. QuadraticEquation Class
Properties:

a, b, and c: The coefficients of the quadratic equation 
𝑎
𝑥
2
+
𝑏
𝑥
+
𝑐
=
0
ax 
2
 +bx+c=0.
Methods:

Constructor: Initializes the coefficients a, b, and c.
Getter Methods:
getA(), getB(), getC(): Return the values of a, b, and c.
Discriminant: Calculates the discriminant 
Δ
=
𝑏
2
−
4
𝑎
𝑐
Δ=b 
2
 −4ac.
Roots Calculation:
getRoot1() and getRoot2(): Return the two roots if the discriminant is non-negative. If negative, they return 0.
3. Test Class
Test 1:
Creates an array of 6 Ring objects, then removes 2 of them randomly.
Calculates and displays the average area of the remaining rings.
Identifies and displays the largest and smallest rings based on their areas.
Test 2:
Prompts the user to input values for a, b, and c to create a QuadraticEquation object.
Based on the discriminant, displays either the two roots, one root, or a message stating that there are no real roots.
