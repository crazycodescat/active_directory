# 01 Installing The Domain Controller

1. Use `sconfig` to :
    - Change the hostname
    - Change the ip addres to static
    - Change the DNS server to our own IP address

2. Install the Active Directory Windows Feature

````shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
````