We believe in right-sized infrastructure design.   As a community, if we over build, we will waste money.  And if we under build, we will won’t be able to handle growth. Thus, we have a 3-phase approach to our infrastructure.

Phase I -  Initial deployment.  
See our diagram here: https://www.dropbox.com/s/6q624wttqrodibf/Tron%20Phase%20I.png?dl=0

Goal is cost effective reliable block production.  We have a 4-server design.  Our public facing server will be a Nginx reverse proxy / load balancer hosted with Google Cloud.  This will hide our full node and protect it from attacks. We will have a full node for user API access, also hosted by Google cloud.  We will have two bare-metal block producing witness servers, one primary and one backup. They will have dual 1 Gbps ISPs, be protected by a Sonicwall firewall, and use wireguard for encrypted secure communications.
During test net operations, on our production servers, our bandwidth consumption was under 10%, our processors ran an average of 4% utilization, while 22% of our RAM was consumed. This gives us room to grow without the need for network redesign, but at a reasonable starting price.

Phase II -  Expansion and Redundancy  
See our diagram here: https://www.dropbox.com/s/bac8g3przjdv6k6/Tron%20Phase%20II.png?dl=0

Once elected as SR and funded, we will expand our operations quickly.  We will grow to 3 locations with witness servers to ensure we stay operational regardless of server, ISP, or physical location failures.  We will also expand the number of our servers to 12 in preparation for a growing user-base and transaction volume.

Phase III -  Increase Server Requirements

Once we have reached full redundancy in operations, we will continue to invest in bigger and better servers as demand grows.  This will include number of cores, RAM, hard drive space, ISP bandwidth, etc.


Additionally, as one of our stragic advantages, our productions servers will be located at switch data center in Reno, NV, USA. It is the first tier 5 facility in the world. It is the most redundant and secure hosting facility ever built. It has sub 20 ms ping times to the western half of the USA. It is a green facility, has low electrical costs at under 5 cents per kWh, a 35% guaranteed savings on internet bandwidth, some of the lowest taxes in the world, and sub 20 ms ping times to half of the USA.
You can see video of the facility here: https://www.switch.com/citadel/
