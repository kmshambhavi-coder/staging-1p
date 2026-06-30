<p align="center">
<img src="./Copy of OS.png" 
     alt="Copy of OS" width="200"/></p>
     
# Copy of OS

### Description
User activity on machine

### Rules
|Primary Source|Secondary Source|Third Source|Forth Source|Type|Primary Destination|Secondary Destination|Third Destination|Forth Destination|
|--------------|----------------|------------|------------|----|-------------------|---------------------|-----------------|-----------------|
|DestinationHostName||||Linked|DestinationAddress||||
|DestinationHostName|DestinationAddress|||Linked|FileName||||
|SourceHostName||||Linked|SourceAddress||||
|SourceUserName|SourceHostName|SourceAddress||Type|DestinationHostName|DestinationAddress|SourceUserName||
|SourceUserName||||Linked|SourceHostName|SourceAddress|||
