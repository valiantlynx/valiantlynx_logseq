

- A stress element has σx = 80 MPa and τxy = 50 MPa cw, as shown in figure below.
- ![Picture1-1.png](../assets/Picture1-1_1675452155745_0.png)
	-
	-
- {:height 357, :width 600}
- (a) Using Mohr's circle,
	- find the principal stresses and directions, and show these on a stress element correctly aligned with respect to the xy coordinates.
	- principal stresses
		- σ1 = (σx + σy)/2 + sqrt(((σx - σy)/2)^2 + τxy^2)
		  σ2 = (σx + σy)/2 - sqrt(((σx - σy)/2)^2 + τxy^2)
		- where σy is the minimum principal stress.
		- σy = σx - 2τxy = 80 MPa - 2(50 MPa) = -20 MPa
		- σ1 = (σx + σy)/2 + R = 30 MPa + 45 MPa = 75 MPa
		- σ2 = (σx + σy)/2 - R = 30 MPa - 45 MPa = -15 MPa
	- direction
		- θ = 1/2 tan^-1(2τxy/(σx - σy))
		- tan 2θ = 2τ/(σx - σy) = 2(50)/(80 - (-20)) = 2
		- θ = tan^-1(2) = 63.43°
			- The direction of the maximum shear stress is found at 63.43° from the x-axis. The direction of the principal stresses are found at 45° from the x-axis.
	- Draw another stress element to show τ1 and τ2, find the corresponding normal stresses, and label the drawing completely.
	- ![image.png](../assets/image_1675458081924_0.png)
	-
	-
	-
- (b) Repeat part (a) using the transformation equations only.
	- the minimum principal stress is calculated the same as above.
	- σ1 = (σx + σy)/2 + √((σx - σy)^2 + 4τ^2)/2 = (80 + (-20))/2 + √((80 - (-20))^2 + 4(50)^2)/2 = 30 MPa + 45 MPa = 75 MPa
	- σ2 = (σx + σy)/2 - √((σx - σy)^2 + 4τ^2)/2 = (80 + (-20))/2 - √((80 - (-20))^2 + 4(50)^2)/2 = 30 MPa - 45 MPa = -15 MPa
	- direction
		- θ = 1/2 tan^-1(2τxy/(σx - σy))
		- tan 2θ = 2τ/(σx - σy) = 2(50)/(80 - (-20)) = 2
		-
		- θ = tan^-1(2) = 63.43°