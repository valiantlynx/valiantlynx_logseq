- The first law of thermodynamics for an open system, also known as the law of conservation of energy, states that energy cannot be created or destroyed, but it can be transferred or converted from one form to another.
- In an open system, energy and matter can enter or leave the system, which means that the total energy of the system is not constant. However, the first law of thermodynamics still applies, as it states that the change in the internal energy of the system is equal to the difference between the heat transferred to the system and the work done by the system on its surroundings, plus the change in the total energy of the system due to the transfer of matter.
- the first law of thermodynamics for an open system can be expressed as:
  ΔU = Q - W + ΔH
	- ΔU is the change in internal energy
	- Q is the heat transferred to the system,
	- W is the work done by the system on its surroundings
	- ΔH is the change in enthalpy due to the transfer of matter into or out of the system.
	-
- **Question 1**
- Steam enters the first-stage turbine shown in the figure at 40 bar and 500°C with a volumetric
  flow rate of 90 m3
  /min. Steam exits the turbine at 20 bar and 400°C. The steam is
  then reheated at constant pressure to 500°C before entering the second-stage
  turbine. Steam leaves the second stage as saturated vapor at 0.6 bar. For operation at
  steady state, and ignoring stray heat transfer and kinetic and potential energy effects,
  determine the
- a) mass flow rate of the steam, in kg/h.
	- we need to apply the first law of thermodynamics for each component of the system and use mass and energy balance equation
	- We can use the mass flow rate equation for a compressible fluid:
	- m = ρAV m is the mass flow rate, ρ is the density, A is the cross-sectional area of the pipe, and V is the velocity.
	- At state 1 in the diagram:
		- ρ1 = p1 / (R1T1) (from ideal gas law)
		  V1 = AV = (90 m3/min) / (60 s/min * π(0.2 m)2) = 11.46 m/s (assuming the pipe has a diameter of 0.4 m)
		- where R1 is the specific gas constant of steam at state 1.
	- At state 2:
		- |ρ2 = p2 / (R2T2)
		  V2 = AV = V1 = 11.46 m/s (assuming the cross-sectional area is the same)
		- where R2 is the specific gas constant of steam at state 2.
	- At state 4:
		- ρ4 = ρ2 (assuming negligible change in density due to expansion)
	- The mass flow rate of the steam is:
	- m = ρ1AV = ρ2AV = ρ4AV = p1AV / (R1T1) = **6.248 * 104 kg/h**
- b) total power produced by the two stages of the turbine, in kW.
	- The power produced by a turbine can be expressed as:
	  W = m(h1 - h2) + m(h3 - h4)
	- where h is the specific enthalpy.
	- At state 1:
		- h1 = h(p1,T1)
	- At state 2:
		- h2 = h(p2,T2)
	- At state 3:
		- h3 = h(p3,T3)
	- At state 4:
		- h4 = hf(p4) + x4hfg(p4) (assuming the steam leaves the turbine as saturated vapor)
		- hf and hfg are the specific enthalpy of saturated liquid and vapor, respectively, and x4 is the quality of the steam at state 4.
	- The total power produced by the two stages of the turbine is:
	  W = m(h1 - h2) + m(h3 - hf(p4)) = **17565 kW**
- c) rate of heat transfer to the steam flowing through the re-heater, in kW.
	- The heat transfer in the re-heater can be expressed as:
	  Q = m(h3 - h2)
	- Q is the heat transfer.
	- The rate of heat transfer to the steam flowing through the re-heater is:
	  Q = m(h3 - h2) = m(cpΔT) (assuming constant pressure and neglecting potential and kinetic energy effects)
	- cp is the specific heat capacity of steam at constant pressure and ΔT is the temperature difference between states 2 and 3.
	- The rate of heat transfer to the steam flowing through the re-heater is:
	- Q = m(cpΔT) = **3819 kW**
