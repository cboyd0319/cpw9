# Project 9 - Honeypot

Time spent: **2.5** hours spent in total

> Objective: Setup a honeypot and intercept some attempted attacks in the wild.

Which Honeypot(s) you deployed
- Dionaea

Any issues you encountered
- I initially had some issues with Google Cloud. In the interest of time, I stood this up in AWS.

A summary of the data collected: number of attacks, number of malware samples, etc.
- Attacks in the last 24 hours: 1,134
- Top attacker: 37.49.231.157 (366 attacks)
- Top attacked port: 5061 (366 times) - Session Initiation Protocol (SIP) over TLS
- Second most attacked port: 445 (204 times) - Windows file shares/SMB
- Total Attacks: 21,242
- Shodan link: https://www.shodan.io/host/18.144.62.152
- Shodan Raw: https://github.com/cboyd0319/cpw9/blob/master/shodan.raw

Any unresolved questions raised by the data collected
- I'd like to take more time to add additional sensors and potentially write some automatic blocking/blackhoing scripts based on detected malicious activity

Additionally, include a json export of the data you collected in the repo, instructions for which can be found in the next section.
- JSON Export: https://github.com/cboyd0319/cpw9/blob/master/json_export/session.json

Screenshots
- Attacks Report: ![](https://github.com/cboyd0319/cpw9/blob/master/images/Screen%20Shot%202018-12-03%20at%204.33.25%20PM.png)


- Sensors: ![](https://github.com/cboyd0319/cpw9/blob/master/images/Screen%20Shot%202018-12-03%20at%204.33.38%20PM.png)
