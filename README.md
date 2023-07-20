# Whos-who
File Upload Vulnerability using Lighweight PHP

---

<img width="150" height="150" alt="whoswho" src="https://github.com/samphoerna/Whos-who/assets/139729508/9998ec6b-7de8-4249-a868-d105ae174d01">

---

Name : WHO'S WHO

Owner : Naman Sahore

Editor: Me AKA Priman Satria

**HOW TO USE:**
*FOR RFI*
Clear .txt extention and upload the script on a server and preform RFI.
*FOR LFI*
Clear .txt and add .php extention to the script and perform LFI by uploading shell script on a vulnerable server.

*RFI (Remote File Inclusion)* and *LFI (Local File Inclusion)* are two common web application vulnerabilities in cybersecurity that allow attackers to include files from external or local sources into the web application. These vulnerabilities can lead to unauthorized access, information disclosure, and remote code execution.

####RFI (Remote File Inclusion):####
RFI occurs when a web application allows the inclusion of remote files from external servers. Attackers exploit this vulnerability by manipulating the application's input parameters, tricking the server into fetching and executing a file hosted on a remote server.

**Exploit and Potential Consequences:**

1. RFI can allow attackers to execute arbitrary code, leading to server compromise and unauthorized access to sensitive data.
2. Attackers can upload malicious files, resulting in remote code execution and possible system compromise

####LFI (Local File Inclusion):####
LFI occurs when a web application allows the inclusion of local files residing on the same server where the application runs. 
Attackers exploit this vulnerability to access sensitive files on the server.	

**Exploit and Potential Consequences:**

1. LFI can reveal sensitive information, such as configuration files, credentials, or system files.
2. If the web server process has elevated privileges, LFI can lead to remote code execution and complete server compromise.

**Summary**

- RFI involves including files from external servers outside of the web application's server.
- LFI involves including files from the same server where the web application is hosted.

RFI and LFI vulnerabilities are critical security issues that require diligent input validation, proper file inclusion methods, and regular security testing to prevent unauthorized access and code execution. Regularly update web application components and follow secure coding practices to mitigate these vulnerabilities effectively.
