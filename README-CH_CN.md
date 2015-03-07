# Awesome Sysadmin
A curated list of amazingly awesome open source sysadmin resources inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php)

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Backups](#backups)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Storage](#cloud-storage)
  * [Code Review](#code-review)
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
  * [Packaging](#packaging)
  * [Queuing](#queuing)
  * [RDBMS](#rdbms)
  * [Security](#security)
  * [Service Discovery](#service-discovery)
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
  * [Blogs](#blogs)
  * [Books](#books)
  * [Editors](#editors)
  * [Newsletters](#newsletters)
  * [Repositories](#repositories)
  * [Websites](#websites)
* [Contributing](#contributing)

## Backups
*Backup software.*

* [Amanda](http://www.amanda.org/) - 客户端-服务器模型备份工具
* [Bacula](http://www.bacula.org) - 另一个客户端-服务器模型备份工具
* [Backupninja](https://labs.riseup.net/code/projects/backupninja) - 轻量级，可扩展的元数据备份系统
* [Backuppc](http://backuppc.sourceforge.net/) - 客户端-服务器模型备份工具和文件共享方案。
* [Burp](http://burp.grke.org/) - 网络备份和还原程序
* [Duplicity](http://duplicity.nongnu.org/) - 使用rsync算法加密的带宽-效率备份
* [Lsyncd](https://github.com/axkibe/lsyncd) - 监控一个本地目录树的变化,然后产生一个进程去同步变化。默认使用rsync。
* [Rsnapshot](http://www.rsnapshot.org/) - 文件系统快照工具
* [SafeKeep](http://safekeep.sourceforge.net/) - 使用rdiff-backup，集中的，基于pull的备份
* [TarSnap](https://www.tarsnap.com/) - 具有一个开源客户端的安全备份服务
* [UrBackup](http://www.urbackup.org/) - 另一个客户端-服务器备份系统
* [DREBS](https://github.com/dojo4/drebs) - AWS EBS支持策略的备份脚本

## Cloning
*Cloning software.*

* [Clonezilla](http://clonezilla.org/) - 分区和磁盘镜像/克隆程序
* [Fog](http://www.fogproject.org/) - 另一个计算机克隆解决方案
* [Redo Backup](http://redobackup.org/) - 简单的备份，恢复和还原

## Cloud Computing

* [AppScale](http:/github.com/AppScale/appscale) -  兼容Google App引擎的开源云计算软件.
* [Archipel](http://archipelproject.org/) - 使用Libvirt管理和监视虚拟机
* [CloudStack](http://cloudstack.apache.org/) - 创建，管理和部署基础云服务的云计算软件
* [Cobbler](http://www.cobblerd.org/) - Cobbler是一个Linux安装服务器，允许快速地构建网络安装环境
* [Eucalyptus](https://www.eucalyptus.com/) - 兼容AWS的开源私有云软件
* [Mesos](http://mesos.apache.org/) - 开发和运行能效高的分布式系统。
* [OpenNebula](http://opennebula.org/) - 一个用于系统管理员和研发运维的用户驱动的云管理平台
* [OpenStack](https://www.openstack.org/) - 构建私有和开放云的开源软件
* [The Foreman](http://theforeman.org/) - Foreman是一个用于物理和虚拟服务器的全生命周期管理工具.FOSS.

## Cloud Orchestration

* [BOSH](http://docs.cloudfoundry.org/bosh/) - IaaS业务流程平台，最初用于部署和管理云计算平台PaaS,但也用于通用的分布式系统。
* [Cloudify](http://www.getcloudify.org/) - 使用Python和YAML编写的开源TOSCA-based云业务流程软件平台。
* [Juju](https://juju.ubuntu.com/) - 云业务流程工具用于管理服务，比如charms，YAML配置和部署脚本集
* [MCollective](http://puppetlabs.com/mcollective) - 来自Puppet实验室的管理服务器业务流程和开发的Ruby框架
* [Overcast](http://andrewchilds.github.io/overcast/) - 在不同的云提供商上部署VMs，并在任何或所有（VM）上通过SSH并行运行命令行和脚本
* [Rundeck](http://rundeck.org/) - 简单的业务流程工具
* [Salt](http://www.saltstack.com/) - Python编写

## Cloud Storage

* [git-annex assistant](http://git-annex.branchable.com/assistant/) - 在你的每一个OSX和Linux电脑，Android设备，可移动驱动，NAS电器和云服务上一个同步文件夹cloud services.
* [ownCloud](https://owncloud.org) - 提供你的文件的统一访问，通过web，你的电脑和你的移动设备
* [Seafile](http://seafile.com) - 另一个开源的云存储解决方案
* [SparkleShare](http://sparkleshare.org/) - 提供云存储和文件同步服务。它默认使用Git作为存储后端
* [Swift](http://docs.openstack.org/developer/swift/) - 一个高可用，分布式，最终一致的对象/大数据存储
* [Syncthing](http://syncthing.net/) - 一个用于私有，加密和身份认证数据的开源系统

## Code Review
*基于Web的协作式代码审查系统.*

* [Gerrit](https://code.google.com/p/gerrit/) - 基于Git版本控制，它促进软件开发人员审查源代码修改和批准或拒绝这些变更。
* [Review Board](https://www.reviewboard.org/) - 基于MIT License的可用自由软件

## Collaborative Software
*Collaborative software or groupware suites.*

* [Citadel/UX](http://www.citadel.org/) - 协同套件（消息和群件）继承于Citadel家族程序
* [EGroupware](http://www.egroupware.org/) - PHP编写的群件软件
* [Horde Groupware](http://www.horde.org/apps/groupware) - 基于PHP的协作软件套件，包括邮件，日历，wiki，时间跟踪和文件管理
* [Kolab](https://www.kolab.org) - 另一个群件套件
* [SOGo](https://www.sogo.nu/) - 协作软件服务器，专注简单性和可伸缩性
* [Zimbra](https://www.zimbra.com/community/) - 协作软件套件，包括邮件服务和web客户端

## Configuration Management Database
*配置管理数据库（CMDB）软件.*

* [i-doit](http://www.i-doit.org/) - 开源的IT文档管理和CMDB
* [iTop](http://www.combodo.com/-Overview-.html) - 一个完全开源的，ITIL,基于web的服务管理工具
* [Ralph](https://github.com/allegro/ralph) - 用于大型数据中心或较小本地网络的资产管理，DICM和CMDB系统
* [Clusto](https://github.com/clusto/clusto) - 帮助跟踪你的库存，在哪，如何连接，同时提供一个和基础架构元素交互的抽象接口

## Configuration Management
*配置管理工具.*

* [Ansible](http://www.ansibleworks.com/) -   Python编写的，通过SSH管理节点
* [CFEngine](http://cfengine.com/) -  轻量级代理系统。通过申明语言配置状态。
* [Chef](http://www.opscode.com/chef/) - Rbuy和Erlang编写，使用纯RubyDSL
* [Fabric](http://www.fabfile.org/) - Python库和cli工具，为应用程序部署或系统管理任务简化使用SSH。
* [Pallet](http://palletops.com/) -  通过Clojure DSL进行架构定义，配置和管理
* [Puppet](http://puppetlabs.com/) -  Ruby编写，使用Puppet声明语言或Rbuy DSL
* [Salt](http://www.saltstack.com/) - Python编写
* [Slaughter](http://steve.org.uk/Software/slaughter/) - Perl编写

## Continuous Integration & Continuous Deployment
*持续集成/部署软件.*

* [Buildbot](http://buildbot.net/) - 基于Python的持续集成工具
* [Drone](https://github.com/drone/drone) - 构建在Docker，使用YAML文件配置的的持续集成服务器
* [GitLab CI](https://www.gitlab.com/gitlab-ci/) - 基于rbuy。他们也提供GitLab用于管理git存储库
* [Go](http://www.go.cd/) - 开源的持续交付服务器
* [Jenkins](http://jenkins-ci.org/) - 一个可扩展的开源持续集成服务器
* [Vlad the Deployer](http://rubyhitsquad.com/Vlad_the_Deployer.html) - 自动化部署

## Distributed Filesystems
*Network distributed filesystems.*

* [Ceph](http://ceph.com/) - 分布式对象存储和文件系统
* [DRBD](http://www.drbd.org/) - 分布式块设备复制
* [LeoFS](http://leo-project.net) - 非结构化对象/数据存储和高可用性,分布,最终一致的存储系统。
* [GlusterFS](http://www.gluster.org/) -  可扩展，网络附加存储文件系统。
* [HDFS](http://hadoop.apache.org/) -  Java编写的，用于Hadoop框架的分布式、可伸缩、可移植文件系统
* [Lustre](http://lustre.opensfs.org/) - 一种并行分布式文件系统,一般用于大规模集群计算。
* [MooseFS](http://www.moosefs.org/) -  容错、网络分布式文件系统。
* [MogileFS](http://mogilefs.org/) - 应用程序级别、网络分布式文件系统。
* [OpenAFS](http://www.openafs.org/) - 只读副本和多操作系统支持的分布式网络文件系统
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - 安全、分散、容错、点对点分布式数据存储和分布式文件系统。
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS是一个用于存储需求的容错式分布式文件系统。

## DNS
*DNS servers.*

* [Bind](https://www.isc.org/downloads/bind/) - 最广泛使用的域名服务软件
* [djbdns](http://cr.yp.to/djbdns.html) - DNS应用集合，包括tinydns
* [Designate](https://wiki.openstack.org/wiki/Designate) -  DNS REST API,支持多种DNS服务器的后端
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - 为小规模网络提供DNS,DHCP和TFTP服务的轻量级服务
* [Knot](https://www.knot-dns.cz/) -  高性能，权威的DNS服务器
* [NSD](http://www.nlnetlabs.nl/projects/nsd/) -  权威的、高性能的、简单的域名服务器。
* [PowerDNS](https://www.powerdns.com/) - 具有各种数据存储后端和负载平衡功能的DNS服务器。
* [Unbound](http://unbound.net/) -  验证、递归和缓存DNS解析器。
* [Yadifa](http://yadifa.eu/) -  具有DNSSEC兼容的轻量级的权威域名服务器，支持.eu的顶级域名。

## Hosting Control Panels
*Web hosting control panels*

* [Ajenti](http://ajenti.org/) - Linux和BSD控制面板
* [Feathur](http://feathur.com) -  VPS供应和管理软件
* [ISPConfig](http://www.ispconfig.org) - Linux主机控制面板
* [VestaCP](http://www.vestacp.com/) - 用于Linux和Nginx的主机面板
* [Virtualmin](http://www.virtualmin.com/) - 基于webmin的Linux控制面板
* [ZPanel](http://www.zpanelcp.com/) - Linux BSD和Windows控制面板

## IMAP/POP3
*IMAP/POP3 mail servers.*

* [Courier IMAP/POP3](http://www.courier-mta.org/imap/) - 快速，可伸缩，企业级IMAP和POP3服务器
* [Cyrus IMAP/POP3](http://cyrusimap.org/) - 运行在密封服务器上,普通用户不允许登录。
* [Dovecot](http://www.dovecot.org/) - 主要考虑安全而编写的IMAP和POP3服务器
* [Qpopper](http://www.eudora.com/products/unsupported/qpopper/) -  一个古老且流行的POP3服务器实现

## IT Asset Management
*IT Assets Management software.*

* [GLPI](http://www.glpi-project.org/spip.php?lang=en) - 带有额外管理接口的信息资源管理器
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - 允许用户清算IT资产
* [RackTables](http://racktables.org/) - 数据中心和服务器房间资产，比如将硬件资产,网络地址,在货架空间,网络配置文档化。
* [Ralph](https://github.com/allegro/ralph) -  针对大型数据中心系统以及小型局域网网络的资产管理、DCIM和CMDB。
* [Snipe IT](http://snipeitapp.com/) - 资产和许可证管理软件

## LDAP
*LDAP servers.*

* [389 Directory Server](http://port389.org) -  通过Red Hat部署
* [Apache Directory Server](http://directory.apache.org/) - 用Java编写的Apache软件基金会项目
* [Fusion Directory](http://www.fusiondirectory.org) - 基于OpenLDAP改善服务和公司目录的管理
* [OpenDJ](http://opendj.forgerock.org/) -  OpenDS分支
* [OpenDS](https://opends.java.net/) - 另一个用Java编写的目录服务器
* [OpenLDAP](http://openldap.org/) - 由OpenLDAP项目开发

## Log Management
*Log management tools: collect, parse, visualize ...*

* [Elasticsearch](http://www.elasticsearch.org/) -  一个基于Lucene的文档存储，主要用于日志索引、存储和分析。
* [Fluentd](http://www.fluentd.org/) -  日志收集和发出
* [Flume](https://flume.apache.org/) - 分布式日志收集和聚合系统
* [Graylog2](http://graylog2.org/) - 具有报警选项的可插入日志和事件分析服务器
* [Heka](http://hekad.readthedocs.org/en/latest/) - 流处理系统，可用于日志聚合
* [Kibana](http://www.elasticsearch.org/overview/kibana/) -  可视化日志和时间戳数据
* [Logstash](http://logstash.net/) - 管理事件和日志的工具
* [Octopussy](http://www.octopussy.pm) - 日志管理解决方案（可视化/报警/报告）

## Monitoring
*Monitoring software.*

* [Cacti](http://www.cacti.net) - 基于Web的网络监控和图形工具
* [Cabot](http://cabotapp.com/) -  监控和报警，类似PagerDuty
* [check_mk](http://mathias-kettner.com/check_mk.html) - Nagios的扩展集合
* [Dash](https://github.com/afaqurk/linux-dash) - 一个用于GNU/Linux机器的低开销web仪表板监控。
* [Icinga](https://www.icinga.org/) -  Nagios分支
* [LibreNMS](https://github.com/librenms/librenms/) -  Observium分支
* [Monit](http://mmonit.com/monit/#home) -  管理和监控Unix系统的小型开源工具
* [Munin](http://munin-monitoring.org/) - 网络资源监控工具
* [Naemon](http://www.naemon.org/) - 基于Nagios4内核的网络监控工具，具有性能加强和新功能
* [Nagios](http://www.nagios.org/) - 计算机系统，网络和基础架构监控软件
* [Observium](http://www.observium.org/) - 服务器和网络设备的SNMP监控，运行在linux
* [OMD](http://omdistro.org/) - 开放的监控分布
* [Opsview](http://www.opsview.com/solutions/core) - 基于Nagios4，Opsview核心，用于小型IT和测试环境
* [Riemann](http://riemann.io/) - 灵活和快速的事件处理器，允许负责时间和度量分析
* [Sensu](http://sensuapp.org/) - 开源的监控框架
* [Sentry](https://getsentry.com/) -  应用监控，事件记录和聚合
* [Shinken](http://www.shinken-monitoring.org/) -  另一个监控框架
* [Thruk](http://www.thruk.org/) -  多后台监控的web接口，支持Naemon，Nagios，Icinga和Shinken
* [Xymon](http://www.xymon.com/) - 灵感来自Big Brother的网络监控
* [Zabbix](http://www.zabbix.com/) -  监控网络和应用的企业级软件
* [Zenoss](http://community.zenoss.org) - 基于Zope的应用，服务器和网络管理平台

## Metric & Metric Collection
*Metric gathering and display software.*

* [Collectd](http://collectd.org/) - 系统统计收集守护进程
* [Collectl](http://collectl.sourceforge.net/) - 高精度系统性能指标收集工具。
* [Dashing](http://dashing.io/) - Ruby gem,允许快速统计仪表板的开发。基于HTML5，允许在数据中心或会议室进行大屏幕显示。
* [Diamond](https://github.com/BrightcoveOS/Diamond) - 基于Python的统计收集守护进程
* [Ganglia](http://ganglia.sourceforge.net/) -  基于RRD用于网格和/或集群的服务器的高性能、可伸缩监控设备。兼容Graphite，使用一个单一的收集进程。
* [Grafana](http://grafana.org/) - 一个Graphite或InfluxDB仪表盘和图形编辑器
* [Graphite](http://graphite.readthedocs.org/en/latest/) - 开源的可伸缩绘图服务器
* [InfluxDB](http://influxdb.com/) - 开源的分布式时间序列数据库，没有外部依赖。
* [KairosDB](https://code.google.com/p/kairosdb/) - 快速分布式可扩展的时间序列数据库,OpenTSDB 1. x的分支。
* [OpenTSDB](http://opentsdb.net/) - 存储和服务大量的时间序列数据，不丢失粒度。
* [RRDtool](http://oss.oetiker.ch/rrdtool/) -  开源企业标准，用于时间序列数据的高性能数据记录和绘图系统
* [Statsd](https://github.com/etsy/statsd/) - 应用统计监听

## Network Configuration Management
*Network configuration management tools.*

* [GestióIP](http://www.gestioip.net/) - 一个自动的基于web的IPV4/IPV6地址管理工具
* [RANCID](http://www.shrubbery.net/rancid/) - 监控网络设备配置和维护历史变更
* [rConfig](http://www.rconfig.com/) - 另一个网络配置管理工具

## Newsletters
*Newsletter software.*

* [DadaMail](http://dadamailproject.com/) - Perl编写的邮件列表管理器
* [phpList](http://www.phplist.com/) - PHP编写的时事通讯管理器

## NoSQL
*NoSQL databases.*

* Column-Family
  * [Apache HBase](http://hbase.apache.org/) -  Hadoop数据库，一个分布式的大数据存储
  * [Cassandra](http://cassandra.apache.org/) - 分布式数据库管理系统，设计用于处理大量数据跨多个服务器。
  * [Hypertable](http://hypertable.org/) - 基于c++的bigtable DBMS,节省通信，可独立或在Hadoop类似的分布式FS上运行。
* Document Store
  * [CouchDB](http://couchdb.apache.org/) - 易于使用,多主机复制的面向文档的数据库系统。
  * [ElasticSearch](http://www.elasticsearch.org/) -  基于Java的数据库,受欢迎的日志聚合,和电子邮件归档项目。
  * [MongoDB](http://www.mongodb.org/) -  另一个面向文档的数据库系统
  * [RavenDB](http://ravendb.net/) -  具有ACID/事物功能的基于文档的数据库
  * [RethinkDB](http://www.rethinkdb.com/) - 开源分布式文档存储数据库，关注JSON
* Graph
  * [FlockDB](https://github.com/twitter/flockdb) - Twitter分布式，容错图数据库
  * [Neo4j](http://www.neo4j.org/) -  开源图数据库
* Key-Value
  * [LevelDB](https://code.google.com/p/leveldb/) - Google高性能键值数据库
  * [Redis](http://redis.io/) -  支持网络，基于内存，键值，亦可持久化数据库
  * [Riak](http://basho.com/riak/) - 另一个容错的键值NoSQL数据库

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

* [fpm](https://github.com/jordansissel/fpm) -  万能的多格式包创建器
* [omnibus-ruby](https://github.com/opscode/omnibus-ruby) -  全栈，跨发行版的包管理软件（Ruby）
* [packman](http://packman.readthedocs.org) - 全栈，跨发行版的包管理软件（Python）
* [tito](https://github.com/dgoodwin/tito) -  为git项目构建RPM

## Queuing

* [BeanstalkD](http://kr.github.io/beanstalkd/) -  一个简单快速的工作队列
* [Gearman](http://gearman.org/) - 快速的多语言队列或任务处理平台
* [NSQ](http://nsq.io/) -  实时分发的消息平台
* [RabbitMQ](http://www.rabbitmq.com/) - 健壮的，全功能，跨发行版的队列系统
* [ZeroMQ](http://zeromq.org/) - 轻量级队列系统

## RDBMS
*Relational DBMS.*

* [Firebird](http://www.firebirdsql.org/) -  真正的全球开源数据库
* [Galera](http://galeracluster.com/) - Galera MySQL集群是一个易于使用的高可用性解决方案，具有很高的系统正常运行时间,没有数据丢失,为未来的增长提供可伸缩性。
* [MariaDB](https://mariadb.org/) - MySQL的社区开发分支
* [MySQL](http://dev.mysql.com/) -  非常流行的RDBMS服务器
* [Percona Server](http://www.percona.com/software) - 增强的，可替换MySQL
* [PostgreSQL](http://www.postgresql.org/) -  对象关系数据库管理系统（ORDBMS)
* [PostgreSQL-XL](http://www.postgres-xl.org/) -  基于PostgreSQL的可伸缩开源数据库集群
* [SQLite](http://sqlite.org/) - 自包容，弱服务器，零配置，支持事务的SQL DBS实现库

## Security
*Security tools.*

* [Denyhosts](http://denyhosts.sourceforge.net/) - 阻止SSH字典攻击和暴力攻击
* [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) -  扫描日志文件，并对具有恶意行为显示的IP采取措施
* [SpamAssassin](https://spamassassin.apache.org/) - 一个强大的和受欢迎的垃圾邮件过滤器，它采用多种检测技术。

## Service Discovery

* [Consul](http://www.consul.io/) -  Consule是伊戈尔服务发现，监控和配置的工具
* [Doozerd](https://github.com/ha/doozerd) -  Doozer是一个高可用，完全一致的存储，用于少量非常重要的数据
* [ZooKeeper](http://zookeeper.apache.org/) -  ZooKeeper是一个集中的服务，用于维护配置信息，命名，提供分布式同步和组服务

## SMTP
*SMTP servers.*

* [Exim](http://www.exim.org/) - 由剑桥大学开发的消息传输代理（MTA)
* [Haraka](http://haraka.github.io/) -  用JavaScirpt编写的高性能，可插入的SMTP服务器
* [MailCatcher](http://mailcatcher.me/) - Ruby gem部署一个简单的SMTP MTA网关，接收所有邮件并在web接口显示。对调试和开发有用。
* [Maildrop](https://github.com/m242/maildrop) - 开源的一次性邮件服务器，对开发也很有用
* [OpenSMTPD](https://opensmtpd.org/) - 从OpenBSD项目实现的安全的SMTP服务器
* [Postfix](http://www.postfix.org/) -  快速，易于管理和安全的Sendmail替代品
* [Qmail](http://cr.yp.to/qmail.html) -  安全的Sendmail替代品
* [Sendmail](http://www.sendmail.com/sm/open_source/) - 消息传输代理（MTA)

## Software Containers
*Operating system–level virtualization.*

* [Bitnami](https://bitnami.com/) - 为web应用，开发栈和虚拟设备生产开源软件安装器或软件包
* [Docker](http://www.docker.com/) -  给开发者和系统管理员构建，发布和运行分布式应用程序的开放平台
* [OpenVZ](http://openvz.org) - Linux平台基于容器的虚拟化

## SSH
*SSH tools.*

* [autossh](http://www.harding.motd.ca/autossh/) - 网络中断后自动复位ssh会话。
* [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - 通过一个图形化控制台控制多个xterm窗口。
* [DSH](http://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer的shell/分布式shell-从一个命令行包装执行多个远程shell命令。
* [Mosh](http://mosh.mit.edu/) -  移动shell
* [parallel-ssh](http://code.google.com/p/parallel-ssh/) - 提供并行的OpenSSH版本和相关工具
* [SSH Power Tool](http://code.google.com/p/sshpt/) - 不使用pre-shared钥匙的情况下对多个服务器同时执行命令和上传文件

## Statistics
*Analytics software.*

* [Analog](http://www.analog.cx/) -  世界上最流行的日志分析工具
* [GoAccess](http://goaccess.io/) - 在终端运行的开源的实时web日志分析和交互视图
* [Piwik](http://piwik.org/) - 免费和开源的web分析应用
* [Webalizer](http://www.webalizer.org/) -  F快速免费的web服务器日志文件分析程序

## Ticketing systems
*Web-based ticketing system.*

* [Bugzilla](http://www.bugzilla.org/) - 由Mozilla项目开发和使用过的通用缺陷跟踪和测试工具
* [Cerb](http://www.cerberusweb.com/) -  基于商业开源许可的基于组的邮件管理项目
* [Flyspray](http://flyspray.org) -  使用PHP编写的缺陷跟踪系统
* [MantisBT](http://www.mantisbt.org/) - 另一个基于web的缺陷跟踪系统
* [osTicket](http://osticket.com/) - 开源的技术支持工单系统
* [Otrs](http://www.otrs.com/) - 免费和开源故障通知单系统软件包,公司,组织,或其他实体可以使用它来基于询问分配工单并跟踪进一步的沟通。and track further communications about them.
* [Request Tracker](http://www.bestpractical.com/rt/) - 使用Perl编写的工单跟踪系统
* [TheBugGenie](http://www.thebuggenie.com) - 开源的工单系统，具有非常完备的用户权限分配

## Troubleshooting
*Troubleshooting Tools.*

* [mitmproxy](http://mitmproxy.org/) - ython工具，用于拦截,查看和修改网络流量。在排除某些问题是非常重要的。
* [Sysdig](http://www.sysdig.org/) - 从一个运行的linux实例上捕获系统状态和活动，之后保存，过滤和分析
* [Wireshark](http://www.wireshark.org/) - 世界上著名的网络协议分析工具

## Project Management
*Web-based project management and bug tracking systems.*

* [ChiliProject](https://www.chiliproject.org) -  Redmine分支
* [GitBucket](https://github.com/takezoe/gitbucket) Clone of GitHub written in Scala; single jar install.
* [GitLab](https://www.gitlab.com/) - 用Rbuy编写的GitHub的克隆
* [Gogs](http://gogs.io/) - 用Go编写
* [OpenProject](https://www.openproject.org) - 开源的项目协作项目
* [Phabricator](http://phabricator.org/) Written in PHP.
* [Redmine](http://www.redmine.org/) -  基于rails在rbuy编写
* [The Bug Genie](http://www.thebuggenie.com/) - PHP编写
* [Trac](http://trac.edgewall.org/) - python编写

## Version control
*Software versioning and revision control.*

* [Fossil](http://www.fossil-scm.org/) - 分布式版本控制，内建wiki和缺陷跟踪
* [Git](http://git-scm.com/) - 速度很快的分布式版本控制和源代码管理
* [GNU Bazaar](http://bazaar.canonical.com/) - 由Cannoicalzi赞助的分布式版本控制系统
* [Mercurial](http://mercurial.selenic.com/) - 另一个版本控制
* [Subversion](http://subversion.apache.org/) - 客户端-服务器版本控制系统

## Virtualization
*Virtualization software.*

* [Ganeti](https://code.google.com/p/ganeti/) - 在KVM和Xen上构建的集群虚拟服务器管理软件
* [KVM](http://www.linux-kvm.org) - Linux内核虚拟化架构
* [oVirt](http://www.ovirt.org/) - 管理虚拟机，存储和虚拟网络
* [Packer](http://www.packer.io/) -  从单个源配置为多个平台创建相同的机器镜像
* [Vagrant](https://www.vagrantup.com/) -  创建完整开发环境的工具
* [VirtualBox](https://www.virtualbox.org/) - 来自Oracle公司的虚拟化产品
* [Xen](http://www.xenproject.org/) - 用于32/64位Intel/AMD(IA 64）和PowerPC 970架构的虚拟机监控器

## VPN
*VPN software.*

* [OpenVPN](https://community.openvpn.net) - 使用一个定制的安全密钥交换协议,利用SSL / TLS。
* [Pritunl](http://pritunl.com/) - 基于OpenVPN的方案，易于设置
* [SoftEther](https://www.softether.org/) -  具有高级特性的多协议VPN软件
* [sshuttle](https://github.com/apenwarr/sshuttle) - 穷人的VPN
* [strongSwan](http://www.strongswan.org/) -  Linux下完整的IPsec实现
* [tinc](http://www.tinc-vpn.org/) - 分布式点对点VPN

## XMPP
*XMPP servers.*

* [ejabberd](http://www.ejabberd.im/) - 用Erlang/OTP编写的XMPP短信服务器
* [Metronome IM](http://www.lightwitch.org/metronome) - Prosody IM分支
* [MongooseIM](https://www.erlang-solutions.com/products/mongooseim-massively-scalable-ejabberd-platform) - ejabberd分支
* [Openfire](http://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器
* [Prosody IM](http://prosody.im/) - Lua编写的XMPP服务器
* [Tigase](https://projects.tigase.org/projects/tigase-server) - java实现的XMPP服务器

## Webmails
*Webmail applications.*

* [Mailpile](https://www.mailpile.is/) -  一个先进，快速的web-mail客户端，具有用户友好的加密的私有个性
* [Roundcube](http://roundcube.net/) -  基于浏览器的IMAP客户端，具有应用类似的用户界面

## Web
*Web servers.*

* [Apache](http://httpd.apache.org/) - 最流行的web服务器
* [Cherokee](http://cherokee-project.com/) - 轻量级，高性能的web服务器/反向代理
* [Lighttpd](http://www.lighttpd.net/) -  speed-critical环境下更优化的web服务器
* [Nginx](http://nginx.org/) - 反向代理，负载均衡器，HTTP缓存和web服务器
* [uWSGI](https://github.com/unbit/uwsgi/) - uWSGI项目，目标在开发一个构建主机服务的全栈

*Web Performance*

* [HAProxy](http://www.haproxy.org/) -  负载均衡，SSL卸载和性能优化，压缩和通用web路由
* [Varnish](https://www.varnish-cache.org/) - 基于HTTP的web应用加速器，关注内存优化和压缩


## Wikis
*Wiki software.*

* [DokuWiki](https://www.dokuwiki.org/dokuwiki) - 使用简单和高度通用的wiki,这并不需要一个数据库。
* [Gollum](https://github.com/gollum/gollum) -  一个简单,Git-powered wiki，具有不错的API和本地前端。
* [ikiwiki](http://ikiwiki.info/) - 一个wiki编译器
* [Mediawiki](http://www.mediawiki.org/wiki/MediaWiki) - 加强Wikipedia
* [MoinMoin](http://moinmo.in/) - 一个高级的易用的扩展性强的Wiki引擎，具有大量的社区用户
 * [Ōlelo Wiki](https://github.com/minad/olelo) -  在Git存储上保存页面的wiki
* [TiddlyWiki](http://tiddlywiki.com) -  JavaScript的完整交互wiki

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [Code as Craft](http://codeascraft.com/) -  Etsy的运维博客，大量的技术博客
* [DevOpsGuys](http://blog.devopsguys.com/) -  Devops顾问，运维博客
* [Rackspace Developers](http://developer.rackspace.com/blog/) - 具有大量Devops主题的博客

## Books
*Sysadmin related books.*

* [The Linux Command Line](http://linuxcommand.org/tlcl.php) -  William Shotts的书，关于Linux命令行
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - DevOps技术如何修复发生在IT组织的问题
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) -  第一和第二版本描述系统和网络管理的最佳实践,独立于特定平台或技术。independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - 一个方法论,旨在启动实施控制和过程改进。
* [UNIX and Linux System Administration Handbook](http://www.admin.com/) -  从使用的角度走进系统管理

## Editors
*Open source code editors.*

* [Atom](https://atom.io/) - 来自Github的文本编辑器
* [Brackets](http://brackets.io/) -  用于web设计和前端开发的开源代码编辑器
* [Eclipse](http://eclipse.org/) -  用Java编写的IDE，具有可扩展的插件系统
* [Geany](http://www.geany.org/) - GTK2文本编辑器
* [GNU Emacs](http://www.gnu.org/software/emacs/) - 一个可扩展，自定义的文本编辑器
* [Haroopad](http://pad.haroopress.com/) - Markdown编辑器，具有实时预览
* [ICEcoder](http://icecoder.net) - 非常棒的代码编辑器，内建常见的web语言
* [jotgit](https://github.com/jdleesmiller/jotgit) - Git支持的实时协作代码编辑
* [Light Table](http://www.lighttable.com/) -  下一代代码编辑器
* [Lime](http://limetext.org/) - 旨在提供一个Sublime Text的开源替代方案
* [TextMate](https://github.com/textmate/textmate/) - OS X下的图形文本编辑器
* [Vim](http://www.vim.org) - 一个高可配置的文本编辑器，用于高效编辑

## Newsletters

* [Servers for Hackers](http://serversforhackers.com/) - 程序员的时事通讯，发现他们需要知道的服务器相关内容。

## Repositories
*Software package repositories.*

* [Dotdeb](http://www.dotdeb.org/) - Debian下LAMP更新包的存储
* [Remi](http://rpms.famillecollet.com/) - RHEL/Centos/Fedora下LAMP更新包的存储

## Websites
*Useful sysadmin related websites.*

* [Ops School](http://www.opsschool.org) - 全面的计划,将帮助你成为一名运维工程师。
* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - 一个非常庞大资源，获得基本的应用程序，工具,甚至是系统管理主题。

# Contributing
Please see [CONTRIBUTING](https://github.com/kahun/awesome-sysadmin/blob/master/CONTRIBUTING.md) for details.
