<div align="center">
    <img src="https://github.com/namilea/NobleGlobalServices/blob/e9f65b9e509904cb5a55d8147454e87180816abe/Cyber%20Security%20Breach%20Procedures.jpg" alt="Brand Image" />
</div>

# Cyber Security Breach Response Procedures

## Introduction

This document outlines two key procedures for responding to external breaches that may impact your business. The first procedure addresses breaches occurring within subcontractor or third-party networks that your business is associated with. The second procedure details steps to follow in the event of a breach within your own organization’s systems. These procedures are designed to help ensure a comprehensive and timely response to any external threat, whether directly or indirectly affecting your business.

### Procedure 1: Subcontracting Company Breach Response

**Scenario:** You receive intelligence (confirmed or unconfirmed) that one of your subcontracting companies has experienced a breach. Your role is to ensure that your systems are not involved and provide forensic support if necessary.

1. **Timestamp the Intelligence**
   - Document the Time: As soon as you receive any intelligence (email, news, or internal communication), take note of the exact time and date. This will serve as the reference point for all subsequent actions.

2. **Analyze Web-Facing Assets and Client Portal**
   - Access the Client Portal and Web-Facing Assets:
   - Use forensic tools to run an analysis of the client’s portal and any public-facing websites you interact with.
   - Focus on any vulnerabilities or suspicious activities that may be associated with the breach.
   - Document your findings.

3. **Review Your Event Logs**
   - Open Event Viewer and focus on logs from the last seven days leading up to the breach.
   - Analyze the logs, checking for unusual behavior, unauthorized login attempts, or irregular access points.

4. **Cross-Reference Data**
   - Compare your forensic findings from the web assets and client portal with the logs from your own system.
   - Look for patterns, IP addresses, or suspicious activity that might link the breach to your systems.

5. **Compile a Report**
   - Create a detailed report that includes:
     - The timeline of when the breach of intelligence was received.
     - Findings from your forensic scans.
     - A summary of suspicious activity in your logs.
     - Relevant IP addresses or attack vectors.
     - Conclusions and follow-up actions.

6. **Notify the Client**
   - Send an email to the client attaching the forensic report.
   - Confirm that you’ve investigated the issue.
   - Assure the client if there are no issues from your systems.

7. **Remain on Standby**
   - Continue monitoring your systems and logs for any further suspicious activity related to the breach.
   - Stay in communication with the client and remain available if they request further assistance.

### Procedure 2: Your Own System Breach Response

**Scenario:** You discover that one of your devices has been compromised, whether through a phishing attack or some other form of breach. You need to isolate the issue, protect other devices, and report it accordingly.

1. **Daily Device Check Before Connecting to the Internet**
   - Before connecting to the internet, perform a log check on the primary device using tools like "iMazing" to check for any suspicious activity.
   - If the primary device shows no issues, proceed to connect your computer to the internet.

2. **Detecting Compromise**
   - If you discover any suspicious activity on your primary device (e.g., phishing, malware, or irregular behavior):
     - Quarantine the Device: Immediately disconnect the device from the internet.
     - Keep the device isolated from your network until further investigation.
     - Run Antivirus and Security Scans: Perform a full scan using antivirus software to detect any malicious files or software.

3. **Investigating the Logs**
   - Check your logs (application, security, and system logs) to review any suspicious activity before, during, and after the detected breach.
   - Look for specific IPs or processes that seem unusual or malicious. Document all relevant logs.

4. **Screen All Other Devices**
   - Before turning on any other device, perform log checks on those systems.
   - Run antivirus scans on all systems that might have interacted with the compromised device.
   - Ensure no other systems were affected by the potential breach.

5. **Block Suspicious IPs**
   - If your investigation uncovers suspicious IPs or activity, block them using your router’s firewall or Windows Firewall.
   - Document the IP addresses and any relevant data from the logs.

6. **Compile and Document Findings**
   - Create a detailed report summarizing:
     - The timeline of the breach discovery.
     - The actions taken to quarantine the device.
     - Any forensic findings (IP addresses, malicious processes, etc.).
     - Antivirus scan results and any conclusions.
   - Store this report in a secure location for future reference and potential client communication.

7. **Notify Clients If Necessary**
   - If the breach involved any client data or systems, notify them immediately with the following:
     - A summary of the breach.
     - A note confirming that you have quarantined the affected system and taken necessary steps to protect the client’s data.
     - Assure them that you are available to assist and provide further information or support if necessary.

8. **Ongoing Monitoring**
   - Continue monitoring your systems for any additional suspicious activity, ensuring all devices remain secure before reconnecting them to the network.
