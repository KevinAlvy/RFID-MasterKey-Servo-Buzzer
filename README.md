# RFID-MasterKey-Servo-Buzzer
The code to run the "MasterKey" command uses the RFID Tag/Card as the Masterkey to add or remove the key into the eeprom

<body>
<h2>💻 Local testing</h2>
<ol>
    <li>Download <code>RFID_Masterkey_Servo_Buzzer.ino</code></li>
    // <a>For RFID RC522-----------------------------------------------------------------------------------</a>
    <li>Connect <code>Pin 3.3v</code> of the Arduino to the <code>3.3v</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin 9</code> of the Arduino to the <code> RST</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin 10</code> of the Arduino to the <code> SDA</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin 11</code> of the Arduino to the <code> MOSI</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin 12</code> of the Arduino to the <code> MISOI</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin 13</code> of the Arduino to the <code> SCK</code> of a RFID RC522 Module</li>
    <li>Connect <code>Pin GND</code> of the Arduino to the <code> GND</code> of a RFID RC522 Module</li>
    // <a>For Active Buzzer--------------------------------------------------------------------------------</a>
    <li>Connect <code>Pin 5v</code> of the Arduino to the <code>VCC</code> of a Active Buzzer Module</li>
    <li>Connect <code>Pin 4</code> of the Arduino to the <code>I/O</code> of a Active Buzzer Module</li>
    <li>Connect <code>Pin GND</code> of the Arduino to the <code>GND</code> of a Active Buzzer Module</li>
    // <a>For Servo----------------------------------------------------------------------------------------</a>
    <li>Connect <code>Pin 5v</code> of the Arduino to the <code>VCC</code> of a Servo</li>
    <li>Connect <code>Pin 8</code> of the Arduino to the <code>I/O</code> of a Servo</li>
    <li>Connect <code>Pin GND</code> of the Arduino to the <code>GND</code> of a Servo</li>
    // <a>For LiquidCrystal_I2C lcd(0x27, 16, 2)-----------------------------------------------------------</a>
    <li>Connect <code>Pin 5v</code> of the Arduino to the <code>VCC</code> of a LCD I2C 16*2</li>
    <li>Connect <code>Pin SDA</code> of the Arduino to the <code>SDA</code> of a LCD I2C 16*2</li>
    <li>Connect <code>Pin SCL</code> of the Arduino to the <code>SCL</code> of a LCD I2C 16*2</li>
    <li>Connect <code>Pin GND</code> of the Arduino to the <code>GND</code> of a LCD I2C 16*2</li>
    // <a>For Button---------------------------------------------------------------------------------------</a>
    <li>Connect <code>Pin 5v</code> of the Arduino to the <code>VCC</code> of a Button</li>
    <li>Connect <code>Pin 3</code> of the Arduino to the <code>I/O</code> of a Button</li>
    <li>Connect <code>Pin GND</code> of the Arduino to the <code>GND</code> of a Button</li>
    <li><code>Upload</code> the sketch and enjoy!</li>
</ol>
<h2>😎 Virtual testing</h2>
<ol>
    <li>Don't have an Arduino with you right now? No worry. You can test it virtually on my <a>simulated TinkerCAD circuit</a></li>
    <li>Click <code>Simulate</code></li>
    <li>Click <code>Start Simulation</code> and enjoy!</li>
<ol>
</body>
