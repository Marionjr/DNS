<p align="center">
</p>![DNS1](https://github.com/Marionjr/DNS/assets/130338872/bb71fb3c-ad53-434d-8bd0-d286ee42268f)


# DNS
Building intuition for DNS

<h1>Creating A-Records,CNAME Records, and Local DNS Cache,</h1>
In this tutorial, we will createe A-Recods, CNAME records while observing the local cache using the IPconfig/displaydns and ipconfig/Flushdns <br />


<h2>Video Demonstration</h2>

- ### [Building Intuition for DNS](https://youtu.be/a351XaGNpUI)

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
- Using Client-1 as a host computer on the domain, using the command prompt ping the A-Record "Mainframe," ping the CNAME record "Search" and Ping the CNAME Record "photography" and observe the cache by running ipconfig/displaydns
- observe the cache for all the A-records, CNAME records that were added to the DNS Server
- Change the IP Address of "Mainframe" to 8.8.8.8 and observe the ping command on client-1
- Run ipconfig/flushdns and attempt another ping command to "Mainframe" from client-1 and observe the updated cache from the DNS server.

  <img width="1680" alt="Screenshot 2023-12-30 at 7 50 31 PM" src="https://github.com/Marionjr/DNS/assets/130338872/9d85a878-77de-42f7-bba6-523c3aecf495">

Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a A-Record record "Mainframe" with an IP Address 10.0.0.4

<img width="1680" alt="Screen Shot 2023-10-11 at 10 44 33 PM" src="https://github.com/Marionjr/DNS/assets/130338872/3436d92b-a662-4a3f-b1ab-a85de5bd5c75">

 Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "search" with a FQDM of www.google.com

<img width="1680" alt="Screen Shot 2023-10-11 at 10 46 44 PM" src="https://github.com/Marionjr/DNS/assets/130338872/d4999ab3-8093-4227-b521-719842aad91b">

Using the DNS manager on the Domain Controller, in the Forward Lookup Zone folder, add a CNAME record "photography" with a FQDM of www.marionthesecond.com 

<img width="1680" alt="Screen Shot 2023-10-11 at 10 41 42 PM" src="https://github.com/Marionjr/DNS/assets/130338872/8575bb28-71d5-49f0-8802-3ccda12bc4f2">

Ping mainframe

<img width="1680" alt="Screen Shot 2023-10-11 at 10 44 57 PM" src="https://github.com/Marionjr/DNS/assets/130338872/58b5f4f5-c028-4864-a6c2-131b450cf8cd">

ping search

<img width="1680" alt="Screen Shot 2023-10-11 at 10 47 07 PM" src="https://github.com/Marionjr/DNS/assets/130338872/1e25510c-4fb3-477a-8cd3-d4e6e9cb9e00">

ping photography

<img width="1680" alt="Screenshot 2023-12-30 at 8 47 49 PM" src="https://github.com/Marionjr/DNS/assets/130338872/d6275a53-17cd-48f8-9d9a-fe9f705ec1a1">

running ipconfig/displaydns



<img width="1680" alt="Screenshot 2023-12-30 at 8 50 50 PM" src="https://github.com/Marionjr/DNS/assets/130338872/a463b451-8bae-4307-ac0b-ea6c3cb44fe7">

Running ipconfig/flushdns

<img width="1680" alt="Screenshot 2023-12-30 at 8 59 00 PM" src="https://github.com/Marionjr/DNS/assets/130338872/540d998a-7eaf-437d-a852-0fa77110daa9">

Change the IP Address of "Mainframe" to 8.8.8.8 and observe the ping command on client-1


<img width="1680" alt="Screenshot 2023-12-30 at 8 59 20 PM" src="https://github.com/Marionjr/DNS/assets/130338872/3087eadf-f6c3-43b1-bb09-b12b4444ced2">

DNS server updated mainframe IP Address from 10.0.0.4 to 8.8.8.8


