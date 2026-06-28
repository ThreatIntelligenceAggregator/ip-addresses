# ip-addresses
All IP addresses are gathered from honeypot infrastructure run by ThreatIntelligenceAggregator.org. 
* brute-force.txt - These IP addresses were observed attempting to log into services for which they are not authorized
* malware.txt - These IP addresses were observed as payloads (hosting malicious files)
* scanner.txt - These IP addresses were observed scanning/connecting to services

Please leave a star if you use this repo or want to motivate further expansion on IP threat intelligence. No API currently for IP addresses but if you want to try out our free domain API you can use it as follows:
https://api.threatintelligenceaggregator.org/domain/{yourdomain}

Example:
https://api.threatintelligenceaggregator.org/domain/discord.gg

Domain API Python Client:
https://github.com/ThreatIntelligenceAggregator/domains_api_client
