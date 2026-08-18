# HEPTA-SAT

Welcome to the **HEPTA-SAT GitHub repository**.

This repository provides programs and related files used in the HEPTA-SAT hands-on CubeSat training program.

Through the HEPTA-SAT Labs, you will progressively learn and experience topics such as:

* OBC (On-Board Computer) programming
* Electrical Power System
* Sensors and data handling
* Data storage
* Wireless communication
* Satellite assembly
* System integration
* Mission design

Before starting the Labs, please complete the following development environment setup.

---

# Getting Started

## Required Software

The following software is mainly used in the HEPTA-SAT Labs.

| Software       | Purpose                                             |
| -------------- | --------------------------------------------------- |
| Arduino IDE    | Writing and uploading programs to the HEPTA-SAT OBC |
| GitHub Desktop | Downloading and managing HEPTA-SAT Lab repositories |

> [!NOTE]
> XCTU and Autodesk Fusion are introduced later as **Additional Contents**.
> They are not required for the initial setup.

---

# 1. Install Arduino IDE

## What is Arduino IDE?

**Arduino IDE** is the development environment used to write, compile, and upload programs to the HEPTA-SAT OBC.

In the HEPTA-SAT Labs, Arduino IDE is used to:

* Write programs for the OBC
* Compile programs
* Upload programs to the OBC
* Check data using the Serial Monitor


---

## Step 1: Download Arduino IDE

Download Arduino IDE from the official Arduino website.

👉 **[Download Arduino IDE](https://www.arduino.cc/en/software)**

Select the installer that matches your operating system.

### Windows

Download the Windows installer and follow the instructions on the screen.

### macOS

Download the macOS version and move Arduino IDE to the **Applications** folder.

### Linux

Download the appropriate package for your Linux environment.


---

# 2. Configure the HEPTA-SAT OBC Board

Installing Arduino IDE alone is not enough to upload programs to the HEPTA-SAT OBC.

You also need to install the board package for the microcontroller used in HEPTA-SAT.

---

## Step 1: Add the Boards Manager URL

Open Arduino IDE.

Go to:

```text
File → Preferences
```

Find:

```text
Additional Boards Manager URLs
```

and add the following URL:

```text
https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json
```

> [!TIP]
> If another URL is already registered, do not delete it.
> Add this URL as a new entry.

---

## Step 2: Install the Board Package

Open **Boards Manager** from the left-side menu in Arduino IDE.

Search for:

```text
pico
```

Install:

```text
Raspberry Pi Pico/RP2040/RP2350
```


After installation, Arduino IDE will support Raspberry Pi Pico and Pico 2 series boards.

---

## Step 3: Select the HEPTA-SAT Board

Go to:

```text
Tools → Board
```

and select the board used for HEPTA-SAT.

For example:

```text
Generic Raspberry Pi Pico 2
```



Before starting a Lab, make sure that the correct board is selected.

---

# 3. Download the HEPTA-SAT Lab Programs

Programs used in each HEPTA-SAT Lab are provided through GitHub repositories.

There are two main ways to obtain the programs:

1. Download the repository as a ZIP file
2. Clone the repository using GitHub Desktop

---

# 4. Method 1: Download as ZIP

This is the simplest method if you are new to GitHub.

Open the repository for the Lab you want to use.

Click:

```text
Code
```

and then:

```text
Download ZIP
```


After downloading:

1. Extract the ZIP file.
2. Open the extracted folder.
3. Find the Arduino `.ino` file.
4. Open the `.ino` file using Arduino IDE.

```text
GitHub Repository
        ↓
       Code
        ↓
   Download ZIP
        ↓
    Extract ZIP
        ↓
 Open the .ino file
        ↓
    Arduino IDE
```

---

# 5. Method 2: GitHub Desktop

## What is GitHub Desktop?

**GitHub Desktop** is an application that allows you to work with GitHub repositories using a graphical interface.

It allows you to perform Git operations without using command-line commands.

For example:

* Clone repositories
* Check file changes
* Commit changes
* Push changes
* Pull updates


---

## Step 1: Install GitHub Desktop

Download GitHub Desktop from the official website.

👉 **[Download GitHub Desktop](https://desktop.github.com/download/)**

Install the application and launch GitHub Desktop.

---

## Step 2: Clone a HEPTA-SAT Repository

Open the HEPTA-SAT Lab repository you want to use.

Click:

```text
Code
```

and then:

```text
Open with GitHub Desktop
```



GitHub Desktop will open.

Select the folder where you want to save the repository and click:

```text
Clone
```

The repository is now stored on your computer.

```text
HEPTA-SAT GitHub
        ↓
       Code
        ↓
Open with GitHub Desktop
        ↓
      Clone
        ↓
   Local Folder
```

Using GitHub Desktop also makes it easier to retrieve updates when the HEPTA-SAT repository is updated.

---

# 6. Initial Setup Checklist

Before starting the HEPTA-SAT Labs, make sure that the following setup has been completed.

* [ ] Arduino IDE is installed
* [ ] The Boards Manager URL has been added
* [ ] Raspberry Pi Pico/RP2040/RP2350 Board Package is installed
* [ ] The HEPTA-SAT OBC board can be selected
* [ ] HEPTA-SAT Lab repositories can be downloaded
* [ ] GitHub Desktop is installed

Once these steps are complete, your basic HEPTA-SAT development environment is ready.

---

# Additional Contents

The following software is used for additional activities such as wireless communication and structural design.

These applications are **not required for the initial setup**.

---

# A. XCTU

## What is XCTU?

**XCTU** is software provided by Digi for configuring and testing XBee wireless communication modules.

HEPTA-SAT uses XBee modules for wireless communication activities.

XCTU can be used to:

* Detect XBee modules
* Check XBee settings
* Configure communication parameters
* Test communication between XBee modules
* Monitor transmitted and received data

### Download

👉 **[Download Digi XCTU](https://www.digi.com/products/embedded-systems/digi-xbee/digi-xbee-tools/xctu)**

Detailed instructions for using XCTU are provided in the communication-related Lab or Additional Content.

---

# B. Autodesk Fusion

## What is Autodesk Fusion?

**Autodesk Fusion** is CAD software used for 3D modeling and mechanical design.

In HEPTA-SAT, Fusion can be used for activities such as:

* Viewing the HEPTA-SAT structure
* Checking 3D models of structural components
* Considering mission component placement
* Designing original structural parts


### Free Trial

👉 **[Autodesk Fusion Free Trial](https://www.autodesk.com/products/fusion-360/free-trial)**

### Students and Educators

Eligible students and educators may also use Autodesk Fusion through the Autodesk Education program.

👉 **[Autodesk Fusion for Students and Educators](https://www.autodesk.com/education/edu-software/fusion)**

Detailed instructions for using Fusion are provided in the structural-design-related Additional Content.

---

# Repository Structure

An example repository structure is shown below.

```text
HEPTA-SAT/
│
├── README.md
│
├── docs/
│   └── images/
│       └── setup/
│           ├── arduino-ide-overview.png
│           ├── arduino-download.png
│           ├── arduino-preferences.png
│           ├── board-manager-pico.png
│           ├── select-board.png
│           ├── github-download-zip.png
│           ├── github-desktop-overview.png
│           ├── github-open-desktop.png
│           ├── github-clone.png
│           ├── xctu-overview.png
│           └── fusion-overview.png
│
├── Lab1/
├── Lab2/
├── Lab3/
├── Lab4/
├── Lab5/
├── Lab6/
└── Additional-Contents/
```
