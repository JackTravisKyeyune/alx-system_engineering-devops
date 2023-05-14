0x19 Postmortem

Issue Summary:
On May 10, 2023, from 4:00 PM to 6:30 PM (EST), the web server of our E-commerce platform website experienced an outage, resulting in slow response times and error messages for some users. Approximately 40% of our customers were affected by this outage.

Root Cause:

The root cause of the outage was identified as a sudden surge in traffic caused by a marketing campaign that was launched without proper load testing. As a result, the web server was overwhelmed and could not handle the incoming requests, causing it to slow down and eventually crash.

Timeline:
4:00 PM - The issue was detected when the monitoring system alerted the operations team of an increase in response times and error rates.

4:05 PM - The operations team investigated the web server logs and identified a sudden surge in traffic.

4:10 PM - The team assumed that the issue was caused by a DDoS attack and initiated measures to mitigate the attack.

4:30 PM - After analyzing the network traffic, the team realized that the surge in traffic was caused by a marketing campaign that was launched without proper load testing.

5:00 PM - The team attempted to optimize the server configurations to handle the increased traffic but was unsuccessful.

5:30 PM - The team decided to scale up the web server infrastructure by adding additional servers to handle the traffic.

6:00 PM - The newly added servers were configured and deployed to handle the traffic.

6:30 PM - The web server infrastructure was fully operational, and the issue was resolved.

Root Cause and Resolution:

The root cause of the issue was a sudden surge in traffic caused by a marketing campaign that was launched without proper load testing. To resolve the issue, the team scaled up the web server infrastructure by adding additional servers to handle the traffic.

Corrective and Preventative Measures:

To prevent a similar outage from happening in the future, the following measures will be implemented:

- Load testing will be performed before any new marketing campaigns or promotions are launched.
- The web server infrastructure will be optimized for scalability and elasticity to handle sudden traffic surges.
- The monitoring system will be enhanced to detect traffic surges and alert the operations team promptly.
- The team will establish a standard incident response plan to address similar issues quickly and effectively.

Tasks to address the issue:
- Perform load testing before any new marketing campaigns or promotions are launched.
- Optimize the web server infrastructure for scalability and elasticity.
- Enhance the monitoring system to detect traffic surges and alert the operations team promptly.
- Establish a standard incident response plan to address similar issues quickly and effectively.
- Train the team on incident response and load testing best practices.

In conclusion, 
The outage that occurred on our e-commerce website was caused by a sudden surge in traffic due to a marketing campaign that was launched without proper load testing. The issue was resolved by scaling up the web server infrastructure. To prevent similar outages in the future, we will implement measures such as load testing, optimizing the infrastructure, and enhancing the monitoring system.
