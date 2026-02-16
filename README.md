# OSINT-SpiderFoot

## Objective

The OSINT-SpiderFoot project aimed to set up and use this open source intelligence automation tool for threat intelligence in controlled environment. The primary focus was to install SpiderFoot on Kali Linux VM and use it to map threat intelligence data for a known email address.

### Skills Learned

- Installation of SpiderFoot tool with use of terminal on Linux based VM.
- Use of SpiderFoot to complete threat intelligence data mapping.
- Ability to read the results of scan.
- Enhanced knowledge of OSINT automation tool.

### Tools Used

- Kali Linux virtual machine as controlled environment.
- Linux terminal to install and run cybersecurity tools.
- SpiderFoot to map threat intelligence data.

## Steps

1. I went to google.com and searched for SpiderFoot. Second result took me to a github reposytory of <a href="https://github.com/smicallef/spiderfoot">SpiderFoot</a>.
2. I have downloaded the zip file to the Kali Linux VM.

<img width="1317" height="656" alt="image" src="https://github.com/user-attachments/assets/1dec0dc1-e5f8-4b28-90d4-dbe786f72734" />

3. I have extracted the files from the zip file in the /Downloads directory.

<img width="576" height="216" alt="image" src="https://github.com/user-attachments/assets/52f125a7-fef2-4ee6-8e82-1542725123c9" />

4. I have initiated the SpiderFoot tool. It is very important to use the correct options with the command.

<img width="1773" height="636" alt="image" src="https://github.com/user-attachments/assets/037c1173-b7ee-49bf-b6bc-af6af37d92bb" />

5. I have opened the provided URL in web browser, selected 'New Scan' from the menu, set up 'Scan Name' and 'Scan Target' and started scan. We can select from range of different target types i.e. domain name, IPv4 address, IPv6 address, hostname, subnet, e-mail address, phone number, human name, username, etc. 

<img width="1277" height="858" alt="image" src="https://github.com/user-attachments/assets/c7993bf0-6652-45e3-84c1-2c095507d90b" />

6. Scan run for couple of minutes before returning the results.

<img width="1511" height="891" alt="image" src="https://github.com/user-attachments/assets/51673f6a-d2d1-4a7a-bf42-24e8c8acb2d1" />

In conclusion email in question had total of 15 hits across multiple sites with one distinct correlation showing that email might have been hacked on two different application domains.


