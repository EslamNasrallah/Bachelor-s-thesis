# Bachelor’s Thesis

The automotive industry is rapidly transitioning toward software-defined vehicles, driven by
the demand for enhanced convenience, safety, autonomy, and electrification. With millions of
lines of code controlling various vehicle systems, ensuring their correct operation is critical [1].
At BMW, the BMW AUTOSAR Core (BAC) serves as the foundation for deeply embedded
ECUs, combining standardized AUTOSAR modules with BMW-specific extensions. However,
traditional validation and testing methods for BAC software, which rely on physical hardware,
are both costly and time-consuming. A complete test setup can cost between 2500 to 5000
Euros, limiting hardware access for many developers. This often results in delays and
inefficiencies in the development process, as hardware issues or incorrect interpretations of
requirements are discovered late.
This thesis addresses the challenges by implementing a fully virtualized test environment
that eliminates the need for physical ECU hardware during the BAC software testing phase.
Key challenges, such as replicating ECU behavior, enabling communication between the
virtual ECU (vECU) and existing ECU testing tools, and accurately simulating the ECU’s
modes, are tackled. Through this virtual environment, early-stage testing and debugging
become possible, significantly accelerating the detection of software errors. Performance
evaluations show that the virtual test setup can reliably simulate real-world conditions,
offering developers a powerful tool for early and efficient testing.