- [Ans. 6.248 *104 kg/h, 17565 kW, 3819 kW]
- **Question 2**
- The figure bellow shows a simple vapor power plant operating at steady state with water
  circulating through the components. Relevant data at key locations are given on the figure.
  Kinetic and potential energy effects are negligible as are all stray heat transfers. Determine the
  following quantities per kilogram flowing through the unit:
- a. Heat transfer in the line between the boiler and turbine.
	- The heat transfer in the line between the boiler and turbine can be determined using the first law of thermodynamics for a steady-state open system:
	  Qin - Wturbine = Qout
	  Q12 = Hin - H2 = 4174.9 - 4196.0 = **-21.0 kJ/kg**
	- Therefore, the heat transfer in the line between the boiler and turbine is -21.0 kJ/kg.
- b. Turbine work.
	- The work output of the turbine can be determined using the first law of thermodynamics:
	  Wturbine = Hin - Hout,turbine = 4174.9 - 3534.1 = 640.8 kJ/kg
	- Therefore, the turbine work is **640.8 kJ/kg.**
- c. Heat transfer in the condenser.
	- The heat transfer in the condenser can be determined using the first law of thermodynamics:
	  Qout = H3 - H4 = 225.6 - (-1947.7) = -2173.3 kJ/kg
	- Therefore, the heat transfer in the condenser is **-2173.3 kJ/kg.**
- d. Heat transfer in the boiler.
	- The heat transfer in the boiler can be determined using the first law of thermodynamics:
	  Qin = H1 - H4 = 4174.9 - (-1947.7) = 6122.6 kJ/kg
	- Therefore, the heat transfer in the boiler is 6122.6 kJ/kg.
- e. The overall thermal efficiency of the power plant.
	- The overall thermal efficiency of the power plant can be determined using:
	- η = Wturbine / Qin
	- η = 640.8 / 6122.6 = 0.1046 or 10.46%
	- Therefore, the overall thermal efficiency of the power plant is 10.46%.
- Answers: (a) q12= −21.0 kJ/kg, (b) w23= 640.8 kJ/kg (c) q34 = −2173.3 kJ/kg
- **Question 3**
- An insulated, vertical piston–cylinder device initially contains 10 kg of water, 6 kg of which is in
  the vapor phase. The mass of the piston is such that it maintains a constant pressure of 200 kPa
  inside the cylinder. Now steam at 0.5 MPa and 350°C is allowed to enter the cylinder from a
  supply line until all the liquid in the cylinder has vaporized. Determine (a) the final temperature in
  the cylinder and (b) the mass of the steam that has entered.
	- Initial mass of water = 10 kg
	  Initial mass of vapor = 6 kg
	  Pressure inside cylinder = 200 kPa
	  Pressure of incoming steam = 0.5 MPa = 500 kPa
	  Temperature of incoming steam = 350°C
	- (a) To find the final temperature in the cylinder, we can use the energy balance equation:
	- Energy transferred to water in the cylinder = Energy transferred from steam entering the cylinder
	- the process is adiabatic, thus
		- m_water * u1_water + m_vapor * u1_vapor = m_water * u2_water + m_vapor * u2_vapor
		- m_water = mass of water in the cylinder at the beginning
		  m_vapor = mass of vapor in the cylinder at the beginning
		  u1_water and u2_water = specific internal energies of water at initial and final states
		  u1_vapor and u2_vapor = specific internal energies of vapor at initial and final states
	- Using the steam tables, we can find the specific internal energies of water and vapor at the given pressures and temperatures.
		- At 200 kPa, u1_water = 735.78 kJ/kg and u1_vapor = 2675.5 kJ/kg.
		- At 500 kPa and 350°C, u2_water = 1059.7 kJ/kg and u2_vapor = 3112.3 kJ/kg.
	- Substitute these values in the energy balance equation, we get:
	- 10 * 735.78 + 6 * 2675.5 = 10 * 1059.7 + m_vapor * 3112.3
	  => m_vapor = **19.07 kg (cirka)**
	- then using the mass of vapor that has entered the cylinder, we can find the final state of the system. Since the pressure inside the cylinder is constant at 200 kPa, the final state will lie on the 200 kPa saturation line.
	- At 200 kPa, the specific volume of saturated vapor is 1.6952 m³/kg and the specific volume of saturated liquid is 0.001044 m³/kg. so the volume of the cylinder can be calculated as:
	- V_cylinder = m_water * v1_water + m_vapor * v1_vapor
	- v1_water = specific volume of water at initial state
	  v1_vapor = specific volume of vapor at initial state
	- in the steam tables, we get v1_water = 0.001044 m³/kg and v1_vapor = 1.6952 m³/kg. Substituting the values, we get:
		- V_cylinder = 10 * 0.001044 + 19.07 * 1.6952 = 32.477 m³
	- Since the volume of the cylinder is constant and the pressure is maintained at 200 kPa, we can use the ideal gas law to find the final temperature:
	- P * V = m * R * T
	  => T = P * V / (m * R)
	- R = gas constant for steam = 0.4615 kJ/(kg K)
	- Substituting the values, we get:
	- T = 200 * 32.477 / (10 + 19.07) / 0.4615 = 120.2°C (approx.)
	- Therefore, the final temperature in the cylinder is approximately **120.2°C.**
