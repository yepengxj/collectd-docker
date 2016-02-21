# collectd-docker
Collectd and RRDtool in a container
sudo system-docker run -d --net=host --name collectd --privileged husseingalal/collectd

You can see the statistics collectd is gathering by accessing http://[ip-address-of-the-server]. The tool will provide the data for each enabled plugin gathered by the collectd daemon.
