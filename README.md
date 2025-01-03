# My Projects Insights

## 1. Experimental Study of Thrust Vectoring in Cyclorotor

![fig1](Pictures/Cyclorotor/Design.png)
#### WHAT is this project?
Cyclorotor is a horizontal axis propulsion system which has been brought back to the main stream of research for study of its viability in aviation commuter segement like flying cars. This project aimed to study the thrust vector experimentally to understand the thrust vector's behavior in relation to phase angle of eccentricity for the possibiities of better control and maneuverability of the system. This project was carried out for the partial fulfillment of my bachelor's degree.
##### Report on this project is available [here](https://drive.google.com/file/d/1eB-UYTzneUBVJCtv-Sf_ccBZjCfi1CdQ/view?usp=sharing)
#### HOW was it done?
- Selection of optimal design parameters from previous experiments.
- Develop the CAD model and simulate for viability of the mechanisms.
- Design a power transmission system as per the torque requirement along with bushings and brackets.
- Validate the functioning with kinematic simulation of the assembled design.
- Design for manufacturing and manufacture by 3D printing.
- Design load-cell based test rig
![fig2](Pictures/Cyclorotor/Product.png)
![fig3](Pictures/Cyclorotor/loadcellcircuit.png)

#### Accomplishments
- Precise 3D printed parts.
- Perfect fits of the assembly parts.
- Successful custom power transmission system development.
- Successful operation and experimentation.
- Comparison of the system in simulation and real environment.
- Thrust direction observed to be always opposite to the eccentric point in case of four blades system.
![fig4](Pictures/Cyclorotor/Assembly_Draft.jpg)


