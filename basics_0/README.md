# Networking Basics

This project is designed to help you understand the basics of computer networking, specifically focusing on the OSI model, network types, IP addresses, and protocols such as TCP and UDP. It also includes practical tasks to work with network ports and connectivity.

## Requirements

### General
- **Allowed editors**: `vi`, `vim`, `emacs`
- All Bash script files will be interpreted on **Ubuntu 20.04 LTS**
- All files should end with a **new line**
- A `README.md` file at the root of the project folder is **mandatory**
- All Bash script files must be **executable**
- Bash scripts must pass **shellcheck** without any error
- The first line of all Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what the script does

### More Info
- For multiple-choice question tasks, just type the number of the correct answer in your answer file, adding a new line for every new answer.

## Tasks

### 0. OSI Model
- **File**: `0-OSI_model`
- **Description**: Answer the following questions about the OSI model:
  1. What is the OSI model?
     - Options:
       - Set of specifications that network hardware manufacturers must respect
       - The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
       - The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology
  2. How is the OSI model organized?
     - Options:
       - Alphabetically
       - From the lowest to the highest level
       - Randomly

### 1. Types of Network
- **File**: `1-types_of_network`
- **Description**: Answer the following questions about types of networks:
  1. What type of network is a computer in a local network connected to?
     - Options: Internet, WAN, LAN
  2. What type of network could connect an office in one building to another office a few streets away?
     - Options: Internet, WAN, LAN
  3. What network do you use when you browse www.google.com from your smartphone (not connected to Wi-Fi)?
     - Options: Internet, WAN, LAN

### 2. MAC and IP Address
- **File**: `2-MAC_and_IP_address`
- **Description**: Answer the following questions about MAC and IP addresses:
  1. What is a MAC address?
     - Options: The name of a network interface, The unique identifier of a network interface, A network interface
  2. What is an IP address?
     - Options: Is to devices connected to a network what postal address is to houses, The unique identifier of a network interface, Is a number that network devices use to connect to networks

### 3. UDP and TCP
- **File**: `3-UDP_and_TCP`
- **Description**: Answer the following questions about UDP and TCP:
  1. Which statement is correct for the TCP box?
     - Options:
       - It is a protocol that is transferring data in a slow way but surely
       - It is a protocol that is transferring data in a fast way and might lose data along in the process
  2. Which statement is correct for the UDP box?
     - Options:
       - It is a protocol that is transferring data in a slow way but surely
       - It is a protocol that is transferring data in a fast way and might lose data along in the process
  3. Which statement is correct for the TCP worker?
     - Options:
       - Have you received boxes x, y, z?
       - May I increase the rate at which I am sending you boxes?

### 4. TCP and UDP Ports
- **File**: `4-TCP_and_UDP_ports`
- **Description**: Write a Bash script that displays listening ports:
  - It should only show listening sockets.
  - It should show the PID and name of the program to which each socket belongs.
  - Example:
    ```
    sudo ./4-TCP_and_UDP_ports
    ```

### 5. Is the Host on the Network
- **File**: `5-is_the_host_on_the_network`
- **Description**: Write a Bash script that pings an IP address passed as an argument:
  - Accepts a string as an argument.
  - Displays `Usage: 5-is_the_host_on_the_network {IP_ADDRESS}` if no argument is passed.
  - Pings the IP 5 times.
  - Example:
    ```
    ./5-is_the_host_on_the_network 8.8.8.8
    ```

## Repository

- **GitHub repository**: `holbertonschool-network`
- **Directory**: `basics_0`
