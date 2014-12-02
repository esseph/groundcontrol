groundcontrol
=============

A basic html5/php/mysql interface for monitoring, graphing and controlling wireless and other devices (ubiquiti, mikrotik, cambium, etc.)

After Ubiquiti released airCRM and forced all of their device command/control to be done using their cloud, a group of experienced WISP professionals decided to get together and create their own solution. Service Providers need direct responsibility for monitoring and managing their network, and vendor-lock in for C&C systems is always a problem.

This project is about removing vendor lock-in from management interfaces, and giving C&C back to network operators on a simple to use system that is brand and product diverse.

Initially we want to be able to:
* poll devices
* collect historic data
* mass change configs
* save config backups
* log and timestamp config changes
* ubnt, mikrotik, cambium ePmP support
* group radios by AP MAC

Eventually, we'd like to be able to:
* Map subscribers to their APs using google maps (or similar)
* create a well documented API, device template, and theming/branding system
* allow other people to create/submit device templates for linux/windows hosts, routers, switches, etc
* allow custom SNMP OID polling
* custom ssh scripts/agents
