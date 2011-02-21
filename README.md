# Scribe Monitoring Tools

Tools for monitoring Scribe with Ganglia and Nagios (nrpe).

## Nagios

A very simple check script for nrpe that relies on the scribe_ctrl Python script. State mapping is as follows (Nagios states to Scribe states):

 * OK -> ALIVE
 * WARNING -> WARNING
 * CRITICAL -> STARTING, STOPPING, STOPPED, DEAD, 'Failed to get status'

## Ganglia

