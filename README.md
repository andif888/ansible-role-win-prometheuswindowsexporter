# ansible-role-win-prometheuswindowsexporter

Role to install Prometheus Windows Exporter

## Table of content

- [Default Variables](#default-variables)
  - [win_prometheuswindowsexporter_allow_firewall](#win_prometheuswindowsexporter_allow_firewall)
  - [win_prometheuswindowsexporter_firewall_port](#win_prometheuswindowsexporter_firewall_port)
  - [win_prometheuswindowsexporter_package_params](#win_prometheuswindowsexporter_package_params)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### win_prometheuswindowsexporter_allow_firewall

Allow port in windows firewall

#### Default value

```YAML
win_prometheuswindowsexporter_allow_firewall: true
```

### win_prometheuswindowsexporter_firewall_port

TCP port to allow in windows firewall

#### Default value

```YAML
win_prometheuswindowsexporter_firewall_port: 9182
```

### win_prometheuswindowsexporter_package_params

package parameters passed to the installer

#### Default value

```YAML
win_prometheuswindowsexporter_package_params: /EnabledCollectors:cpu,cs,logical_disk,memory,net,os,service,system,tcp
```

## Discovered Tags

**_win-prometheuswindowsexporter-autostart_**


## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