## 2. Micromouse
Our project “Micromouse” is guided by the rules of International Micromouse Competition where an autonomous maze-solving robot has to be developed which is capable of solving a 16*16 maze with each cell of size 18cm. The maze can have different configurations, but the start is always at one of the four corners and the destination is always at the center of the maze. This project was done for participating in International Micromouse Competition organized by
[TechFest2019-20 at IIT Bombay](https://techfest.org/).
A micro sized robot was built on PCB board integrating N20 Micro-gear motor, STM32 Bluepill microcontroller, L293D motor driver, MPU9250 IMU sensor, VL530X ssenor and LiPo battery.

![fig5](Pictures/Micromouse/KiCAD.jpg)
![fig6](Pictures/Micromouse/Naanu.jpg)

However Tremaux algroithm was suitable for controlling the robot, its exploratory nature challenged our time and memory constraint. Thus an optimal algorthim was devleoped employing a potential value algorithm in conjunction with Tremaux improving search and run time in the micromouse.  The fused algorithm running on the STM32 Bluepill microcontroller explores and finds the shortest path in a 16x16 maze. Proximity sensors, gyroscope, and magnetometer together with encoder motors aid the micromouse to understand its surrounding hindrances and make precise movements while traversing through a maze. The optimized algorithm eliminates any paths that may lead the micromouse further away from the center of the maze during the initial run itself and saves a significant amount of time while solving a maze.

##### Report on this project is available [here](https://drive.google.com/file/d/183wrktVCq5AOybMiit0GX_J2vyt4wZQf/view?usp=sharing)

## Flow Chart of the Optimized Algorithm

![flowchart](/Pictures/Micromouse/flow_chart.png)

Here are the three different versions of micromouse designed and fabricated. The bot at the center was used during the IMC-2020.
![bots](/Pictures/Micromouse/bots.png)
![fig7](Pictures/Micromouse/robo.jpg)


## Citation:
You can find our publication [here](https://ictaes.org/wp-content/uploads/2020/09/IJAE-2020-Vol.03-No.02/7_Sanjaya_Vol3_No2.pdf?ckattempt=1).
```
@article{rijalinternational,
  title={Optimizing Tremaux Algorithm in Micromouse Using Potential Values},
  journal={International Journal of Advanced Engineering},
  author={Rijal, Sanjay and Nepal, Rabin and Lwagun, Rhimesh and Pati, Rohit and Bhatta, Janardan},
  volume={3},
  issue={2},
  year={2020}
}
```

## 3. Shireto
[(Team Shireto Website Link)](https://teamshireto.com)

![fig8](Pictures/Shireto/Chassis_design.png)
#### WHAT is this project?
Shireto is a dynamic student-led group of motorsport enthusiasts from various disciplines within Thapathali Campus with the aim to enhance the knowledge on vehicle development and participate in racing events and competitions globally. The project started in 2019 with the aim to participate in Shell Eco Marathon 2021 in EV category and we successfully manufactured a competitive prototype. Now team Shireto is working on formula type cars to participate in Formula Student events.

The car was designed and developed based on the guidelines of Shell Eco Marathon and was pure electric. The main aim was to acquire as much mileage as possible with as less electric power consumption as possible hence, the structures were designed to the optimal weight to strength ratio with aluminium. Body was manufactured using fiberglass applying the casting method. Powertrain consisted a hub-motor attached wheel and a custom developed 36V 15Ah controller powered by LiFePo battery.
![fig9](Pictures/Shireto/Chassis.png)
![fig10](Pictures/Shireto/Manufacture.png)
#### HOW is it done?
- CAD modeling (CATIA) and CFD analysis (ANSYS) of the structures
- Ergonomic analysis using Human Builder Workbench in CATIA
- Chassis fabricaion using TIG welding on aluminium Al 6063 tubes
- Casted fibreglass body panel using polyester resin with cobalt catalyst and hardener
- Hub-motor powertrain system
![fig11](Pictures/Shireto/Product.png)

#### Accomplishments
- Guidelines compliant competitive vehicle
- Optimal aerodynamics
- Rigid chassis structure
- 70+ Km range with 1KWh of energy


## 4. EV Conversion
#### WHAT is this project?
This project was carried out in collaboration with EVahan (a startup company in Nepal) with my responsibility as General Engineer. It focused on converting an IC engine powered two-wheeler vehicle into a pure electric.
![fig13](Pictures/EV_conversion/EVConvert.jpg)

##### Report on this project is available [here](https://drive.google.com/file/d/10gWs83NFK3THqdROTqU345aQyBRbm8cr/view?usp=sharing)
#### HOW is it done?
- Client's requirements identification.
- Motor specifications and battery capacity calculation using Simulink Model.
- Swing-arm modification for the installation of motor.
- Battery casing attachment to the chassis.
- Redesigning the wiring system.
![fig14](Pictures/EV_conversion/VehicleResistive.png)
![fig15](Pictures/EV_conversion/BatteryDesign.png)

#### Accomplishments
- Develop a general simulink model to calculate motor specification and battery capacity.
- Manufacture a completely operational vehicle.
- Programmed the motor controller for regenerative braking and 2 driving modes.
- Safe and road compliant vehicle.

## 5. Battery Pack Development
#### WHAT is this project?
Battery packs are built by combining battery cells in parallel and series configuration. This project is aimed at manufacturing a custom battery pack for electric bicycles. A 36V 15Ah battery pack with a fire-insulated cover equipped with charge-discharge ports, a display port and function keys was designed and manufactured.

##### Report on this project is available [here](https://drive.google.com/file/d/1CvMc2M0b08G_HyTX1NpBqHgKvPnaDJ8o/view?usp=sharing)

![fig16](Pictures/Battery_casing/547320747141988.jpeg)
#### HOW is it done?
- Battery configuration was calculated for series and parallel.
- A 3.7V 2600mAh lithium 18650 battery cells were used.
- 6 cells were connceted in parallel to form a cluster and such 10 clusters were connected in series.
- Dimensions extraction from the battery cluster, BMS, display console, and power socket
- 3D model of the battery cover was designed in Catia V5.
- Manufacture battery cover using 3D printing technique.
- FRP board and fiberglass sheets were used to insulate the battery pack.
- Assemble battery cover and Test.

![fig17](Pictures/Battery_casing/Casing_design.png)

![fig18](Pictures/Battery_casing/IMG1.jpg)

#### Accomplishments
- 36V 15Ah battery pack was built.
- Integration of BMS.
- Proper placement of display and power sockets.
- Proper fire inuslation.
- Well manufactured battery cover.
