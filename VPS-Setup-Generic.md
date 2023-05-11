#### Proposal: *Enterprise Linux server preparation, deployment & configuration*
- Version: **1.1**
- Author: ***Broken Arrow*** | Info@Binary.Men | <a href="https://github.com/SKJoy/personal/blob/main/resume.md" target="_blank">Resume</a>
- Last update: **May 11, 2023**
---
#### System
- **Type**: VPS or bare metal (unmanaged) on Amazon Web Services, Digital Ocean, Google Cloud or any infrastructure including in premise
- **Role**: Server (headless)
- **Network scope**: Internet & intranet
- **Operating system**: RHEL 8 compatible AlmaLinux, Rocky or CentOS Stream
- **Management panel**: Web GUI with file manager (System administrator & domain user)
- **Terminal**: SSH
---
#### Services
- **Hosting**: Resource quota limit enabled multi domain & subdomain with DNS zone editor
- **Web (HTTP)**: NginX, Varnish & Apache with bandwidth graph
- **SSL certificate**: Automated Let's Encrypt certificate generation & renewal
- **Database**: MariaDB 10.11 (MySQL compatible), PostgreSQL 13 & MongoDB 4
- **Mail**: SMTP, POP & IMAP (SSL/TLS enabled) with SPF, DKIM & WebMail support
- **Development**: PHP 8.2, Node.JS 19 & Python 3
- **Containerization**: Docker
- **Firewall**: General purpose with automatic failed attempt blocking & DDoS protection
- **Automated script installation**: PHP application installer for a number of open source packages like Laravel, Joomla, WordPress, NextCloud, etc.
- **Other**: CronJob manager, FTP, DNS, Redis, CertBot and automatic site & database backup
---
#### Tools
- Git
- Console GUI file manager
- Advanced process manager
- Start up service manager
---
#### Optional value added services
- Real time messaging (XMPP multi domain)
- Real time audio video message (XMPP)
- MQTT broker
- Web drive (like Google drive)
---
#### Prerequisites & requirements
- Provision to load OS image and install from scratch or a fully installed fresh minimal copy of the OS
- Full root access to the system (no SUDO)
- Subdomain pointed to the system where the specific domain cannot be hosted with the system
- At least one domain to be hosted with the system
- Preconfigured name server pointers to the system if the system is to be used as name server for hosted domains
---
#### Note
- Live preview can be arranged optionally at a functionally working condition
- All software mentioned above should be either freeware, free version, free edition or open source with general public license (usage or commercial) without feature or service expiry