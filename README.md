# ModbusTCP2MQTT
Sungrow &amp; SMA Solar Inverter addon for Home Assistant
This addon will connect directly to your Inverter using ModbusTCP/MobusWebTCP

<img src="images/diagram.gif"/>

## Support models
**The Inverter must be accessible on the network using TCP.**

### PV Grid-Connected String Inverters
SG30KTL, SG10KTL, SG12KTL, SG15KTL, SG20KTL, SG30KU, SG36KTL, SG36KU, SG40KTL, SG40KTL-M, SG50KTL-M, SG60KTL-M, SG60KU, SG30KTL-M, SG30KTL-M-V31, SG33KTL-M, SG36KTL-M, SG33K3J, SG49K5J, SG34KJ, LP_P34KSG, SG50KTL-M-20, SG60KTL, SG80KTL, SG80KTL-20, SG60KU-M, SG5KTL-MT, SG6KTL-MT, SG8KTL-M, SG10KTL-M, SG10KTL-MT, SG12KTL-M, SG15KTL-M, SG17KTL-M, SG20KTL-M, SG80KTL-M, SG111HV, SG125HV, SG125HV-20, SG30CX, SG33CX, SG36CX-US, SG40CX, SG50CX, SG60CX-US, SG110CX, SG250HX, SG250HX-US, SG100CX, SG100CX-JP, SG250HX-IN, SG25CX-SA, SG75CX, SG3.0RT, SG4.0RT, SG5.0RT, SG6.0RT, SG7.0RT, SG8.0RT, SG10RT, SG12RT, SG15RT, SG17RT, SG20RT

### PV Grid-Connected String Inverters Gen 2
SG5K-D, SG8K-D

### Residential Hybrid Inverters
SH5K-20, SH3K6, SH4K6, SH5K-V13, SH5K-30, SH3K6-30, SH4K6-30, SH5.0RS, SH3.6RS, SH4.6RS, SH6.0RS, SH10RT, SH8.0RT, SH6.0RT, SH5.0RT


## Installation
1. Navigate in your Home Assistant frontend to Supervisor -> Add-on Store.
2. Click the 3-dots menu at upper right ... -> Repositories and add [https://github.com/TenySmart/HassioAddon](https://github.com/TenySmart/HassioAddon)
3. Install ModbusTCP2MQTT Addon
4. Configure and Start it

## Meta
  
This add-on is based on [SunGather](https://github.com/bohdan-s/SunGather)
