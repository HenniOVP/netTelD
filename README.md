# netTelD
Daemon which implements netTel as described in : https://docs.google.com/presentation/d/1uqVGDOPo5-3Nh-RG8vp5PKpKqlQo2ZMNAimxqwf6bs0/edit#slide=id.g1781e444bf_0_10


- Usage:
  * start with: ./netTelD.py start
  * stop with: ./netTelD.py stop
  * or use the supplied netTelD.service to start/stop it via systemd with: systemctl start netTelD.service
  
The log can be found here: /var/lib/netTel/netTel.log