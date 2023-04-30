- The rotating solid steel shaft is simply supported by bearings at points $B$ and $C$ and is driven by a gear (not shown) which meshes with the spur gear at $D$, which has a $150$-mm pitch diameter. The force $F$ from the drive gear acts at a pressure angle of $20^\circ$. The shaft transmits a torque to point $A$ of $T_A = 340 \text{ N} \cdot \text{m}$. The shaft is machined from steel with $S_y = 420 \text{ MPa}$ and $S_{ut} = 560 \text{ MPa}$. Using a factor of safety of $2.5$, determine the minimum allowable diameter of the $250$-mm section of the shaft based on:
- a) a static yield analysis using the distortion energy theory and
- b) a fatigue failure analysis. Assume sharp fillet radii at the bearing shoulders for estimating stress concentration factors.
	- Given from q:
		- $d = 150 \text{ mm}$
		- $\beta = 20^\circ$
		- $T_A = 340 \text{ N} \cdot \text{m}$
		- $S_y = 420 \text{ MPa}; S_{ut} = 560 \text{ MPa}$
		- $m=2.5$
	- i) for torque first:
	  \begin{align*}
	  T &= \frac{F \cos \beta d}{2} \\
	  F &= \frac{2T}{d \cos \beta} \\
	  F &= \frac{2\cdot 340}{150\cdot 10^{-3} \cdot \cos 20^\circ} \\
	  F &= 4824.27 \text{ N}
	  \end{align*}
	- ii) Moment about $C$:
	  \begin{align*}
	  M_C &= F\cdot \frac{100}{1000} \\
	  M_C &= 482.427 \text{ N} \cdot \text{m}
	  \end{align*}
	- iii) For sharp fillet at the shoulders:
	  \begin{align*}
	  K_t &= 2.7 \\
	  K_{ts} &= 2.2
	  \end{align*}
	- iv) Notch sensitivity factor:
	  \begin{align*}
	  qs &= 0.9 \\
	  q &= 0.8
	  \end{align*}
	- v) Stress concentration factors:
	  \begin{align*}
	  K_f &= 1+ 0.8(2.7-1) \\
	  K_f &= 2.4 \\
	  K_{fs} &= 1 + 0.9(2.2-1) \\
	  K_{fs} &= 2.1
	  \end{align*}
	- a) By using static yield analysis:
	  \begin{align*}
	  d &= \left[\frac{16n}{\pi S_y}\left[4\left(K_f m\right)^2+3\left(K_{fs}T\right)^2\right]^\frac{1}{2}\right]^\frac{1}{3} \\
	  d &= \left[\frac{16\cdot 2.5}{\pi \cdot 420\cdot 10^6}\left[4\left(2.4\cdot 482.427\right)^2+3\cdot \left(2.1\cdot 340\right)^2\right]^\frac{1}{2}\right]^\frac{1}{3} \\
	  d &= 0.04301 \text{ m or } d = 43.01 \text{ mm}
	  \end{align*}
	- \begin{enumerate}
	- \item[(a)] Using the distortion energy theory for static yield analysis, the minimum allowable diameter of the 250-mm section of the shaft is given by:
	  \begin{align*}
	  d &= \left(\dfrac{16n}{\pi}\dfrac{3Ty}{2\pi d^3}\right)^{\frac{1}{4}} \\
	  &= \left(\dfrac{16(2.5)}{\pi}\dfrac{3(340)}{2\pi (0.25)^3}\right)^{\frac{1}{4}} \\
	  &= 0.04301\text{ m or }43.01\text{ mm}
	  \end{align*}
	-
	- \item[(b)] By fatigue-failure analysis, using the Goodman criterion
	- Surface factor:
	   \begin{align*}
	     K_a &= 4.51\times(S_{ut})^{-0.265} \\
	     &= 4.51\times(560)^{-0.265} \\
	     &= 0.84
	   \end{align*}
	- For $r=107$ mm:
	   \begin{align*}
	     q &= 0.72 \\
	     q_s &= 0.77
	   \end{align*}
	- $K_f$ and $K_{fs}$:
	   \begin{align*}
	     K_f &= 1+q(2.7-1) \\
	     &= 2.2 \\
	     K_{fs} &= 1+q_s(2.2-1) \\
	     &= 1.9
	   \end{align*}
	- Endurance limit:
	   \begin{align*}
	     S_e &= K_aK_fK_{fs}\dfrac{S_{ut}}{2} \\
	     &= 0.84\times0.81\times0.5\times560 \\
	     &= 191\text{ MPa}
	   \end{align*}
	- Diameter:
	   \begin{align*}
	     d &= \left(\dfrac{16n}{\pi}\left[4\left(\dfrac{k_fM_a}{S_e}\right)^2+3\left(\dfrac{k_{fs}T_m}{S_y}\right)^2\right]^{\frac{1}{2}}\right)^{\frac{1}{3}} \\
	     &= \left(\dfrac{16\times2.5}{\pi}\left[4\left(\dfrac{2.2\times482.4\times10^3}{191\times10^6}\right)^2+3\left(\dfrac{1.9\times340}{420\times10^6}\right)^2\right]^{\frac{1}{2}}\right)^{\frac{1}{3}} \\
	     &= 0.05259\text{ m or }52.6\text{ mm}
	   \end{align*}
	- Therefore, the minimum allowable diameter of the 250-mm section of the shaft based on (a) a static yield analysis using the distortion energy theory is 43.01 mm and (b) based on a fatigue failure analysis is 52.6 mm.
	-
-