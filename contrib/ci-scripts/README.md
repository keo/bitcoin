## Setting up TeamCity

### Install Ubuntu Trusty

TODO: security / lockdown instructions

### Install Postgresql

TODO: install instructions
TODO: create teamcity user and database


Edit `/etc/postgresql.conf` to reflect the following settings:

```
shared_buffers=512MB
checkpoint_segments=32
checkpoint_completion_target=0.9
synchronous_commit=off
```

Then run `/etc/init.d/postgresql reload` to reload settings.

### Install TeamCity

TODO: install instructions

### Setup Build Configurations
### Setup Agents
