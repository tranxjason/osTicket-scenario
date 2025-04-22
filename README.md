<p align="center">
  <img src="https://github.com/user-attachments/assets/2720abbc-06da-4811-be45-eec6c5e6e64b"/>
</p>

<h1>osTicket: Ticket Resolution and Troubleshooting</h1>
This project is designed to show examples through osTicket, a powerful open-source help desk solution, focusing on ticket resolution and troubleshooting. I will delve into the ticket lifecycle, from initiation to resolution, and examine troubleshooting strategies to address common issues. This project aims to empower IT professionals, help desk agents, and support teams to navigate challenges seamlessly, ensuring a smooth and effective support experience for end-users.
<br />

<h2>Key Objectives</h2>

__Mastering Ticket Resolution__

- <b>Microsoft Azure (Virtual Machines/Compute)</b>

__Effecient Troubleshooting Techniques__

- <b>Explore and implement troubleshooting strategies for common IT issues, ensuring quick and effective problem-solving.</b>

__Enhancing User Satisfaction__

- <b>Learn how to provide timely and effective support to end-users, fostering a positive experience and minimizing downtime.</b>

__Building a Knowledge Base__

- <b>Develop a comprehensive knowledge base that documents common issues and their resolutions, empowering both support teams and end-users.</b>

<h2>Environment and Technologies Used</h2>

- <b>Microsoft Azure (Virtual Machines)</b> 
- <b>Remote Desktop Connection</b>
- <b>Active Directory Domain Services</b>
- <b>osTicket</b>

<h2>Operating Systems Used</h2>

- <b>Windows 10 Pro</b> 
- <b>Windows Server 2022</b>

<h1>Tickets</h1>

<h3>Scenario A: Granting Admin Rights</h3>

User: James Holden 

Background: 

James Holden, a senior software developer, has successfully obtained approval for elevated administrative rights. As the IT administrator, your task is to grant James the necessary permissions while ensuring a secure and controlled activation process.

