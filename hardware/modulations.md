---
description: >-
  Explore our comprehensive guide on Flipper Zero Modulations, diving into its
  functionalities and usage. Unravel a new world of digital interaction.
---

# 🟢 Modulations

#### Flipper Zero Modulations

Flipper Zero is a multi-tool device for pentesters and geeks, equipped with several radio and hardware protocols. Modulations played a central role in its function, enabling it to communicate across a wide range of frequencies and protocols.

**Common Modulation Types in Flipper Zero**

* **ASK (Amplitude Shift Keying):** This modulation changes the amplitude of the carrier wave to encode data, often used in RF remote controls.
* **FSK (Frequency Shift Keying):** FSK modulates the frequency of the carrier wave and is commonly used in data communication for modems, RFID, and other digital radio systems.
* **PSK (Phase Shift Keying):** A modulation that alters the phase of the carrier wave to transmit data. It is often used in wireless LANs, RFID, and Bluetooth communication.

**Modulation Applications in Flipper Zero**

* **RF Communications:** Flipper Zero can mimic remote controls and other RF devices by using ASK or FSK modulation to communicate with them.
* **Data Analysis:** The tool can analyze the modulation scheme used by a device to help understand its communication protocol.
* **Custom Protocols:** Users can create custom modulation schemes to communicate with niche or proprietary devices.

_For practical usage details or advanced configuration, please refer to the official Flipper Zero documentation or the active community forums._

### Modulation options supported by the C1101 chip

| Modulation       | Description                            |
| ---------------- | -------------------------------------- |
| ASK/OOK          | Amplitude Shift Keying / On-Off Keying |
| 2-FSK            | Frequency Shift Keying (Binary)        |
| 4-FSK            | Frequency Shift Keying (Quaternary)    |
| MSK              | Minimum Shift Keying                   |
| GFSK             | Gaussian Frequency Shift Keying        |
| GMSK             | Gaussian Minimum Shift Keying          |
| OQPSK            | Offset Quadrature Phase-Shift Keying   |
| ASK/OOK (MSK)    | Combination of ASK/OOK and MSK         |
| ASK/OOK (GFSK)   | Combination of ASK/OOK and GFSK        |
| ASK/OOK (GMSK)   | Combination of ASK/OOK and GMSK        |
| FSK (GFSK)       | Combination of FSK and GFSK            |
| FSK (GMSK)       | Combination of FSK and GMSK            |
| MSK (GFSK)       | Combination of MSK and GFSK            |
| MSK (GMSK)       | Combination of MSK and GMSK            |
| OQPSK (GFSK)     | Combination of OQPSK and GFSK          |
| OQPSK (GMSK)     | Combination of OQPSK and GMSK          |
| 2-FSK (GFSK)     | Combination of 2-FSK and GFSK          |
| 2-FSK (GMSK)     | Combination of 2-FSK and GMSK          |
| 4-FSK (GFSK)     | Combination of 4-FSK and GFSK          |
| 4-FSK (GMSK)     | Combination of 4-FSK and GMSK          |
| GFSK (MSK)       | Combination of GFSK and MSK            |
| GMSK (MSK)       | Combination of GMSK and MSK            |
| GFSK (OQPSK)     | Combination of GFSK and OQPSK          |
| GMSK (OQPSK)     | Combination of GMSK and OQPSK          |
| 2-FSK (MSK)      | Combination of 2-FSK and MSK           |
| 2-FSK (OQPSK)    | Combination of 2-FSK and OQPSK         |
| 4-FSK (MSK)      | Combination of 4-FSK and MSK           |
| 4-FSK (OQPSK)    | Combination of 4-FSK and OQPSK         |
| GFSK (2-FSK)     | Combination of GFSK and 2-FSK          |
| GMSK (2-FSK)     | Combination of GMSK and 2-FSK          |
| GFSK (4-FSK)     | Combination of GFSK and 4-FSK          |
| GMSK (4-FSK)     | Combination of GMSK and 4-FSK          |
| 2-FSK (GFSK/MSK) | Combination of 2-FSK and GFSK/MSK      |
| 4-FSK (GFSK/MSK) | Combination of 4-FSK and GFSK/MSK      |
| GFSK/MSK (2-FSK) | Combination of GFSK/MSK and 2-FSK      |
| GFSK/MSK (4-FSK) | Combination of GFSK/MSK and 4-FSK      |
| OOK (2-FSK)      | Combination of OOK and 2-FSK           |
| OOK (4-FSK)      | Combination of OOK and 4-FSK           |
| OOK (GFSK)       | Combination of OOK and GFSK            |
| OOK (MSK)        | Combination of OOK and MSK             |
| OOK (OQPSK)      | Combination of OOK and OQPSK           |
| 2-FSK (OOK)      | Combination of 2-FSK and OOK           |
| 4-FSK (OOK)      | Combination of 4-FSK and OOK           |
| GFSK (OOK)       | Combination of GFSK and OOK            |
| MSK (OOK)        | Combination of MSK and OOK             |
| OQPSK (OOK)      | Combination of OQPSK and OOK           |
