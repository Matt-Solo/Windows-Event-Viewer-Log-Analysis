# Windows-Event-Viewer-Log-Analysis


This project demonstrates how I used Windows Event Viewer to analyze system, security, and application logs for cybersecurity purposes. Event Viewer is a core tool for any SOC analyst or incident responder, helping detect, investigate, and document system behavior and potential threats.



Project Objective

To explore real-world usage of Windows Event Viewer and practice extracting and analyzing logs relevant to cybersecurity, threat detection, and incident response.



Key Steps Performed

1. Opened **Windows Event Viewer** (`Press Windows + R, type eventvwr, and hit Enter, eventvwr.msc`)
2. Navigated to key logs:
   - **Windows Logs > Security**
   - **Windows Logs > System**
   - **Windows Logs > Application**
3. Applied filters for important event types such as:
   - Logon attempts (Event ID `4624`, `4625`)
   - Privilege escalation (Event ID `4672`)
   - Account lockouts or changes (Event ID `4720`, `4722`, `4723`)
4. Took screenshots of relevant logs for documentation.
5. Exported logs (`.evtx`) for further analysis.
6. Documented key findings in a Word report.
   


Sample Event IDs

| Event ID | Description                      |
|----------|----------------------------------|
| 4624     | Successful logon                 |
| 4625     | Failed logon attempt             |
| 4672     | Admin privileges assigned        |
| 4720     | New user account created         |
| 4722     | User account enabled             |
| 4723     | Password change attempted        |



Step 1: Launch Event Viewer:
Press Windows + R, type eventvwr, and hit Enter.
<img width="750" height="1125" alt="image" src="https://github.com/user-attachments/assets/986b56a4-35b0-462a-86c8-adfa1726bf79" /> 



Step 2: Navigate Log Categories:
Expand Windows Logs in the left pane: Application, Security, Setup, System, Forwarded Events.
<img width="1366" height="735" alt="WLs" src="https://github.com/user-attachments/assets/4d2501e4-8928-44e9-9c14-0077569b03c9" /> 



Step 3: View Security Logs
Click Security to investigate logon events (Event ID 4624 - Successful Logon, 4625 - Failed Logon), privilege escalation (4672, 4673, 4674), account lockouts (4740), and user group additions (4728, 4732, 4756).
<img width="1362" height="639" alt="SLs" src="https://github.com/user-attachments/assets/1966194a-21b7-4ed3-ade4-bf4bc38ef35d" /> 



Step 4: Filter Events
Use the 'Filter Current Log...' option to filter by Event Level and Event IDs.
<img width="1351" height="700" alt="FCL" src="https://github.com/user-attachments/assets/09ad0f09-f28c-46d7-9af0-9e986266c0e1" /> 



Step 5: Analyze Event Details
Click an event to review Date & Time, Logon Type, Source IP, User Account, and SID.
<img width="1376" height="654" alt="AED" src="https://github.com/user-attachments/assets/b34e66b3-c0b5-4987-8566-7dc4450b03dd" /> 








