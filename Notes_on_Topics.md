## General appraoch:

- Theoretical claims
- Simulation
- Hardware implementation and controlled experiments

## What are the faults?

- Rotor asymmetries
- Stator phase unbalance
- Rotor phase unbalance
- Stator turn-to-turn short circuit faults
- Stator open-circuit faults
- Rotor mass imbalance
- Rotor misalignment
- Bearing failure

## Condition monitoring techniques

- **Motor Current Signature Analysis (MCSA)**
	- Faults create specific harmonics
	- Extracting data from current harmonics (which faults can be detected?)
	- Can be implemented on an existing motor drive!
	- Code optimization is needed.
	
- **Harmonic Current Injection**
	- Creates torque and speed ripples and magnetic flux etc. can be estimated from speed feedback.
	- Permanent magnet temperature can be estimated using high frequency resistance of the machine.
	
- **Vibration**
	- Accelerometers, velocity and displacement sensors can be used.
- **Acoustic Emission**
	- Requires large number of sensors and high sampling rates.
- **Strain**
- **Torque**
	- Torque signal can be obtained from electrical variables therefore may not need extra torque transducers.
- **Temperature**
- **Oil Parameters**
- **SCADA Signals**
	
## Control and signal processing techniques

- **Modal pedictive control (MPC)**
	- Which estimation techniques does it utilize?
	
- **Kalman Filter Based Estimation**
	- Requires less computation and accurate on linear Gaussian systems.
	
- **Particle Filter Based Estimation**
	- Computationally heavy but more accurate on non-linear or non-Gaussian systems.
	
- **Other signal processing methods**
	- Hilbert Transform
	- FFT
	- STFT
	- Look journals for more details. (4 July 2017)
	
- **Neural Network, AI**
