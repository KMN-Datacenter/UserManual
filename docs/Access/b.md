# VPN Access
This assumes that you are familiar with virtualization, operating systems configuration and VPNs.

1. Create a Jump Server with Windows 11, ensure it has a connection to the Internet..
2. Download the Fortinet client from http://forticlient.com/. I am currently using  v. 7.4.3
3. Install this software.
4. Run the software
5. Create a new connection
6. Select IPsec VPN
7. The connection name is “KMN”
8. Remote gateway is 91.123.225.1
9. The pre-shared key will be sent to you
10. Click on “Save login”
11. Click apply

<figure>
<img src = "https://kmn-datacenter.github.io/UserManual/images/fig1.jpg">
<figcaption>Fig 1. VPN Setup.</figcaption>
</figure>

Now try to log in. 

- You will be prompted for a username; use your L number
- You will be prompted for a password; this will be sent to you individually

Click __Connect__

If you run into problems...
Fortinet made a change in late 2025 which may require us to tweak a setting, get in touch with Harman if you run into trouble.