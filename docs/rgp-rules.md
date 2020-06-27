## Roboget - Packages engine v0.1.7
#### last updated December/21/2019 


Supported sections
---
```

[Info]
		This section provides Information only

----------------------------------------------------------------------------------------------------------

[Links] 
		All links goes to the [Links] section

----------------------------------------------------------------------------------------------------------

[Variables]

	Url1=http://www.imirin.com/files/36/Roboget/47/Roboget.zip


----------------------------------------------------------------------------------------------------------
```

Supported commands
---
```

GetFile: 
		Link1=GetFile|http://www.imirin.com/files/36/Roboget/47/Roboget.zip|PARAMTER
		or using [Variables]
		Link2=GetFile|%Url1%|PARAMTER

		Supported parameter: 
		|P for setting the PRIOR/Default Browser download
		|D for setting download in a DIRECT download
		|M for setting a Mirror
		|RETURN for exiting download function after last link

----------------------------------------------------------------------------------------------------------

GetPortable: 
		Link1=GetPortable|http://www.imirin.com/files/36/Roboget/47/Roboget.zip|PARAMTER
		
		Supported parameter: 
		|P for setting the PRIOR/Default Browser download
		|D for setting download in a DIRECT download
		|M for setting a Mirror

----------------------------------------------------------------------------------------------------------

Detect: 
		Link1=Detect|File system or registry key
		Optional you can use the Detect command, to check whether an package is Installed


----------------------------------------------------------------------------------------------------------

Run files: 
		File1=RunFile|<path to application>?
		
----------------------------------------------------------------------------------------------------------

Execute command-line: 

		File1=RunCommand|<command>

		Supported parameter: 
		|SHOWCLI for showing a Windows command-line interface during execution
		
----------------------------------------------------------------------------------------------------------

Kill process:
		File1=TaskKill|<process name>|WARNING
		Used to terminate tasks by process id (PID) or image name

		Supported parameter: 
		|WARNING for showing optional hint
		
----------------------------------------------------------------------------------------------------------

```
