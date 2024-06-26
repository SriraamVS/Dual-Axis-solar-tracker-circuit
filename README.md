# Dual-Axis-solar-tracker-circuit
Design and implementation of Dual Axis solar tracker circuit

**Motivation** 
    A dual-axis solar tracking system helps in the generation of maximum power by continuously adjusting the direction of solar panels based on the sun's movement in both the horizontal and vertical axes. While dual-axis solar tracking systems require more complex mechanisms and control systems compared to fixed installations, their potential for increased energy output can lead to cost savings in the long run. The use of solar energy helps reduce greenhouse gas emissions, air pollution, and dependence on fossil fuels. By selecting a dual-axis solar tracking system as our project, we contribute to the broader goal of sustainable energy development and combat climate change. Demonstrating the viability and benefits of such systems can inspire others to adopt renewable energy solutions, leading to a greener and more sustainable future.

**Problem Statement** 
    The problem addressed in this project is the design and development of an efficient solar tracking system that improves the energy output of solar panels. The proposed system aims to overcome the limitations of fixed-position solar panels, which do not adapt to the changing position of the sun, resulting in suboptimal energy generation. The system should
    • Maximize the power generation when compared to a fixed panel.
    • Track the light source accurately in both directions (dual axis)
    • Be compatible with climatic change.
    • Runs a dc fan from the power generated by the light source.

**Design Procedure**
    • The type and size of solar panels to be used was identified.
    • The power supply requirements for the system were calculated.
    • Light Dependent Resistors (LDRs) were chosen as light intensity sensors.
    • An op-amp was used to convert LDR resistance into a voltage signal.
    • TP4056 battery charger IC was used to store excess energy produced by solar panels 
    in a lithium cell.
    • L7805CV voltage regulator was implemented to provide a stable 5V power supply 
    for the circuit.
    • L293D was chosen to control the DC motors.
    • The motor driver was connected to the op-amp output.
    • The H-bridges within the motor driver were configured to control motor direction 
    and speed.
    • DC motors and gearing mechanisms were incorporated to adjust the solar panel's 
    position.
    • The system's performance was analyzed and areas for improvement were identified.
