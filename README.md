# <p align="center">INFORMATION GATHERING...</p>

## AIM :

To perform information gathering techniques using kali linux.

## PROCEDURE :

### STEP 1 :

Install kali linux either in partition or virtual box or in live mode.

### STEP 2 :

Investigate on the various categories of tools as follows:

### STEP 3 :

Open terminal/browser and try execute necessary commands/use url to perform information gathering.

## Pen Test Tools Categories :  

Following Categories of pen test tools are identified for information gathering:

  Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

  #### http://www.whois.com/whois 
  
  Website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT :

![out1](https://github.com/anto-richard/InformationGathering/assets/93427534/2a3b8d33-0a4e-4c5e-a974-b34465da292b)

## Finding IP address :

Ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```

## Output :

![out2](https://github.com/anto-richard/InformationGathering/assets/93427534/98adb770-1d24-4f23-bfc6-057218a9ad53)

## Finding Hosting Company :

Get further detail by using ip2location.com website.

## Output :

![out3](https://github.com/anto-richard/InformationGathering/assets/93427534/9a6f7240-5d63-4df1-9bcc-7ac9472db61a)

## History of the website :

## Output :

#### https://web.archive.org/

![out4](https://github.com/anto-richard/InformationGathering/assets/93427534/404e45d0-caa6-4669-8298-5de125ded489)

# Webserver Fingerprinting :

## Netcat :

```
nc 172.17.52.118 80
```

## Output :

![out5](https://github.com/anto-richard/InformationGathering/assets/93427534/bc4923f0-3123-4a33-a0bc-2a9df99e245d)

## nmap :

```
nmap -p 21 -sV --script=banner ftp.vim.org
```

## Output :

![out6](https://github.com/anto-richard/InformationGathering/assets/93427534/b0f4b5f9-71ca-4dd0-99b7-175747314bdf)

## Whatweb :

```
whatweb infosys.com
```

```
whatweb zoho.com
```

```
whatweb -v -a 3 172.17.52.201
```

## Output :

![out7](https://github.com/anto-richard/InformationGathering/assets/93427534/1864ea7a-f52a-4387-8519-0579b8602326)

![out8](https://github.com/anto-richard/InformationGathering/assets/93427534/0438c4c2-2f10-4662-a19f-0ca4d5735c07)

## httprint :

```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```

## Output :

![out9](https://github.com/anto-richard/InformationGathering/assets/93427534/5d6b790a-e8b5-4494-815f-e7d8148e6e86)

# Tracing the Location :

## TCP Traceroute :

```
sudo traceroute -T www.saveetha.ac.in
```

## Output :

![out10](https://github.com/anto-richard/InformationGathering/assets/93427534/4af44e35-e01f-411b-9c92-199b4f6ba2a9)

## UDP Traceroute :

```
sudo traceroute -U www.saveetha.ac.in
```

## Output :

![out11](https://github.com/anto-richard/InformationGathering/assets/93427534/a26f88c2-338a-4632-a26d-bf76d2040b51)

## ICMP Traceroute :

```
sudo traceroute  www.saveetha.ac.in
```

## Output :

![out12](https://github.com/anto-richard/InformationGathering/assets/93427534/4e5d74c7-c464-4497-86e1-7eee6178c17e)

## RESULT :

The information gathering techniques tools/procedure were identified successfully.

