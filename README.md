#<IMG SRC="https://raw.githubusercontent.com/downtrodden/monitor/gh-pages/flame.gif" HEIGHT="75" BORDER="1"><IMG SRC="https://raw.githubusercontent.com/downtrodden/monitor/gh-pages/M590_Arduino_small.jpg" HEIGHT="150" BORDER="1"><IMG SRC="https://raw.githubusercontent.com/downtrodden/monitor/gh-pages/flame.gif" HEIGHT="75" BORDER="1"> M590 Serial SMS Gateway

<strong>M590 GPRS</strong> Breakout Module with <strong>ESP8266</strong> and <strong>Arduino</strong> sketches.

The only Library used is Software Serial......

The most reliable power source is a LIPO, any cheap Power Bank (2.1A IPAD Type)

Try a Different SIM if there is repeated failure to AT+CCID...

Modify the a, b, c & d Sections to provide flags for the main loop
to provide PWM, WS2812 or whatever you need....

Read a sensor and reply with a data value.....

Send SMS containing #e0 to read sensor and recieve a reply with the data.... 

Send SMS containing #e1 to clear SMS
