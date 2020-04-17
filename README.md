# <div align="center">Applied-Linear-Controls-Project-Part-1</div>
**<div align="center">To develop and validate an empirical discrete-time state-space model of the dynamic system using [system identification](https://www.mathworks.com/help/ident/gs/about-system-identification.html) methods</div>**

> **Note**: For this project, we assume that nothing specific is known about the system dynamics; however, we do know that it has two outputs and one input, and we know that the system is open-loop stable.

### How to Access the Unknown Plant function in the script:
```Matlab
  y = s20_plant(u)
```

#### Task List:
- [x] Executing Code
- [x] Debugging (Compariason of [H1 Estimate](https://community.sw.siemens.com/s/article/what-is-a-frequency-response-function-frf) and Minimum Realization FRF)
- [x] Finding the appropriate reduced order LTI object whose FRF is in coherence with the above 2

#### Objectives Achieved: 

- Constructed an excitation signal for System Identification following the satuaration limit for DAC (Digital-to-Analog Converter)
- Estimated the SNR (Signal to Noise Ratio) for each path of signal `u1 -> y1` and `u1 -> y2`
- Computed the Power Spectrum for responses and noise signals
- Applied H1 estimate technique to estimate the Frequency Response function and estimated coherence of each path
- 



<p align="center"><img src="auv_animate.gif">  </p>



#### Languages Used:
- Matlab
- Latex 

#### Use of each file:
- [**Midterm_Project_Japnit_Sethi.mlx**](Midterm_Project_Japnit_Sethi.mlx) - Executable file with learly defined problem statement and approach
- [**Midterm_Project_Japnit_Sethi.pdf**](Midterm_Project_Japnit_Sethi.pdf) - Published Document for a quick check of Solutions and Code
- [**s20_plant.p**](s20_plant.p) - Plant function file that takes excitation u as input (1xN) and returns the output response y(2xN), where N is the number of samples
- [**Midterm_Project_Data**](Midterm_Project_Data) - Track of Iterations for Pole Placements method
