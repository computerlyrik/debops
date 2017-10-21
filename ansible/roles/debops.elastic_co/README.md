## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) elastic_co

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-elastic_co.svg?style=flat)](https://travis-ci.org/debops/ansible-elastic_co)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--elastic__co-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-elastic_co/)


The `debops.elastic_co` Ansible role can be used to configure APT
repositories maintained by the [Elasticsearch BV](https://www.elastic.co/about)
company on Debian and Ubuntu hosts. The APT repositories are used to distribute
`elasticsearch`, `logstash`, `kibana`, `filebeat`, `metricbeat`,
`packetbeat` and `heartbeat` APT packages. The role allows only for
installation of these packages, additional configuration and management of the
installed software is performed by other Ansible roles.



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).