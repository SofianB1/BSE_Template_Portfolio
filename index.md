# Windows Unlock Using RFID
I am working on a RFID scanner that will automatically unlock my windows PC for once the RFID card is scanned. This will help me save time so that I do not have to enter my own password, but still the computer is safe.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sofian | The Clinton School | Electrical Engineering | Incoming Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
UNDER CONTRUCTION. 

[![Final Milestone](UNDER CONSTRUCTION){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was to now integrate the RFID scanner into the project. This required soldering pin connectors to my RFID board, wiring the board to my ESP32, and finally implementing the code in order for it to work as my final project. I first wanted to find more information on how an RFID scanner works. RFID scanners are much like barcode scanners, both read information and transmit this information to the computer chip. Barcode scanners use lasers to read information, while RFID scanners use very low-powered radio signals to communicate with a tiny computer chip within an RFID card or tag. This signal can read an ID, which is a set of numbers and letters. This Identification information can be used any way possible with code embedded in the computer itself. This is how I'm using my RFID tag to simply tell the computer I am me and the computer unlocks itself. The unlocking capability is completely within the ESP32 chip, however, the RFID scanner will simply give the go ahead for the code to be run when my card is scanned. The wiring connections that I made between the RFID scanner and the ESP32 were fairly simple, schematics for this were already provided for other boards, so I just had to map out which pins I wanted to use for each corresponding RFID board function. The coding aspect of the final project was not too complex. I already was able to fully open the computer using a push button sketch, therefore all i had to do was adapt the RFID part to the code. This required me to import more libraries in order to use the bluetooth functionality of the ESP32 as a keyboard on my computer. This would allow it to type in the password via bluetooth. I also needed to make sure that I could read my RFID card properly. I did this by coding a short section to display the RFID scanner readings in the serial monitor. Then I can use this information to write in the code itself that my specific card ID means that the process of opening the computer, otherwise, nothing will occur. 


[![Third Milestone](UNDER CONTRUCTION){:target="_blank" rel="noopener"}
# First Milestone
  

My first milestone was functionally getting my button configuration to work with my ESP32. An ESP32 is a micro controller similar to an Arduino that allows me to send signals and power to any parts necessary. This process allowed me to get familiar with working on ESP32 and using the button configuration to carry out a process. At first, I wired an LED light to the button and ESP32 using a breadboard, then focused on writing new code to send signals to my ESP32 using the button which would in turn send power to the LED light. Some issues I encountered in this process were wiring the button, ESP32, and LED/resistors all together. I had to first get familiar with the parts I was using and get a basic understanding of electrical engineering. I then had to learn basic code syntax to write my own code that would allow me to control the LED light using the button. Through the process, I had to learn about Loop statements, If else statements, Indexing, and using variables in my code. Afterwards, I was able to get my LED interacting with my button and ESP32. My next step was to get the ESP32 to interact with my PC’s keyboard via bluetooth. This would work by using the button to send a signal to my ESP32 to indicate when text would be written automatically on my computer. To do this I needed to download keyboard libraries to the ESP32 in order to format the code and connect my ESP32 to my computer via bluetooth in order for it to actually use the computer’s keyboard using the bluetooth function. A library is necessary to use the functionality of the bluetooth keyboard in the ESP32, this library was downloaded from a Github page. I then use my code from the LED and button configuration to adapt the code in order for the button to write text on my computer.

[![First Milestone](UNDER CONSTRUCTION){:target="_blank" rel="noopener"}
