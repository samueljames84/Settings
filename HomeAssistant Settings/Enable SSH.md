# Enable SSH On Home assistant

Create After Loginto home assistant

Go to `Settings` > `Addons` > Search for `Terminal & SSH`

Install `Terminal & SSH`

### Enable all the settings for this Addon

```
Start on boot   > Enable
Watchdog        > Enable
Auto update     > Enable
Show in sidebar > Enable
```

### Setting Up SSH Configuration

* Go to `Settings` > `Addons` >  `Advanced SSH & Web Terminal`'
* Go to the `Configuration` Tab on the top
* Set the `Username`and `Password`

username: homeassistant
password: "******"
authorized_keys: []
sftp: false
compatibility_mode: false
allow_agent_forwarding: false
allow_remote_port_forwarding: false
allow_tcp_forwarding: false
* Save the configuration bu clicking `Save` button on the bottm of the page.

### Reference

Refer the YouTube Video [HOW TO Enable SSH In Home Assistant (2023)](https://youtu.be/dAmGYrKDpZE)