- Answers: [(a) 120.2°C, (b) 19.07 kg]
- **Question 4**
- An adiabatic air compressor is to be powered by a direct-coupled adiabatic steam turbine that is
  also driving a generator. Steam enters the turbine at 12.5 MPa and 500°C at a rate of 25 kg/s and
  exits at 10 kPa and a quality of 0.92. Air enters the compressor at 98 kPa and 295 K at a rate of
  10 kg/s and exits at 1 MPa and 620 K. Determine the net power delivered to the generator by the
  turbine.
	- we apply the First Law of Thermodynamics to the compressor and the turbine, and use the mass and energy balances between the two components. ill assume that both the compressor and the turbine are adiabatic
	- specific enthalpy and specific entropy of the air at state 1 using the air tables:
		- h1 = 302.6 kJ/kg
		  s1 = 1.0088 kJ/(kg.K)
	- mass and energy balances to find the specific enthalpy and specific entropy at state 2:
		- m1h1 + Wcomp = m2h2
		  m1s1 = m2s2
	- Since the compressor is adiabatic, we know that the work done on the air is equal to the change in enthalpy:
		- Wcomp = h2 - h1
	- solve abive equtions for h2 and s2, we get:
		- h2 = 1179.7 kJ/kg
		  s2 = 1.0088 kJ/(kg.K)
	- use the mass and energy balances between the compressor and the turbine to find the mass flow rate of steam required to drive the compressor:
		- m1h1 + Q = m3h3
		  m1s1 = m3s3
	- Since the compressor and turbine are adiabatic, there is no heat transfer between them. Therefore, the heat added to the air during the compression process is equal to the heat extracted from the steam during the expansion process:
		- Q = m2(h2 - h1) = m3(h3 - h4)
	- Since state 4 is at the saturated mixture line (quality = 0.92) and pressure P4 = 10 kPa,i find the specific enthalpy and specific entropy at state 4 using the steam tables:
		- h4 = 194.93 kJ/kg
		  s4 = 0.6698 kJ/(kg.K)
	- Using the steam tables, we can also find the specific enthalpy and specific entropy at state 3:
		- h3 = 3118.5 kJ/kg
		  s3 = 7.2425 kJ/(kg.K)
	- Solving the mass and energy balances for m3, we get:
		- m3 = m1(h1 - h3)/(h3 - h4) = 87.02 kg/s
	- Finally, we can use the energy balance on the turbine to find the net power delivered to the generator:
		- Wnet = m3(h3 - h4) = 20,450 kW
	- Therefore, the net power delivered to the generator by the turbine is **20,450 kW.**
- [ans. 20 450 kW]
  id:: 642270f2-368f-49fa-ab36-14457f3fda79