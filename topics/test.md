# About this Document

The System Security Plan (SSP) is designed to provide an overview of the security requirements of the system and describe the controls in place or planned for meeting those requirements. The SSP also defines responsibilities and expected behavior of all individuals who access the system.

This document and its accuracy are critical for system certification activity. For this reason, this SSP will be reviewed and updated, as necessary, at least annually. Documentation of each review and change made to the SSP will be captured in the Version History at the beginning of this document. Items that should be included in the review are:

- Change in system architecture
- Change in system status
- Additions/deletions of system interconnections
- Change in system scope
- Change in certification and accreditation status

# Deepwave Information Control Enclave (DICE)
The Deepwave Information Control Enclave (DICE) software is comprised of one overarching system and does not contain any additional systems or major applications. This SSP describes the controls in place to provide a level of security appropriate for the information to be transmitted, processed, or stored within the infrastructure. Information security is an asset vital to our critical infrastructure and its effective performance and protection is a key component of our organization. Proper management of information technology systems is essential to ensure the confidentiality, integrity and availability of the data transmitted, processed, or stored by DICE information system.
The security safeguards implemented by Deepwave meet the policy and control requirements set forth in this SSP. This system is subject to consistent monitoring with applicable laws, regulations, organizational policies, procedures, and practices.

# Information System Owners
The following individuals possess in-depth knowledge of DICE and/or its functions and operation.

| | |
|:-------|:------|
| Name:	| John Ferguson | 
| Title: | CEO |
| Company / Organization: | Deepwave Digital |
| Address: | 1429 Walnut St, Suite 1000 |
| | Philadelphia, PA 19102 |
| Phone Number: | 267-538-0473 |
| E-mail Address: | john@deepwavedigital.com |

| | |
|:-------|:------|
| Name: | Chris Siefert |
| Title: | Operations Manager |
| Company / Organization: | Deepwave Digital |
| Address: | 1429 Walnut St, Suite 1000 |
| | Philadelphia, PA 19102 |
| Phone Number: | 267-538-0473 |
| E-mail Address: | chris.siefert@deepwavedigital.com |

# Assignment of Security Responsibility

The Facility Security Officer identified below has been appointed in writing and is deemed to have significant cyber and operational role responsibilities.

| | |
|:-------|:------|
| Name: | John Ferguson |
| Title: | CEO |
| Company /Organization: | Deepwave Digital |
| Address: | 1429 Walnut St, Suite 1000 |
| | Philadelphia, PA 19102 |
| Phone Number: | 267-538-0473 |
| E-mail Address: | john@deepwavedigital.com |

# Information System Operational Status
The DICE system is currently in the Operational life-cycle phase. The system is operating and in production.

# Information System Type
DICE is classified as a general support system. It is an interconnected set of information resources under the same direct management control and shares common functionality.

# General System Description / Purpose
The DICE system provides unclassified interconnectivity between its employees to support business operations. The primary business area supported by this system is Deepwave Digital main facility headquarters located in Philadelphia, PA. There are both internal and external (remote) users. There are three users at headquarters. Applications supported by the general support system are:
- PreVeil for Windows

# Deepwave Digital Network Diagram
The following architectural diagram provides a visual depiction of the major hardware components that constitute the DICE system.

![Garrison Network](Garrison_Network.png)

# Garrison Network
 
9.	System Environment
DICE is a custom environment composed of Windows Operating Systems with a list of approved hardware components, software components, and networking components. An up-to-date list of approved components may be found in the CCMC repository. 
Approval List	Description	File Location
Hardware Components	CSV file containing the list of endpoints and servers that are authorized to join DICE	It-admin/CMMC/environment/hardware-components.csv
Networking Components	CSV file containing the list of networking hardware that is authorized to join DICE	It-admin/CMMC/environment/networking-components.csv
Software Components	CSV file containing the list of software that is approved for installation on DICE hardware	It-admin/CMMC/environment/software-components.csv
10.	System Interconnection / Information Sharing
The DICE infrastructure does not participate in any system interconnections where there is a direct connection between two or more IT systems for the purpose of sharing information resources.
11.	Laws, Regulations, and Policies Affecting the System
The following laws and regulations apply to the information system:
•	Privacy Act of 1974 as amended [5 USC 552a]
•	Defense Federal Acquisition Regulation Supplement (DFARS) [Clause 252.204-7012 - Safeguarding Covered Defense Information and Cyber Incident Reporting]
•	NIST Special Publication 800-171 r2
12.	Minimum Security Controls
Security controls must meet minimum-security control baseline requirements. There are security control baseline requirements for management controls, operational controls, and technical controls.
Management security controls identify the management safeguards and countermeasures in-place or planned for the Deepwave Digital system. Management Controls are those safeguards and countermeasures that focus on the management of risk and the management of the information security system. They are actions that are performed primarily to support information system security management decisions.
Operational security controls identify the operational safeguards and countermeasures in-place or planned for the Deepwave Digital system. Operational controls are those safeguards and countermeasures that are primarily implemented and executed by people as opposed to systems and technology.
Technical security controls identify the technical safeguards and countermeasures in-place or planned for the Deepwave Digital system. Technical Controls are those safeguards and countermeasures that are primarily implemented and executed by the information system through mechanisms contained in the hardware, software, or firmware components of the system.
Security controls that are representative of the sensitivity of the Deepwave Digital systems are described in the sections that follow. Only security controls mandated by the CMMC are implemented or planned and are described below. Additional security controls may be added below as they are implemented or planned for the Deepwave Digital system.
Deepwave Digital has begun the process of organizing each Security Control family into its own policy document that bears the name of the control family. Each policy will identify the roles and responsibilities of those tasked with implementation of the control family. 

