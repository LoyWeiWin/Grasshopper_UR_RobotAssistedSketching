# Robot-Assisted Sketching using Grasshopper

## Overview
This project investigates how Grasshopper can facilitate communication with the Universal Robots UR10 collaborative robot to perform diverse sketching tasks on a flat planar surface. By leveraging Grasshopper's parametric design capabilities and integrating advanced plugins, the system achieves precise control and high-quality outputs. The research aims to provide open-source tools and detailed documentation for broader accessibility and adoption.

<img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedSketching/blob/main/Assets/Thumbnails/Vid_RoboticSketching.gif" alt="Alt Text" width="650">


## Project
- Perforated Panel Sheet
- Sketching Robot
- Sketching Robot (Incorporates algorithms inspired by the Traveling Salesman Problem (TSP) to determine the shortest and most efficient sketching routes,)

## Software Requirement
- Rhino 7 or latest
- [Robot plugin](https://github.com/visose/Robots)
- [Generation plugin](https://www.food4rhino.com/en/app/generation)
- [Rooster plugin](https://www.food4rhino.com/en/app/rooster)

## Key Features
- **Parametric Design Control**: Use Grasshopper to dynamically adjust sketching pattern (bychanging reference image).
- **Compatibility with Universal Robot**: Seamless integration with UR collaborative robots for industrial applications.
- **3D Printed End Effector**: [3D printed pen holder](https://www.printables.com/model/259360-robot-spring-loaded-sharpie-end-effector-eoat-for-) designed by [@N8THEGR8](https://www.printables.com/@N8THEGR8_239577).  

## Repository Structure
- `GrasshopperFiles/`: Grasshopper scripts.
- `RhinoFiles/`: Robot workcell, and end-effectors.
- `Assets/`: Images, thumbnails and videos
- `Docs/`: Documentation for installation, and troubleshooting.

> [!TIP]
> For more setup instrucions and usage, see the [Wiki](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedSketching/wiki).

## Contributing
Contributions to improve this workflow are welcome! Please follow the contributing guidelines in the [contributing guidelines](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedSketching/wiki/05_Contributing-Guidelines.md) in wiki.

## Code of Conduct
This project follows the Contributor Covenant Code of Conduct. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

> [!WARNING]  
> If you are unfamiliar with using cobots (collaborative robots), please ensure you have supervision from a qualified advisor or professional. Alternatively, simulate your intended workflow in a Grasshopper environment before working with physical machines.
> The contributor or owner of this repository is not responsible for any physical damage, injury, or harm caused to the immediate environment or individuals due to improper usage of cobots or related tools.

## Acknowledgements
This project was independently developed as part of my personal initiative and commitment to advancing this field.

## References
1. Liao, Shuran. (2023). The Solutions to Traveling Salesman Problem. Highlights in Science, Engineering and Technology. 47. 136-143. 10.54097/hset.v47i.8182. 




