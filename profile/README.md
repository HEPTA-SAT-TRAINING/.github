# HEPTA-SAT

Welcome to the **HEPTA-SAT GitHub repository**.

This page explains the software setup for the HEPTA-SAT Labs.

---

# Before Starting the Labs

Please complete the following setup **before starting the HEPTA-SAT Labs**.

## Required Setup

- [ ] Install Arduino IDE
- [ ] Install the Raspberry Pi Pico/RP2040/RP2350 board package
- [ ] Confirm that `Generic Raspberry Pi Pico 2` can be selected

> [!IMPORTANT]
> Before starting the Labs, you only need to complete the **Arduino IDE and HEPTA-SAT OBC board setup**.
>
> Other software can be installed later when needed.

---

# 1. Install Arduino IDE

Arduino IDE is used to write and upload programs to the HEPTA-SAT OBC.

**[Download Arduino IDE](https://www.arduino.cc/en/software)**

---

# 2. Configure the HEPTA-SAT OBC Board

Open Arduino IDE and go to:

`File → Preferences`

Add the following URL to **Additional Boards Manager URLs**:

```text
https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json
```

> [!TIP]
> If another URL is already registered, add this URL as a new entry without deleting the existing one.

Next, open **Boards Manager** and search for:

`pico`

Install:

`Raspberry Pi Pico/RP2040/RP2350`

After installation, select:

`Tools → Board → Generic Raspberry Pi Pico 2`

Your basic HEPTA-SAT development environment is now ready.

---

# Lab Programs

Programs used in each HEPTA-SAT Lab are available in the GitHub repositories.

To download a Lab program, open the repository and select:

`Code → Download ZIP`

You can also use **GitHub Desktop** to clone and manage the repositories.

---

# Software Used When Needed

The following software **does not need to be installed before starting the Labs**.

Install it when instructed in the relevant Lab or Additional Content.

| Software | Used for |
| --- | --- |
| GitHub Desktop | Managing GitHub repositories |
| XCTU | XBee wireless communication |
| Autodesk Fusion | Structural design and 3D modeling |

---

## GitHub Desktop

GitHub Desktop is useful for cloning and managing HEPTA-SAT repositories.

**[Download GitHub Desktop](https://desktop.github.com/download/)**

It will be introduced when GitHub operations are needed.

---

## XCTU

XCTU is used to configure and test **XBee wireless communication modules**.

**[Download Digi XCTU](https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu)**

It will be introduced in the communication-related activities.

---

## Autodesk Fusion

Autodesk Fusion is used for **3D modeling and structural design**.

**[Autodesk Fusion Free Trial](https://www.autodesk.com/products/fusion-360/free-trial)**

Eligible students and educators can also use the Autodesk Education program:

**[Autodesk Fusion for Students and Educators](https://www.autodesk.com/education/edu-software/fusion)**

It will be introduced in the structural-design-related activities.

---

# Setup Summary

| Software | When to Install |
| --- | --- |
| **Arduino IDE** | **Before starting the Labs** |
| **Pico Board Package** | **Before starting the Labs** |
| GitHub Desktop | When needed |
| XCTU | When needed |
| Autodesk Fusion | When needed |

> [!IMPORTANT]
> **Before the Labs:** Set up Arduino IDE and the HEPTA-SAT OBC board.
>
> **During the Labs:** Install other software only when it is needed.
