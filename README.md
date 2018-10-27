Keepalived
==========

Image based on Alpine Linux.
Starts keepalived daemon and automaticaly chooses external facing interface.

Configuration
-------------

Use following environment variables to configure the service:

* `INSTANCE_ID` - Translates to `virtual_router_id` in the `keepalived.conf`
* `VIRTUAL_IPS` - Space separated list of virtual IP addresses
* `INTERFACE` - [optional] Network interface to assign virutal IP addresses - defaults to the public interface
* `PASS` - [optional] password for the keepalived authentication