12.1	ACCESS CONTROL (AC)
AC.L1-3.1.1
Limit information system access to authorized users, processes acting on behalf of authorized users, or devices (including other information systems)
Control Summary
Deepwave has identified authorized users, processes and devices that are connected to the system and maintains a list of those users and their roles via tracked modifications to the respective access control list. This list is located in the it-admin repository and is maintained as needed.  Deepwave Digital has limited access to the DICE systems to only authorized users and those users have limited access to DICE systems. Deepwave has the tools to identify, define, and limit access to transactions and functions that authorized users are permitted to execute for all systems. 

System	Role	Functions Accessed	Actions Limiting Access 
PreVeil	User	•	Encrypted email, file storage, access to any folders/files shared with user	A PreVeil account is required for any user to access the PreVeil system. Access rights are enforced via private, user and device-based key authentication cryptography. Any accidental communications (into or out of the system) and/or spoofing attempts are eliminated with the Trusted Community feature. The Device Management feature provides control over all active devices within the system. Organization-specified Admin roles and Approval Groups are required for invasive Admin actions. 
PreVeil 	Administrator	•	Encrypted email, file storage, access to any folders/files shared with user.
•	Administrative functions including, Approval Groups, approving allow-listing (whitelisting), approving added/removing approved devices, adding/removing users, adding/removing administrators etc.	
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy 
Deepwave Digital Access Control

AC.L1-3.1.2
Limit information system access to the types of transactions and functions that authorized users are permitted to execute.
Control Summary
Deepwave Digital methods and enforcement mechanisms to limit information system access to the types of transaction and function that authorized users are permitted to execute are listed below in the Roles and Responsibility Matrix below. Users will only be permitted to access functions within their defined role. The list of individual users and their assigned roles is located here UserAccessRoles

Role	Responsibilities	Actions Permitted to Execute
PreVeil User	PreVeil users will only be able to access information shared with them by the PreVeil Administrator.  PreVeil users will be able to access only information that they have a “need-to-know”.  	•	Encrypted email
•	Access to any folders/files shared with user or created by user. Access types include:
o	View-Only: no sharing or downloading capabilities
o	Read-Only: no sharing, but has download capabilities
o	Edit: able to edit and download, but no sharing capabilities
o	Edit & Share: able to edit, download, and share
PreVeil Administrator	PreVeil Administrators are responsible for maintaining the safety and integrity of the PreVeil system and all authorized users/devices therein. PreVeil Administrators are the only users with access to the PreVeil Admin Console. 	•	Adding/removing authorized users and devices
•	Reviewing PreVeil admin logs, daily
•	Actions within the Approval Group(s)
•	Sharing files with users who have a “need-to-know” 
•	Evaluating security controls within the organization as they pertain to PreVeil monthly and update, as needed
•	Ensuring the PreVeil access list is kept up to date after terminations/transfers. 
•	Establishing and maintaining the PreVeil allow-list (whitelist)
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy
Deepwave Digital Access Control

AC.L2-3.1.3
Control the flow of CUI in accordance with approved authorizations.
Control Summary
Deepwave Digital has designated PreVeil as the only system used by Deepwave Digital for CUI transmission and storage. Only authorized individuals within Deepwave Digital will be permitted access to PreVeil and CUI within.  The list below outlines the roles and responsibilities for PreVeil and CUI data flow within the system. The list of individual users and their assigned roles is located here UserAccessRoles

