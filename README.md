Download Link: https://assignmentchef.com/product/solved-cs-3700-homework-8
<br>
<strong>Problem A</strong>. Consider the network setup in the following figure, where the router is a NATed router. Suppose that the ISP assigns the router the address 192.162.30.79 and that the network address of the home network is 172.20.0.0/16. a. Assign addresses to interfaces 1 and 2, and hosts A, B and C.

<ol start="34">

 <li>Suppose host B has an ongoing TCP connection to port 4567 at server 34.182.19.20 from port 80 at host B. The NATed router assigns a new port 8080 for this TCP connection. Provide the corresponding entry in the NAT translation table and the source ip, source port, destination ip, and destination port in each of the four IP datagrams shown below.</li>

</ol>




<strong> </strong>

<strong>Problem B</strong>.  Below is the information displayed by a command “traceroute www.google.com” on my computer.




<ol>

 <li>Is the IP address of my computer included in the information given above? If yes, what is it and is it a private or public IP address?</li>

 <li>What is the IP address of www.google.com when this traceroute command was executed? Is it a private or public IP address?</li>

 <li>What’s the relationship between the two DNS names: www.google.com and den03s09-in-f4.1e100.net? (Hint: which is the alias name and which is the canonical name?)</li>

 <li>How many routers are involved in the communication between my computer and the web server at www.google.com?</li>

 <li>What are the initial TTL and the destination IP enclosed by my computer in the set of IP datagrams that are dropped by the router 72.14.194.239?</li>

 <li>When the router xe-0-0-1.core-910.frgp.net drops the ip datagram enclosing a UDP segment from my computer, does it send a UDP segment or an ICMP message to the host? What are the type and code of router enclosed in such UDP segment or ICMP message? What’s the source IP in the IP datagram carrying this UDP/ICMP packet?  Whose IP is used as the destination IP for this UDP/ICMP packet?  (<em>hint</em>: websever’s, my computer’s, router 147.153.69.30’s, or …?)</li>

 <li>What are the final TTL and the destination IP enclosed in the set of IP datagrams when they arrive at the webserver www.google.com? Does this webserver send a UDP segment or an ICMP message back to the host? What are the type and code enclosed in such UDP segment or ICMP message? What’s the source IP in the IP datagram carrying this UDP/ICMP packet? Whose IP is used as the destination IP for this UDP/ICMP packet?  (<em>hint</em>: websever’s, my computer’s, router 147.153.69.30’s, or …?)</li>

</ol>




<strong>Problem C</strong>.  Tunneling is used for the transition from IPv4 to IPv6. The route from Host A to Host B is shown as below (see <em>next</em> page), where ip1, ip2, … ip10 are the ip addresses of the hosts and the interfaces of routers.   Host A sends a TCP segment to Host B.  To deliver this TCP segment, for the <strong>IP datagram</strong> transmitted over <strong>EACH of the FIVE link (1<sub>st</sub> link, 2<sub>nd</sub> link, …, 5<sub>th</sub> link)</strong> describe

<ul>

 <li>the type of IP datagram (IPv4 or IPv6),</li>

 <li>the source ip address,</li>

 <li>the destination ip address.</li>

</ul>

















