# Incident Report

## Executive Summary
This lab was started by collecting baseline system information. It was followed by a wireshark capture on the monitoring & analysis machine.
suspicious activity was generated from the attacker machine. This was followed by a scan of all the traffic in wireshark.
security logs were viewed from the victim machine in the event viewer. An image of all the activity was created with FTK Imager and viewed in autopsy.
This is the executive summary of the report.

## Timeline
start time
12:58
end time
200

## Systems Involved
### Virtual Machines
- Windows VM
- Ubuntu VM
- Kali VM
### Tools
- Nmap
- Event Viewer
- FTK Imager
- Autopsy

## Evidence Collected
- All evidence is recorded and can be viewed in autopsy case number 002

## Network Findings
- Using Nmap we were able to view activity on another machine using the ip address

## Indicators of compromise
- Windows keeps security logs and activity in the event viewer.

## Containment Recommendations
- for this lab the firewalls were turned off for the purpose of the lab.
- windows firewalls should remain up to prevent compromise.

## Lessons Learned
- Windows has a lot of applications that help with system security. FTK Imager only decrypts the image if you have imager pro.
- Wazuh is a tool that can detect automatically what I found manually.
