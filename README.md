# Wireshark

# Wireshark-Packet-Capture-Lab
Capturing Telnet Session

<h2>Description</h2>
In this lab, I am using Wireshark to find a user's password in a telnet session capture.
<br />


<h2>Languages and Utilities Used</h2>

- Wireshark </b> 

<h2>Environments Used </h2>

- <b>Wireshark 

<h2>Program walk-through:</h2>

<p align="center">
First I will open up a downloaded pcap file containing the users network traffic.. : <br/>
<img src="https://i.imgur.com/zgE5PVY.png"/>
<br />
<br />
Then I filter to only show Telnet packets:  <br/>
<img src="https://i.imgur.com/sSRVVG5.png"/>
<br />
<br />
then i right click on a telnet packet, click on follow, and then click on TCP Stream. (shortcut is to "ctrl, alt, shift and T). This displays all telnettraffic in a clear and redable format: <br/>
<img src="https://i.imgur.com/u37Pu1j.png"/>
<br />
<br />
The Users password is now displayed in plain text:  <br/>
<img src="https://i.imgur.com/9HKXeWh.png"/>
<br />
Brief explanation of whats going on in the playbook: 
Its important to also know the hackers and cybercriminals work and think in order to better protect organizations you may be working for as a network or IT Professional. This will help you better also desgin and configure network with security in mind and help in understanding the value of always following security principles.
  <br/>
</p>

<!--
 ```diff
- text in red
+ text in green
