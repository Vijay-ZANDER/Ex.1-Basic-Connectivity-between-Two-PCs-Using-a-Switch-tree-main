## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1898" height="976" alt="Screenshot 2026-10-15 161519" src="https://github.com/user-attachments/assets/24d18b7a-0510-4706-b82b-07bf325d4c30" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Result
<img width="1901" height="781" alt="Screenshot 2026-10-15 161602" src="https://github.com/user-attachments/assets/389f5e1e-dcfd-4b94-b908-7746093cc6b7" />
<img width="1920" height="1080" alt="Screenshot 2026-10-15 161803" src="https://github.com/user-attachments/assets/cf8a3150-6017-4dd3-becf-bfb568307b11" />
<img width="1920" height="1080" alt="Screenshot 2026-10-15 162032" src="https://github.com/user-attachments/assets/aede36be-16fc-4317-b70c-cf4e865c8a31" />
<img width="1920" height="1080" alt="Screenshot 2026-10-15 162041" src="https://github.com/user-attachments/assets/92d9a60d-c541-470a-8dda-f82e4d0308b0" />

# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
