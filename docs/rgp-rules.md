## Roboget - Packages engine v0.1.5 
#### last updated December/07/2019 


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
		Optional you can use the Detect command, to check wheter an package is Installed



```

