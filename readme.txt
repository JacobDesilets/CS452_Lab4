CS452 Lab 2 - Jacob DeRosa and Jacob Desilets

The object is an Easter Island head 🗿

We implemented Phong shading in the fragment shader. For our point light,
we used the method described in class. For the directional light, we
used a method similar to the point light, but the directional light is
not attenuated and the incidence value (i) is just the direction light direction
instead of subtracting the transformed vertex position.