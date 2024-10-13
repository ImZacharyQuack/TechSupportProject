
# Technical Support Project

Grade - 100%
&emsp;

## Introduction
During the final three weeks of September, you will, during class time, work either on your own or as a group of two to do each of the three tasks below. Make sure that you read all the requirements (task 1 through to 3) before starting on the project. Therefore, before you even start copying and configuring machines, plan what it is you are going to do and create a short risk management plan (see task 3 below).

You are asked to submit just one file. This will contain the report plus two appendices, one for task 1 and one for task 2.

Here are the three tasks....

&emsp;
## Task One
Copy clones from P:\Clones and create a workgroup comprising of three computers, two with Windows 10 and one with Windows 11.

They should...

- be on an internal virtual switch (not vmnet 2, 3, 4 or 5)
- have static IP addresses
- have Internet connectivity via a PfSense firewall.
- contain five user accounts: Leon, Lucy, Luke, Lily and Leo (These accounts all - start with "L" to remind us that they are local user accounts.)
- one of the machines should contain a share with data that is shared to the other two machines.

Take screenshots as evidence of your work.

&emsp;
## Task Two
Copy a Windows Server (but not the Core version) from P:\Clones and create a domain environment with a single Windows Server 2022 domain controller. Then use the three computers of Task 1 (so two Windows 10 and one Windows 11 machine).

Make sure that...

- the three computers of Task 1 are all on the same internal virtual switch (not vmnet 2, 3, 4 or 5)
- you make use of a static IP address on the domain controller and promote it to a domain controller using a domain name of your choosing
- you create five domain user accounts on the domain controller, namely David, Debbie, Dominic, Diana and Dean (These all start with the letter "D" to remind us that they are domain accounts.)
- you can log in as David, Debbie, Dominic, Diana and Dean from any of the Windows clients.
- the domain controller has a share that all machines can access finally (that is, the last thing you do) add a PfSense firewall and check that all six machines can now access the firewall.
Take screenshots as evidence of your work.

&emsp;
## Task Three
Write a short report roughly 2 pages in length that documents

- your initial risk management plan, with its emphasis on risk conditions, likelihood, impact, exposure and priority (see week 2)
- where your virtual machines are stored (name of the student workstation e.g. S267-12 and the path e.g. D:\Student Projects\CS163\Bob Hope\ProjectVMs)
- the network of task 1 and the network of task 2 (e.g. computer names, IP addresses and so on)
- the problems encountered and the solutions implemented reflections of how you found this project

