# Openhab Thing Plugin

## Description:

Icinga2 plugin to monitor the state of an openhab3 thing through REST-API.

## Usage:
```
-- url    URL of OpenHab instance, for example openhab.domain.com
-- port   Port of OpenHab instance, for example is 8843.
-- token  Token for OpenHab auth, generated by openhab.
-- uid    UID of the thing, that should be checked.
```

## Example:
```
/usr/lib/nagios/plugins/check_openhab_thing --url 192.168.1.100 --port 8443 --token verysecrettoken --uid UidOfTheOpenhabThingToMonitor
```