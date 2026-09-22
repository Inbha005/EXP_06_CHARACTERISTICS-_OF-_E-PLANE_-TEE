# exp_6_study_and_characterization_of_e_plane_tee

# Experiment 6 — Study and Characterization of E-Plane Tee

---

## Aim

To study the characteristics of an E–plane tee (series tee) and to determine the power–division ratio between its collinear arms and the isolation between them.

## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, H-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="932" height="296" alt="image" src="https://github.com/user-attachments/assets/4001f811-59b0-49a9-9acb-2b5afb89d4b1" />


---

## Theory

An E–plane tee is a waveguide junction in which the axis of the side arm is parallel to the electric (E) field of the main waveguide, formed by cutting a slot along the narrow wall so the side arm extends in the plane containing the E–field. It behaves as a series junction: when power is fed into the side arm (port 3, the E–arm), it divides equally between the two collinear arms (ports 1 and 2) but the two outputs are 180° out of phase with each other. Conversely, signals fed into the two collinear arms in phase cancel at the E–arm, while signals fed 180° out of phase add at the E–arm. This phase–reversing power split makes the E–plane tee useful in balanced mixers and other circuits requiring a phase difference between the two output signals.

##CIRCUIT / PORT DIAGRAM
<img width="765" height="562" alt="image" src="https://github.com/user-attachments/assets/03376dfe-5bf2-4b37-a704-46ae82764dce" />


## Procedure

1. The bench is set up with the E–plane tee connected as the device under test and the klystron output stabilised.
2. Power is fed into the E–arm (port 3); port 2 is terminated in a matched load and the detector is connected to port 1, and the output reading is noted.
3. The detector and matched load are interchanged between ports 1 and 2, and the output at port 2 is noted with port 1 terminated.
4. To find the isolation between the two collinear arms, power is fed into port 1, port 3 is terminated in a matched load, and the leakage at port 2 is measured. 5. All readings are recorded in dB

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
