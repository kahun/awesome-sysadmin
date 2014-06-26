# Awesome Sysadmin
A curated list of amazingly awesome open source sysadmin resources inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php)

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Backups](#backups)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Storage](#cloud-storage)
  * [Collaborative Software](#collaborative-software)
  * [Configuration Management Database](#configuration-management-database)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS](#dns)
  * [Hosting Control Panels](#hosting-control-panels)
  * [IMAP/POP3](#imappop3)
  * [IT Asset Management](#it-asset-management)
  * [LDAP](#ldap)
  * [Log Management](#log-management)
  * [Monitoring](#monitoring)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Network Configuration Management](#network-configuration-management)
  * [Newsletter](#newsletters)
  * [NoSQL](#nosql)
  * [RDBMS](#rdbms)
  * [SMTP](#smtp)
  * [Software Containers](#software-containers)
  * [SSH](#ssh)
  * [Statistics](#statistics)
  * [Ticketing systems](#ticketing-systems)
  * [Troubleshooting](#troubleshooting)
  * [Project Management](#project-management)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * [XMPP](#xmpp)
  * [Web](#web)
  * [Webmails](#webmails)
  * [Wikis](#wikis)
* [Resources](#resources)
  * [Books](#books)
  * [Editors](#editors)
  * [Websites](#websites)
* [Contributing](#contributing)

## Backups
*Backup software.*

* [Amanda](http://www.amanda.org/) - Client-server model backup tool.
* [Bacula](http://www.bacula.org) - Another Client-server model backup tool.
* [Backupninja](https://labs.riseup.net/code/projects/backupninja) - Lightweight, extensible meta-backup system.
* [Backuppc](http://backuppc.sourceforge.net/) - Client-server model backup tool with file pooling scheme.
* [Burp](http://burp.grke.org/) - Network backup and restore program.
* [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
* [Rsnapshot](http://www.rsnapshot.org/) - Filesystem Snapshotting Utility.
* [SafeKeep](http://safekeep.sourceforge.net/) - Centralized pull-based backup using `rdiff-backup`.
* [TarSnap](https://www.tarsnap.com/) - Secure backup service with an open-source client.
* [UrBackup](http://www.urbackup.org/) - Another client-server backup system.
* [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.

## Cloning
*Cloning software.*

* [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program.
* [Fog](http://www.fogproject.org/) - Another computer cloning solution.
* [Redo Backup](http://redobackup.org/) - Easy Backup, Recovery and Restore.

## Cloud Computing

* [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services.
* [Eucalpytus](https://www.eucalyptus.com/) - Open source private cloud software with AWS compatibility.
* [OpenNebula](http://opennebula.org/) - An user-driven cloud management platform for sysadmins and devops.
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [The Foreman](http://theforeman.org/) - Foreman is a complete lifecycle management tool for physical and virtual servers. FOSS.
* [Cobbler](http://www.cobblerd.org/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments. 

## Cloud Orchestration

* [Cloudify](http://www.getcloudify.org/) -  Open source TOSCA-based cloud orchestration software platform written in Python and YAML.
* [Rundeck](http://rundeck.org/) - Simple orchestration tool.
* [Salt](http://www.saltstack.com/) - It's written in Python.

## Cloud Storage

* [git-annex assistant](http://git-annex.branchable.com/assistant/) - A synchronised folder on each of your OSX and Linux computers, Android devices, removable drives, NAS appliances, and cloud services.
* [ownCloud](http://owncloud.org) - Provides universal access to your files via the web, your computer or your mobile devices.
* [Seafile](http://seafile.com) - Another Open Source Cloud Storage solution.
* [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.

## Collaborative Software
*Collaborative software or groupware suites.*

* [Citadel/UX](http://www.citadel.org/) - Collaboration suite (messaging and groupware) that is descended from the Citadel family of programs.
* [EGroupware](http://www.egroupware.org/) - Groupware software written in PHP.
* [Kolab](www.kolab.org) - Another groupware suite.
* [SOGo](http://www.sogo.nu/) -  Collaborative software server with a focus on simplicity and scalability.
* [Zimbra](http://www.zimbra.com/community/) - Collaborative software suite, that includes an email server and web client.

## Configuration Management Database
*Configuration management database (CMDB) software.*

* [i-doit](http://www.i-doit.org/) - Open Source IT Documentation and CMDB.
* [iTop](http://www.combodo.com/-Overview-.html) - A complete open source, ITIL, web based service management tool.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.

## Configuration Management
*Configuration management tools.*

* [Ansible](http://www.ansibleworks.com/) -  It's written in Python and manages the nodes over SSH.
* [CFEngine](http://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
* [Chef](http://www.opscode.com/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
* [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
* [Puppet](http://puppetlabs.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
* [Salt](http://www.saltstack.com/) - It's written in Python.
* [Slaughter](http://steve.org.uk/Software/slaughter/) - It's written in Perl.

## Continuous Integration & Continuous Deployment
*Continuous integration/deployment software.*

* [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration.
* [GitLab CI](https://www.gitlab.com/gitlab-ci/) - Based off of ruby. They also provide GitLab, which manages git repositories.
* [Go](http://www.thoughtworks.com/products/go-continuous-delivery) - Open source agile build and release management software.
* [Jenkins](http://jenkins-ci.org/) - An extendable open source continuous integration server.
* [Vlad the Deployer](http://rubyhitsquad.com/Vlad_the_Deployer.html) - Deployment automation.

## Distributed Filesystems
*Network distributed filesystems.*

* [Ceph](http://ceph.com/) - Distributed object store and file system.
* [DRBD](http://www.drbd.org/) - Disributed Replicated Block Device.
* [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
* [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
* [Lustre](http://lustre.opensfs.org/) -  A type of parallel distributed file system, generally used for large-scale cluster computing.
* [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
* [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DNS
*DNS servers.*

* [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
* [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
* [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
* [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
* [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
* [Yadifa](http://yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.

## Hosting Control Panels
*Web hosting control panels*

* [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
* [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
* [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
* [VestaCP](http://www.vestacp.com/) - Hosting panel for Linux but with Nginx.
* [Virtualmin](http://www.virtualmin.com/) - Control panel for Linux based on webmin.

## IMAP/POP3
*IMAP/POP3 mail servers.*

* [Courier IMAP/POP3](http://www.courier-mta.org/imap/) - Fast, scalable, enterprise IMAP and POP3 server.
* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in.
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind.
* [Qpopper](http://www.eudora.com/products/unsupported/qpopper/) - One of the oldest and most popular server implementations of POP3.

## IT Asset Management
*IT Assets Management software.*

* [GLPI](http://www.glpi-project.org/spip.php?lang=en) - Information Resource-Manager with an additional Administration Interface.
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Snipe IT](http://snipeitapp.com/) - Asset & license management software.

## LDAP
*LDAP servers.*

* [389 Directory Server](http://port389.org) - Developed by Red Hat.
* [Apache Directory Server](http://directory.apache.org/) - Apache Software Foundation project written in Java.
* [Fusion Directory](http://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
* [OpenDJ](http://opendj.forgerock.org/) - Fork of OpenDS.
* [OpenDS](https://opends.java.net/) - Another directory server written in Java.
* [OpenLDAP](http://openldap.org/) - Developed by the OpenLDAP Project.

## Log Management
*Log management tools: collect, parse, visualize ...*

* [Elasticsearch](http://www.elasticsearch.org/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
* [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper
* [Graylog2](http://graylog2.org/) - Pluggable Log and Event Analysis Server with Alerting options.
* [Kibana](http://www.elasticsearch.org/overview/kibana/) - Visualize logs and time-stamped data.
* [Logstash](http://logstash.net/) - Tool for managing events and logs.

## Monitoring
*Monitoring software.*

* [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
* [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
* [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
* [Icinga](https://www.icinga.org/) - Fork of Nagios.
* [LibreNMS](https://github.com/librenms/librenms/) - fork of Observium.
* [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
* [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
* [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
* [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
* [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
* [OMD](http://omdistro.org/) - OMD - The Open Monitoring Distribution.
* [Opsview](http://www.opsview.com/solutions/core) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
* [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
* [Sensu](http://sensuapp.org/) - Open source monitoring framework.
* [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
* [Thruk](http://www.thruk.org/) - Multibackend monitoring webinterface with support for Naemon, Nagios, Icinga and Shinken.
* [Xymon](http://www.xymon.com/) - Network monitoring inspired by Big Brother.
* [Zabbix](http://www.zabbix.com/) - Eenterprise-class software for monitoring of networks and applications.
* [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.

## Metric & Metric Collection
*Metric gathering and display software.*

* [Collectd](http://collectd.org/) - System statistic collection daemon.
* [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
* [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
* [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
* [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
* [Graphite](http://graphite.readthedocs.org/en/latest/) - Open source scaleable graphing server.
* [InfluxDB](http://influxdb.com/) - Open source distributed time series database with no external dependencies.
* [OpenTSDB](http://opentsdb.net/) - OpenTSDB - Store and server massive amounts of time series data without losing granularity.
* [RRDtool](http://oss.oetiker.ch/rrdtool/) - Open source industry standard, high performance data logging and graphing system for time series data.
* [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.

## Network Configuration Management
*Network configuration management tools.*

* [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configurarion and maintain history of changes.
* [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.

## Newsletters
*Newsletter software.*

* [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
* [phpList](http://www.phplist.com/) - Newsletter manager written in PHP.

## NoSQL
*NoSQL servers.*

* [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
* [CouchDB](http://couchdb.apache.org/) - Ease of use, with multi-master replication document-oriented database system.
* [MongoDB](http://www.mongodb.org/) - Another document-oriented database system.
* [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
* [RethinkDB](http://rethinkdb.com) - Built to store JSON documents, and scale to multiple machines with very little effort. It supports really useful queries like table joins and group by.
* [Riak](http://basho.com/riak/) - Another fault-tolerant key-value NoSQL database.
* [InfluxDB](http://influxdb.com/) - An open-source distributed time series database with no external dependencies.

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

* [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
* [omnibus-ruby](https://github.com/opscode/omnibus-ruby) - Full stack, cross distro packaging software (Ruby).
* [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).

## Queuing

* [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
* [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.
* [ZeroMQ](http://zeromq.org/) - Lightweight queuing system.

## RDBMS
*Relational DBMS.*

* [Firebird](http://www.firebirdsql.org/) - True universal open source database.
* [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
* [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
* [MySQL](http://dev.mysql.com/) - Most popular RDBMS server.
* [Percona Server](http://www.percona.com/software) - Enhanced, drop-in MySQL replacement.
* [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
* [PostgreSQL-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based database cluster.
* [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional SQL DBS.

## SMTP
*SMTP servers.*

* [Exim](http://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in JavaScript.
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement.
* [Qmail](http://cr.yp.to/qmail.html) - Secure Sendmail replacement.
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA).

## Software Containers
*Operating system–level virtualization.*

* [Docker](http://www.docker.com/) - Open platform for developers and sysadmins to build, ship, and run distributed applications.
* [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.

## SSH
*SSH tools.*

* [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [Mosh](http://mosh.mit.edu/) - The mobile shell.
* [parallel-ssh](http://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
* [SSH Power Tool](http://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.

## Statistics
*Analytics software.*

* [Analog](http://www.analog.cx/) - The most popular logfile analyser in the world.
* [Piwik](http://piwik.org/) - Free and open source web analytics application.
* [Webalizer](http://www.webalizer.org/) - Fast, free web server log file analysis program.

## Ticketing systems
*Web-based ticketing system.*

* [Bugzilla](http://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project.
* [Cerb](http://www.cerberusweb.com/) - A group-based e-mail management project built with a commercial open source license.
* [Flyspray](http://flyspray.org) - Web-based bug tracking system written in PHP.
* [MantisBT](http://www.mantisbt.org/) - Another web-based bug tracking system.
* [osTicket](http://osticket.com/) - Open source support ticket system.
* [Otrs](http://www.otrs.com/) -  A free and open-source trouble ticket system software package that a company, organization, or other entity can use to assign tickets to incoming queries and track further communications about them.
* [Request Tracker](http://www.bestpractical.com/rt/) - Ticket-tracking system written in Perl.
* [TheBugGenie](http://www.thebuggenie.com) - Open source ticket system with extremely complete users rights granularity.

## Troubleshooting
*Troubleshooting Tools.*

* [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.

## Project Management
*Web-based project management and bug tracking systems.*

* [ChiliProject](https://www.chiliproject.org) - Fork of Redmine.
* [GitLab](https://www.gitlab.com/) - Clone of GitHub written in ruby.
* [Gogs](http://gogs.io/) - Written in Go
* [Redmine](http://www.redmine.org/) - Written in ruby on rails.
* [The Bug Genie](http://www.thebuggenie.com/) - Written in PHP.
* [Trac](http://trac.edgewall.org/) - Written in python.

## Version control
*Software versioning and revision control.*

* [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
* [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
* [Mercurial](http://mercurial.selenic.com/) - Another distributed revision control.
* [Subversion](http://subversion.apache.org/) - Client-server revision control system.

## Virtualization
*Virtualization software.*

* [Ganeti](https://code.google.com/p/ganeti/) - Cluster virtual server management software tool built on top of KVM and Xen.
* [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
* [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
* [Packer](http://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
* [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
* [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
* [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

## VPN
*VPN software.*

* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](http://pritunl.com/) - OpenVPN based solution. Easy to set up.
* [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](http://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.

## XMPP
*XMPP servers.*

* [ejabberd](http://www.ejabberd.im/) - XMPP instant messaging server written in Erlang/OTP.
* [Metronome IM](http://www.lightwitch.org/metronome) - Fork of Prosody IM.
* [MongooseIM](https://www.erlang-solutions.com/products/mongooseim-massively-scalable-ejabberd-platform) - Fork of ejabberd.
* [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server.
* [Prosody IM](http://prosody.im/) - XMPP server written in Lua.
* [Tigase](https://projects.tigase.org/projects/tigase-server) - XMPP server implementation in Java.

## Webmails
*Webmail applications.*

* [RainLoop](http://rainloop.net/) - Simple, modern & fast web-based IMAP client.
* [Roundcube](http://roundcube.net/) - Browser-based IMAP client with an application-like user interface.

## Web
*Web servers.*

* [Apache](http://httpd.apache.org/) - Most popular web server.
* [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
* [Lighttpd](http://www.lighttpd.net/) -  Web server more optimized for speed-critical environments.
* [Nginx](http://nginx.org/) -  Reverse proxy, load balancer, HTTP cache, and web server.
* [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.
* [Varnish](https://www.varnish-cache.org/) - Very popular HTTP cache server.

## Wikis
*Wiki software.*

* [DokuWiki](https://www.dokuwiki.org/dokuwiki) - Simple to use and highly versatile wiki that doesn't require a database.
* [ikiwiki](http://ikiwiki.info/) - A wiki compiler.
* [Mediawiki](http://www.mediawiki.org/wiki/MediaWiki) - Used to power Wikipedia.
* [MoinMoin](http://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users.
* [TiddlyWiki](http://tiddlywiki.com) - Complete interactive wiki in JavaScript.

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Books
*Sysadmin related books.*

* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
* [UNIX and Linux System Administration Handbook](http://www.admin.com/) - Approaches system administration from a practical perspective.

## Editors
*Open source code editors.*

* [Atom](https://atom.io/) - A hackable text editor from Github.
* [Brackets](http://brackets.io/) - Open source code editor for web designers and front-end developers.
* [Eclipse](http://eclipse.org/) - IDE written in Java with an extensible plug-in system.
* [Geany](http://www.geany.org/) - GTK2 text editor.
* [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
* [Lime](http://limetext.org/) - Aims to provide an open source solution to Sublime Text
* [Vim](http://vim.org) - A highly configurable text editor built to enable efficient editing.

## Websites
*Useful sysadmin related websites.*

* [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
* [Dotdeb](http://www.dotdeb.org/) - Repository with LAMP updated packages for Debian.
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.

# Contributing
Please see [CONTRIBUTING](https://github.com/kahun/awesome-sysadmin/blob/master/CONTRIBUTING.md) for details.
