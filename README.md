# Docker-Examples
Docker Scripts and Examples


Open sokcet for Jenkins on ubuntu server 20.04
sudo vi /lib/systemd/system/docker.service
ExecStart=/usr/bin/dockerd -H fd:// --containerd=/run/containerd/containerd.sock -H fd:// -H tcp://0.0.0.0:2375
