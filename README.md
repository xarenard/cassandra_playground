# cassandra_playground
Personal Cassandra Playground with Vagrant and Ansible

```
ubuntu@node1:~$ nodetool status
Datacenter: dc1
===============
Status=Up/Down
|/ State=Normal/Leaving/Joining/Moving
--  Address   Load       Tokens       Owns (effective)  Host ID                               Rack
UN  10.0.0.2  69.91 KiB  256          69.8%             1c9f2752-a31d-4859-a4b2-aebaf5d73131  rack1
UN  10.0.0.3  69.92 KiB  256          64.7%             65640871-7b8b-407b-aef2-c38def2a2ec4  rack1
Datacenter: dc2
===============
Status=Up/Down
|/ State=Normal/Leaving/Joining/Moving
--  Address   Load       Tokens       Owns (effective)  Host ID                               Rack
UN  10.0.0.4  69.92 KiB  256          65.5%             fe2ae0bc-dda6-45a9-9406-cc0d792d24bf  rack1
```
