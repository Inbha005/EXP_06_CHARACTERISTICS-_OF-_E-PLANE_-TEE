# exp_6_study_and_characterization_of_h_plane_tee

# Experiment 6 — Study and Characterization of H-Plane Tee

---

## Aim

To study the characteristics of an E–plane tee (series tee) and to determine the power–division ratio between its collinear arms and the isolation between them.

## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, H-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="746" height="446" alt="image" src="https://github.com/user-attachments/assets/5cc5ccb7-2004-4a24-8e14-044ebcef6cad" />

---

## Theory

In an H-plane tee an auxiliary waveguide arm is fastened perpendicular to the **narrow wall** of the main guide. It is a three-port device in which the axis of the auxiliary (side) arm is parallel to the planes of the magnetic field of the main guide, and the coupling from the main guide to the branch guide is by means of **magnetic fields** — hence the name H-plane tee.

The perpendicular arm is generally taken as the input and the other two arms are in **shunt** with it, so the junction is also called a **shunt tee**.

Because of the symmetry of the tee, when power enters the auxiliary arm and the two main arms 1 and 2 are terminated in identical loads, the power supplied to each load is **equal and in phase**. Conversely, if two signals of equal amplitude and the same phase are fed into the two main arms, they add together in the side arm. The H-plane tee therefore acts as an **adder**.

##CIRCUIT / PORT DIAGRAM
<img width="765" height="562" alt="image" src="https://github.com/user-attachments/assets/03376dfe-5bf2-4b37-a704-46ae82764dce" />


## Procedure

1. Set up the microwave bench: klystron power supply → klystron mount → isolator → variable attenuator → frequency meter → slotted section → component under test (H-plane tee) → detector mount → VSWR meter.
2. Keep the control knobs of the klystron power supply at their initial settings (mode switch: AM; beam voltage knob: fully anti-clockwise; repeller voltage knob: fully clockwise; meter switch: beam current) and switch on the supply, the VSWR meter and the cooling fan.
3. Energise the klystron for maximum output at the desired frequency by adjusting the beam and repeller voltages; measure the operating frequency with the frequency meter and then detune it.
4. **Reference reading:** without the H-plane tee in the line, set the variable attenuator to obtain a convenient full-scale reference reading on the VSWR meter. Note the attenuator setting **A₁** dB.
5. **Insert the component:** connect the H-plane tee in the line, feeding the arm under test and terminating the remaining arms in matched loads.
6. Reduce the attenuation until the VSWR meter reads the same reference value. Note the attenuator setting **A₂** dB. The difference (A₁ − A₂) dB gives the coupling/isolation for that pair of ports.
7. **Power division:** feed the H-arm, terminate one collinear arm in a matched load and measure the power at the other collinear arm; repeat with the arms interchanged. The measured coupling should be about **3 dB** for each collinear arm.
8. **Isolation:** feed the H-arm and measure the power coupled to the isolated port, with all other ports match-terminated.
9. **VSWR of each port:** feed the port under test, terminate the remaining ports in matched loads, and measure the VSWR using the slotted line.
10. Repeat the measurements for each of the three ports.

---
##PROCEDURE FLOWCHART
<img width="1040" height="550" alt="image" src="https://github.com/user-attachments/assets/cfce8c8a-a9d0-4e6d-b65d-4f2a74e0860b" />


## Observation

TABULATION

<img width="1086" height="145" alt="image" src="https://github.com/user-attachments/assets/421560ca-5f99-4aec-aef5-e97f696b4575" />
<img width="1076" height="130" alt="image" src="https://github.com/user-attachments/assets/9472b4a4-1650-4540-a2e3-08b5fb9f2212" />

FORMULA

1. Power division ratio (Port 3 → Port 1, Port 2) = Pin – Pout = 10 log10 (Pin / Pout) dB (ideally ≈ 3 dB at each arm, 180° out of phase)
2. Isolation between collinear arms = 10 log10 (P1 / P2) dB
MODEL GRAPH AND ACTUAL GRAPH

<img width="1077" height="402" alt="image" src="https://github.com/user-attachments/assets/1e11f5f4-593c-400e-a8f2-f099bb27fb6a" />

CALCULATION

1. Power at Port 1 (from Port 3) = 0.0 – (–3.5) = 3.5 dB down.
2. Power at Port 2 (from Port 3) = 0.0 – (–3.4) = 3.4 dB down.
3. Both arms are within 0.1 dB of each other and close to the ideal 3 dB point, confirming an equal power split; the 180° phase reversal between the two outputs (a property of the series junction) is confirmed separately using a phase–shifter/slotted–line comparison.
4. Isolation (Port 1 → Port 2, with Port 3 matched) = 0.0 – (–24.0) = 24.0 dB.


---

## Precautions

* Check all connections before switching on the kit.
* Keep all knobs at minimum before switching on the power supplies; the HT must be OFF while switching on the mains.
* Do not exceed a beam current of 30 mA, and keep the repeller voltage within the specified range.
* Terminate all unused ports in matched loads while taking readings.
* Do not look directly into an open waveguide.

## Result
The power–division ratio between the collinear arms of the given E–plane tee was found to be 3.5 dB and 3.4 dB (nearly equal), and the isolation between the collinear arms was found to be 24.0 dB. The equal power split with a 180° phase reversal, characteristic of a series (E–plane) junction, was verified.
