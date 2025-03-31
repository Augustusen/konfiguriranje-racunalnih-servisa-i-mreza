# Network Configuration and Services Setup

This project demonstrates the configuration of static IP addresses, dynamic IP addresses using DHCP, and network services across different networks using Cisco Packet Tracer. The project also includes the integration of IoT devices within a network for smart control and management.

## How it Works:

### 1. Configuration of Static IP Addresses in NETWORK 2 and NETWORK 3:
Static IP addresses are manually configured for devices in NETWORK 2 and NETWORK 3 to ensure stable communication within the networks. NETWORK 2 uses the address range 192.168.2.0, and NETWORK 3 uses 192.168.3.0.

- Example static IPs for NETWORK 3:
  - **PC5**: 192.168.3.2 255.255.255.0
  - **PC6**: 192.168.3.3 255.255.255.0
- **Default Gateway**: 192.168.3.1 (Router R3)

### 2. DHCP Configuration in NETWORK 1:
A DHCP server is used to dynamically assign IP addresses to devices in NETWORK 1. Devices automatically receive IP addresses, gateway, and DNS settings.

- Example DHCP configuration:
  - **Pool Name**: serverPool
  - **Start IP Address**: 192.168.1.1
  - **Subnet Mask**: 255.255.255.0
  - **Default Gateway**: 192.168.1.1
  - **DNS Server**: 8.8.8.8 (Google DNS)

### 3. IoT Devices Integration:
NETWORK 1 is connected to IoT devices through a wireless Access Point (AP). Mobile and IoT devices can communicate via the AP and be controlled from the network.

### 4. Serial Connections Between Routers:
Routers R1, R2, and R3 are connected via serial connections, enabling communication between different networks.

- Example IP configuration for serial interfaces:
  - **R1 to R2**: 11.0.0.2
  - **R2 to R3**: 10.0.0.2

### 5. IoT Server and Mobile Device Control:
The IoT Server allows centralized management of IoT devices (e.g., motion sensors, thermostats, cameras). A mobile device, connected to the network, can control these devices via the IoT Monitor app.

### 6. Motion Detection and Thermostat Settings:
The motion detector and thermostat are key IoT devices in the network. The motion detector activates lights when motion is detected, while the thermostat adjusts temperature based on pre-set values.

---

## Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/Augustusen/konfiguriranje-racunalnih-servisa-i-mreza.git
