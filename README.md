<p align="center">
<img src="https://i.imgur.com/EMB7gDW.jpg"/>
</p>

<h1>VPN Setup and Explanation</h1>
This tutorial outlines the basics of virtual private networks by installing Proton VPN on a remote desktop and observing how it changes the IP address.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Notepad
- https://protonvpn.com/
  

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Open notepad and record the IP address from your local computer in a notepad text file by using https://www.whatismyip.com/
- Using an Azure virtual machine record its IP address using the same method.
- Dowload Proton VPN onto the virtual machine.
- Use the virtual machine to download and install Proton VPN.
- Use Proton VPN to change the virtual machine's IP address and record it using the same method.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/kennethmoen/VM-Setup-and-Explanation/assets/145589069/5d013d6f-c3d1-49d8-bc42-eaf910131408"/>
</p>
<p>
Use a web browser and go to  https://www.whatismyip.com/ and record the IP address in notepad as shown in the above screenshot.
</p>
<br />

<p>
<img src="https://github.com/kennethmoen/VM-Setup-and-Explanation/assets/145589069/f6451d58-72a2-4b71-bac2-42ffdfd946d9"/>
</p>
<p>
  Use an Azure Virtual Machine and find the IP using the same method and note the difference.
</p>
<br />

<p>
<img src="https://i.imgur.com/Xxvdftj.png"/>
</p>
<p>
Using the virtual machine install Proton VPN by going to https://protonvpn.com/ and clicking the highlighted button.
</p>
<br />
<img src="https://i.imgur.com/lMSMruc.png"/>
</p>
<p>
Once the VPN is installed connect to the Japanese server. The VPN in the disconnected state will show connect instead of disconnect. Click on that button and allow the virtual machine to establish a VPN connection which will take a few moments.
</p>
<br />
<img src="https://i.imgur.com/W4oxZK0.png"/>
</p>
<p>
Once connected to the server return to ttps://www.whatismyip.com/ and note the difference. This concludes the basic setup for a VPN and demonstration of how it changes IP addresses
</p>
<br />
