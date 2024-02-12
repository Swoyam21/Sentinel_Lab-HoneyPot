<h1>Geo-Location Enrichment and Visualization</h1>





<h2>Description</h2>

The honeypot lab is a controlled environment designed to simulate vulnerable systems, enticing malicious actors to interact with them, thereby gathering valuable intelligence on cyber threats and attack methodologies. Leveraging Azure infrastructure and PowerShell automation, this lab deploys and manages honeypot instances, while integrating IPGeolocation API for pinpointing the geographical origins of malicious activities. By providing insights into emerging cyber threats, this lab enhances cybersecurity defenses and fosters proactive threat mitigation strategies.

<br />
<br />

<br />
<br />

<p align="center">
<img src="https://i.imgur.com/3d3CEwZ.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Language, Platforms and Tools Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer
- <b>Azure:</b> Utilized for hosting and managing the infrastructure supporting the honeypot lab, facilitating scalable deployment and effective monitoring of malicious activities.
- <b>IPGeolocation API:</b> Used to integrate into honeypot lab to automatically retrieve and analyze geolocation dataof incoming attempts, enhancing the understanding of the geographic origins of potential threats within the lab enviornment.
- <b>Microsoft Sentinel:</b> The honeypot lab integrates seamlessly with Microsoft Sentinel, enhancing threat detection and response capabilities by correlating honeypot-generated data with other security telemetry within the Azure enviornment.

<h2>Attacks from Germany coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>
![60](https://github.com/Swoyam21/Sentinel_Lab-HoneyPot/assets/97996681/0e176621-fd52-470c-b301-ceb137c03b32)



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
