# Honeypot Assignment

**Time spent:** **10** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?

Using Git Bash on Windows 10 i deploye MHN-Admin with GCP. I followed the instructions using the gcloud commands to create the mhn-admin VM. After i ssh into the mhn-admin vm i install the package using 'git clone' and am able to see the application using the external IP. 

<img src="https://github.com/MattPlum/Honeypot/blob/341d90ce7fba7171654355edd996efcd3f78cadd/m2.gif"/>

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?

Dionaea is one of the many honeypots supported by MHN. It can be chosen through the MHN Admin Deploy page which generates a wget token that enables the honeypot. It has multiple ports open to lure in attackers and collect data on attacks.  

<img src="https://github.com/MattPlum/Honeypot/blob/b58827d965a9135e22ec2c9e102c817f0b7e4198/honeypot.gif">https://github.com/MattPlum/Honeypot/blob/b58827d965a9135e22ec2c9e102c817f0b7e4198/honeypot.gif

### Database Backup (Required) 

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?

RDBMS is Relational Database Management System and the one MHN-Admin uses ???. The exported JSON file contains the information from the attacks on the honeypot such as which honeypot was attacked, src/dest ports, ip, time, and protocol used. 

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*

### Deploying Additional Honeypot(s) (Optional)

#### X Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?

<img src="x-honeypot.gif">

### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

MD5 Hash: *Run `md5sum` on the file and record the hash here.*

SHA1 Hash: *Run `sha1sum` on the file and record the hash here.*

<img src="x-malware.gif">

## Notes

Describe any challenges encountered while doing the assignment.
