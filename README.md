# Discover

Discover is a Python class designed to facilitate network exploration, analysis, and manipulation tasks. It provides a range of functionalities for tasks such as network scanning, MAC address alteration, and host discovery using ARP and ICMP protocols.

**Key Features:**

1. **Network Data Retrieval:** Retrieve network data including private IP addresses, subnet masks, and network interfaces.
2. **MAC Address Manipulation:** Change MAC addresses of network interfaces, either randomly or specified.
3. **Host Discovery Methods:** Discover hosts using ARP or ICMP protocols, with options for maximum host groups, verbosity, and mapping.
4. **Traceroute and DNS Lookup:** Perform traceroute to trace the route to a destination IP address and perform DNS lookup for domain names.
5. **OS Fingerprinting:** Perform OS fingerprinting on target IP addresses to identify the operating system.
6. **User-Friendly Menus:** Utilize user-friendly menus and input prompts for selecting and executing specific tasks.
7. **Error Handling:** Includes error handling mechanisms to handle unexpected errors gracefully.
8. **Customization:** Customize parameters such as verbosity and file saving options.


**EngineDiscover Subclass:**

The `EngineDiscover` subclass enhances functionality with additional options and refined user input handling. It provides an interactive menu for users to select and execute specific tasks seamlessly.


**Usage:**

The class can be utilized for various network exploration and analysis tasks, offering flexibility and ease of use. It is suitable for both beginner and advanced users seeking to analyze and manipulate network data effectively.


**Contributing:**

Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository, make your changes, and submit a pull request.



### Getting Started

Clone the repository.
    
    git clone https://github.com/kassam-99/Discover.git


Install dependencies

    pip install -r requirements.txt


### Usage Examples


    cd Discover

    python Discover.py
