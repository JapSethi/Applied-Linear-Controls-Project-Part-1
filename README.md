# Applied-Linear-Controls-Project-Part-1
**<div align="center">To develop and validate an empirical discrete-time state-space model of the dynamic system using [system identification](https://www.mathworks.com/help/ident/gs/about-system-identification.html) methods</div>**

> **Note**: For this project, we assume that nothing specific is known about the system dynamics; however, we do know that it has two outputs and one input, and we know that the system is open-loop stable.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

#### Objectives Achieved: 

- Constructed an excitation signal for System Identification following the satuaration limit for DAC (Digital-to-Analog Converter)
- 


- Modeled MIMO dynamic systems using state-space techniques.
- Analytically and numerically solved for the dynamic response of any linear dynamic system and relate the response to the state-space system description.
- Analyzed the open-loop and closed-loop stability of any state-space representation.
- Designed linear state-feedback controllers using pole placement techniques.

<p align="center"><img src="auv_animate.gif">  </p>



#### Languages Used:
- Matlab
- Latex 

#### Use of each file:
- [**Midterm_Project_Japnit_Sethi.mlx**](Midterm_Project_Japnit_Sethi.mlx) - Executable file with learly defined problem statement and approach
- [**Midterm_Project_Japnit_Sethi.pdf**](Midterm_Project_Japnit_Sethi.pdf) - Published Document for a quick check of Solutions and Code
- [**s20_plant.p**](s20_plant.p) - Plant function file that takes excitation u as input (1xN) and returns the output response y(2xN), where N is the number of samples
- [**Midterm_Project_Data**](Midterm_Project_Data) - Track of Iterations for Pole Placements method
