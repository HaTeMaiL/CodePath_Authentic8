# Project 9 - Honeypot

Time spent: **7** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

## Experience

* Which Honeypot(s) you deployed
  - I deployed the first honeypot, the honeypot directed at http through Dionaea.
* Any issues you encountered
  - There were countless issues encountered using the command line on the host machine rather than the GCP Dashboard. In some cases, a command had to to run two or three times before it didn't provide an error. In other cases, the only way to progress was to enter the command.
  - Some other steps had to be taken that weren't directly outlined in the instructions but rather were only understood to be necessary after countless efforts, redirection, and rereadings of the instructions until there was an understanding that there was something missing in order to accomplish a step.
  - My biggest problem came in that with multiple tries with the first mhm-admin vm I made. I couldn't get a honeypot running that would be attacked. I consistently made honeypot VMs that had no attacks. Ultimately, I had to start from square one and build the system all over again and not just new VMs.
* A summary of the data collected: number of attacks, number of malware samples, etc.
  - At the time of saving the JSON file, there were 1104 attacks with a majority coming from the United Srares and then Russia, the Netherlands, and Taiwan/China. 
  ![Attacks](https://github.com/HaTeMaiL/CodePath_Authentic8/blob/master/Honeypot/mhm-honeypot-1_attacks.PNG)
* Any unresolved questions raised by the data collected
  - 

## Notes

Describe any challenges encountered while doing the work
