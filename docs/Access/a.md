# Accounts
Authorization, authentication, and accounting (AAA) are centralised and are based on Microsoft's Active Directory.
This is a separate directory service from that of ATU. 

Any lecture or researcher may request access and an account will be created in the form *firstname.surname*

Any lecturer may request student access and this is normally a class group. The lecture should forward a CSV file of students, typically an export from _Blackboard_.

## Suitability
Access is intended for technically proficient people only. If you are not a Computing student or staff member, you will struggle to gain any benefit.

We do not have a help desk!

Note that we are not service providers, you need to discuss requirements in advance and we do *not* offer an SLA. We will not be able to respond quickly during the academic year.

## Access from ATU Donegal
There is network access from the ATU Donegal Port Road campus to the data center. 
We are outside the perimeter firewall, you may access the data center from the laboratories, but there is no access from systems back into the campus.
Since 2025, there is no access from the Wireless network.

## VPN Access
This assummes that you are familar with virtualization, operating systems configuration and VPNs.

1. Create a Jumpserver with Windows 11, ensure it has a connection to the Internet..
2. Download the Fortinet client from http://forticlient.com/ 
3. Install this software.
4. Run the software
5. Create a new connection

<figure>
<img src = "https://kmn-datacenter.github.io/UserManual/images/fig1.jpg">
<figcaption>Fig 1. Setup.</figcaption>
</figure>

6. Select IPsec VPN
7. The connection name is “KMN”
8. Remote gateway is 91.123.225.1
9. The pre-shared key is “hardtoguess”
10. Click on “Save login”
11. Click apply

Now try to log in. 
- You will be prompted for a username; use your L number
- You will be prompted for a password; this will be sent to you individually

Click __Connect__

