# Project-2-Cybersecurity-Bootcamp-Red-V.S.-Blue
   In my Columbia Engineering Cybersecurity Bootcamp course, we conducted a full red team, blue team, and mitigation methodologies analytic report on a virtual lab environment set up through Microsoft's Azure Labs.

The slideshow .pdf contains:
  A network map of all machines on the network which contained a host hypervisor, a web server, an ELK stack, and an attacking Kali machine.
  A table describing the function of each machine on the network
  An assessment of what was believed to be the most dangerous vulnerabilities to the web server
  A detailed description of the tools, processes, and achievements of each exploit performed on the web server as well as screenshots to showcase the results of each exploit.
  An analysis of logs and packet data captured from the ELK stack for each exploit along with screenshots of relevant parsing of data.
  Mitigation techniques, alarm thresholds, and solutions towards the other vulnerabilities on the web server.

   For this project, a pre-built lab environment was made for the class using Microsoft Azure’s platform as a service, Azure Lab Services. The first day of the class was spent simulating an attack by using the Kali machines to find vulnerabilities on the network (192.168.1.0/24). The second day was spent analyzing logs captured from the vulnerable web server (Capstone) using the ELK stack and visualized by Kibana. The web server was sending the packets it was receiving and transmitting into packetbeat, its current resource usage into metricbeat, and commands/events occuring on the terminal into filebeat. All of the statistics and data was visualized using Kibana and through the search functionality, we were able to identify when certain attacks occurred and how those attacks were achieved. The third day was spent aggregating all the information that was documented over the past two days through questions and notes in a slideshow presentation made to inform and express the findings clearly and efficiently so as to communicate to a wider audience.
