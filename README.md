# Ansible playbook for test install k8s at SOHO env.

Many things are hardocoded for my own custom usage.

It supports:

* Install one or more control nodes
* HA: HaProxy and Keepalived for API
* CNI: calico via tigera operator.
* nodelocaldns on each node.