Role	Responsibilities	Actions Permitted to Execute
PreVeil User	PreVeil users will only be able to access information shared with them by the PreVeil Administrator and/or other users. PreVeil users will be able to access only information that they have a “need-to-know”.  	•	Encrypted email
•	Access to any folders/files shared with user or created by user. Access types include:
o	View-Only: no sharing or downloading capabilities
o	Read-Only: no sharing, but has download capabilities
o	Edit: able to edit and download, but no sharing capabilities
o	Edit & Share: able to edit, download, and share
PreVeil Administrator	PreVeil Administrators are responsible for maintaining the safety and integrity of the PreVeil system and all authorized users/devices therein. PreVeil Administrators are the only users with access to the PreVeil Admin Console. 	•	Adding/removing authorized users and devices
•	Reviewing PreVeil admin logs, daily
•	Actions within the Approval Group(s)
•	Sharing files with users who have a “need-to-know” 
•	Evaluating security controls within the organization as they pertain to PreVeil monthly and update, as needed
•	Ensuring the PreVeil access list is kept up to date after terminations/transfers. 
•	Establishing and maintaining the PreVeil allow-list (whitelist)
PreVeil utilizes end-to-end encryption with user and device-based keys to enforce information flow restrictions for CUI.  End to end encryption with user and device-based keys provides tools for control of CUI at the user and device level. Only those granted access by Company Name administrators can view the information. End to end encryption provides complete security of data at the server level whether on-premises or in the cloud. PreVeil's Trusted Community feature can also limit access to CUI. 
PreVeil’s Trusted Community functionality restricts CUI flow to external 3rd parties that are managed by Deepwave Digital PreVeil administrators.
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy
Deepwave Digital Access Control

AC.L2-3.1.4
Separate the duties of individuals to reduce the risk of malevolent activity without collusion.
Control Summary
Deepwave Digital has established separate accounts for individuals whose duties and accesses must be separated to reduce risk of malicious activity or collusion. The list below reviews the different user types and accesses within Deepwave Digital. The list of individual users and their assigned roles is located here UserAccessRoles

Role	Responsibilities	Actions Permitted to Execute
PreVeil User	PreVeil users will only be able to access information shared with them by the PreVeil Administrator and/or other users. PreVeil users will be able to access only information that they have a “need-to-know”.   	•	Encrypted email
•	Access to any folders/files shared with user or created by user. Access types include:
o	View-Only: no sharing or downloading capabilities
o	Read-Only: no sharing, but has download capabilities
o	Edit: able to edit and download, but no sharing capabilities
o	Edit & Share: able to edit, download, and share
PreVeil Administrator	PreVeil Administrators are responsible for maintaining the safety and integrity of the PreVeil system and all authorized users/devices therein. PreVeil Administrators are the only users with access to the PreVeil Admin Console. 	•	Adding/removing authorized users and devices
•	Reviewing PreVeil admin logs, daily
•	Actions within the Approval Group(s)
•	Sharing files with users who have a “need-to-know” 
•	Evaluating security controls within the organization as they pertain to PreVeil monthly and update, as needed
•	Ensuring the PreVeil access list is kept up to date after terminations/transfers. 
•	Establishing and maintaining the PreVeil allow-list (whitelist)
CUI Allowed user 	Microsoft Windows users will only be able to access systems and information shared with them by the Administrator	•	Use approved applications
•	Access the internet
•	Use email
•	Edit personal files
•	Print documents
•	Access network resources
•	Change personal settings
•	Run non admin programs
Administrator	Microsoft Windows Administrators are responsible for maintaining the safety and integrity of the Windows system and all authorized users/devices therein. Microsoft 365 Administrators are the only users with access to the Azure Active Directory, Defender 365, and Intune Admin Console.	•	All user actions
•	Install software
•	Modify system settings
•	Access other user profiles
•	Disable web filtering
•	Install drivers
•	Manage user accounts
•	Access certain system folders
CUI Blocked user	CUI blocked users will not be able to login to any end point within the CUI Enclave user Group 	•	No Actions allowed. 

Personnel are granted system privileges based on job roles and responsibilities. Access authorizations are utilized and assigned to enable separation of duties within Deepwave Digital infrastructure using technical and procedural controls.
Deepwave Digital uses the PreVeil system for all CUI transmission and storage. PreVeil’s Approval Group model ensures that invasive system actions that could decrypt CUI can only occur with multiple authorizations from a pre-defined list of administrators. Only Administrators can access administrative functions and only a cryptographically controlled Approval Group of Administrators can perform system actions that would delete or decrypt enterprise data, thereby restricting intentional or unintentional execution of malicious activities. 
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy
Deepwave Digital Access Control

