# Isolated TTL to RS485 converter - SCHEMATIC and PCB
RS485 is a most used wired communication for industrial purposes. In many cases we need a solution to isolated or internal circuit from RS bus. To this aim I put a simple and cheep circuit using optocouplers to isolate TTL side from RS bus. Also because the power of circuit supplied by RS bus, it is a good solution to use in low power or battery devices connecting to RS485 bus.  
  
  On the other hand, in many usage we have just a TX and RX for serial port and there is no extra pin to control transmission direction. So this circuit work appropriately in this limitation.  
  
The PCB designed in 1 layer and components used in this circuit are followed in below:   

| # | Component | Value | Footprint | Qty |
| --- | --- | --- | --- | --- |
| 1 | Cap | 100nF | 1206 | 1 |
| 2 | Tantal_Cap | 10uF 25v | CaseB | 1 |
| 3 | Tantal_Cap | 10uF 16v | CaseB | 1 |
| 4 | TVS_Diode | SMBJ12A | DO-214AA | 2 |
| 5 | Res | 10 | 1206 | 2 |
| 6 | Res | 100 | 1206 | 2 |
| 7 | Res | 1k | 1206 | 2 |
| 8 | Res | 10k | 1206 | 2 |
| 9 | LDO_Regulator | HT7550 | SOT-89 | 1 |
| 10 | Fast_Optocoupler | 6N136 | DIP-8 | 2 |
| 11 | Zener_Diode | 18v | miniMelf | 1 |
| 12 | Terminal |  |  | 1 |

# PCB
![SCH](https://user-images.githubusercontent.com/50070107/170229342-8c6d5eee-4557-4498-86ea-c550a7db20b3.jpg)
# SCHEMATIC
![PCB](https://user-images.githubusercontent.com/50070107/170229902-f03b6b1a-70ce-423b-8c16-67337aa52625.jpg)
