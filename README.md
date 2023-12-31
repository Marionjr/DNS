<p align="center">
</p>

# DNS
Building intuition for DNS

<h1>Creating A-Records,CNAME Records, and Local DNS Cache,</h1>
In this tutorial, we will createe A-Recods, CNAME records while observing the local cache using the IPconfig/displaydns and ipconfig/Flushdns <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols ICMP

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows 2019 Server

<h2>High-Level Steps</h2>

- Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a A-Record record "Mainframe" with an IP Address 10.0.0.4
- Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "search" with a FQDM of www.google.com
- Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "photography" with a FQDM of www.marionthesecond.com

  <img width="1680" alt="Screenshot 2023-12-30 at 7 50 31 PM" src="https://github.com/Marionjr/DNS/assets/130338872/9d85a878-77de-42f7-bba6-523c3aecf495">

Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a A-Record record "Mainframe" with an IP Address 10.0.0.4

<img width="1680" alt="Screen Shot 2023-10-11 at 10 44 33 PM" src="https://github.com/Marionjr/DNS/assets/130338872/3436d92b-a662-4a3f-b1ab-a85de5bd5c75">

 Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "search" with a FQDM of www.google.com

<img width="1680" alt="Screen Shot 2023-10-11 at 10 46 44 PM" src="https://github.com/Marionjr/DNS/assets/130338872/d4999ab3-8093-4227-b521-719842aad91b">

Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "photography" with a FQDM of www.marionthesecond.com 



