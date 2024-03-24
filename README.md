![Banner image for Robotic Programming at Staffordshire University](/BB_Banner_RP_ULTRA@4x.png)
# myRIO Square Wave Generator
A Virtual Instrument (VI) which is to be deployed onto a National Instruments myRIO to generate a square wave. This wave can be used to simulate data from a wheel speed type sensor.

The VI contains a control panel which displays errors (unused in this version), and controls for the duty cycle (as a percentage of the pulse width) and wave frequency (in Hertz).

## Using the Virtual Instrument
Download/Fork the VI. Be sure to unzip the downloaded folder.

Before the following instructions, ensure that the myRIO is set up according to the tutorial sheet. Ask the module tutor if unsure.

- Open LabVIEW 2021, **32 bit** on the S404 PCs, this is **not** the version which shows up when typing into the Start Menu
  - Scroll down the programs in the Start Menu until reaching **N** click the **orange** icon for the **"NI LabVIEW 2021 SP1"** application
- When it opens, click the **"myRIO Project"** on the left hand side under **"Create New Project"**
- Provide a Project Name and ensure that the Project Root is located within the correct student directory
- Select the correct Target, which will be "Plugged into USB", this will likely show up with the prefix **"NI-myRIO-1900..."**
- Leave the FPGA Personality as Default and click **"Finish"**
- Expand the Target within the project by clicking the **[+]** icon
- Right click the file named **"Main.vi"** that is within the Target and select **"Replace With"**
  - In the dialogue that opens, navigate to the downloaded VI from this repository
  - Select **"SquareWave.vi"** and click **"OK"**
- Save the Project (ctrl+S)
- Double click **"SquareWave.vi"**
- Once the VI has opened, click the **"Run"** arrow icon button at the top left of the application
- Control the duty cycle and frequency with the labelled dials

### Note
If the deployment process raises a conflict, allow it to replace the existing application.

The VI is provided without a project so that it can be added to a connected myRIO project, and to ensure familiarity with that process.



