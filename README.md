# zabbix-templates
Zabbix Templates created/adapted by Muutech Monitoring Solutions (www.muutech.com)

If you need any help, contact us at info@muutech.com

Check out our Zabbix + Grafana Demo online: http://demo.muutech.com

Tested in Zabbix 3.2.X

To install, just import each template you need into Zabbix. Important, some templates depends on others, mainly allocated in the SNMP folder.

* ACCESS POINTS
  * CISCO WAP200
  * D-LINK DAP-2360
  * D-LINK DWL-3200AP
  * ENGENIUS EOC-3610
* SERVERS
  * IBM AS/400
* SNMP
  * SNMP AGENT - NEEDED BY ALMOST EVERY TEMPLATE (includes ICMP monitoring, and notification if SNMP is down)
  * SNMP_DISKS_GENERIC_INTERFACES_PROCESSES_V1 - NEEDED BY IBM_AS400 TEMPLATE (basically a V1 version of SNMP default templates)
  * SNMP_INTERFACES_BY_ALIAS - NEEDED BY ALLIED_TELESIS_AT-8000S
* SWITCHES
  * ALLIED TELESIS AT-8000S
  * CISCO Sx200 Sx300 (CISCO SMALL BUSINESS SG200, SG300, etc.)
* UPS
  * RIELLO UPS
  * UPS-MIB - NEEDED BY RIELLO_UPS
