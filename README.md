# Curtis Tech Projects Portfolio
Full Tech Portfolio, including projects

## NETWORK SECTION##

📡 Network Connectivity Test — Ping Diagnostic
This project demonstrates a basic but essential networking diagnostic using the Linux ping command. It verifies connectivity, latency, and packet reliability when communicating with an external host.

![Ping Test Screenshot](images/ping-test.png)

🧪 What This Test Shows
Executed a 6‑packet ICMP ping to google.com to measure network responsiveness.

Verified 0% packet loss, confirming a stable and reliable connection.

Observed consistent round‑trip times between 19–22 ms, indicating low latency.

Demonstrated use of Linux command‑line tools for network troubleshooting.

Showcased ability to interpret RTT statistics (min/avg/max/mdev) for performance analysis.

🌐 Network Path Analysis — Traceroute to Google
This project demonstrates how to analyze the path packets take across the Internet using the traceroute command. It reveals each hop between your machine and Google’s servers, helping diagnose routing issues, latency spikes, or ISP‑level problems.

![Traceroute Screenshot](images/traceroute-google.png)

🧪 What This Test Shows:
Ran a IPv4 traceroute to google.com to map the full network path.

Identified each hop between the local machine and Google’s server at 142.250.176.78.

Observed normal routing through local gateway, home router, and ISP nodes.

Noted several hops returning * * *, which is common when routers block ICMP responses.

Verified final hop reached Google’s infrastructure (1e100.net) with ~22 ms latency.

Demonstrated ability to use traceroute for network diagnostics and route analysis.

📊 Output Summary:
12 hops were required to reach Google’s server.

Local gateway and LAN responded normally.

ISP nodes (Spectrum/Charter) showed expected latency patterns.

Some intermediate routers did not respond (timeouts), which is normal behavior.

Final hop resolved to Google’s server with ~22 ms response time.

Route confirms a healthy connection with no abnormal delays.
