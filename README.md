# MilkNet

Operate all machines under your control and throw milk at your target.

## NOTICE

Please abide by the user's local laws, and the developer does not take any responsibility.

This project is still under development, please use another project.

## TODO

MilkNet BotNet
service module
host module
load module
worm module
all in one

service/host
Can use cdn hidden service
The domain name can be hardcoded in the program
http service, do not use long links, each request is 1min apart
task Each task is transmitted with json
update Self-update, every startup/1h
log/tz regularly reports the latest logs, and the server counts the machines that are online within 30 minutes and generates statistical graphs
telnet When the host requests telnet, open a shell from the local

load
4 layers: tcp/syn/reflect/udp/mem/ntp/dns/icmp
7 layer: get/post/stress/pps/head

worm
Prepare broiler equipment probing method list
Check the intranet and 0.0.0.0/8 for hackers, send poc, send itself after completion, perform a series of operations and run
When the worm is run, it will persist, then connect to the server and register the device
