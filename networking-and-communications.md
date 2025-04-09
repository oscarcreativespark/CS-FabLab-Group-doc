---
description: https://academy.cba.mit.edu/classes/networking_communications/index.html
---

# Networking and communications

💡Group assignment

* Send a message between two projects
* Document your work to the group work page and reflect on your individual page what you learned

***

### About this week <a href="#id-19caf66e-e64e-80b8-84d4-ed596f48b527" id="id-19caf66e-e64e-80b8-84d4-ed596f48b527"></a>

> _Briefly describe the goal of the assignment. What are you characterizing, testing, or exploring_

For this week we are sending a input from one project over TXRX to another project

The input device is Carls linear pot module for a FabXiao.

***

### Tools and materials used <a href="#id-19caf66e-e64e-80c5-a554-f0cbeb7653e5" id="id-19caf66e-e64e-80c5-a554-f0cbeb7653e5"></a>

> _List all the machines, software and materials used in this assigment._

* Thonny
* Fab Xiao (RP2040)
* Thoms Dev board (RP Pico)
* Circuit Python

***

### Process and methodology <a href="#id-19caf66e-e64e-80a2-ab2d-fc20f3d842b3" id="id-19caf66e-e64e-80a2-ab2d-fc20f3d842b3"></a>

> Describe step-by-step what the group did. Include sketches, screenshots, or videos if possible.

#### Transmision:

For the transmitting board we used the following code in CircuitPython to send a UART over the TX and TX pins on our devices.

```
import board
import busio
import digitalio
import analogio
import time

# Set up UART on TX=GD6, RX=D7 (we only use TX here)
uart = busio.UART(tx=board.TX, rx=board.RX, baudrate=9600)

# Set up a pot on analog pin A0
pot = analogio.AnalogIn(board.A0)

center = 65535/2 # The center of the pot
neutral_zone = 10000 # Area on pot where there is no input

while True:
    
    pot_value = pot.value
    deviation = pot_value - center

    print(pot_value)

    if abs(deviation) > neutral_zone: 
        
        if deviation > 0:
            uart.write(b'PRESSED\n')
            print("Sent: PRESSED")
    time.sleep(1)


```

#### Recieve



***

### Group conclusions <a href="#id-19caf66e-e64e-8061-b14c-fb82b8c7a6c0" id="id-19caf66e-e64e-8061-b14c-fb82b8c7a6c0"></a>

> **Findings:** \[What did you learn from the process?]

> **Challenges:** \[What issues did you encounter?]

> **Solutions:** \[How did you solve them?]

Type here

***

### Files <a href="#id-19caf66e-e64e-80a4-95e3-f86c8ad668db" id="id-19caf66e-e64e-80a4-95e3-f86c8ad668db"></a>

> Add all files created for this group assignment

See below link to to files created this week:
