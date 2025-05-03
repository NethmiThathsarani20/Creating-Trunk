# Inter-Switch VLAN Configuration with Trunking
Overview
This repository contains a complete Cisco switch configuration demonstrating:

Multi-switch VLAN implementation

Trunk link configuration

Native VLAN setup

Configuration verification

Switch Configurations
Switch 1 (SW1)
VLANs Created:

VLAN ID	Name
10	HR
20	SALES
30	QA
40	DEV
99	NATIVE
Port Assignments:

Fa0/1-3 → VLAN 10 (HR)

Fa0/4-5 → VLAN 20 (SALES)

Fa0/6-8 → VLAN 30 (QA)

Fa0/15,17 → VLAN 40 (DEV)

Fa0/24 → Trunk port

Switch 2 (SW2)
VLANs Created:

VLAN ID	Name
10	HR
20	SALES
30	QA
40	DEV
99	NATIVE
Port Assignments:

Fa0/5-7 → VLAN 10 (HR)

Fa0/9-10 → VLAN 20 (SALES)

Fa0/11-12 → VLAN 30 (QA)

Fa0/19-21 → VLAN 40 (DEV)

Fa0/24 → Trunk port

Key Features
✔️ End-to-end VLAN configuration across two switches
✔️ Secure trunk configuration with:

Explicit VLAN allowed list (10,20,30,40)

Dedicated native VLAN (99)
✔️ Complete verification commands
✔️ Configuration saving
