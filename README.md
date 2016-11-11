# hello-world
Learning how to use GitHub

Hello there!
I'm completely new to the glorious world of GitHub, so I'm just following this handy tutorial I found.

the Magnitude of a vector, commonly denoted ||__x__||, is the pythagorean theorem in n dimensional space.

Dot product is __x__ &middot; __y__

Cross product is __x__ &times; __y__

#Vector Projection

Projection is a useful operation with many applications.

Given two vectors __x__ and __y__, the projection of __x__ onto __y__, commonly denoted proj<sub>__y__</sub>(__x__) or __x__<sub>||__y__</sub>, is a scalar multiple of __y__ based on the length of __x__ in the direction of __y__. It can be calculated as __x__<sub>||__y__</sub> = ((__x__ &middot; __y__) / (__y__ &middot; __y__)) __y__

The Rejection operation is also introduced. Commonly denoted __x__<sub>&perp;__y__</sub>, it is the vector orthogonal to __y__ in the same half-space as __x__ with magnitude equal to the component of __x__ in that direction. It is more easily calculated as __x__<sub>&perp;__y__</sub> = __x__ - __x__<sub>||__y__</sub>.

Given vectors __x__, __y__, and __z__, the scalar triple product is \[__x__, __y__, __z__\] = (__x__ &times; __y__) &middot; __z__.

Because of the antisymmetry of the cross product, it then follows that \[__x__, __y__, __z__\] = (__x__ &times; __y__) &middot; __z__ = -(__y__ &times; __x__) &middot; __z__ = -\[__y__, __x__, __z__\]. In particular, any even permutation of the input vectors is equal, while any odd permutation is negated.

The geometric interpretation of the scalar triple product is that it is the volume of the parallelepiped with edges __x__, __y__, and __z__.  This is because \[__x__, __y__, __z__\] = (__x__ &times; __y__) &middot; __z__ = ||__x__ &times; __y__||||__z__||cos(&theta;). From before, ||__x__ &times; __y__|| is the area of the parallelogram with edges __x__ and __y__. Now since &theta; is the angle betwee __z__ and __x__ &times; __y__, then ||__z__||cos(&theta;) is the height of the parallelepiped. Then ||__x__ &times; __y__||||__z__||cos(&theta;) is the base of the parallelepiped times the height, and hence is the volume.
