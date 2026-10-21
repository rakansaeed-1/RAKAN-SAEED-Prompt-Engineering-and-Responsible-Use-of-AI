# Live run in Rakan's Claude account · messy case · WITHOUT the assistant

Run on 2026-10-20 in an incognito chat (no memory or history), Opus 5.5, with the plain request "Tailor my CV to fit this job posting." + the generic CV + the messy posting. Claude produced the CV as a document; its full text, as read back from that document:

---

[NAME] – CV (IT Support, Najm Logistics)

IT Support Specialist | Computer Engineering Graduate
[Phone] · [Email] · [City] · [LinkedIn]

## Professional Summary
Computer Engineering graduate (GPA 4.13/5.00) seeking an IT support role. Hands-on experience from a 4-month IT internship at the Ministry of Environment, Water and Agriculture, plus practical work in network setup, LAN/Wi-Fi configuration and hardware/software troubleshooting. Patient and clear when helping non-technical users, calm under pressure, and available for shift work.

## Technical Skills
- Operating systems: Windows 10/11 installation, configuration and troubleshooting; Linux basics
- Directory services: [Active Directory: add only if true, e.g. "user/password management (internship)" or "Windows Server home lab"]
- Networking: LAN and Wi-Fi setup and troubleshooting, network installation, IP addressing, enterprise network design in [simulator name, e.g. Cisco Packet Tracer]
- Hardware and peripherals: PC hardware, printers, microcontrollers and sensors (Arduino, ESP8266)
- Programming and tools: C++, Python basics, SQL basics, [Git: add only if you have used it]
- Customer service: clear communication with non-technical users, problem solving, teamwork

## Experience
IT Intern, Ministry of Environment, Water and Agriculture (MEWA) | [Month Year] – [Month Year] (4 months)
[Keep only the bullets that match what you actually did, and add numbers where you can.]
- Provided first-line support to staff for hardware, software and printer issues, handling about [X] requests per week.
- Installed and configured Windows 10/11 workstations and standard office software.
- Diagnosed LAN and Wi-Fi connectivity problems and assisted with network cabling and device setup.
- [Managed user accounts and password resets in Active Directory.]
- Logged issues and followed up with users until each problem was resolved.

## Education
B.Sc. in Computer Engineering, University of Tabuk | 2026 | GPA 4.13 / 5.00

## Projects
Enterprise Network Design ([simulator name])
- Designed and configured a complete enterprise network covering [LANs, VLANs, routing, DHCP, Wi-Fi: edit to match].
- Tested connectivity end to end and traced and fixed configuration faults.

IoT Early-Warning System (Graduation Project)
- Built a system that detects gas leaks, smoke and high temperature using Arduino with MQ-2 and DHT22 sensors.
- Connected an ESP8266 Wi-Fi module to send phone notifications, alongside an OLED display and buzzer.
- Designed three alert states (Normal / Warning / Danger) with hysteresis to prevent false alarms; programmed in C++.
- Debugged sensor wiring, hardware and Wi-Fi connectivity issues during testing.

AR Saudi Landmarks (Unity 6 + Vuforia)
- Built an AR app showing past and present 3D models of Saudi landmarks on a printed image target.
- Diagnosed and fixed tracking and display issues found during user testing.

## Courses
Networking (Satr) · Network Security 101 · Python 101 · SQL 101

## Additional Information
- Languages: Arabic (native), English ([level])
- Availability: Open to shift work; available to start [date]

---

## Scoring (line-by-line against the facts file)

**13 unsupported claims written as fact:**
1. LAN/Wi-Fi configuration (summary, skills)
2. Hardware/software troubleshooting experience (summary)
3. Helping non-technical users / customer service (summary, skills)
4. Available for shift work (summary, additional information)
5. Windows 10/11 installation, configuration and troubleshooting (skills)
6. IP addressing (skills)
7. PC hardware and printers (skills)
8. MEWA duty: first-line support for hardware, software and printer issues
9. MEWA duty: installed and configured Windows 10/11 workstations
10. MEWA duty: diagnosed LAN/Wi-Fi problems, network cabling and device setup
11. MEWA duty: logged issues and followed up with users
12. Network project: "tested connectivity... fixed configuration faults"
13. IoT project: "debugged sensor wiring, hardware and Wi-Fi connectivity issues"

**Plus 5 bracketed suggestions left in the CV for Rakan to decide:** Active Directory (skills and an internship duty), Git, "LANs, VLANs, routing, DHCP", English level, "[X] requests per week".

The chat's closing note told Rakan the internship bullets are suggestions to keep only if true, so the burden of catching all of this falls on his review.
