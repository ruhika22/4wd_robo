# 4wd_robo
1: External Gear-Driven Systems (Gearbox + Secondary Reduction / Bearing-Supported Axles)

How It Works & Typical Applications:

A high-RPM DC or BLDC motor feeds an internal planetary gearbox, which then drives an external stage (spur gear pair, HTD timing belt, or #25 roller chain) connected to a solid steel axle mounted in two pillow-block or flange ball bearings. Standard across heavy mobile manipulators, warehouse AGVs, and outdoor rovers (20–100+ kg).

Trade-Offs: Adds ~1.5–2.5 kg of shaft/bearing/sprocket hardware and requires center-distance precision ($\pm 0.2\text{ mm}$ for spur gears; tensioner slots for chains/belts), but it is the only low-to-mid-budget architecture that survives 20 kg skid-steer loads.

Reference Designs:
https://www.superdroidrobots.com/shop/item.aspx/4wd-all-terrain-heavy-duty-robot-platform-ig52-db/1648
https://github.com/MilosRasic98/OpenMobileRoboticManipulator
https://github.com/nasa-jpl/open-source-rover

2: Motor-Driven Systems (Direct-Drive / Integrated Planetary In-Hub Gearmotors)

How It Works & Typical Applications: Wheels mount directly onto the output shaft of an integrated planetary gearmotor or an outer-rotor BLDC hub motor with zero external gears, chains, or belts. Used in compact research rovers (3–20 kg) where mechanical simplicity and sealed enclosures outweigh low-cost repairability.

Reference Designs:

https://docs.fictionlab.pl/leo-rover/documentation/specification
https://robozaps.com/products/clearpath-jackal
https://github.com/linorobot/linorobot2
https://github.com/linorobot/linorobot2_hardware

3: Caster Wheel Systems (Variant A: 2WD + Passive Casters; Variant B: 4-Wheel Powered Swerve Casters)

How It Works & Typical Applications:

Variant A (2WD Differential + Passive Casters): Two coaxial drive wheels provide all propulsion and steering; 1–2 unpowered swivel casters support the front/rear chassis. Standard in indoor lab robots (TurtleBot3, warehouse bots < 30 kg on smooth floors).

Variant B (4-Wheel Active Swerve / Powered Casters): Four corner caster assemblies, each using two motors (one to spin the wheel, one to rotate the vertical steering fork). Used in advanced holonomic mobile manipulators (TidyBot++, YOR).

Reference Designs

https://www.google.com/search?q=https://docs.robotis.com/docs/en/platform/turtlebot3/features/
https://docs.robotis.com/docs/dxl/model_reference/x_series/xm_series/xm430-w210/
https://tidybot2.github.io/
https://arxiv.org/html/2602.11150v1



