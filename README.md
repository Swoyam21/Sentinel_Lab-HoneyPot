<h1>Geo-Location Enrichment and Visualization</h1>





<h2>Description</h2>

The honeypot lab is a controlled environment designed to simulate vulnerable systems, enticing malicious actors to interact with them, thereby gathering valuable intelligence on cyber threats and attack methodologies. Leveraging Azure infrastructure and PowerShell automation, this lab deploys and manages honeypot instances, while integrating IPGeolocation API for pinpointing the geographical origins of malicious activities. By providing insights into emerging cyber threats, this lab enhances cybersecurity defenses and fosters proactive threat mitigation strategies.


<h2>First View of the Virtual Machine after logging in</h2>

<p align="center">

<img src="https://imgur.com/SzjEtqv.png" height="80%" width="80%" alt="Custom Log"/><br /><br />
</p>

<h2>Turning off all the firewalls to expose it with very low security</h2>

<p align="center">

<img src="https://imgur.com/QXmFkYt.png" height="80%" width="80%" alt="Custom Log"/><br /><br />
</p>

<h2>Language, Platforms and Tools Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer
- <b>Azure:</b> Utilized for hosting and managing the infrastructure supporting the honeypot lab, facilitating scalable deployment and effective monitoring of malicious activities.
- <b>IPGeolocation API:</b> Used to integrate into honeypot lab to automatically retrieve and analyze geolocation dataof incoming attempts, enhancing the understanding of the geographic origins of potential threats within the lab enviornment.
- <b>Microsoft Sentinel:</b> The honeypot lab integrates seamlessly with Microsoft Sentinel, enhancing threat detection and response capabilities by correlating honeypot-generated data with other security telemetry within the Azure enviornment.

<h2>Attacks from Germany coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://imgur.com/fwYAghN.png" height="80%" width="80%" alt="Custom Log"/><br /><br />
</p>

<h2>World map of incoming attacks after Couple of minutes (built custom logs including geodata)</h2>

<p align="center">

<img src="https://imgur.com/zlipuDa.png" height="80%" width="80%" alt="Custom Log"/><br /><br />
</p>

<h2>After couple of hours, this is the final result</h2>

<p align="center">

<img src="https://imgur.com/bdyXVVx.png" height="80%" width="80%" alt="Custom Log"/><br /><br />
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
