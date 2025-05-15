# Wireless-Networking-Equipment-Standards-Network-Architecture-and-Case-Studies.

---

## Table of Contents


1.	Introduction to Wireless Networking
	- 1.1. Overview of Wireless Networking Technologies:
2.	Wireless Networking Equipment
3.	Wireless Networking Standards
4.	Cisco Packet Tracer
	- 4.1. Overview
	- 4.2. Implementation of Cisco Packet Tracer for simulating wireless networks.
	- 4.3. Setting up Primary wired LAN using Cisco packet tracer.
	- 4.4. Setting up primary wireless LAN using Cisco packet tracer.
	- 4.5. Configuring access points and wireless LAN controller (WLC).
	- 4.6. Packet Tracer – Project file:
5.	Network Design and Topology
6.	Troubleshooting steps
7.	Future Trends in Wireless Networking
8.	Case Studies and Practical Examples
	- 8.1. Real-world Examples of Wireless Network Deployments:
	- 8.2. Case Studies of Organizations Implementing Wireless Networking Solutions:
	- 8.3. Lessons Learned and Best Practices from Practical Implementations:
9.	Conclusion
10. References

---
 
## List of Figures
- Figure 1 Image of Wired LAN using Cisco Packet Tracer.
- Figure 2 DNS services.
- Figure 3 WLC landing page.
- Figure 4 Setting up LAN controller.
- Figure 5 Making of network and advanced settings.
- Figure 6 Applied the settings.
- Figure 7 Manually powering the LAP.
- Figure 8 LAP gateway was given through DHCP.
- Figure 9 Authentication step.
- Figure 10 Laptops having wireless connections.
- Figure 11 Network topology.

---

## List of Tables
- Table 1 Comparison of Different Wireless Networks.
- Table 2 Network devices and their IP addresses.
- Table 3 Troubleshooting steps.

---
 
1.	Introduction to Wireless Networking
- 1.1.	Overview of Wireless Networking Technologies:

Wireless Networks have become ubiquitous in the world. Some of the examples of wireless networks have been listed below:

