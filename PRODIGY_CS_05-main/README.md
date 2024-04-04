This is one of my cybersecurity internship tasks at Prodigy InfoTech. 
It is a simple packet sniffing tool written in python using scapy library which captures network packets.
**Since packet sniffing can be a violation of privacy and security, and creating such tools without proper authorization is against ethical guidelines, there are some limitations on the code provided above.**
The above code only captures TCP packets as the call to the sniff() function has a filter which captures only TCP packets.
For capturing all types of packets, `"tcp"` must be changed to `""` where the sniff() function is called.
It will only capture 10 packets as the default count is specified as 10. It can be changed manually to a larger value or the count can be removed(by removing the counter & count from sniff() function being called). If the count is removed the packets will be captured indefinitely until the program is terminated manually.
*The details about captured packets will be saved to `packet_sniffer_results.txt` file.*
**User might require superuser/administrator privileges for running this code. I tested this on my Kali Linux terminal on my virtual machine where I had to be a superuser.**
