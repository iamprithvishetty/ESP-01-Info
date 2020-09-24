# ESP-01-Info
Here all the information related to Esp-01 is provided

# 1) Unzip the Esp_Flasher

# 2) Download the bin file of any one of the firmware

# 3) Open Arduino IDE and upload BareMinimum in Arduino 

i.e 
void setup()
{

}

void loop()
{

}

# 4) Open the datasheet and make the aprropriate connection (UART MODE) 

#    Esp-01 to Arduino Connections

#    Vcc => 3.3V // GND => GND // GPIO0 => GND  // GPIO2 => 3.3V
#    CS => 3.3V  // TXD => TX  //  RXD => RX

# 5) Select the appropriate firmware bin file and COM-PORT in Flasher.exe and Download

# 6) Once flashing done i.e (99% and some error neglect) remove GPIO0 set Baud rate 9600 or 115200 and type AT

