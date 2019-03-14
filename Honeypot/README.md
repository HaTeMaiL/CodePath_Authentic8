# Project 9 - Honeypot

Time spent: **7** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

## Experience

* Which Honeypot(s) you deployed
  - I deployed the first honeypot, the honeypot directed at http through Dionaea.
* Any issues you encountered
  - There were countless issues encountered using the command line on the host machine rather than the GCP Dashboard. In some cases, a command had to to run two or three times before it didn't provide an error. In other cases, the only way to progress was to enter the command through the GCP console.
  - My biggest problem came in that with multiple tries with the first mhm-admin vm I made. I couldn't get a honeypot running that would be attacked. I consistently made honeypot VMs that had no attacks. Ultimately, I had to start from square one and build the system all over again and not just new VMs.
* A summary of the data collected: number of attacks, number of malware samples, etc.
  - At the time of saving the JSON file, there were 1104 attacks with a majority coming from the United States and then Vietnam, the Netherlands, and Taiwan/China.
  - While taking note of the other information, the Attacker IPs remained the same with India replacing Taiwan after refreshing the page while the number of attacks increased. However, it showed that the top five attacked ports where the following in this order: 8088 (HTTP), 23 (Telnet), 110 (POP3), 445 (Microsoft-DS), 5060(SIP). This meant that most went through the pcap protocol, then the smbd protocol and SipCall/SipSession protocol.
  
 ![Attacks](https://github.com/HaTeMaiL/CodePath_Authentic8/blob/master/Honeypot/mhm-honeypot-1_attacks.PNG)
* Any unresolved questions raised by the data collected
  - 

## Notes

Describe any challenges encountered while doing the work
* Some other steps had to be taken that weren't directly outlined in the instructions but rather were only understood to be necessary after countless efforts, redirection, and rereadings of the instructions until there was an understanding that there was something missing in order to accomplish a step.
