# Computer controlled cutting

💡 Group assignment

* Do your lab’s safety training
* Characterize your lasercutter’s focus, power, speed, rate, kerf, joint clearance and types.
* Document your work to the group work page and reflect on your individual page what you learned.&#x20;

***

## About this week

> _Briefly describe the goal of the assignment. What are you characterizing, testing, or exploring_

Part one of this week is to work together as a group to build the skills to use the machines effectively, safely and to characterize there properties.

***

## Tools and materials used

> _List all the machines, software and materials used in this assigment._

* [Grashopper](https://www.grasshopper3d.com/)
* [Fusion 360](https://www.autodesk.com/eu/products/fusion-360/)
* [Inkscape](https://inkscape.org/)
* [Beam Studio](https://www.fluxlasers.com/beam-studio/)
* [Inkscape](https://inkscape.org/)

***

## Process and methodology

> Describe step-by-step what the group did. Include sketches, screenshots, or videos if possible.

### **1. Safety Induction**

The induction that we were given for this class was the same standard induction that members of the FabLab would get. The key goals are to understand how the laser can create unsafe situations and what to do when those situations arise. As a rule we try to pull from manufacturers recommendations, in the guide below we were guided buy \[Flux]\([https://support.flux3dp.com/hc/en-us/articles/333757063556-FLUX-Safety-Precautions#:\~:text=- Do not leave the machine,the laser light during operation.)](https://support.flux3dp.com/hc/en-us/articles/333757063556-FLUX-Safety-Precautions) who have complied some nice concise guidelines.

1. General Safety Precautions

✔ Read the Manual – Always review the manufacturer’s instructions before operating. ✔ Use in a Well-Ventilated Area – Ensure proper airflow and fume extraction to prevent inhalation of hazardous fumes. ✔ Know Emergency Procedures – Familiarize yourself with emergency stop functions, fire extinguishers, and first aid kits.

1. Personal Protective Equipment (PPE)

✔ Safety Glasses – Use laser safety glasses if operating an open-lid machine. ✔ Gloves (Optional) – Wear gloves when handling materials but NOT while operating the machine (loose gloves can get caught). ✔ Mask/Respirator – If working with materials that emit strong fumes, wear a respirator suited for fumes/particulates.

1. Machine Setup & Pre-Operation Checks

✔ Inspect the Machine – Check for damaged components, frayed cables, or misaligned laser lenses. ✔ Clean the Work Area – Remove debris and flammable materials from the laser bed. ✔ Check Ventilation & Air Assist – Ensure the exhaust fan and air assist are functioning properly.

1. Approved & Prohibited Materials

✔ Approved Materials – Wood, acrylic, paper, leather, fabric, cardboard, certain plastics. ❌ Prohibited Materials – PVC, vinyl, polycarbonate, fiberglass, coated metals, and materials that produce toxic fumes.

1. Operating the Laser Cutter

✔ Never Leave the Machine Unattended – Always monitor during operation. ✔ Secure the Material – Ensure the work piece is flat and properly positioned to prevent movement.

✔ Use Proper Settings – Match power, speed, and frequency settings to the material type and thickness.

1. Fire Prevention & Emergency Procedures

🔥 Stay Alert for Fires – If flames persist for more than a few seconds, stop the job immediately and smother fire with fire blanket. 🧯 Fire Extinguisher Nearby – Use a CO₂ or dry chemical extinguisher if needed. Do NOT use water. ⚡ Emergency Shutoff – Know how to quickly power down the machine in case of a malfunction.

1. Post-Operation Maintenance

✔ Allow Cooling Time – Wait before removing materials to avoid burns. ✔ Clean the Work Area – Remove any leftover debris to prevent fire hazards. ✔ Check & Clean Components – Regularly clean the lens, mirrors, and exhaust system.

### **2. Characterize**

#### **Speed and Power**

The key learning outcomes from the below is the relationship between power and speed and how they affect a cut. For a given result often possible to get what you need by holding one constant and reducing the variables to just one. For example on most of our lasers power will max out before speed so keeping power at the highest safe level and then using spread as you key variable for dialing in your depth of cut has been a key learning. See some experimentation below from our group assignment.

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-1.jpeg)

_Material testing_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-2.jpeg)

_Open Beam Studio_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-3.jpeg)

_Use camera tool to scan bed_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-4.jpeg)

_In this example we are using some of beam studios build in test cards_

_The x-axis represents increasing power and the y-axis represents increasing speed_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-5.jpeg)

_We place the test card on the stock in the machine_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-6.jpeg)

_This has set all the layers to control the laser power and speed for each square_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-7.jpeg)

_After sending the program analyses the vectors and create a tool path_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-8.jpeg)

_We hit start and the laser starts its work_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-9.jpeg)

_Examples in a few materials_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-10.jpeg)

_Repeat the process for the engravings_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-11.jpeg)

_Click through_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-12.jpeg)

_And start the job_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-13.jpeg)

_Examples in a few materials_

![](https://fabacademy.org/2025/labs/creativespark/students/carl-mcateer/images/w3/w3-sc3-9.jpeg)

***

## Group conclusions

> **Findings:** \[What did you learn from the process?]

> **Challenges:** \[What issues did you encounter?]

> **Solutions:** \[How did you solve them?]

Understanding the how and why of the laser has been the key for dealing with novel situations when they arise and also bringing jobs to the next level in terms of fit and finish. Understanding kerf in particular is a key factor in gaining control as to how your parts go together.

***

## Files

See below link to to files created this week:

[Kerf\_fit\_test.zip](attachment:fa143099-59b4-408d-a68f-fd5d41aa57d2:Kerf_fit_test.zip)
