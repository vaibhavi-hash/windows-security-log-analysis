# windows-security-log-analysis
# Windows Security Event Log Analysis 🔐

## 📌 About the Project

Windows Security Event Log Analysis is a beginner-level cybersecurity project focused on understanding and investigating security-related activities recorded by the Windows operating system.

Windows records events related to logons, authentication failures, and other security activities. By reviewing these events, security analysts can identify unusual patterns, investigate potential security concerns, and understand what happened on a system.

In this project, I used Windows Event Viewer to examine selected Security Event Logs and Google Sheets to organize the event details, document observations, and record my analysis.

## 🎯 Why This Project?

Security logs are an important source of evidence during cybersecurity investigations. They help analysts understand system activity and investigate events that may indicate a security issue.

The purpose of this project was to gain hands-on experience with Windows Security Logs, learn how to interpret common Event IDs, and understand how a beginner SOC analyst documents and assesses security-related events.

## 🛠️ Tools Used

- **Windows Event Viewer:** To view and examine Windows Security Events.
- **Google Sheets:** To organize event details, record observations, and document interpretations.

## 🔍 What Did I Investigate?

I reviewed three Windows Security Event IDs:

| Event ID | Event Type             | What It Indicates                                     |
| -------- | ---------------------- | ----------------------------------------------------- |
| 4624     | Successful Logon       | A successful logon was recorded.                      |
| 4625     | Failed Logon           | A logon attempt failed.                               |
| 4798     | User Group Enumeration | A process enumerated a user's local group membership. |

## ⚙️ Project Workflow

1. Opened Windows Event Viewer and accessed Windows Logs → Security.
2. Reviewed selected events using their Event IDs.
3. Examined relevant fields, including timestamps, account information, logon types, and failure reasons where available.
4. Organized the collected information in Google Sheets.
5. Documented observations and assessed whether events appeared routine or required further investigation.
6. Prepared findings and considered privacy before sharing project materials publicly.

## 📊 Key Findings

- Reviewed a successful logon event associated with the SYSTEM account and Logon Type 5.
- Examined failed logon events that included the reason “Unknown user name or bad password.”
- Reviewed a user group membership enumeration event.
- Identified the importance of examining event context before concluding that an activity is malicious.

The available evidence did not confirm a cyberattack or system compromise. Failed logons and group enumeration can occur during legitimate activity, so further investigation may be necessary to determine their significance.

## 🧠 Skills and Learning Outcomes

Through this project, I practised:

- Windows Security Event Log analysis
- Understanding authentication-related Event IDs
- Interpreting logon types and failure reasons
- Organizing investigation notes and evidence
- Distinguishing potentially suspicious activity from confirmed malicious behaviour
- Applying basic security documentation and privacy practices

## ⚠️ Limitations

This project involved a small, manual review of selected Windows Security Events. It did not include automated detection, SIEM-based correlation, or a confirmed incident investigation. Additional event correlation and system context would be required for stronger conclusions.

## 🔒 Privacy and Responsible Sharing

Sensitive information, including usernames, IP addresses, and computer identifiers, should be redacted from public materials. Original logs and unredacted screenshots are kept private.

## 📄 Project Report

The detailed investigation report is available in the `report/` folder.

## 👩‍💻 Author

**[Vaibhavi singh]**

Cybersecurity Student&#x20;

