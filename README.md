# PX4 Modification Example Files

This repository provides **example PX4 source code modifications** to complement the appendices of Garrett Asper's Master's Thesis, as well as the [UAV-Toolbox-Setup-Guide](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide) and [BRAT Framework](https://github.com/gurt1223/brat) repositories. These example files enable features such as **custom uORB topic logging**, **user-defined parameters**, **custom telemetry streams**, and **firmware memory reduction** for PX4-based flight controllers.

---

## Table of Contents
- **[File Guide](#file-guide)**
- **[How to Use](#how-to-use)**
- **[Related Resources](#related-resources)**
- **[Related Publications](#related-publications)**
- **[Acknowledgments](#acknowledgments)**
- **[Citing This Resource](#citing-this-resource)**

---

## File Guide
- **Custom Logging/**  
  Example files for creating and integrating new uORB topics into the PX4 logging system.

- **Parameters/**  
  Example files showing how to define and integrate custom PX4 parameters.

- **Telemetry/**  
  Example MAVLink stream modifications for enabling a custom telemetry message.

- **Flash Memory/cubeorange/**  
  Firmware and configuration adjustments to reduce flash usage on the CubeOrange autopilot.

---

## How to Use
1. Follow the setup steps in the [UAV-Toolbox-Setup-Guide](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide) to set up the UAV Toolbox and its dependent software.  
2. Choose which modifications you want to apply (e.g., parameters, telemetry, or logging).  
3. Copy the example files into the corresponding PX4 source directories (outlined in the thesis appendix in [UAV-Toolbox-Setup-Guide](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide)).  
4. Rebuild the PX4 firmware and upload it to your flight controller.  
5. Use the modifications to enhance your own MATLAB/Simulink logic or the logic you create in the [BRAT Framework](https://github.com/gurt1223/brat) for algorithm testing.

---

## Related Resources
- **[UAV Toolbox Setup Guide](https://github.com/gurt1223/UAV-Toolbox-Setup-Guide)**  
  Comprehensive setup instructions for MATLAB/Simulink integration with PX4.

- **[BRAT Framework](https://github.com/gurt1223/brat)**  
  Lightweight starter project for testing custom Simulink algorithms using PX4 I/O.

---

## Related Publications
<details>
<summary>Click to expand</summary>

[1]	Asper, G. D. and Simmons, B. M., “Rapid Flight Control Law Deployment and Testing Framework for Subscale VTOL Aircraft,” NASA/TM−20220011570, Sept. 2022. 

[2]	Asper, G. D., Simmons, B. M., Ackerman, K. A., Axten, R. M., and Corrigan, P. E., “Inexpensive Multirotor Platform for Advanced Controls Testing (IMPACT): Development, Integration, and Experimentation,” NASA/TM-20240000223, March 2024. 

[3]	Simmons, B.M., Ackerman, K.A., and Asper, G.D. “Aero-Propulsive Damping Characterization for eVTOL Aircraft Using Free Motion Wind-Tunnel Testing,” AIAA SciTech 2025 Forum, AIAA Paper 2025-0006, Jan. 2025.

[4]	Corrigan, P.E., Matt, J.J., and Asper, G.D. “Design and Testing of an Octocopter for Aerodynamic and Power Consumption Modeling,” NASA/TM-20240013453, March 2025. 

[5]	Asper, G.D. and Woolsey, C.A., “Toward a Fault-Tolerant Control Allocation Evaluation Framework for eVTOL Aircraft,” VSGC Student Research Conference, Virginia Space Grant Consortium, April 2025.

[6]	Simmons, B.M., Ackerman, K.A., Asper, G.D., Gray, M.N., Snyder, S.M., Axten, R.M., Geuther, S.C., and Chan, R. “Subscale Tiltrotor eVTOL Aircraft Dynamic Modeling and Flight Control Software Development,” Vertical Flight Society Annual Forum & Technology Display, May 2025. 
Awarded Best Paper Submitted to the Modeling & Simulation Technical Committee.

[7]	Comer, A.M., Simmons, B.M., and Asper, G.D. “Design, Simulation, and Flight Testing of a Multi-Purpose VTOL Flight Control System,” NASA/TM—20250000954, September 2025. 

[8]	Simmons, B.M., Ackerman, K.A., and Asper, G.D. “Aero-Propulsive Damping Characterization for eVTOL Aircraft Using Free Motion Wind-Tunnel Testing,” Journal of Aircraft, In review.

[9]	Corrigan, P.E., Asper, G.D., Simmons, B.M., and Woolsey, C.A., “Aircraft System Identification Approach for Control Surface Fault Diagnosis,” AIAA SciTech 2026 Forum, Submitted for consideration, 2026. 

[10]	Asper, G.D., Corrigan, P.E., Simmons, B.M., and Woolsey, C.A., “An Evaluation of Fault-Tolerant Control Allocation Strategies for eVTOL Aircraft,” AIAA SciTech 2026 Forum, Submitted for consideration, 2026.

</details>

---

## Acknowledgments
Thank you to Patrick Corrigan, Benjamin Simmons, and Anthony Comer for your support in learning the ins and outs of this toolchain.<br>
Thank you to the developers at MathWorks, particularly Arun Mathamkode and Ankur Bose, for your insight and openness to feedback on problems and improvements.

---

## Citing This Resource
If you use the steps or frameworks in this repository for your research, please cite Garrett Asper's Master's Thesis:<br>  
Asper, G. D., “An Evaluation of Fault-Tolerant Control Allocation Strategies for eVTOL Aircraft,” M.S. Thesis, Virginia Tech, Blacksburg, VA, To be published Spring 2026.<br>
_Please check back in January to ensure there are no updates to the citation. The repository contains a prerelease of the appendices, but citing the above thesis is the most effective way to acknowledge these resources._