![image](https://github.com/user-attachments/assets/dedfb678-99e2-423d-a3de-58b2f06dd1a7)

Table 1 Comparison of Different Wireless Networks (Patel & Suthar, 2019) 

---

2.	Wireless Networking Equipment

Let’s learn more about each type of wireless networking equipment, their functions, features, and examples of popular manufacturers:

#### Wireless Routers:

Function: Wireless routers combine the functionality of a traditional wired router with that of a wireless access point. They facilitate connectivity between devices on a local network and the internet (Panek, 2019; Zhu et al., 2004).

Features:
- Wi-Fi support (802.11 standards).
- Network address translation (NAT) for IP sharing.
- Firewall capabilities for network security.
- Quality of Service (QoS) settings for traffic prioritization (Panek, 2019; Zhu et al., 2004).

Popular Manufacturers: Cisco, TP-Link, Netgear, Asus, and D-Link (Panek, 2019; Zhu et al., 2004).

#### Wireless Access Points (WAPs):

Function: Wireless Access Points provide wireless connectivity to devices within their coverage area, allowing them to connect to a wired network (Deenadhayalan et al., 2023; Panek, 2019; Pearsonhighered.com, 2024; Yumpu.com, 2012).
Features:
- Wi-Fi broadcasting capabilities.
- Multiple SSID support for creating separate wireless networks.
- Power over Ethernet (PoE) support for easy deployment.
- Centralized management for enterprise deployments (Deenadhayalan et al., 2023; Panek, 2019; Pearsonhighered.com, 2024; Yumpu.com, 2012).

Popular Manufacturers: Aruba Networks (HPE), Ubiquiti Networks, Ruckus (now part of CommScope), Cisco Meraki (Deenadhayalan et al., 2023; Pearsonhighered.com, 2024; Yumpu.com, 2012).

#### Wireless Switches:
Function: Wireless switches, also known as wireless LAN controllers, manage multiple access points in large-scale deployments, providing centralized management and control (Deenadhayalan et al., 2023).
Features:
- AP management and configuration.
- Dynamic channel assignment and load balancing.
- Rogue AP detection and mitigation.
- Seamless roaming support for client devices (Deenadhayalan et al., 2023).

Popular Manufacturers: Cisco, Aruba Networks (HPE), Extreme Networks, Juniper Networks (Deenadhayalan et al., 2023).

#### Wireless Range Extenders:
Function: Range extenders amplify and rebroadcast existing Wi-Fi signals, extending the coverage area of a wireless network (Pearsonhighered.com, 2024).
Features:
- Simple setup and configuration.
- Compatibility with various Wi-Fi standards.
- Signal strength indicators for optimal placement.
- Ethernet ports for wired connections (Pearsonhighered.com, 2024).

Popular Manufacturers: TP-Link, Netgear, Linksys, and D-Link (Panek, 2019; Pearsonhighered.com, 2024).

#### Wireless Network Adapters:
Function: Wireless network adapters enable devices without built-in Wi-Fi capability to connect to wireless networks (Pearsonhighered.com, 2024).
Features:
- Compatibility with different Wi-Fi standards.
- USB or PCIe interfaces for connectivity.
- WPA/WPA2 encryption support for security (Pearsonhighered.com, 2024).

Popular Manufacturers: TP-Link, Netgear, Asus, Intel, and Broadcom (Panek, 2019; Pearsonhighered.com, 2024).

#### Wireless Antennas:
Function: Wireless antennas enhance the transmission and reception of wireless signals, improving network coverage and performance (Pearsonhighered.com, 2024).
Features:
- Omni-directional or directional coverage patterns.
- Adjustable gain for signal strength optimization.
- Compatibility with various access points and routers.
- Weatherproof construction for outdoor use (Pearsonhighered.com, 2024).

Popular Manufacturers: Ubiquiti Networks, MikroTik, L-com, Cisco (Pearsonhighered.com, 2024).

---

3.	Wireless Networking Standards

Overview of the IEEE 802.11 standards, also known as Wi-Fi, and their evolution:

- IEEE 802.11 Standards Overview:

IEEE 802.11 is a set of wireless networking standards developed by the Institute of Electrical and Electronics Engineers (IEEE) for wireless local area networks (WLANs) (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

These standards define the protocols and technologies for wireless communication between devices, such as laptops, smartphones, and access points (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

- Evolution of Wi-Fi Standards:

802.11a: Introduced in 1999, 802.11a operates in the 5 GHz frequency band and offers data rates up to 54 Mbps. It provided faster speeds than the earlier 802.11b standard but had a shorter range due to higher frequency (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

802.11b: Also introduced in 1999, 802.11b operates in the 2.4 GHz frequency band and offers data rates up to 11 Mbps. It had a more extended range than 802.11a but slower speeds (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

802.11g: Introduced in 2003, 802.11g operates in the 2.4 GHz frequency band and offers data rates up to 54 Mbps. It maintained compatibility with 802.11b devices while providing faster speeds and improved range (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

802.11n (Wi-Fi 4): Introduced in 2009, 802.11n operates in both the 2.4 GHz and 5 GHz frequency bands and offers data rates up to 600 Mbps (with multiple antennas using MIMO technology). It significantly improved speed and range over previous standards (Pahlavan & Krishnamurthy, 2020; Panek, 2019). 

802.11ac (Wi-Fi 5): Introduced in 2013, 802.11ac operates in the 5 GHz frequency band and offers data rates up to several gigabits per second (Gbps) by utilizing wider channels and more advanced modulation techniques. It further improved speed and performance, especially in crowded Wi-Fi environments (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

802.11ax (Wi-Fi 6): Introduced in 2019, 802.11ax operates in both the 2.4 GHz and 5 GHz frequency bands and offers higher data rates, increased capacity, and improved efficiency compared to previous standards. It introduced features such as Orthogonal Frequency Division Multiple Access (OFDMA) and Target Wake Time (TWT) to enhance performance in high-density deployments (Pahlavan & Krishnamurthy, 2020).

These Wi-Fi standards have evolved over the years to meet the increasing demand for faster speeds, better coverage, and improved efficiency in wireless networks, enabling a wide range of applications across various industries and consumer environments (Pahlavan & Krishnamurthy, 2020; Panek, 2019).

---

4.	Cisco Packet Tracer 

- 4.1.	Overview

Cisco Packet Tracer is a powerful network simulation tool developed by Cisco Systems (Rashid et al., 2019). It is widely used by networking professionals, educators, and students to design, configure, troubleshoot, and experiment with network topologies and protocols in a virtual environment (Rashid et al., 2019).

- 4.2.	 Implementation of Cisco Packet Tracer for simulating wireless networks.

In our project, we have assigned IP addresses to the network devices to implement a wireless network in the Cisco Packet Tracer. In this project, we have used network devices like:

![image](https://github.com/user-attachments/assets/8b529af0-14e4-47ae-9aaf-2737a3965639)

Table 2 Network devices and their IP addresses

- 4.3.	Setting up Primary wired LAN using Cisco packet tracer.

![image](https://github.com/user-attachments/assets/337c3f68-2f6f-4b89-ad2c-9c2d4de2e0a9)

Figure 1 Image of Wired LAN using Cisco Packet Tracer
	
We have used servers like DHCP, DNS, Web server, and E-mail server to provide services like assigning IP addresses, translating human-readable addresses to IP addresses, provide internet services and mailing services, respectively.

We have used two personal computers to check if these services are enabled. DHCP has successfully assigned IP addresses. “River.edu” has been given as a domain name for the address 15.10.1.3. The result of the address is shown below:

![image](https://github.com/user-attachments/assets/0a013f88-851f-49ab-9d2e-64f4ff511f38)

Figure 2 DNS services.

Web services have been enabled to modify the Wireless LAN Controller (WLC), which has the IP address 192.168.1.1.

- 4.4.	 Setting up primary wireless LAN using Cisco packet tracer.

We used PC2 as the staging PC to enable WLC and configure it. Upon giving 192.168.1.1. The WLC landing page has been shown. 

![image](https://github.com/user-attachments/assets/b58e159b-f103-449b-bbcc-c42cb7297207)
 
Figure 3 WLC landing page.

- 4.5.	Configuring access points and wireless LAN controller (WLC).

Upon creating an admin account, the controller setup has been asked, as shown below.

![image](https://github.com/user-attachments/assets/6624f7f6-37ec-4096-a3b2-7107fd20806a)
 
Figure 4 Setting up LAN controller.

![image](https://github.com/user-attachments/assets/6e9619be-5381-4022-9187-f8b3c5ac9b5e)
 
Figure 5 Making of network and advanced settings.

![image](https://github.com/user-attachments/assets/b5d2019e-7744-4233-8616-4a854f0b3dd9)
 
Figure 6 Applied the settings.

The page loads for a certain period after changing the IP address from 192.168.1.1 to 15.10.1.6. This is because we have accessed 192.168.1.1 on the web, which no longer exists. The staging PC can be removed after this process. 

Light Weight Access Point have been given power supply manually by connecting it to an adaptor. Further, the gateway assigning was given through DHCP.

We used wireless laptops and authenticated them. WPA2 – PSK was the authentication mode in our project. A passphrase was given as per the settings made for WLC.

![image](https://github.com/user-attachments/assets/5726cbf1-adcb-43ff-91e6-fbe5ee9687a4)
 
Figure 7 Manually powering the LAP.

![image](https://github.com/user-attachments/assets/1cb27a01-21b6-4454-9dc8-c9653479bf05)
 
Figure 8 LAP gateway was given through DHCP.

![image](https://github.com/user-attachments/assets/ed4d35fc-77cd-4fbe-9e7d-d25d2cdc5485)
 
Figure 9 Authentication step.

![image](https://github.com/user-attachments/assets/350459c0-ba8d-4623-ae95-7e7bc813ce1b)
 
Figure 10 Laptops having wireless connections.

- 4.6. Packet Tracer – Project file:



---
 
5.	Network Design and Topology

We have re-ordered the final structure according to the network topology. For better understanding, we partitioned them as shown in Figure 11.

- 2911 router is a layer three device shown in layer 3.
- Servers are layer two devices and have been shown in layer 2.
- Since the Layer 2 switch has been taken, the switch is taken in Layer 2.
- WLC and LAP are layer two network devices. Hence, they are shown in layer 2.
- PCs and laptops are Layer 2 devices shown in layer 2.

![image](https://github.com/user-attachments/assets/7b2ce889-ecff-4317-9f39-000790d1500a)

Figure 11 Network topology.

---
 
6.	Troubleshooting steps

We have encountered various troubleshooting steps while doing wireless networking through Cisco Packet Tracer. Those troubleshooting steps and solutions are as follows:

![image](https://github.com/user-attachments/assets/d12366f7-53d2-4f5c-825b-7811cb6866d5)

Table 3 Troubleshooting steps.

---

7.	Future Trends in Wireless Networking

New wireless technologies like 5G, Wi-Fi 6E, and IoT are changing how we connect to the internet. 5G is super-fast and can handle many data at once. It is like upgrading from a slow bicycle to a super-fast sports car! With 5G, things like watching videos, playing games, and using virtual reality will be smoother and quicker. Plus, it is excellent for things like self-driving cars, remote healthcare, and making our cities smarter (Wang et al., 2020).

Wi-Fi 6E is like a booster pack for your home internet. It adds extra space to a new frequency band, making your Wi-Fi faster and more reliable, especially if many devices are connected simultaneously. This means you can enjoy things like streaming high-quality videos and using intelligent gadgets around your home without lag or interruptions (Kovtun et al., 2023).

The Internet of Things (IoT) connects everyday objects to the Internet, like your fridge, thermostat, or even your pet's collar (Shafique et al., 2020). These devices need low-power internet connections and can reach far distances (Shafique et al., 2020). Moreover, that is where technologies like narrowband IoT and LTE-M are useful (Ghosh et al., 2019). They help these devices stay connected for a long time without being charged often (Shafique et al., 2020).

We must upgrade our internet infrastructure to make all these remarkable technologies work. This means installing new equipment like base stations, small cells, and Fiber optic cables to handle the faster speeds and more devices. It is like adding more lanes to a highway to accommodate more traffic (Shafique et al., 2020).

As technology evolves, so do the rules and standards governing how devices communicate. Organizations like the 3rd Generation Partnership Project (3GPP) and the Institute of Electrical and Electronics Engineers (IEEE) ensure that all these devices can talk smoothly and securely (Ghosh et al., 2019).

We can do so many exciting things with these new wireless technologies. For example, ultra-reliable low-latency communication (URLLC) can help make self-driving cars safer, massive machine-type communication (mMTC) can make our cities more efficient and enhanced mobile broadband (eMBB) can make our internet even faster (Ghosh et al., 2019; Shafique et al., 2020).

Nevertheless, of course, there are challenges too; things like ensuring everyone has access to high-speed internet, keeping our data safe and private, and managing all the devices connected to the internet are essential things we need to figure out as we move forward with these new technologies (Ghosh et al., 2019; Shafique et al., 2020).

---
 
8.	Case Studies and Practical Examples

- 8.1 Real-world Examples of Wireless Network Deployments:
	1. Smart Cities:
		- Scenario: Imagine a city aiming to become more innovative by deploying a network connecting traffic lights, smart meters, and public Wi-Fi hotspots.
		- Technology: This city might use a mix of Wi-Fi 6, LoRaWAN, and cellular networks based on data requirements and coverage needs.
		- Challenges: The main hurdles include ensuring coverage for all areas, maintaining security, and managing interference from multiple devices.
		- Benefits: By implementing such a network, the city can enjoy improved traffic management, more efficient energy usage, and better experiences for its citizens (Sicari et al., 2019).
	2. Hospitals:
		- Scenario: Consider a hospital needing a reliable network for patient monitoring, staff communication, and secure access to medical records.
		- Technology: For this, a combination of Wi-Fi 6 and a private LTE network could be employed, each serving different needs within the hospital.
		- Challenges: High uptime, HIPAA compliance, and managing device density in critical areas are the key challenges.
		- Benefits: Implementing such a network can lead to enhanced patient care, streamlined workflows, and increased mobility for staff members (Sicari et al., 2019).
	3. Manufacturing Facilities:
		- Scenario: Think of a factory requiring a network for industrial automation, inventory tracking, and machine-to-machine communication.
		- Technology: Depending on latency and reliability requirements, industrial-grade Wi-Fi or private LTE networks might be suitable.
		- Challenges: Real-time performance, rugged environments, and securing industrial control systems pose significant challenges.
		- Benefits: Deploying such a network can boost productivity, minimize downtime, and improve decision-making based on data insights (Sicari et al., 2019).
	4. Educational Institutions:
		- Scenario: Picture a university needing a network for student devices, online learning, and access to research resources.
		- Technology: High-density Wi-Fi 6 could serve well, with the potential for private LTE in specific areas like libraries or research labs.
		- Challenges: Managing many devices, ensuring fair access, and filtering inappropriate content are vital hurdles.
		- Benefits: Implementing such a network can enhance the learning experience, foster collaboration, and provide access to educational resources anytime, anywhere (Sicari et al., 2019).

- 8.2. Case Studies of Organizations Implementing Wireless Networking Solutions:
	1. Google Fiber:
	Google Fiber is renowned for deploying high-speed fiber optic networks, supplemented with Wi-Fi coverage for homes and businesses. They employ mesh Wi-Fi systems for improved coverage and reliability (Google Fiber, 2024).
	2. Marriott International:
	Marriott upgraded its global Wi-Fi network to enhance guest connectivity and offer differentiated services. Challenges included managing diverse devices and ensuring consistent performance across locations (Marriott International, 2024).
	3. Amazon Go:
	Amazon Go utilizes cameras, sensors, and Wi-Fi to enable cashier-less shopping. Their network must be reliable and secure to handle real-time data and transactions (Douglas, 2019).
	4. Tesla:
	Tesla vehicles rely on cellular and Wi-Fi connectivity for software updates, diagnostics, and infotainment features. They prioritize low latency and high security for safe operation (Tesla, 2024).

- 8.3. Lessons Learned and Best Practices from Practical Implementations:
	1. Thorough Planning: Assess needs, budget, and future growth before deploying any solution.
	2. Security First: Implement robust authentication, encryption, and segmentation to protect sensitive data.
	3. Scalability and Flexibility: Choose technologies adaptable to changing needs and device densities.
	4. Optimize Performance: Utilize techniques like channel management and load balancing for optimal performance.
	5. Effective Monitoring and Management: Proactively monitor network performance and address issues promptly for smooth operations.

By following these best practices and learning from real-world examples, organizations can successfully deploy wireless networking solutions tailored to their needs and requirements.

---
 
9.	Conclusion

In wrapping up our project on wireless networking equipment and standards using Cisco Packet Tracer, we have gained valuable insights into how wireless networks work in real-life situations. We created a robust wireless network by setting up a network with wired DHCP, DNS, email, web servers, Cisco 2911 routers, Wireless LAN controllers, and lightweight access points. With two personal computers and two wireless laptops connected smoothly, our network ran without significant problems.

Our project shows just how crucial wireless networking equipment and standards are in today's world of technology. Wireless networks have become crucial for connecting us all, making it easy to chat, share, and access data from anywhere. Using Wi-Fi, DHCP, and DNS, companies can work better, get things done faster, and quickly adapt to changes.

Plus, we have seen how crucial it is to stick to rules and best practices when setting up wireless networks. These rules ensure that all our devices can talk to each other nicely and that our data is kept safe. By following these standards set by big organizations like IEEE and Cisco, companies can keep their networks running smoothly, avoid problems, and make smart investments for the future.

Further, there is a lot more to explore and discover in wireless networking. New technologies like Wi-Fi 6, 5G, and IoT are still growing and changing, offering even faster, stronger, and safer networks. Moreover, exciting stuff like edge computing and AI can improve our networks. We can make our networks even more remarkable by watching these trends and testing new ideas.

To sum up, our project shows how crucial wireless networking is for making our lives and work easier. By using the latest tech and following the rules, companies can do amazing things, connect better, and keep growing in our digital world.

---
 
## References
- Deenadhayalan, P., P Kumar, R., & Reddy, V. C. (2023, August). Functional Segments and Software Defined Trends in Enterprise Networks. ResearchGate. https://www.researchgate.net/publication/372814834_Functional_segments_and_software_defined_trends_in_enterprise_networks

- Douglas, J. (2019, November 12). Amazon Go, the Cashierless Retail Store of the Future, has some new competition. CNBC; CNBC. https://www.cnbc.com/2019/11/12/amazon-go-cashierless-store-of-the-future-has-some-new-competition.html

- Ghosh, A., Maeder, A., Baker, M., & Chandramouli, D. (2019). 5G Evolution: A View on 5G Cellular Technology Beyond 3GPP Release 15. IEEE Access, 7, 127639–127651. https://doi.org/10.1109/access.2019.2939938

- Google Fiber. (2024). Google Fiber | Gigabit Fiber Optic Internet. Fiber.google.com; Google Fiber. https://fiber.google.com/

- Kovtun, V., Altameem, T., Al-Maitah, M., & Kempa, W. (2023, September 11). Information Technology for Maximizing Energy Consumption for Useful Information Traffic in a Dense Wi-Fi 6/6E Ecosystem. MDPI. https://www.mdpi.com/2079-9292/12/18/3847

- Marriott International. (2024). A Breakthrough in Meeting and Event Internet from Marriott. Marriott International. https://www.marriott.com/meeting-event-hotels/meetings/wifi-simplified.mi

- Pahlavan, K., & Krishnamurthy, P. (2020, November 19). Evolution and impact of Wi-Fi Technology and Applications: A historical perspective - international journal of wireless information networks. SpringerLink. https://link.springer.com/article/10.1007/s10776-020-00501-8

- Panek, C. (2019). Networking Fundamentals. In Google Books. John Wiley & Sons. https://books.google.com/books?hl=en&lr=&id=4X21DwAAQBAJ&oi=fnd&pg=PR16&dq=functions+OR+features+OR+802.11+%22Wireless+Networking+standards%22&ots=yIOzU1wpDN&sig=dTbbb3hR8260peFXgNY_sXgR9wI

- Patel, H., & Suthar, F. (2019, February). Overview of Wireless Mesh Network’s in Bluetooth Mesh. ResearchGate. https://www.researchgate.net/publication/351625727_OVERVIEW_OF_WIRELESS_MESH_NETWORK’S_IN_BLUETOOTH_MESH

- Pearsonhighered.com. (2024). Wireless Networking - Higher education | Pearson. pearsonhighered.com. https://www.pearsonhighered.com/assets/samplechapter/0/1/3/1/0131358383.pdf

- Rashid, N. A., Othman, Z. bin, Johan, R. bin, & Sidek, S. bin Hj. (2019, September 25). Cisco Packet Tracer Simulation as Effective Pedagogy in Computer Networking Course. Cisco Packet Tracer Simulation as Effective Pedagogy in Computer Networking Course - Learning & Technology Library 
(LearnTechLib). https://www.learntechlib.org/p/216606/

- Shafique, K., Khawaja, B. A., Sabir, F., Qazi, S., & Mustaqim, M. (2020). Internet of Things (IoT) for Next-Generation Smart Systems: A Review of Current Challenges, Future Trends and Prospects for Emerging 5G-IoT Scenarios. IEEE Access, 8(8), 23022–23040. https://doi.org/10.1109/ACCESS.2020.2970118

- Sicari, S., Rizzardi, A., & Coen‐Porisini, A. (2019). How to Evaluate an Internet of Things System: Models, Case Studies, and Real Developments. Software: Practice and Experience, 49(11), 1663–1685. https://doi.org/10.1002/spe.2740

- Tesla. (2024). Connectivity. Www.tesla.com. https://www.tesla.com/support/connectivity

- Wang, C.-X., Renzo, M. D., Stanczak, S., Wang, S., & Larsson, E. G. (2020). Artificial Intelligence Enabled Wireless Networking for 5G and Beyond: Recent Advances and Future Challenges. IEEE Wireless Communications, 27(1), 16–23. https://doi.org/10.1109/mwc.001.1900292

- Yumpu.com. (2012, November 16). 802.11n Wireless Access Point with PoE. yumpu.com. https://www.yumpu.com/en/document/read/3825377/80211n-wireless-access-point-with-poe

- Zhu, H., Li, M., Chlamtac, I., & Prabhakaran, B. (2004, September). A Survey of Quality of Service in IEEE 802.11 Networks. ResearchGate. https://www.researchgate.net/publication/3435990_A_survey_of_quality_of_service_in_IEEE_80211_networks

---

## Author
*Deepak Yelleti* (Student ID: A0000074884)  
CS553AH1: Networking Technologies, Rivier University  
Professor: Daniel Ward  
Date: February 27, 2024

---
