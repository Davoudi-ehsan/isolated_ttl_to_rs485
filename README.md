# Isolated TTL to RS485 convertor - SCHEMATIC and PCB
RS485 is a most used wired communication for industrial purposes. In many cases we need a solution to isolated or internal circuit from RS bus. To this aim I put a simple and cheep circuit using optocouplers to isolate TTL side from RS bus. Also because the power of circuit supplied by RS bus, it is a good solution to use in low power or battery devices connecting to RS485 bus.  
  
  On the other hand, in many usage we have just a TX and RX for serial port and there is no extra pin to control transmission direction. So this circuit work appropriately in this limitation.  
  
The PCB designed in 1 layer and components used in this circuit are followed in below:  
- Cap&emsp;&emsp;&emsp;&emsp;&emsp;100nF&emsp;&emsp;1206&emsp;&emsp;&emsp;1
- TantalCap&emsp;&emsp; 10uF-16v&emsp;caseB&emsp;&emsp; 1
- TantalCap&emsp;&emsp; 10uF-25v&emsp;caseB&emsp;&emsp; 1
- TVS&emsp;&emsp;&emsp;&emsp;&emsp;SMBJ12A&emsp;&emsp;&emsp;&emsp;&emsp; 2
- Res&emsp;&emsp;&emsp;&emsp;&emsp;10&emsp;&emsp;&emsp;&emsp;1206&emsp;&emsp;&emsp;2
- Res&emsp;&emsp;&emsp;&emsp;&emsp;100&emsp;&emsp;&emsp;&emsp;1206&emsp;&emsp;2
- Res&emsp;&emsp;&emsp;&emsp;&emsp;1k&emsp;&emsp;&emsp;&emsp;1206&emsp;&emsp;&emsp;2
- Res&emsp;&emsp;&emsp;&emsp;&emsp;10k&emsp;&emsp;&emsp;&emsp;1206&emsp;&emsp;2
- Regulator&emsp;&emsp; HT7550&emsp;&emsp;SOT-89&emsp;1
- Optocoupler&emsp;6N136&emsp;&emsp;DIP-8&emsp;&emsp;2
- Zener_diode&emsp;18v&emsp;&emsp;&emsp;miniMelf&emsp;1  

# PCB
![SCH](https://user-images.githubusercontent.com/50070107/170229342-8c6d5eee-4557-4498-86ea-c550a7db20b3.jpg)
# SCHEMATIC
![PCB](https://user-images.githubusercontent.com/50070107/170229902-f03b6b1a-70ce-423b-8c16-67337aa52625.jpg)
