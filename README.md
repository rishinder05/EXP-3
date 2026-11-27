## EXPERIMENT NO. 3 – STAIRCASE WIRING

| **Name:** |U Rishinder | **Reg. No.:** |26008317 |
|---|---|---|---|
| **Date:** | 27.11.2026| **Batch / Section:** |26ODJ084 |

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram

<img width="1280" height="877" alt="e8c77e59-ec33-411c-b10b-1ad24ea25b27" src="https://github.com/user-attachments/assets/e95ff624-fcbc-4fb9-a489-759dfe595fa7" />


**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection

<img width="1280" height="852" alt="image" src="https://github.com/user-attachments/assets/4fcb1e02-e7b0-44c3-9b5b-545404da1f69" />


| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 |OFF |OFF |ON |
| 2 |OFF |ON |OFF |
| 3 |ON |OFF |OFF |
| 4 |ON |ON |ON |

## B. CROSS CONNECTION

### Circuit diagram

<img width="1043" height="578" alt="image" src="https://github.com/user-attachments/assets/887af08d-5269-4815-ba8e-cac4a21213b2" />


**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

<img width="1053" height="536" alt="image" src="https://github.com/user-attachments/assets/8ff6bc70-3e9c-494c-a6eb-ef9c6f2507f4" />


| S. No. | Switch S1 position | Switch S2 position | Lamp status (ON / OFF) |
|:---:|:---:|:---:|:---:|
| 1 |OFF |OFF |OFF |
| 2 |OFF |ON |ON |
| 3 |ON |OFF |ON |
| 4 |ON |ON |OFF |

## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation

<img width="1920" height="1080" alt="EXP 3 b1" src="https://github.com/user-attachments/assets/4d56beba-48cd-46e9-97b4-c92fae6dee6b" />


**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation

<img width="1920" height="1080" alt="EXP 3 a1" src="https://github.com/user-attachments/assets/3069d52e-833b-445a-a68a-fe5e0e147ca2" />


**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
