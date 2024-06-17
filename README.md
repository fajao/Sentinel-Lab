<h1>Failed RDP to IP Geolocation Information</h1>


 ### Check Josh Madakor amazing content here - [YouTube Demonstration](https://youtu.be/RoZeVbbZ0o0?si=YOLQN19VRi9Bigmc)


<h2>Description</h2>
<b>This Powershell script is responsible for parsing out Windows Event Log information for failed RDP attacks and using IP2Location API to collect geographic information about the attackers location. In John's video he used a different API, so this script is only an adaptation with slightly modifications.
</b>
<br />
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ip2location.io:</b> IP Address to Geolocation API

<h2>World map of incoming attacks after 10 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="/assets/043.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>