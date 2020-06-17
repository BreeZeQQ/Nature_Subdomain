# Nature_SubdomainEnumeration
In-depth Subdomain Enumeration with Combined Tools

</br>Simple script for in-depth subdomain enumeration with </br>
**-> Sublist3r</br>
-> Amass</br>
-> Aquatone</br>
-> Subfinder</br>**
Use every tool and give output for each one.</br>
**Combine Subdomains into one large and Unique Subdomain file.**</br>
**Find Reverse-IP for each Subdomain and append it to FINAL result file.**</br></br>
**Give FINAL result file contain BIG,UNIQUE,TOTAL Subdomain included Reverse-IP adresses.**</br></br>
**After giving FINAL result file script start detailed port(80, 81, 443, 591, 2082, 2087, 2095, 2096, 3000, 8000, 8001, 8008, 8080, 8083, 8443, 8834, 8888) scan and give results.**

#### Install Requirements
`apt-get install sublist3r` Install Sublist3r</br>
`wget "https://github.com/michenriksen/aquatone/releases/download/v1.7.0/aquatone_linux_amd64_1.7.0.zip"`</br>
`unzip aquatone_linux_amd64_1.7.0.zip`</br>
`mv aquatone /usr/bin/aquatone`</br>
<br>`apt-get install amass` Install Amass
<br>`gem install aquatone`  Install Aquatone
<br>`apt-get install golang` Install Golang for Subfinder
<br>`GO111MODULE=on go get -v github.com/projectdiscovery/subfinder/cmd/subfinder` Install Subfinder

#### Prerequisites
----</br>

#### Usage
  ```sh
$ chmod +x nature.sh
$ /nature.sh <domain>
```
  
