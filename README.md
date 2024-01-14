## Server Rack (Main)

### Powerstrip - Model: PDBC10

1. Cable Modem
   - Description: Internet gateway device.
   - Connection: Eero 6 Pro

2. Eero 6 Pro
   - Description: Home Wi-Fi router.
   - Connection: Rapink Patch (RP) 01 > Juniper (J) 00

3. Raspberry Pi (PiHole)
   - Description: Ad-blocking DNS server.
   - Connection: RP05 > J08

4. Cisco ASA
   - Description: Firewall and network security appliance.
   - Connection: RP06 > J12

5. NAS (lil NAS)
   - Description: Network-attached storage for personal files.
   - Connection: RP04 > J06

6. Zigbee Hub
   - Description: Hub for Zigbee smart home devices.
     - Manages and controls Zigbee-compatible devices such as smart lights, sensors, and switches.
   - Connection: RP06 > J10

7. Bottom rack PSU
   - Description: 6 port PSU
   - Connection: N/A

8. NAS (NAS boy)
   - Description: Another NAS for additional storage needs.
   - Connection: RP03 > J04

### Powerstrip - Model: Kleen

1. Switch - Trendnet Teg-5916Dg
   - Description: Network switch.
   - Connection: Not Used

2. Switch - Juniper ex2200
   - Description: Main network switch.
   - Connection: N/A

3, 4. Server: Dell (Winserver 01)
   - Description: [Placeholder]
   - OS: [Placeholder]
   - Roles: [Placeholder]
   - Connection: 

5. TP-Link Managed Switch
   - Description: Managed Network Switch
   - Connection: Not Used

6. Lightify Hub
   - Description: Light Controller
   - Connection: Kitchen cabinet lighting

### Powerstrip - Model: Unknown

1. DVR - Amazon ReCast
   - Description: Digital Video Recorder for over-the-air TV.
   - Connection: RP05 > J09

### 48-port Juniper Switch (J48)
   - Description: High-density network switch with 48 ports.
     - Used for connecting various devices in the network.
   - Connections:
        - [0] Eero Pro 6
        - [1] Windows PC (core)
        - [2] NASboy
        - [4] lil NAS
        - [5] Raspberry PI
        - [6] Zigbee
        - [7] Cisco ASA
        - [8] XBox One S
        - [9] Amazon ReCast
        - [22] Google Voice
