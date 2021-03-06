|||
|---|---|
|**ID**|**C0005**|
|**Objective(s)**|[Communication](../communication)|
|**Related ATT&CK Technique**|None|


WinINet
=======
The Windows Internet (WinINet) application programming interface (API) is used by malware to interact with FTP and HTTP protocols to access Internet resources.

The methods below are those of most interest in malware analysis. Details can be found at [[1]](#1). 

Methods
-------
|Name|ID|Description|
|---|---|---|
|**InternetConnect**|C0005.001|Opens an FTP or HTTP session for a given site.|
|**InternetOpen**|C0005.002|Initializes an application's use of the WinINet functions.|
|**InternetOpenURL**|C0005.003|Opens a resource specified by a complete FTP or HTTP URL.|
|**InternetReadFile**|C0005.004|Reads data from an open Internet file (URL data).|
|**InternetWriteFile**|C0005.005|Writes data to an open Internet file.|

References
----------
<a name="1">[1]</a> https://docs.microsoft.com/en-us/windows/win32/wininet/wininet-functions
