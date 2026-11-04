# 1 Systems and Subsystems
Systems were identified as areas or parts of the process that execute a singular whole function.
A clear boundary exists between two systems
- Raw ore handles raw ore until it is given to Crushing
- Crushing does the crushing and handles the material until it is given to Desliming
- I separated Potash processing into 3 Systems as they are 3 clearly separate steps
  - Desliming handles removal of clay
  - Flotation separates out the Halite (NaCl)
  - Cristalization cristalizes the product
  - Reagent and chemicals System services all three using its dedicated subsystems
- Product handling is the final step of our process
- Water system services the whole process plant with its varied subsystems
- Electrical covers all power distributions for each building as well as the power distribution subsystem as these all discipline specific
- Similarly with Instrumentation and Controls
Subsystems can stand alone for testing within their system. We can test Clay disposal for functionality without having to do desliming. Same for testing the crushing circuit and letting crushed ore fall in bucket or on floor and separately testing the conveyence.
The difference would be the level of complexity. But also conceptual boundary. Again I could have had desliming flotation and cristalization in one system, but I decided to seperate them as they are each very large and do have conceptual boundaries between them.

---

# 2 Systemization Objectives
We divide facilities into systems and subsystems because we can build them test them run them deliver them in parts that come together. If instead you installed all pumps first you could only test the pumps but until pipes are connected you are stuck. Building and commissioning the plant by subsystems allows you to gradually increase scope of testing and functionality over time. As such you can handover system by system. And on top of that you could have one system running while another is being built, for example extracting and collecting ore, ore crushing and storing crushed ore while the desliming and flotation systems are still under construction. It is important to note that different companies can execute on different systems and subsystems, as they have specialties. Systemization can keep them all in their respected places.

---

# 3 Boundary Definition
Factors that determine system boundaries are conceptual step in the process, physical area, and discipline mostly involved in the system.
As for the subsystems boundaries, they are determined by identifying the smallest working group of assets that can be run and tested together.
It would be prudent to keep physical distance or boundaries between subsystems that have function al boundaries. For delivery and maintenance purposes, you want to be able to isolate a subsystem and work on it without having to shut down other subsystems to do that. Example, raw ore conveying can dump on floor or bucket while we examine the crusher, or a good old shovel can replace conveyor feed for subsystem testing purposes.
Interfaces between systems (and their respected subsystems) should be clear and not interfering with either of the two systems.

---

# 4 Engineering Disciplines
- Process Engineering
  - clear conceptual steps in the process are main defining lines between systems
- Mechanical Engineering
  - mechanical equipment
  - mechanical completion
- Piping Engineering
  - pump testing
  - piping routing verification
- High Voltage Engineering
  - each facility has its own power supply station and cables
  - all facility power supply run in parallel to prevent power shut down in one area or system/subsystem to shutting down a whole another are
- SNPC
  - subsystems should have independently setup control loops with sensors
- Civil and Structural Engineering
  - Buildings for areas

---

# 5 Project Stakeholders
- Engineering
- Construction
- Commissioning
- Project Management
- Operations
- HSE

`note to chatgpt: i don't know how to start this part`

---

# 6 Completion and Commissioning
How does systemization structure support?
- Construction Completion
  - You want to build the facility where the subsystems would be
  - Constructing buildings that will contain subsystems and systems that are scheduled earlier should be done earlier
  - supports correct order and scheduling of construction to enable further steps
- Mechanical Completion
  - this is sometimes lumped in with construction
  - it concerns itself with correct installation of assets that will belong to the subsystems
  - you would want to install and check assets in such order that you enable pre-commissioning of one subsystem after another
- Pre-commissioning
  - subsystems with all their assets passing MC and walkdowns can be scheduled for subsystem testing
- Commissioning
  - when all system's subsystems have been turned over and pre-commissioned and handed over they can be tested as a whole system and eventually started up
- After all systems are started up we can do final handover
