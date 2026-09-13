# Kernel-dll-injector
Kernel-Mode Driver that loads a dll into every new created process that loads kernel32.dll module </br>
Code is based on reversed rootkit Sirifef aka max++, one of the most well coded rootkits for Windows Operating Systems of all time </br>
# How to use
Project is compiled using VS 2013 and WDK 8.1, if you use a new version simply upgrade the whole project, should work just fine </br>
Windows x86 version only </br>
Place your dll in whatever location, compile the driver with the new dll path </br>
Load the driver </br>
Dll should inject in every new process that needs to load kernel32.dll </br>
# Limitations
Not compatible with x64, but adaptability its pretty much straightforward </br>
Not sure about the impact the whole process injection can cause on the system, tested the project for about 1 hour and no BSOD's whatsoever </br>
# Update
Historical security research project — 2018
This project was developed as part of Windows kernel research and malware reverse engineering. It demonstrates kernel-mode process manipulation and DLL injection techniques based on analysis of the Sirifef rootkit.
This repository is preserved as an archival example of my earlier Windows internals/security research and is no longer actively maintained.
