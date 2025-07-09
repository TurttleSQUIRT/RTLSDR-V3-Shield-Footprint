# RTLSDRV3-Shield-Footprint
PCB board library files for Altium and other CAD software to allow you to design addon shields for the RTL-SDR
![image](https://github.com/user-attachments/assets/fd6ce70c-1677-4bbd-b527-4fcff965e1af)

![image](https://github.com/user-attachments/assets/aa98bc9b-8eb1-4ed8-b9b3-725709d26c71)

![image](https://github.com/user-attachments/assets/d12b4875-e1a1-4be7-8d3f-ec59744db6f6)



The current PCB footprint files should work with the RTL SDR V4, but I'm still waiting for mine to arrive to measure it. The pins on the board are labeled for their actual GPIO ports unlike on the SDR PCB. 

You may use any headers you like for the connection to the board, as long as the pitch is 2mm for the GPIO and 1.27 for the clock selector pins,  but the ones I happened to use in the footprint are as follows:
- [FTSH-102-04-L-D](https://www.digikey.com/en/products/detail/samtec-inc/FTSH-102-04-L-D/6691917?gQT=1) 4 Pin Clock
- [2PH1-04-UA](https://www.digikey.com/en/products/detail/adam-tech/2PH1-04-UA/9830490) 4 Pin IO
- [2PH1-07-UA](https://www.digikey.com/en/products/detail/adam-tech/2PH1-07-UA/9830373?_gl=1*1nskp6f*_up*MQ..&gclid=CjwKCAjwprjDBhBTEiwA1m1d0jyHd7EbUyi2BZ6WBnKEdPJ4hO-z-PR6A-W-btdEfwfTODgZfIo14BoCsjEQAvD_BwE&gclsrc=aw.ds&gbraid=0AAAAADrbLljkDSvB-JRU0Ef7sMyKYZog3) 7 Pin IO



Make sure that your pins rise up off the SDR board >6.38 mm as to allow the capacitor, SMA, and USB plug room.

More to this Project is to come, such as a demo board, case 3D models, SDR Pin and programming documentation etc...
