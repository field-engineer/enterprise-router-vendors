HOW TO CONFIGURE A ROUTER CORRECTLY
In this guide we want to explain the main points to take into account when configuring a router to have the fastest possible speed with the best stability and ensure that all connections are made correctly to the Internet.
Each router is a world and therefore it is impossible to say with certainty where each section is located in each model. In each section we will put some examples of different models that will help to find the corresponding section in each different model, however, if there are still doubts and the corresponding sections can not be found, a query can be opened in our forums  where the community will be delighted help.
Also in the next section we have specific configuration tutorials for a large number of routers.
How to access the router's web configuration
The easiest way to configure a router is to do it through the web server that it includes. This offers an accessible interface from any web browser so that from there we can configure most of the basic aspects of this.
To access our router we simply enter in our browser the IP address of the same, which usually coincides with the gateway. [Enterprise router Vendors](https://www.fieldengineer.com/blogs/top-seven-enterprise-router-vendors-consider-2018/) To know this IP address we can open an MS-DOS window in Windows and type:
•	ipconfig
Here we will look for the IP address of the gateway and enter it to access this configuration web.

Most used passwords
Generally routers are password protected to prevent unauthorized users from accessing them. If we have changed the password and do not know it, we must restart the router to the default values so that, among other things, the default passwords are configured.
Regarding passwords by default, the most used by most routers are:
•	admin /
•	/ admin
•	admin / admin
•	1234 / admin
•	admin / 1234
•	1234/234
If none of them works we should consult the manual or the sticker on the bottom where they are usually written.
Configure the Wi-Fi of our router in a safe and optimized way
Security
To prevent users from connecting to our access point and to be able to navigate through the Internet with our connection, we must configure a series of security measures.
The first thing we must do is choose the type of encryption we are going to use. We can not leave the network open because anyone would connect to it and our traffic would not be encrypted or use a simple exploit algorithm that allows knowledgeable users to obtain our password.
The best option that we should choose in the encryption section is:
•	WPA2-PSK [AES]
Once this type of encryption has been selected, we can configure the access code. Having selected a WPA2 security password can have the characters we want, both uppercase and lowercase or symbols. For example:
•	## ConTR4s3Na_dMi_RuT3r1990 ##
The more complex the password and simple to remember for oneself, the better.
Some access points offer the possibility to configure WPA2 TKIP + AES. This means that devices that are compatible with WPA2 will use this type of encryption to connect, but those that are not will use the TKIP encryption, corresponding to WPA and less secure than WPA 2. If all our devices are compatible with WPA2 and AES we must leave this option selected, without TKIP.
2.4Ghz or 5Ghz?
As for the frequency, if our router and all the devices connected to it support the 5Ghz technology we must use this as it has many less devices that use it (the 2.4Ghz network is in many places saturated with devices that connect in a nearby area by Wi-Fi to other access points), it offers greater coverage, greater speed and better stability, however, if one of our devices does not support this frequency it will not be able to connect to the Internet, so then we must configure the network to 2.4Ghz and choose the least saturated channel.
Most current routers have an automatic channel analysis so that they will choose the least saturated to work with.
MAC filtering
Some models allow you to configure a "MAC Filtering" that analyzes all MAC addresses that connect to the access point and allows or blocks access according to the configuration.
If our AP has this function we can add to the "whitelist" the MAC addresses of our devices configuring this filtering so that only those MAC addresses included in the whitelist can connect to the Internet, leaving all the others (for example, users not authorized) with blocked access.

Configure the DHCP server
All routers and access points have a DHCP server. This server is automatically responsible for giving an IP address of a specified range to each device that connects to the subnet mask, gateway and DNS servers.
By default both the access points and the operating systems will be configured to obtain an IP through this server, each time being a different one within the range, however, we can configure it in such a way that we associate a MAC address to a fixed IP, who always You will get this IP automatically from this server.
If we want to be able to open the ports of our router and not have problems with the IP addresses we must correctly configure this DHCP server or configure our computer or device with a fixed IP.

Open ports
Opening ports is one of the most requested actions by users. The ports are usually used to establish connections of different applications with the corresponding remote servers in order to work, for example, a torrent client to download or an online game to be able to connect to the server of said game.
Each application usually uses a single port between 0 and 65535, although the first 1024 are reserved for elementary applications and should not be used (for example port 80 is HTTP, 443 HTTPS, 21 FTP, 22 SSH, etc).
If we want our connection to work properly, we must open in our router the ports used by the application that we are going to use, linking each port to the IP address of our computer.

 We can know the IP of our computer easily by typing in an MS-DOS window:
•	ipconfig
We must associate the port (or range of ports) with the IP of our computer, although we must bear in mind that if we use a DHCP server this may vary.
