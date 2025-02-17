# **Oled_eye_display**

![face](https://github.com/user-attachments/assets/fac3c497-b126-4b15-934c-a5b5d02c642e)


The Oled Eye Display project serves to enhance user interaction by providing visual feedback in an engaging manner. This display features graphic representations of eyes that are capable of blinking, looking upward and downward, and displaying various emotions such as amusement and annoyance. The project employs Arduino technology to create basic geometric shapes, including rounded squares and triangles, that simulate the appearance of eyes. A tutorial video accompanies this project, offering a comprehensive guide to each step outlined on this page, ensuring clarity and accessibility for all users.

### **CONNECTIONS:**

The connection of the Arduino to the display is relatively straightforward, and it is crucial to emphasize that the display operates on a 3V power supply; thus, it should not be connected to the 5V pin. We adhered to the pinout recommended by the Adafruit_SSD1306 library for the I2C connection, as detailed below:

Arduino - Display  
3V3 - VCC  
GND - GND  
A5 - SCL  
A4 - SDA  

This configuration creates the wiring shown in the following figure.

![OLED+Circuit](https://github.com/user-attachments/assets/8371b00d-f419-4a5d-b26e-6abb420c53ed)

### **UPLOADING THE CODE**
