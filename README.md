# Home Lab Setup Running Active Directory
Built a virtual home lab using VirtualBox and Windows Server 2019 to simulate an enterprise IT environment. Configured Active Directory, created users with PowerShell, and connected a Windows 10 client to the domain. Gained hands-on experience in system administration and cybersecurity fundamentals.

Summary of the project is as follows:
The setup Home Lab running Active Directory (AD) depicts a basic Windows networking environment with AD with a few networking services resembling how a corporate network would be. Domain controller VM housed AD with two network adapters (NICs) in which one was connected to the outside internet and one was connected to the VMs private network in which the clients would be connected to. IP was assigned to the internal network while the external network used the same IP as the home router. Server was then named and AD was installed and its domain named. NAT and Routing were then configured allowing clients on the private network to reach the internet through the domain controller. DHCP was then setup on the domain controller allowing automatic IP identification from the newly created Win10 VM. PowerShell script was then ran in which created 1000 users in the AD. Windows 10 Client VM was then created which was then connected to the private virtual box network. 



Download links:

Oracle VirtualBox: https://www.virtualbox.org/wiki/Downloads
Windows Server 2019 ISO: https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019
New Users and PowerShell script: https://github.com/joshmadakor1/AD_PS/archive/master.zip 
Direct link to the PowerShell script: https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1 

Link to the complete Tutorial: https://www.youtube.com/watch?v=MHsI8hJmggI&list=PLqBeiU46hx1H--SNfTrohTOWeqkK-M2Y0&ab_channel=JoshMadakor 
