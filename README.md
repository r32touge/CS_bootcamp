# CS_bootcamp
Repo for cybersec bootcamp stuffs

This repo is a collection of linux commands, Ansible playbooks, config files from my cybersecurity class.
Mainly this repo houses the commands and playbooks used to setup a cloud network utilizing Docker containers.

The Ansible playbooks were used to configure a newtwork of 4 machines, 3 machines on one virtual network peered
with a 4th machine on a separate virtual network, due to limitations with Azure's free/trial account.

The 4th machine was used as an ELK server to monitor syslogs and vm metrics such as CPU and memory usage. 
This was monitored use Beats, particularly Filebeats for syslogs and Metricbeats for metrics.
