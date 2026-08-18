# HEPTA-SAT

Welcome to the **HEPTA-SAT GitHub repository**.

Before starting the HEPTA-SAT Labs, please complete the following setup.

---

# Contents

1. [Arduino IDE Setup](#1-arduino-ide-setup)
2. [GitHub Desktop Setup](#2-github-desktop-setup)
3. [Additional Software](#3-additional-software)

---

# 1. Arduino IDE Setup

Arduino IDE is used to write and upload programs to the HEPTA-SAT OBC.

## 1.1 Install Arduino IDE

Download and install Arduino IDE.

**[Download Arduino IDE](https://www.arduino.cc/en/software)**

---

## 1.2 Configure the HEPTA-SAT OBC Board

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

The Arduino IDE setup is now complete.

---

# 2. GitHub Desktop Setup

GitHub Desktop is used to download and manage the HEPTA-SAT Lab repositories.

## 2.1 Install GitHub Desktop

Download and install GitHub Desktop.

**[Download GitHub Desktop](https://desktop.github.com/download/)**

---

## 2.2 Clone a HEPTA-SAT Lab Repository

Open the HEPTA-SAT Lab repository you want to use.

Click:

`Code → Open with GitHub Desktop`

GitHub Desktop will open.

Select the folder where you want to save the repository and click:

`Clone`

The Lab repository is now stored on your computer.

You can open the Arduino `.ino` file from the cloned repository using Arduino IDE.

---

# Setup Checklist

Before starting the HEPTA-SAT Labs, make sure that:

- [ ] Arduino IDE is installed
- [ ] Raspberry Pi Pico/RP2040/RP2350 board package is installed
- [ ] `Generic Raspberry Pi Pico 2` can be selected
- [ ] GitHub Desktop is installed
- [ ] HEPTA-SAT Lab repositories can be cloned

> [!IMPORTANT]
> **Arduino IDE setup and GitHub Desktop setup should be completed before starting the Labs.**

---

# 3. Additional Software

The following software is used in specific Labs or additional activities.

You **do not need to install these applications in advance**.  
Install them when instructed in the relevant Lab or Additional Content.

| Software | Purpose |
| --- | --- |
| XCTU | XBee wireless communication |
| Autodesk Fusion | Structural design and 3D modeling |

---

## 3.1 XCTU

XCTU is software provided by Digi for configuring and testing XBee wireless communication modules.

In HEPTA-SAT, XCTU is mainly used for communication-related activities.

**[Download Digi XCTU](https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu)**

Detailed instructions will be provided when XCTU is used.

---

## 3.2 Autodesk Fusion

Autodesk Fusion is CAD software used for 3D modeling and structural design.

In HEPTA-SAT, Fusion can be used to:

- View the HEPTA-SAT structure
- Check component placement
- View 3D models
- Design structural parts

**[Autodesk Fusion Free Trial](https://www.autodesk.com/products/fusion-360/free-trial)**

Eligible students and educators can also use the Autodesk Education program:

**[Autodesk Fusion for Students and Educators](https://www.autodesk.com/education/edu-software/fusion)**

Detailed instructions will be provided when Fusion is used.
