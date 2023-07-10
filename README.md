# Awesome Zabbix

![Telegram Badge](https://img.shields.io/badge/join_us-on_telegram-%2326A5E4?logo=telegram&color=%2326A5E4&link=https%3A%2F%2Ft.me%2FZabbixTech)

We use the ZabbixTech community Telegram channel for instant communication, follow the [link here to join](https://t.me/ZabbixTech).

<a href="https://www.zabbix.com/"><img src="https://github.com/lasseoe/awesome-zabbix/raw/main/assets/zabbix_logo_500x131.png" alt="Zabbix LLC" title="Zabbix LLC" /></a>

awesome-zabbix is a curated list of Zabbix tools, tutorials, integrations and whatever else that might be useful when working with Zabbix. Inspired by [awesome-go](https://github.com/avelino/awesome-go/).
Please submit a pull request if you have something valuable that would improve this list.

A red ball 🔴 indicates that the resource is written by, maintained or otherwise affiliated with [Zabbix LLC.](https://www.zabbix.com/).

## Contents

- [Awesome Zabbix](#awesome-zabbix)
  - [Contents](#contents)
  - [Ansible](#ansible)
  - [API](#api)
  - [Books](#books)
  - [Notifications and Alerts](#notifications-and-alerts)
  - [SNMP](#snmp)
  - [Templates](#templates)
  - [Triggers](#triggers)
  - [Visualization](#visualization)
    - [Maps](#maps)
    - [Modules and Widgets](#modules-and-wigets)
    - [External](#external-visualization)
  - [Zabbix Protocols](#zabbix-protocols)

**[⬆ back to top](#contents)**

## Ansible

> Ansible is a suite of software tools that enables infrastructure as code. It is open-source and the suite includes software provisioning, configuration management, and application deployment functionality.

- [ansible](https://github.com/ansible/ansible) - Official Ansible GitHub repository.
- [community-zabbix](https://docs.ansible.com/ansible/latest/collections/community/zabbix/index.html) - Zabbix Community Collection. 🔴
- [forward-to-eda](https://blog.zabbix.com/forward-zabbix-events-to-event-driven-ansible-and-automate-your-workflows/25893/) - Forward Zabbix Events to Event-Driven Ansible and Automate your Workflows. 🔴

**[⬆ back to top](#contents)**

## API

> The Zabbix API allows you to programmatically retrieve and modify configuration of Zabbix and provides access to historical data. The Zabbix API is an HTTP-based API, and it is shipped as a part of the web frontend. It uses the JSON-RPC 2.0 protocol.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/api) - Zabbix API documentation. 🔴
- [testing-with-postman](https://mpolinowski.github.io/docs/DevOps/Zabbix/2022-01-13--zabbix-api-testing/2022-01-13) - Testing the Zabbix API with Postman.
- [hnakamur/go-zabbix](https://github.com/hnakamur/go-zabbix) - A minimal Zabbix API client for Go.
- [py-zabbix](https://github.com/adubkov/py-zabbix) - Zabbix module for Python

**[⬆ back to top](#contents)**

## Books

> Books, documents, whitepapers etc.

- [zabbix-6-cookbook](https://www.packtpub.com/product/zabbix-6-it-infrastructure-monitoring-cookbook-second-edition/9781803246918) -  Zabbix 6 IT Infrastructure Monitoring Cookbook - Second Edition.
- [zabbix-7-cookbook](https://www.packtpub.com/product/zabbix-7-it-infrastructure-monitoring-cookbook-third-edition/9781801078320) - Zabbix 7 IT Infrastructure Monitoring Cookbook - Third Edition.

**[⬆ back to top](#contents)**

## Notifications and Alerts

> You would not want to stare at the triggers or events list all the time. It would be much better to receive notification if something significant (such as a problem) has happened. Also, when problems occur, you would like to see that all the people concerned are informed.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/config/notifications) - Notifications upon events. 🔴
- [zabbix-ampel](https://github.com/niceshops/zabbix-ampel) - Physical traffic light that displays trigger priorities.

**[⬆ back to top](#contents)**

## SNMP

> Simple Network Management Protocol (SNMP) is an Internet Standard protocol for collecting and organizing information about managed devices on IP networks and for modifying that information to change device behaviour. Devices that typically support SNMP include cable modems, routers, switches, servers, workstations, printers, and more.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/config/items/itemtypes/snmp) - Zabbix SNMP documentation. 🔴
- [snmpwalk2zabbix](https://github.com/Sean-Bradley/SNMPWALK2ZABBIX) - Create a Zabbix template from an snmpwalk response.
- [mib2zabbix](https://github.com/sputtene/mib2zabbix) - Perl script that generates a Zabbix v3 Template in XML format from an OID tree in a SNMP MIB file ([docs](https://kb.offbyone.be/projects/public-knowledge-base/wiki/Convert_a_MIB_file_to_a_Zabbix_template)).

**[⬆ back to top](#contents)**

## Templates

> Templates is an excellent way of reducing one's workload and streamlining the Zabbix configuration. A template is a set of entities that can be conveniently applied to multiple hosts.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/config/templates) - Templates and template groups. 🔴
- [integrations](https://www.zabbix.com/integrations) - Zabbix owned integration directory of templates, tools etc. 🔴
- [community-templates](https://github.com/zabbix/community-templates) - Zabbix owned GitHub repo with community templates. 🔴
- [zabbix-template-apt-upgrade-monitoring](https://github.com/AkuLink1/zabbix-template-apt-upgrade-monitoring) - Monitor available package upgrades on Debian & Ubuntu and other apt-based hosts.
- [zabbix-template-yum-upgrade-monitoring](https://github.com/AkuLink1/zabbix-template-yum-update-monitoring) - Monitor available package upgrades on RHEL, CentOS and other yum-based hosts.

**[⬆ back to top](#contents)**

## Triggers

> Triggers are logical expressions that "evaluate" data gathered by items and represent the current system state. Trigger expressions allow to define a threshold of what state of data is "acceptable". Therefore, should the incoming data surpass the acceptable state, a trigger is "fired" - or changes its state to PROBLEM.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/config/triggers) - Zabbix Trigger documentation. 🔴
- [baseline-and-anomaly](https://mpolinowski.github.io/docs/DevOps/Zabbix/2022-01-16--zabbix-v6-baseline-monitoring/2022-01-16c) - Creating triggers for Baseline monitoring and Anomaly detection.
- [custom-hysteresis](https://www.burlutsky.su/monitoring/zabbix-create-custom-process-monitoring-cpu-mem-with-hysteresis/) - Create custom process monitoring (CPU, MEM) with hysteresis.

**[⬆ back to top](#contents)**

## Visualization

> Dashboards, maps, widgets, UI and external visualization & reporting.

### Maps

- [zabbix-map-builder-go](https://github.com/Spartan0nix/zabbix-map-builder-go) - CLI tool to help administrators build Zabbix maps using host mappings (network devices, etc.).

### Modules and Wigets

- [zabbix-module-hosts-tree](https://github.com/BGmot/zabbix-module-hosts-tree) - Module to show groups/hosts as a tree under Monitoring -> Hosts Tree menu item in Zabbix.
- [zabbix-module-latest-data](https://github.com/BGmot/zabbix-module-latest-data) - Module to group items under Monitoring -> Latest data per Tag as it used to be with Application grouping in previous versions of Zabbix.
- [zabbix-module-avail-report](https://github.com/BGmot/zabbix-module-avail-report) - Module to add new features to "Availability Report"
- [zabbix-module-menu](https://github.com/BGmot/zabbix-module-menu) - Module to prevent automatic main menu items collapsing effectively to allow you to keep several main menu sections expanded.

### External Visualization

- [grafana-zabbix](https://github.com/alexanderzobnin/grafana-zabbix) - Visualize your Zabbix metrics with the leading open source software for time series analytics.

**[⬆ back to top](#contents)**

## Zabbix Protocols

> Zabbix data exchange protocols, mostly useful for development or in-depth debugging.

- [official-docs](https://www.zabbix.com/documentation/current/en/manual/appendix/protocols) - Zabbix Protocols Documentation. 🔴
- [datadope-io/go-zabbix](https://github.com/datadope-io/go-zabbix) - Go package that implements the Zabbix Sender protocol (only partial support).

**[⬆ back to top](#contents)**

