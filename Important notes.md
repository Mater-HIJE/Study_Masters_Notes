In today’s digital age, information is power. Whether you’re a journalist, researcher, cybersecurity expert, or just a curious individual, having access to the right information-gathering tools can make a world of difference. In this blog post, I’ll explore a comprehensive list of information-gathering tools that are accessible and user-friendly, empowering you to become a digital detective in your own right.

![IMAGE](https://cdn.dribbble.com/users/1954667/screenshots/4166040/gather-customer-data-2.gif)

So... information gathering is a stone-base in pentesting. with no information, there nothing to do. Because that, we starting with information gathering. the goal of this **long** session not just to know to to gather information only, ==but to master gathering.==

Its meaningless to start gathering any information without know where your device are and which network that located on. Before we start with this session you need to know what IP signed to your device and some other information

# Know your device

## 1. ifconfig

`ifconfig` is a system administration utility in Unix-like operating systems for network interface configuration. It informant you in details about your ethernet connection (IP & MAC) and device loop setting.

> While using Kali as VM or WSL note that Kali is in a deferent network from your real device is, because NAT that VMware using 

## 2. iwconfig

`iwconfig` do the same thing as ifconfig. but this command for wireless connection.

## 3. netstat

`netstat` is a command-line **tool** for stating all connection processes that your device is running, monitoring and troubleshooting computer network issues.

You can use these commands to utilize -a bit...-this tool:

`netstat -ano`
* Shows all connection in a list form.

`netstat -r`
* Shows routing table of your device.

## 4. route

`route` displays and modifies the entries in the local IP routing table. If used without parameters, **route** displays help at the command prompt.

## ==5. ip==

Yeah. `ip` is a command in Debian Linux. It become easier to do many things with this tool, but I will tell you how yo use it ==**ONLY**== to gather information about your device

`ip a` 
This command will do the same thing as ifconfig

`ip n`
This shows device's ARP table

`ip r`
do as `route` do

_______________________________________________________________

**So The rest of this session is divided into ==two main parts==**:

1. Passive information gathering
2. Active information gathering
