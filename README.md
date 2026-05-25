# Stouts.chrony

Ansible role to install and configure Chrony NTP client/server

#### Variables

```yaml
chrony_enabled: true # Enable/Disable role
chrony_timesyncd_remove: true # Remove systemd-timesyncd if present
```

#### Usage

Add `Stouts.chrony` to your roles and set vars in your playbook file.

#### License

Licensed under the MIT License. See the LICENSE file for details.