AC.L2-3.1.5
Employ the principle of least privilege, including for specific security functions and privileged accounts. 
Control Summary
Deepwave Digital implements the principle of least privilege within the information systems. Users are granted the minimum levels of access and privileges required to perform their duties. The list below reviews the roles and responsibilities for all Deepwave Digital resources within in scope Deepwave Digital systems:
Role	Responsibilities	Actions Permitted to Execute
PreVeil User	PreVeil users will only be able to access information shared with them by the PreVeil Administrator and/or other users. PreVeil users will be able to access only information that they have a “need-to-know”.  	•	Encrypted email
•	Access to any folders/files shared with user or created by user. Access types include:
o	View-Only: no sharing or downloading capabilities
o	Read-Only: no sharing, but has download capabilities
o	Edit: able to edit and download, but no sharing capabilities
o	Edit & Share: able to edit, download, and share
PreVeil Administrator	PreVeil Administrators are responsible for maintaining the safety and integrity of the PreVeil system and all authorized users/devices therein. PreVeil Administrators are the only users with access to the PreVeil Admin Console. 	•	Adding/removing authorized users and devices
•	Rev
•	iewing PreVeil admin logs, daily
•	Actions within the Approval Group(s)
•	Sharing files with users who have a “need-to-know” 
•	Evaluating security controls within the organization as they pertain to PreVeil monthly and update, as needed
•	Ensuring the PreVeil access list is kept up to date after terminations/transfers. 
•	Establishing and maintaining the PreVeil allow-list (whitelist)
CUI allowed user	Microsoft Windows users will only be able to access systems and information shared with them by the Administrator	•	Use approved applications
•	Access the internet
•	Use email
•	Edit personal files
•	Print documents
•	Access network resources
•	Change personal settings
Run non admin programs
administrator	Microsoft Windows Administrators are responsible for maintaining the safety and integrity of the Windows system and all authorized users/devices therein. Microsoft Administrators are the only users with access to the Azure Active Directory, Defender 365, and Intune Admin Console.	•	All user actions
•	Install software
•	Modify system settings
•	Access other user profiles
•	Disable web filtering
•	Install drivers
•	Manage user accounts
Access certain system folders
CUI Blocked user	CUI blocked users will not be able to login to any end point within the CUI Enclave user Group 	•	No Actions allowed. 
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy
Deepwave Digital Access Control

AC.L2-3.1.6
Use non-privileged accounts or roles when accessing non-security functions. 
Control Summary
Deepwave Digital has identified non-security functions and requires users to use non-privileged accounts or roles when accessing non-security functions.
Deepwave Digital administrators are assigned two separate accounts or account functionality is logically separated.    A list of all administrators can be found here UserAccessRoles.

Role	Responsibilities	Actions Permitted to Execute
PreVeil User	PreVeil users will only be able to access information shared with them by the PreVeil Administrator and/or other users. PreVeil users will be able to access only information that they have a “need-to-know”.  	•	Encrypted email
•	Access to any folders/files shared with user or created by user. Access types include:
o	View-Only: no sharing or downloading capabilities
o	Read-Only: no sharing, but has download capabilities
o	Edit: able to edit and download, but no sharing capabilities
o	Edit & Share: able to edit, download, and share
PreVeil Administrator	PreVeil Administrators are responsible for maintaining the safety and integrity of the PreVeil system and all authorized users/devices therein. PreVeil Administrators are the only users with access to the PreVeil Admin Console. 	•	Adding/removing authorized users and devices
•	Reviewing PreVeil admin logs, daily
•	Actions within the Approval Group(s)
•	Sharing files with users who have a “need-to-know” 
•	Evaluating security controls within the organization as they pertain to PreVeil monthly and update, as needed
•	Ensuring the PreVeil access list is kept up to date after terminations/transfers. 
•	Establishing and maintaining the PreVeil allow-list (whitelist)
Deepwave Digital uses PreVeil for all CUI transmission and storage.  PreVeil users have a single secure account in their organization with authorized elevated privileges. Administrative Approval Groups protect against inappropriate access or deletion by an individual Administrator PreVeil Security White Paper.Standard non-encrypted email and file storage/sharing can still be utilized for communication and storage of data that is not CUI. Company uses Google Drive, Microsoft One Drive, Gmail for business.
For additional information, please see the Deepwave Digital Customer Responsibility Matrix.
Referenced Policy
Deepwave Digital Access Control



## Control Number 1

Limit unsuccessful logon attempts.

### Control Summary
Company has configured its systems to limit unsuccessful logon attempts. Each Company  system has restrictions to limit unsuccessful logon attempts, please see the table below for additional information:

| System | Unsuccessful Logon Attempt Prohibition Actions |
|:-------|:------|
| Acme Software | This policy is designed to establish guidelines for limiting unsuccessful login attempts to Acme software systems, with the aim of enhancing security, preventing unauthorized access, and protecting sensitive data. The maximum number of consecutive unsuccessful login attempts to Acme software systems is set at three (3) attempts. After three (3) consecutive unsuccessful login attempts, the user's account will be temporarily locked to prevent further login attempts. |
| Windows Endpoints | The company blocks unsuccessful logon attempts to endpoints. After 10 unsuccessful logins endpoints will wipe all data. |

For additional information, please see the Company Security Implementation document.

### Referenced Policy
Control Access Policy



#
#
#
# 
# Dillinger
## _The Last Markdown Editor, Ever_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

