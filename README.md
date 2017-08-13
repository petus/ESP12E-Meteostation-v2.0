# ESP12E-Meteostation-v2.0<br>
(english language) https://time4ee.com, https://time4ee.com/articles.php?article_id=48<br>
(czech language) https://chiptron.cz, https://chiptron.cz/articles.php?article_id=113<br>
Mini meteostation with ESP12E (ESP8266, NodeMCU)<br>

Mini meteostation contains 4x 4pin headers for I2C sensors and one analog header for connecting of analog sensor like CO2 sensor.<br>

PCB is designed in eagle.<br>
The platic box is KM-27 and 3D case will be available asap.<br>
<br>
Uploading of code:<br>
Meteo board | USB-UART bridge<br>
RESET -> DTR<br>
TX -> RX<br>
RX -> TX<br>
FLASH -> GND<br>
<br>
Choose NodeMCU 1.0 board in Board manager, upload the code.<br>
<br>
Connecting of I2C sensor:<br>
Meteo board | I2C sensor<br>
\+ -> VCC (3.3V)<br>
c -> SCL<br>
d -> SDA<br>
no label -> GND<br>
<br>
And power supply of course.<br>
<br>
The meteo board can be powered by mini USB connector, 3.3V pin header or external power supply (up to 16V)<br>
<br>
If you want to use sleeping mode of the ESP12E, solder SJ1 jumper (GPIO16 and RESET pin)
