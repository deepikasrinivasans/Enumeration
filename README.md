# EX 03 Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:
## site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![1ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/94014f92-c78c-44b8-a21c-244bd1481f5f)
## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![2ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/76f610d7-763e-4ca6-b534-076840a9fc61)
## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![3ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/8e8d9cb9-f6f9-4555-8625-829b92b06a93)
## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![4ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/e6555a66-5ba2-4a46-a80f-da43869e8525)


## intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![5ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/79944ffc-a9a8-4e9a-af8d-bf32977dc6cf)


## link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![6ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/d59ecd11-c990-432b-8a13-526fcad94464)


## cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.


![7ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/d91fcd8a-dd37-4cfa-aa4f-e71f58e7483e)

## DNS Recon
![8ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/41423be6-3531-49e8-8653-a53e967afb3e)

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## dnsenum
![9ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/7c1c1205-f693-49ad-8597-00a2e9881b32)
![10ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/0f878d3f-c14e-4ece-a67e-4992517789fb)

Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
![12ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/d68554b8-2bd5-4475-ab37-c17ba521d4c7)

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
select any username in the first column of the above file and check the same
## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
![13ethical](https://github.com/deepikasrinivasans/Enumeration/assets/119393935/9e28e1c0-c9cd-437c-b7aa-5d146ebe5405)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

