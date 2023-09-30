# Tcpdump-Task
Analyzing network layer communication.

I was given a scenario that I am a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted my company to report that they were not able to access the company website, and saw the error "destination port unreachable" after waiting for the page to load.

I am tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, I visit the website and also receive the same error "destination port unreachable". Next, I load my network analyzer tool, tcpdump, and load the webpage again. This time, I receive a lot of packets in my network analyzer. The analyzer shows that when I send UDP packets and receive an ICMP response returned to my host, the results contain an error message: "udp port 53 unreachable".

I have captured data packets using a network analyzer tool, it was my job to identify which network protocol and service were impacted by this incident. Then I needed to write a follow-up report.

This incident, in the meantime, is being handled by security engineers after me and other analysts have reported the issue to my direct supervisor.
