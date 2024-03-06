# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
### OUTPUT:

![Screenshot_2024-03-05_02-53-41](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/858ba6a4-ea23-4469-916f-40ddd47af6af)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
### OUTPUT:

![Screenshot_2024-03-05_02-59-50](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/f44fd73f-9af8-408d-8eb7-be6b0270ea3a)

## History of the website:
### OUTPUT:

![Screenshot_2024-03-05_03-04-45](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/01f08d98-7e49-4f2b-a145-f5f6adb5501f)

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

### OUTPUT:

![Screenshot_2024-03-05_03-11-56](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/2875aba9-9c69-4419-b585-40d228728dc8)

## nmap:
### OUTPUT:

![Screenshot_2024-03-05_03-15-01](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/610e20d5-e6d5-40e6-b472-91badb39bdb8)

## Tracing the Location
## UDP Traceroute:
sudo traceroute -U www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-16-52](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/71d1a624-ee85-4d80-85d5-98a74d7e34d2)

## ICMP Traceroute:
sudo traceroute  www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-18-07](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/bf644d5f-3474-438c-93c8-6d189c2bea53)


## TCP Traceroute:
sudo traceroute -T www.google.com
### OUTPUT:

![Screenshot_2024-03-06_03-19-44](https://github.com/MaheshS03/EH-EX02-InformationGathering/assets/128498431/2f12d67e-82e6-4ae9-9ce9-24c6d043ca87)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
