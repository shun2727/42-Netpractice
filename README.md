_This project has been created as partof the 42 curriculum by syee_
# NetPractice

## Description 
Netpractice is an activity desgned to intorduce the basics of  **computer networking**. In this activity i will lean how to configure **IP addresses**, **connect devices** though a **router** and understand the role of a **gateway**.

There conists of **10 networking** problems presented in the form of levels.  

## Instructions
Steps to run the activity in the form of a web page :

1. download the .tar file provided in the subject page and extract to a folder 
2. Within the folder "NetPractice" open termonal and run ```./run.sh```
3. The interface will be available on the browser
![net_practice_login_page](net_practice_login.png)
4. enter the credentials and start 

## Resources
_The following section will addreses the concepts learnt and the sources accessed for the materials_

### TCP/IP addressing
There are 
> CIDR : Classless Inter-Domian Routing, a system used to efficiently allocate IP addressses and group them together

|CIDR |	Subnet Mask |	Usable IPs |	Comment |
|-----|-------------|--------------|------------|
|/8  |	255.0.0.0 	|	16,777,214 |	Very large (Class A) network|
|/16 |	255.255.0.0 |	65,534		|Large (Class B) network|
|/24 |	255.255.255.0 |	254			|Common for small networks|
|/30 |	255.255.255.252 |	2		|	Used for point-to-point links|
|/32 |	255.255.255.255	|1			|Represents a single IP address|
- public IP
- private IP range :


### Subnet masks
- explaination : if same subnet mask == same network 
- how to calculate subnet masks

### default gateways
-

---
### Routers
- Devices that route packet to 

### Switches
What is a network switch ?
	- 
Types of switches include :
	1. L2 (layer 2 switch)
	2. L3 (Layer 3 switch)
source : https://www.cloudflare.com/learning/network-layer/what-is-a-network-switch/

#### Differences of switches and Routers

--- 
### OSI layers : Open systems interconneciton 
Purpose of the layers are to transmit raw bits from physical hardware to an interface over the internet.

#### Layers (7) low to highest:
Acrostic to memorize : A Priest Saw Two Nuns Doing Push-ups
1. Physical : 

2. Datalink : takes raw bits and organizes it into **frames**. (frame : a unit of data transmission (data packet) in OSI model consisting of header, payload and trailer)
	- Handles : 
		- Framing (organizing raw bits into frames)
		- MAC addressing (source/destination) (in header)
		- Error detection/correction (in trailer)
		- Encoding/decoding
	- Contents of a frame :
		- header : usually just MAC address (src and dest)
		- payload : actual data, can be anything
		- trailer : extra infromation added at the end of the frame 
	
		![frame simplified](frames_simplified.png)
	- Examples of frame : 
		```
		ethernet frame
		[Dest MAC | Source MAC] | Payload | trailer
		```
		```
		WIFI frame 
		[Dest MAC | Source MAC | BSSID | Seq No.] | Payload | trailer
		```

	> all frames have the same format (3 items), there are different types of frames (ethernet , wifi). All frames will get sent out eventualy, subsequently one by one. 

	source for frame content : (https://www.slideshare.net/slideshow/framing-in-data-link-layer-136604265/136604265#2)
	
	source : (https://www.geeksforgeeks.org/computer-networks/data-link-layer/)

3. Network : 
4. Transport
5. Session 
6. Presentation
7. Application

source : https://www.fortinet.com/resources/cyberglossary/osi-model

### TCP/IP : Trasnmission Control Protocol/Internet Protocol 
#### Layers (5)
1. Application Layer
2. Transport Layer
3. Internet Layer
4. Data Link Layer
5. Physical Layer

![osi-vs-tcpp-ip-models](osi-vs-tcp-ip-models.svg)

source : https://www.networkacademy.io/ccna/network-fundamentals/understanding-the-osi-model

### Comparing TCP/IP and OSI layer

These two concepts are the 
--- 



