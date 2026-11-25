## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |SANTHANADEVI S | **Reg. No.:** |26018176|
|---|---|---|---|
| **Date:** |25-11-2026 | 
---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 4 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="1045" height="488" alt="Screenshot 2026-11-25 133018" src="https://github.com/user-attachments/assets/80ede6f5-0c50-4bac-a909-61c47c94d0d3" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1057" height="597" alt="Screenshot 2026-11-25 133114" src="https://github.com/user-attachments/assets/b4990036-785f-4f66-b052-5ef903395252" />

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.



## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| *S. No.* | *Supply voltage Vs (V)* | *VR1 (V)* | *VR2 (V)* | *VR3 (V)* | *VR1 + VR2 + VR3 (V)* |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1 | 3 | 1 | 1 | 1 | 3 |
| 2 | 6 | 2 | 2 | 2 | 6 |
| 3 | 9 | 3 | 3 | 3 | 9 |
| 4 | 12 | 4 | 4 | 4 | 12 |
| 5 | 15 | 5 | 5 | 5 | 15 |

### B. KCL – Current measurements

| *S. No.* | *Supply voltage Vs (V)* | *Total current It (A)* | *Branch current I1 (A)* | *Branch current I2 (A)* | *Branch current I3 (A)* | *I1 + I2 + I3 (A)* |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 1 | 3 | 0.009 | 0.003 | 0.003 | 0.003 | 0.009 |
| 2 | 6 | 0.018 | 0.006 | 0.006 | 0.006 | 0.018 |
| 3 | 9 | 0.027 | 0.009 | 0.009 | 0.009 | 0.027 |
| 4 | 12 | 0.036 | 0.012 | 0.012 | 0.012 | 0.036 |
| 5 | 15 | 0.045 | 0.015 | 0.015 | 0.015 | 0.045 |
## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="470" height="738" alt="Screenshot 2026-11-25 133137" src="https://github.com/user-attachments/assets/ce228950-e68d-4a89-9774-ec8453473d8c" />
<img width="457" height="295" alt="Screenshot 2026-11-25 133147" src="https://github.com/user-attachments/assets/2b35224b-152d-426a-be90-adcf7f6c3ffc" />

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="470" height="221" alt="Screenshot 2026-11-25 133207" src="https://github.com/user-attachments/assets/a4fb5609-141e-434e-b997-c12e5931bfa9" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