![jim](https://github.com/user-attachments/assets/a86f779f-9b8a-4d78-ab99-03d3d33a01c9)

<h3>Approach to Resolution:</h3>

Verification

- <b>Validate James's identity and admin rights approval.</b>

Access Control Configuration:

- <b>Once verification is done, modify James's user profile and assign the appropriate administrative privileges.</b>
- <b>Ensure that his machine allows him remote access.</b>

![mydomainjames](https://github.com/user-attachments/assets/d6aa5745-5591-49ec-bbed-89b7a1988d0c)

Configure specific permissions based on James's approved request, such as adding him to the Remote Desktop Users Group

![jamesholdenusers](https://github.com/user-attachments/assets/08d9798f-419f-4240-be15-310fb0e8339d)

Communication:

- <b>Inform James that his admin rights have been granted successfully.</b>
- <b>Include a summary of the specific permissions he now holds and any relevant guidelines for responsible use.</b>

Documentation & Closure:

- <b>Document the completion of the admin rights activation in osTicket. -Close the ticket, indicating that the task has been completed, and provide documentation for future audits or inquiries.</b>

![jamesend](https://github.com/user-attachments/assets/d9443c06-a7fc-4ea0-b53a-bbe2a192b0b4)

<h3>Scenario B: Addressing Slow System Performance</h3>

User: Camina Drummer

Background:

Camina Drummer, a marketing manager, submits a ticket through osTicket, reporting a low memory warning and persistent slow performance on her workstation. As the IT helpdesk agent, your objective is to diagnose and resolve the issue to enhance Camina's overall system responsiveness.

![camina](https://github.com/user-attachments/assets/6a0532ce-34fc-4cc3-87b8-2eafaa1f26d2)

<h3>Approach to Resolution:</h3>

Initial Assessment:

- <b>Engage in a threaded discussion to gather more information about the specific performance issues Camina is encountering.</b>
- <b>Request details such as recent software installations, background processes, and any error messages she might have encountered.</b>

![camina2](https://github.com/user-attachments/assets/e419d1b4-624b-4a11-8a40-76effbb01643)

Remote Diagnosis:

- <b>Engage in a threaded discussion to gather more information about the specific performance issues Camina is encountering.</b>

<h3>Specific Problem Identified:</h3>

Camina Drummer's workstation is experiencing slow performance and low memory warnings mainly due to not having enough RAM for her demanding marketing applications. These include graphic design and video editing software, along with many browser tabs open at once. A lack of regular cleanup, like deleting temporary files and optimizing disk space, has also made the system slower over time.

<h3>Resolution Steps:</h3>

- <b>Go to add or remove programs and delete any unnecessary applications.</b>

![app remove](https://github.com/user-attachments/assets/261b0451-caca-40c0-a5f1-e84bade488b4)

Check Task Manager to identify resource-intensive processes, unnecessary apps at startup, and potential bottlenecks affecting system performance.

- <b>Empty the recycling bin to free up some disk space.</b>

![recyling bin](https://github.com/user-attachments/assets/d914d622-6c82-495f-971d-fa4b9b5d2e68)

Open the Disk Cleanup application and perform a cleanup.

![disk cleanup](https://github.com/user-attachments/assets/8a5b36d7-b22c-407a-8e07-ce7167ee4d14)

Go to Windows Features and turn off features not needed by the user

- <b>After performing the tasks, diagnose the performance of the workstation.</b>

![windows features](https://github.com/user-attachments/assets/01ad2c59-52fe-4e7f-b8c5-04ec438060bb)

Documentation & Closure:

- <b>Inform Camina through osTicket of the initial assessment findings.</b>
- <b>Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.</b>
- <b>Close the ticket within osTicket when Camina confirms the satisfactory resolution of the slow system performance issue or when the case is deemed resolved based on the follow-up assessments.</b>

![caminaclose](https://github.com/user-attachments/assets/6fa24d74-bd30-4ad1-8b9f-82ee0030a2ae)

<h3>Scenario C: Laptop Camera Not Working on Windows 11</h3>

User: Alex Kamal

Background:

Alex Kamal, a sales representative, submits a ticket through osTicket, reporting that the integrated camera on his laptop is not functioning properly after upgrading to Windows 11. Alex relies on video calls for client meetings and needs a prompt resolution to ensure uninterrupted communication.

![alex kamal](https://github.com/user-attachments/assets/cf372fe3-64bf-43ca-b23e-fe59123b955e)

<h3>Approach to Resolution:</h3>

Initial Assessment:

- <b>Engage in a threaded discussion within osTicket to gather more information about the issue.</b>

![alex2](https://github.com/user-attachments/assets/d258a637-fb24-430a-9a76-ae5b1dfe76b0)

Remote Diagnosis:

- <b>Access Alex’s laptop through a remote desktop connection.</b>
- <b>Check device manager if the necessary drivers are installed.</b>

![camera](https://github.com/user-attachments/assets/bf105a9d-e225-4bcb-a5d5-0e727106e0c4)

<h3>Specific Problem Identified:</h3>

Upon conducting a remote diagnostic session with Alex Kamal's laptop, it was discovered that the integrated camera is not recognized by the Windows 11 operating system. This issue seems to stem from outdated camera drivers that are incompatible with Windows 11.

Communication:

- <b>Inform Alex through osTicket that the initial assessment indicates a potential driver-related issue with the camera after the Windows 11 upgrade.</b>

![alex3](https://github.com/user-attachments/assets/d7940525-c6c1-4cbc-afba-ddb862736b53)

<h3>Resolution Steps:</h3>

- <b>Download the camera drivers from the manufacturers website and install the drivers manually.</b>
- <b>Reboot the system after making the changes to ensure proper implementation.</b>

![drivers](https://github.com/user-attachments/assets/a5c02697-c82b-401b-bdf0-85616dddd1c8)

Documentation & Closure:

- <b>Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.</b>
- <b>Close the ticket within osTicket when Alex confirms the satisfactory resolution of the laptop camera issue.</b>

![alexend](https://github.com/user-attachments/assets/7f5c534b-e775-415c-9b4a-4969e9f838e4)

<h3>Scenario D: Resolving Email Synchronization Issues</h3>

User: Amos Burton

Background:

Amos Burton, a sales executive, submits a ticket via osTicket, reporting that his email is not synchronizing properly across his devices. As the IT help desk agent, your goal is to troubleshoot and resolve the synchronization issue to ensure seamless access to his emails across all platforms.

![amos b](https://github.com/user-attachments/assets/cd1f00d9-3f45-4f76-92d0-fb60b132a2ec)

<h3>Approach to Resolution:</h3>

Initial Assessment:

- <b>Initiate a detailed conversation with Amos through osTicket, asking for specifics about the devices he uses, the email client or service, and any error messages he has encountered.</b>
- <b>Determine if the issue started after a particular update or change in settings.</b>
- <b>Establish a remote desktop connection to further diagnose the problem.</b>

![amos1](https://github.com/user-attachments/assets/5261cc7c-9915-486c-8c66-d37a86747ff5)

<h3>Specific Problem Identified:</h3>

During the remote diagnosis, it's discovered that Amos's smartphone and tablet are not set to use IMAP for his email account, which is essential for synchronizing emails across multiple devices. Instead, they are configured with POP3, leading to emails being downloaded to a single device and not being accessible on others.

<h3>Resolution Steps:</h3>

- <b>Change the email settings from POP3 to IMAP on both his smartphone and tablet.</b>
- <b>Ensure that Amos's laptop is also configured to use IMAP for his email account, ensuring consistency across all devices.</b>

![popimap](https://github.com/user-attachments/assets/16cfac9f-fe7a-4e8d-8d6d-130123bd5c9c)

Test email synchronization by instructing Amos to send a test email to himself and check if it appears across all his devices.

Documentation & Closure:

- <b>Document all steps taken to resolve Amos's email synchronization issue within osTicket, including the initial problem identification, communication logs, and the resolution process.</b>
- <b>Close the ticket within osTicket once Amos confirms the issue is resolved to his satisfaction, ensuring a record of the solution is available for future reference.</b>

![amosimpap](https://github.com/user-attachments/assets/0a833b2a-f2fd-45af-bd34-65793684f8e4)

<h3>Scenario E: Addressing Printer Connectivity Problems</h3>

User: Anderson Dawes

Background:

Anderson Dawes, an account manager, submits a ticket through osTicket, indicating that he cannot connect to the network printer from his laptop. The printer is essential for his role, as he frequently needs to print contracts and reports for clients. As the IT help desk agent, your task is to diagnose and rectify the connectivity problem to restore Anderson's printing capabilities.

![anderson d](https://github.com/user-attachments/assets/6459c6cf-09fa-4c70-89ad-edd6db6d1c03)

<h3>Approach to Resolution:</h3>

Initial Assessment:

- <b>Communicate with Anderson and ask further questions about the problem.</b>
- <b>Establish a remote desktop connection to Anderson’s workstation to further diagnose the issue.</b>

![anderson2](https://github.com/user-attachments/assets/244ee7e1-8747-4859-b8a6-f01139ed3313)

<h3>Specific Problem Identified:</h3>

The primary issue hindering Anderson Dawes from connecting to the network printer is an incorrect printer IP address configuration on his laptop. After the recent network upgrade, the IP addresses of several devices, including printers, were changed to accommodate the new networking schema. However, Anderson's laptop retained the old IP address for the printer, leading to failed connection attempts. This misconfiguration is a common oversight following network modifications, especially if devices are manually configured or if the update communication does not reach all users effectively.

<h3>Resolution Steps:</h3>

- <b>Update Printer IP Address on Anderson's Laptop</b>
- <b>This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address. This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address.</b>

![printerport](https://github.com/user-attachments/assets/922a5e91-a30b-4d27-b7f1-075923515e3d)

Verify connectivity by attempting to print a test page.

Documentation & Closure:

- <b>Document the steps taken to resolve the issue within osTicket Additionally, update any internal IT documentation to reflect the new network configuration and troubleshooting steps for related issues.</b>
- <b>Close the ticket once Anderson confirms the issue is resolved.</b>

![andersoneend](https://github.com/user-attachments/assets/c8fafc7f-084f-40a1-b9e4-e01616aa2381)

<h2>Key Objectives</h2>

This project serves as an essential guide for IT help desk agents and support teams, offering in-depth scenarios from granting administrative rights to resolving complex email synchronization issues. It highlights the critical role of a structured approach in IT troubleshooting, emphasizing key insights:

- <b>Structured Problem-Solving: Importance of a step-by-step approach from problem identification to solution documentation.</b>
- <b>User-Centric Communication: Keeping users informed is essential. Keeping users updated is key to trust and a positive experience.</b>
- <b>Adaptability and Continuous Learning: The need for IT professionals to stay adaptable and continuously learn to tackle a wide range of issues.</b>
- <b>Documentation and Knowledge Sharing: Essential for building a knowledge base that facilitates quicker future resolutions.</b>

These points highlight the essentials of effective IT troubleshooting: methodical problem-solving, clear communication, adaptability, and thorough documentation.


