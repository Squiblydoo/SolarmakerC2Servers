# SolarmakerC2Servers
This is a repository of C2 IP addresses seen in use by Solarmarker. Per [Prodaft's analysis](https://www.prodaft.com/resource/detail/solarmarker-depth-analysis-report), the IP addresses point to Load Balancers that point to the Admin panel and Management pane;. See their report linked above for more details.

These IP addresses tend to change weekly, but I am hosting a list of previously seen IP for the sake of documentation. It can also be interesting to visualize them in various ways to determine if there are trends. At this point, I am only providing the IP addresses. Visualization and other aspects are up to you.

The IP addresses and hostnames are taken directly from the executables. If you have a list of IP to add, let me know and let me know how you extracted them. I am weary of adding any IP/Hostnames that I can't validate myself.

I personally maintain an [OTX for AlienVault](https://otx.alienvault.com/pulse/60cf75bfb13dce62b5febdb1). The IP addresses in the OTX are set to expire after 1 month due to the frequent changes of C2. The intention is to reduce false positives by allowing the IP to expire. This repository is also intended to be a historical list of C2 that have been used.



## Example
The following are examples of the data used. 
An IP lookup was used to identify ASN associated with the IP addresses. Then the data was graphed using Flourish.Studio
![image](https://user-images.githubusercontent.com/77356206/157724504-d367ad51-ada5-4d0f-8a0b-34fb7c3ce6d6.png)
https://public.flourish.studio/visualisation/8939187/ 

In the following example, networkx was then used to create a network map and output a DOT file which was then used to generate a graph using fdp.

![1028](https://user-images.githubusercontent.com/77356206/139301249-dcc4ca77-23f3-453e-b664-256a1f9f24ec.png)
