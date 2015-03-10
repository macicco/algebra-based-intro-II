# Lab 6: Defibrillators III: Current through the chest

### Additional Equipment

-   DMM and battery eliminator
-   Resistors, cables, alligator clips

## Conceptual (C-Level) DONE BEFORE LAB

## Basic Lab (B-Level)

In defibrillation, two metal contacts (the paddles) are placed in contact with the skin of a patient. A large voltage is applied for a short time, which causes a large current to flow through the patient's chest, in an attempt to restart the person's heart.[^1]

A defibrillator is essentially a capacitor, electrically, and when connected to a patient forms an RC circuit (i.e. circuit with a resistor and capacitor. In this lab we are focusing on the "R" part: the patient, modeled as a resistor.

When current passes from paddle to the other it goes through several steps:

1. Positive paddle through skin to interior of chest.
2. Through the chest, some of which goes through the heart. For the purposes of this lab we will think of this current as taking one of two paths: through the heart or not through the heart.
3. From the chest through the skin to the negative paddle.

Your goal in this lab is to set up a circuit of resistors to model this current flow. The resistors you are using are representative of the resistances in a human chest, but the voltage we will apply, 5V, is 1000 times smaller than the voltage in a defibrillator, so the currents we measure will be 1,000 times smaller.[^2]

**Your assignment in the B-level part of this lab is to calculate and then measure the current flowing through the resistor in your circuit that represents the heart and to calculate the current that would flow the heart of a real patient whose overall resistance matched your circuit's resistance.**

A good lab report should address all of these points:

+ Describe the circuit you are using to represent the patient and justify your model (i.e. what are you doing and why).
+ Resistance values for the resistors you use. Like real people, the resistors you are using are not identical, and do not have the same resistance as each other.
+ Calculation of the current you expect to go through the "heart" given the applied voltage and the measured value of the resistances of the resistors you use.
+ Measured value of the current through the "heart" and calculation of the value that would be obtained if your "patient" was connected to a real defibrillator at 5kV.


## Advanced/Extended Lab Ideas (A-Level)

Choose **ONE** of the topics below to investigate.

- Calculate the power dissipated in the skin, chest, and heart.
- Propose **and carry out** an experiment on something related to voltage, current, and resistance or defibrillation that you are curious about. *Get your lab instructor's approval before beginning.*

[^1]: Well, sort of. A defibrillator's name comes from fibrillation, a condition in which the muscles in the heart's ventricles are contracting in an uncoordinated way. So the heart hasn't stopped, technically, it has simply become incapable of pumping blood. A defibrillator passes a large enough current through the heart to actually briefly stop it (or at least depolarize it), after which it often starts beating the right way.

[^2]: Which is a good thing, of course, or we'd need a real defibrillator if you accidentally touched the wrong wires.
