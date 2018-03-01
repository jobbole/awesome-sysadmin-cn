# 系统管理员资源大全中文版

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) 就是 kahun 发起维护的 系统管理员 资源列表，内容包括：备份/克隆软件、云计算/云存储、协作软件、配置管理、日志管理、监控、项目管理

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

* * *

### 我们要做什么？

- 基于 awesome-sysadmin 资源列表，我们将对各个资源项进行编译整理。
- 整理后的内容，将收录在[伯乐在线资源频道](http://hao.jobbole.com/)。可参考已整理的内容：
  - 《[Logstash：日志文件管理工具](http://hao.jobbole.com/logstash/)》
  - 《[MyCli：支持自动补全和语法高亮的 MySQL 客户端](http://hao.jobbole.com/mycli-mysql/)》

* * *

### 如何参与本项目？

<!-- 从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 有 系统管理员/运维 相关实践经验；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「系统管理员大全」 -->

* * *

### 本项目的参与者

- 维护者：[tangyouhua](https://github.com/tangyouhua)

- 贡献者：[cucr](http://www.jobbole.com/members/cucr/)、[冰斌](http://hao.jobbole.com/author/libing1209/)、[黄余粮](http://www.jobbole.com/members/huangyuliang/)、You

注：名单不分排名，不定期补充更新

* * *

<!-- ### 奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

* 整理超过 20 个资源后，可在伯乐在线上开通打赏；
* 每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
* [奖励详情](http://hao.jobbole.com/rewards/)

* * * -->


## 备份

备份软件

*   Amanda：客户端-服务器模型备份工具。[官网](http://www.amanda.org/)
*   Bacula：另一个客户端-服务器模型备份工具。[官网](http://www.bacula.org/)
*   Backupninja：轻量级，可扩展的元数据备份系统。[官网](https://labs.riseup.net/code/projects/backupninja)
*   Backuppc：客户端-服务器模型备份工具和文件共享方案。[官网](http://backuppc.sourceforge.net/)
*   Burp：网络备份和还原程序。[官网](http://burp.grke.org/)
*   Duplicity：使用rsync算法加密的带宽-效率备份。[官网](http://duplicity.nongnu.org/)
*   Lsyncd：监控一个本地目录树的变化,然后产生一个进程去同步变化。默认使用rsync。[官网](https://github.com/axkibe/lsyncd)
*   Rsnapshot：文件系统快照工具。[官网](http://www.rsnapshot.org/)
*   SafeKeep：使用rdiff-backup，集中的，基于pull的备份。[官网](http://safekeep.sourceforge.net/)
*   TarSnap：具有一个开源客户端的安全备份服务。[官网](https://www.tarsnap.com/)
*   UrBackup：另一个客户端-服务器备份系统。[官网](http://www.urbackup.org/)
*   DREBS：AWS EBS支持策略的备份脚本。[官网](https://github.com/dojo4/drebs)

## 克隆

克隆软件

*   Clonezilla：分区和磁盘镜像/克隆程序。[官网](http://clonezilla.org/)
*   Fog：另一个计算机克隆解决方案。[官网](http://www.fogproject.org/)
*   Redo Backup：简单的备份，恢复和还原。[官网](http://redobackup.org/)

## 云计算

*   AppScale - 兼容Google App引擎的开源云计算软件.
*   Archipel：使用Libvirt管理和监视虚拟机。[官网](http://archipelproject.org/)
*   CloudStack：创建，管理和部署基础云服务的云计算软件。[官网](http://cloudstack.apache.org/)
*   Cobbler：Cobbler是一个Linux安装服务器，允许快速地构建网络安装环境。[官网](http://www.cobblerd.org/)
*   Eucalyptus：兼容AWS的开源私有云软件。[官网](https://www.eucalyptus.com/)
*   Mesos：开发和运行能效高的分布式系统。[官网](http://mesos.apache.org/)
*   OpenNebula：一个用于系统管理员和研发运维的用户驱动的云管理平台。[官网](http://opennebula.org/)
*   OpenStack：构建私有和开放云的开源软件。[官网](https://www.openstack.org/)
*   The Foreman：Foreman是一个用于物理和虚拟服务器的全生命周期管理工具.FOSS.。[官网](http://theforeman.org/)

## 云业务流程

*   BOSH：IaaS业务流程平台，最初用于部署和管理云计算平台PaaS,但也用于通用的分布式系统。[官网](http://docs.cloudfoundry.org/bosh/)
*   Cloudify：使用Python和YAML编写的开源TOSCA-based云业务流程软件平台。[官网](http://www.getcloudify.org/)
*   Juju：云业务流程工具用于管理服务，比如charms，YAML配置和部署脚本集。[官网](https://juju.ubuntu.com/)
*   MCollective：来自Puppet实验室的管理服务器业务流程和开发的Ruby框架。[官网](http://puppetlabs.com/mcollective)
*   Overcast：在不同的云提供商上部署VMs，并在任何或所有（VM）上通过SSH并行运行命令行和脚本。[官网](http://andrewchilds.github.io/overcast/)
*   Rundeck：简单的业务流程工具。[官网](http://rundeck.org/)
*   Salt：Python编写。[官网](http://www.saltstack.com/)

## 云存储

*   git-annex assistant：在你的每一个OSX和Linux电脑，Android设备，可移动驱动，NAS电器和云服务上一个同步文件夹。[官网](http://git-annex.branchable.com/assistant/)
*   ownCloud：提供你的文件的统一访问，通过web，你的电脑和你的移动设备。[官网](https://owncloud.org/)
*   Seafile：另一个开源的云存储解决方案。[官网](http://seafile.com/)
*   [SparkleShare](http://hao.jobbole.com/sparkleshare/)：提供云存储和文件同步服务。它默认使用Git作为存储后端。[官网](http://sparkleshare.org/)
*   Swift：一个高可用，分布式，最终一致的对象/大数据存储。[官网](http://docs.openstack.org/developer/swift/)
*   Syncthing：一个用于私有，加密和身份认证数据的开源系统。[官网](http://syncthing.net/)

## 代码审查

基于Web的协作式代码审查系统

*   Gerrit：基于Git版本控制，它促进软件开发人员审查源代码修改和批准或拒绝这些变更。[官网](https://code.google.com/p/gerrit/)
*   Review Board：基于MIT License的可用自由软件。[官网](https://www.reviewboard.org/)

## 协作软件

协作软件和群件套件

*   Citadel/UX：协同套件（消息和群件）继承于Citadel家族程序。[官网](http://www.citadel.org/)
*   EGroupware：PHP编写的群件软件。[官网](http://www.egroupware.org/)
*   Horde Groupware：基于PHP的协作软件套件，包括邮件，日历，wiki，时间跟踪和文件管理。[官网](http://www.horde.org/apps/groupware)
*   Kolab：另一个群件套件。[官网](https://www.kolab.org/)
*   SOGo：协作软件服务器，专注简单性和可伸缩性。[官网](https://www.sogo.nu/)
*   Zimbra：协作软件套件，包括邮件服务和web客户端。[官网](https://www.zimbra.com/community/)

## 配置管理数据库

配置管理数据库（CMDB）软件

*   i-doit：开源的IT文档管理和CMDB。[官网](http://www.i-doit.org/)
*   iTop：一个完全开源的，ITIL,基于web的服务管理工具。[官网](http://www.combodo.com/-Overview-.html)
*   Ralph：用于大型数据中心或较小本地网络的资产管理，DICM和CMDB系统。[官网](https://github.com/allegro/ralph)
*   Clusto：帮助跟踪你的库存，在哪，如何连接，同时提供一个和基础架构元素交互的抽象接口。[官网](https://github.com/clusto/clusto)

## 配置管理

配置管理工具

*   Ansible：Python编写的，通过SSH管理节点。[官网](http://www.ansibleworks.com/)
*   CFEngine：轻量级代理系统。通过申明语言配置状态。[官网](http://cfengine.com/)
*   Chef：Ruby和Erlang编写，使用纯RubyDSL。[官网](http://www.opscode.com/chef/)
*   Fabric：Python库和cli工具，为应用程序部署或系统管理任务简化使用SSH。[官网](http://www.fabfile.org/)
*   Pallet：通过Clojure DSL进行架构定义，配置和管理。[官网](http://palletops.com/)
*   Puppet：Ruby编写，使用Puppet声明语言或Ruby DSL。[官网](http://puppetlabs.com/)
*   Salt：Python编写。[官网](http://www.saltstack.com/)
*   Slaughter：Perl编写。[官网](http://steve.org.uk/Software/slaughter/)

## 持续继承和持续部署

持续集成/部署软件

*   Buildbot：基于Python的持续集成工具。[官网](http://buildbot.net/)
*   Drone：构建在Docker，使用YAML文件配置的的持续集成服务器。[官网](https://github.com/drone/drone)
*   GitLab CI：基于Ruby。他们也提供GitLab用于管理git存储库。[官网](https://www.gitlab.com/gitlab-ci/)
*   Go：开源的持续交付服务器。[官网](http://www.go.cd/)
*   Jenkins：一个可扩展的开源持续集成服务器。[官网](http://jenkins-ci.org/)
*   Vlad the Deployer：自动化部署。[官网](http://rubyhitsquad.com/Vlad_the_Deployer.html)

## 分布式文件系统

网络分布式文件系统

*   Ceph：分布式对象存储和文件系统。[官网](http://ceph.com/)
*   DRBD：分布式块设备复制。[官网](http://www.drbd.org/)
*   LeoFS：非结构化对象/数据存储和高可用性,分布,最终一致的存储系统。[官网](http://leo-project.net/)

*   GlusterFS：可扩展，网络附加存储文件系统。[官网](http://www.gluster.org/)
*   HDFS：Java编写的，用于Hadoop框架的分布式、可伸缩、可移植文件系统。[官网](http://hadoop.apache.org/)
*   Lustre：一种并行分布式文件系统,一般用于大规模集群计算。[官网](http://lustre.opensfs.org/)
*   MooseFS：容错、网络分布式文件系统。[官网](http://www.moosefs.org/)
*   MogileFS：应用程序级别、网络分布式文件系统。[官网](http://mogilefs.org/)

*   OpenAFS：只读副本和多操作系统支持的分布式网络文件系统。[官网](http://www.openafs.org/)

*   TahoeLAFS：安全、分散、容错、点对点分布式数据存储和分布式文件系统。[官网](https://tahoe-lafs.org/trac/tahoe-lafs)
*   XtreemFS：XtreemFS是一个用于存储需求的容错式分布式文件系统。[官网](http://www.xtreemfs.org/)

## DNS

DNS服务器

*   Bind：最广泛使用的域名服务软件。[官网](https://www.isc.org/downloads/bind/)
*   djbdns：DNS应用集合，包括tinydns。[官网](http://cr.yp.to/djbdns.html)
*   Designate：DNS REST API,支持多种DNS服务器的后端。[官网](https://wiki.openstack.org/wiki/Designate)
*   dnsmasq：为小规模网络提供DNS,DHCP和TFTP服务的轻量级服务。[官网](http://www.thekelleys.org.uk/dnsmasq/doc.html)
*   Knot：高性能，权威的DNS服务器。[官网](https://www.knot-dns.cz/)
*   NSD：权威的、高性能的、简单的域名服务器。[官网](http://www.nlnetlabs.nl/projects/nsd/)
*   PowerDNS：具有各种数据存储后端和负载平衡功能的DNS服务器。[官网](https://www.powerdns.com/)
*   Unbound：验证、递归和缓存DNS解析器。[官网](http://unbound.net/)
*   Yadifa：具有DNSSEC兼容的轻量级的权威域名服务器，支持.eu的顶级域名。[官网](http://yadifa.eu/)

## 主机控制面板

Web主机控制面板

*   Ajenti：Linux和BSD控制面板。[官网](http://ajenti.org/)
*   Feathur：VPS供应和管理软件。[官网](http://feathur.com/)
*   ISPConfig：Linux主机控制面板。[官网](http://www.ispconfig.org/)
*   VestaCP：用于Linux和Nginx的主机面板。[官网](http://www.vestacp.com/)
*   Virtualmin：基于webmin的Linux控制面板。[官网](http://www.virtualmin.com/)
*   ZPanel：Linux BSD和Windows控制面板。[官网](http://www.zpanelcp.com/)

## IMAP/POP3

IMAP/POP3邮件服务器

*   Courier IMAP/POP3：快速，可伸缩，企业级IMAP和POP3服务器。[官网](http://www.courier-mta.org/imap/)
*   Cyrus IMAP/POP3：运行在密封服务器上,普通用户不允许登录。[官网](http://cyrusimap.org/)
*   Dovecot：主要考虑安全而编写的IMAP和POP3服务器。[官网](http://www.dovecot.org/)
*   Qpopper：一个古老且流行的POP3服务器实现。[官网](http://www.eudora.com/products/unsupported/qpopper/)

## IT资产管理

IT资产管理软件

*   GLPI：带有额外管理接口的信息资源管理器。[官网](http://www.glpi-project.org/spip.php?lang=en)
*   OCS Inventory NG：允许用户清算IT资产。[官网](http://www.ocsinventory-ng.org/en/)
*   RackTables：数据中心和服务器房间资产，比如将硬件资产,网络地址,在货架空间,网络配置文档化。[官网](http://racktables.org/)
*   Ralph：针对大型数据中心系统以及小型局域网网络的资产管理、DCIM和CMDB。[官网](https://github.com/allegro/ralph)
*   Snipe IT：资产和许可证管理软件。[官网](http://snipeitapp.com/)

## LDAP

LDAP服务器

*   389 Directory Server：通过Red Hat部署。[官网](http://port389.org/)
*   Apache Directory Server：用Java编写的Apache软件基金会项目。[官网](http://directory.apache.org/)
*   Fusion Directory：基于OpenLDAP改善服务和公司目录的管理。[官网](http://www.fusiondirectory.org/)
*   OpenDJ：OpenDS分支。[官网](http://opendj.forgerock.org/)
*   OpenDS：另一个用Java编写的目录服务器。[官网](https://opends.java.net/)
*   OpenLDAP：由OpenLDAP项目开发。[官网](http://openldap.org/)

## 日志管理

日志管理工具：收集，解析，可视化

*   Elasticsearch：一个基于Lucene的文档存储，主要用于日志索引、存储和分析。[官网](http://www.elasticsearch.org/)
*   Fluentd：日志收集和发出。[官网](http://www.fluentd.org/)
*   Flume：分布式日志收集和聚合系统。[官网](https://flume.apache.org/)
*   Graylog2：具有报警选项的可插入日志和事件分析服务器。[官网](http://graylog2.org/)
*   Heka：流处理系统，可用于日志聚合。[官网](http://hekad.readthedocs.org/en/latest/)
*   Kibana：可视化日志和时间戳数据。[官网](http://www.elasticsearch.org/overview/kibana/)
*   Logstash：管理事件和日志的工具。[官网](http://hao.jobbole.com/logstash/)
*   Octopussy：日志管理解决方案（可视化/报警/报告）。[官网](http://www.octopussy.pm/)


## 监控

监控软件

*   Cacti：基于Web的网络监控和图形工具。[官网](http://www.cacti.net/)
*   Cabot：监控和报警，类似PagerDuty。[官网](http://cabotapp.com/)
*   check_mk：Nagios的扩展集合。[官网](http://mathias-kettner.com/check_mk.html)
*   [Dash](http://hao.jobbole.com/linux-dash/)：一个用于GNU/Linux机器的低开销web仪表板监控。[官网](http://linuxdash.afaqtariq.com/#/system-status) [Github](https://github.com/afaqurk/linux-dash)
*   Icinga：Nagios分支。[官网](https://www.icinga.org/)
*   LibreNMS：Observium分支。[官网](https://github.com/librenms/librenms/)
*   Monit：管理和监控Unix系统的小型开源工具。[官网](http://mmonit.com/monit/#home)
*   Munin：网络资源监控工具。[官网](http://munin-monitoring.org/)
*   Naemon：基于Nagios4内核的网络监控工具，具有性能加强和新功能。[官网](http://www.naemon.org/)
*   Nagios：计算机系统，网络和基础架构监控软件。[官网](http://www.nagios.org/)
*   Observium：服务器和网络设备的SNMP监控，运行在linux。[官网](http://www.observium.org/)
*   OMD：开放的监控分布。[官网](http://omdistro.org/)
*   Opsview：基于Nagios4，Opsview核心，用于小型IT和测试环境。[官网](http://www.opsview.com/solutions/core)
*   Riemann：灵活和快速的事件处理器，允许负责时间和度量分析。[官网](http://riemann.io/)
*   Sensu：开源的监控框架。[官网](http://sensuapp.org/)
*   Sentry：应用监控，事件记录和聚合。[官网](https://getsentry.com/)
*   Shinken：另一个监控框架。[官网](http://www.shinken-monitoring.org/)
*   Thruk：多后台监控的web接口，支持Naemon，Nagios，Icinga和Shinken。[官网](http://www.thruk.org/)
*   Xymon：灵感来自Big Brother的网络监控。[官网](http://www.xymon.com/)
*   Zabbix： Enterprise-class software for monitoring of networks and applications.。[官网](http://www.zabbix.com/)
*   Zabbix：监控网络和应用的企业级软件。[官网](http://www.zabbix.com/)
*   Zenoss：基于Zope的应用，服务器和网络管理平台。[官网](http://community.zenoss.org/)

## 度量和度量收集

度量收集和显示软件

*   Collectd：系统统计收集守护进程。[官网](http://collectd.org/)
*   Collectl：高精度系统性能指标收集工具。[官网](http://collectl.sourceforge.net/)
*   Dashing：Ruby gem,允许快速统计仪表板的开发。基于HTML5，允许在数据中心或会议室进行大屏幕显示。[官网](http://dashing.io/)
*   Diamond：基于Python的统计收集守护进程。[官网](https://github.com/BrightcoveOS/Diamond)
*   Ganglia：基于RRD用于网格和/或集群的服务器的高性能、可伸缩监控设备。兼容Graphite，使用一个单一的收集进程。[官网](http://ganglia.sourceforge.net/)
*   Grafana：一个Graphite或InfluxDB仪表盘和图形编辑器。[官网](http://grafana.org/)
*   开源的可伸缩绘图服务器
*   InfluxDB：开源的分布式时间序列数据库，没有外部依赖。[官网](http://influxdb.com/)
*   KairosDB：快速分布式可扩展的时间序列数据库,OpenTSDB 1.x的分支。[官网](https://code.google.com/p/kairosdb/)
*   OpenTSDB：存储和服务大量的时间序列数据，不丢失粒度。[官网](http://opentsdb.net/)
*   RRDtool：开源企业标准，用于时间序列数据的高性能数据记录和绘图系统。[官网](http://oss.oetiker.ch/rrdtool/)
*   Statsd：应用统计监听。[官网](https://github.com/etsy/statsd/)

## 网络配置管理

网络配置管理工具

*   GestióIP：一个自动的基于web的IPV4/IPV6地址管理工具。[官网](http://www.gestioip.net/)
*   RANCID：监控网络设备配置和维护历史变更。[官网](http://www.shrubbery.net/rancid/)
*   rConfig：另一个网络配置管理工具。[官网](http://www.rconfig.com/)

## 时事通讯

时事通讯软件

*   DadaMail：Perl编写的邮件列表管理器。[官网](http://dadamailproject.com/)
*   phpList：PHP编写的时事通讯管理器。[官网](http://www.phplist.com/)

## NOSQL

NOSQL数据库

*   列族
    *   Apache HBase：Hadoop数据库，一个分布式的大数据存储。[官网](http://hbase.apache.org/)
    *   Cassandra：分布式数据库管理系统，设计用于处理大量数据跨多个服务器。[官网](http://cassandra.apache.org/)
    *   Hypertable：基于c++的bigtable DBMS,节省通信，可独立或在Hadoop类似的分布式FS上运行。[官网](http://hypertable.org/)
*   文档存储
    *   CouchDB：易于使用,多主机复制的面向文档的数据库系统。[官网](http://couchdb.apache.org/)
    *   ElasticSearch：基于Java的数据库,受欢迎的日志聚合,和电子邮件归档项目。[官网](http://www.elasticsearch.org/)
    *   MongoDB：另一个面向文档的数据库系统。[官网](http://www.mongodb.org/)
    *   RavenDB：具有ACID/事物功能的基于文档的数据库。[官网](http://ravendb.net/)
    *   RethinkDB：开源分布式文档存储数据库，关注JSON。[官网](http://www.rethinkdb.com/)
*   图
    *   FlockDB：Twitter分布式，容错图数据库。[官网](https://github.com/twitter/flockdb)
    *   Neo4j：开源图数据库。[官网](http://www.neo4j.org/)
*   键值
    *   LevelDB：Google高性能键值数据库。[官网](https://code.google.com/p/leveldb/)
    *   Redis：支持网络，基于内存，键值，亦可持久化数据库。[官网](http://redis.io/)
    *   [Riak](http://hao.jobbole.com/riak/)：另一个容错的键值NoSQL数据库。[官网](http://basho.com/riak/)

NoSQL服务器比较: [http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis](http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis)

## 打包

*   fpm：万能的多格式包创建器。[官网](https://github.com/jordansissel/fpm)
*   omnibus-ruby：全栈，跨发行版的包管理软件（Ruby）。[官网](https://github.com/opscode/omnibus-ruby)
*   packman：全栈，跨发行版的包管理软件（Python）。[官网](http://packman.readthedocs.org/)
*   tito：为git项目构建RPM。[官网](https://github.com/dgoodwin/tito)

## 队列

*   BeanstalkD：一个简单快速的工作队列。[官网](http://kr.github.io/beanstalkd/)
*   Gearman：快速的多语言队列或任务处理平台。[官网](http://gearman.org/)
*   NSQ：实时分发的消息平台。[官网](http://nsq.io/)
*   RabbitMQ：健壮的，全功能，跨发行版的队列系统。[官网](http://www.rabbitmq.com/)
*   ZeroMQ：轻量级队列系统。[官网](http://zeromq.org/)

## RDBMS

关系数据库管理系统

*   Firebird：真正的全球开源数据库。[官网](http://www.firebirdsql.org/)
*   Galera：Galera MySQL集群是一个易于使用的高可用性解决方案，具有很高的系统正常运行时间,没有数据丢失,为未来的增长提供可伸缩性。[官网](http://galeracluster.com/)
*   MariaDB：MySQL的社区开发分支。[官网](https://mariadb.org/)
*   MySQL：非常流行的RDBMS服务器。[官网](http://dev.mysql.com/)
*   Percona Server：增强的，可替换MySQL。[官网](http://www.percona.com/software)
*   PostgreSQL：对象关系数据库管理系统（ORDBMS)。[官网](http://www.postgresql.org/)
*   PostgreSQL-XL：基于PostgreSQL的可伸缩开源数据库集群。[官网](http://www.postgres-xl.org/)
*   SQLite：自包容，弱服务器，零配置，支持事务的SQL DBS实现库。[官网](http://sqlite.org/)

## 安全

安全工具

*   Denyhosts：阻止SSH字典攻击和暴力攻击。[官网](http://denyhosts.sourceforge.net/)
*   Fail2Ban：扫描日志文件，并对具有恶意行为显示的IP采取措施。[官网](http://www.fail2ban.org/wiki/index.php/Main_Page)
*   SpamAssassin：一个强大的和受欢迎的垃圾邮件过滤器，它采用多种检测技术。[官网](https://spamassassin.apache.org/)

## 服务发现

*   Consul：Consule是伊戈尔服务发现，监控和配置的工具。[官网](http://www.consul.io/)
*   Doozerd：Doozer是一个高可用，完全一致的存储，用于少量非常重要的数据。[官网](https://github.com/ha/doozerd)
*   ZooKeeper：ZooKeeper是一个集中的服务，用于维护配置信息，命名，提供分布式同步和组服务。[官网](http://zookeeper.apache.org/)

## SMTP

SMTP服务器

*   Exim：由剑桥大学开发的消息传输代理（MTA)。[官网](http://www.exim.org/)
*   Haraka：用JavaScirpt编写的高性能，可插入的SMTP服务器。[官网](http://haraka.github.io/)
*   MailCatcher：Ruby gem部署一个简单的SMTP MTA网关，接收所有邮件并在web接口显示。对调试和开发有用。[官网](http://mailcatcher.me/)
*   Maildrop：开源的一次性邮件服务器，对开发也很有用。[官网](https://github.com/m242/maildrop)
*   OpenSMTPD：从OpenBSD项目实现的安全的SMTP服务器。[官网](https://opensmtpd.org/)
*   Postfix：快速，易于管理和安全的Sendmail替代品。[官网](http://www.postfix.org/)
*   Qmail：安全的Sendmail替代品。[官网](http://cr.yp.to/qmail.html)
*   Sendmail：消息传输代理（MTA)。[官网](http://www.sendmail.com/sm/open_source/)

## 软件容器

操作系统级别的虚拟化

*   Bitnami：为web应用，开发栈和虚拟设备生产开源软件安装器或软件包。[官网](https://bitnami.com/)
*   Docker：给开发者和系统管理员构建，发布和运行分布式应用程序的开放平台。[官网](http://www.docker.com/)
*   OpenVZ：Linux平台基于容器的虚拟化。[官网](http://openvz.org/)

## SSH

SSH工具

*   autossh：网络中断后自动复位ssh会话。[官网](http://www.harding.motd.ca/autossh/)
*   Cluster SSH：通过一个图形化控制台控制多个xterm窗口。[官网](http://sourceforge.net/projects/clusterssh/)
*   DSH：Dancer的shell/分布式shell-从一个命令行包装执行多个远程shell命令。[官网](http://www.netfort.gr.jp/~dancer/software/dsh.html.en)
*   Mosh：移动shell。[官网](http://mosh.mit.edu/)
*   parallel-ssh：提供并行的OpenSSH版本和相关工具。[官网](http://code.google.com/p/parallel-ssh/)
*   SSH Power Tool：不使用pre-shared钥匙的情况下对多个服务器同时执行命令和上传文件。[官网](http://code.google.com/p/sshpt/)

## 统计

分析软件

*   Analog：世界上最流行的日志分析工具。[官网](http://www.analog.cx/)
*   GoAccess：在终端运行的开源的实时web日志分析和交互视图。[官网](http://goaccess.io/)
*   Piwik：免费和开源的web分析应用。[官网](http://piwik.org/)
*   Webalizer： F快速免费的web服务器日志文件分析程序。[官网](http://www.webalizer.org/)

## 工单系统

基于web的工单系统

*   Bugzilla：由Mozilla项目开发和使用过的通用缺陷跟踪和测试工具。[官网](http://www.bugzilla.org/)
*   Cerb：基于商业开源许可的基于组的邮件管理项目。[官网](http://www.cerberusweb.com/)
*   Flyspray：使用PHP编写的缺陷跟踪系统。[官网](http://flyspray.org/)
*   MantisBT：另一个基于web的缺陷跟踪系统。[官网](http://www.mantisbt.org/)
*   osTicket：开源的技术支持工单系统。[官网](http://osticket.com/)
*   Otrs：免费和开源故障通知单系统软件包,公司,组织,或其他实体可以使用它来基于询问分配工单并跟踪进一步的沟通。[官网](http://www.otrs.com/)
*   Request Tracker：使用Perl编写的工单跟踪系统。[官网](http://www.bestpractical.com/rt/)
*   TheBugGenie：开源的工单系统，具有非常完备的用户权限分配。[官网](http://www.thebuggenie.com/)

## 故障排除

故障排除工具

*   mitmproxy：ython工具，用于拦截,查看和修改网络流量。在排除某些问题是非常重要的。[官网](http://mitmproxy.org/)
*   Sysdig：从一个运行的linux实例上捕获系统状态和活动，之后保存，过滤和分析。[官网](http://www.sysdig.org/)
*   Wireshark：世界上著名的网络协议分析工具。[官网](http://www.wireshark.org/)

## 项目管理

基于web的项目管理和缺陷跟踪系统

*   ChiliProject：Redmine分支。[官网](https://www.chiliproject.org/)
*   GitBucket：用Scala编写的GitHub的克隆，单独jar安装。[官网](https://github.com/takezoe/gitbucket)
*   GitLab：用Ruby编写的GitHub的克隆。[官网](https://www.gitlab.com/)
*   Gogs：用Go编写。[官网](http://gogs.io/)
*   OpenProject：开源的项目协作项目。[官网](https://www.openproject.org/)
*   Phabricator：PHP编写。[官网](http://phabricator.org/) 
*   Redmine：基于rails在ruby编写。[官网](http://www.redmine.org/)
*   The Bug Genie：PHP编写。[官网](http://www.thebuggenie.com/)
*   Trac：python编写。[官网](http://trac.edgewall.org/)

## 版本控制

软件版本和版本控制

*   Fossil：分布式版本控制，内建wiki和缺陷跟踪。[官网](http://www.fossil-scm.org/)
*   Git：速度很快的分布式版本控制和源代码管理。[官网](http://git-scm.com/)
*   GNU Bazaar：由Cannoicalzi赞助的分布式版本控制系统。[官网](http://bazaar.canonical.com/)
*   Mercurial：另一个版本控制。[官网](http://mercurial.selenic.com/)
*   Subversion：客户端-服务器版本控制系统。[官网](http://subversion.apache.org/)

## 虚拟化

虚拟化软件

*   Ganeti：在KVM和Xen上构建的集群虚拟服务器管理软件。[官网](https://code.google.com/p/ganeti/)
*   KVM：Linux内核虚拟化架构。[官网](http://www.linux-kvm.org/)
*   oVirt：管理虚拟机，存储和虚拟网络。[官网](http://www.ovirt.org/)
*   Packer：从单个源配置为多个平台创建相同的机器镜像。[官网](http://www.packer.io/)
*   Vagrant：创建完整开发环境的工具。[官网](https://www.vagrantup.com/)
*   VirtualBox：来自Oracle公司的虚拟化产品。[官网](https://www.virtualbox.org/)
*   Xen：用于32/64位Intel/AMD(IA 64）和PowerPC 970架构的虚拟机监控器。[官网](http://www.xenproject.org/)

## VPN

VPN软件

*   OpenVPN：使用一个定制的安全密钥交换协议，利用SSL/TLS。[官网](https://community.openvpn.net/)
*   Pritunl：基于OpenVPN的方案，易于设置。[官网](http://pritunl.com/)
*   SoftEther：具有高级特性的多协议VPN软件。[官网](https://www.softether.org/)
*   sshuttle：穷人的VPN。[官网](https://github.com/apenwarr/sshuttle)
*   strongSwan：Linux下完整的IPsec实现。[官网](http://www.strongswan.org/)
*   tinc：分布式点对点VPN。[官网](http://www.tinc-vpn.org/)

## XMPP

XMPP服务器

*   ejabberd：用Erlang/OTP编写的XMPP短信服务器。[官网](http://www.ejabberd.im/)
*   Metronome IM：Prosody IM分支。[官网](http://www.lightwitch.org/metronome)
*   MongooseIM：ejabberd分支。[官网](https://www.erlang-solutions.com/products/mongooseim-massively-scalable-ejabberd-platform)
*   Openfire：实时协作（RTC）服务器。[官网](http://www.igniterealtime.org/projects/openfire/)
*   Prosody IM：Lua编写的XMPP服务器。[官网](http://prosody.im/)
*   Tigase：java实现的XMPP服务器。[官网](https://projects.tigase.org/projects/tigase-server)

## Webmails

Webmail应用

*   Mailpile：一个先进，快速的web-mail客户端，具有用户友好的加密的私有个性。[官网](https://www.mailpile.is/)
*   Roundcube：基于浏览器的IMAP客户端，具有应用类似的用户界面。[官网](http://roundcube.net/)

## Web

Web服务器

*   Apache：最流行的web服务器。[官网](http://httpd.apache.org/)
*   Cherokee：轻量级，高性能的web服务器/反向代理。[官网](http://cherokee-project.com/)
*   Lighttpd：speed-critical环境下更优化的web服务器。[官网](http://www.lighttpd.net/)
*   Nginx：反向代理，负载均衡器，HTTP缓存和web服务器。[官网](http://nginx.org/)
*   uWSGI：uWSGI项目，目标在开发一个构建主机服务的全栈。[官网](https://github.com/unbit/uwsgi/)

Web性能

*   HAProxy：负载均衡，SSL卸载和性能优化，压缩和通用web路由。[官网](http://www.haproxy.org/)
*   Varnish：基于HTTP的web应用加速器，关注内存优化和压缩。[官网](https://www.varnish-cache.org/)

## Wikis

Wiki软件

*   DokuWiki：使用简单和高度通用的wiki,这并不需要一个数据库。[官网](https://www.dokuwiki.org/dokuwiki)
*   Gollum：一个简单、Git驱动的wiki，具有不错的API和本地前端。[官网](https://github.com/gollum/gollum)
*   ikiwiki：一个wiki编译器。[官网](http://ikiwiki.info/)
*   Mediawiki：加强Wikipedia。[官网](http://www.mediawiki.org/wiki/MediaWiki)
*   MoinMoin：一个高级的易用的扩展性强的Wiki引擎，具有大量的社区用户。[官网](http://moinmo.in/)
*   TiddlyWiki：JavaScript的完整交互wiki。[官网](http://tiddlywiki.com/)
*   Ōlelo Wiki：在Git存储上保存页面的wiki。[官网](https://github.com/minad/olelo)

# 资源

各种资源，比如书籍，网站和文章，用于提升技能和知识

## 博客

*   Code as Craft：Etsy的运维博客，大量的技术博客。[官网](http://codeascraft.com/)
*   DevOpsGuys：Devops顾问，运维博客。[官网](http://blog.devopsguys.com/)
*   Rackspace Developers：具有大量Devops主题的博客。[官网](http://developer.rackspace.com/blog/)

## 书籍

Sysadmin相关书籍

*   The Linux Command Line：William Shotts的书，关于Linux命令行。[官网](http://linuxcommand.org/tlcl.php)
*   The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win：DevOps技术如何修复发生在IT组织的问题。[官网](http://itrevolution.com/books/phoenix-project-devops-book/)
*   The Practice of System and Network Administration：第一和第二版本描述系统和网络管理的最佳实践,独立于特定平台或技术。[官网](http://everythingsysadmin.com/books.html)
*   The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps：一个方法论,旨在启动实施控制和过程改进。[官网](http://www.itpi.org/the-visible-ops-handbook-review.html)
*   UNIX and Linux System Administration Handbook：从使用的角度走进系统管理。[官网](http://www.admin.com/)

## 编辑器

开源的代码编辑器

*   Atom：来自Github的文本编辑器。[官网](https://atom.io/)
*   Brackets：用于web设计和前端开发的开源代码编辑器。[官网](http://brackets.io/)
*   Eclipse：用Java编写的IDE，具有可扩展的插件系统。[官网](http://eclipse.org/)
*   Geany：GTK2文本编辑器。[官网](http://www.geany.org/)
*   GNU Emacs：一个可扩展，自定义的文本编辑器。[官网](http://www.gnu.org/software/emacs/)
*   Haroopad：Markdown编辑器，具有实时预览。[官网](http://pad.haroopress.com/)
*   ICEcoder：非常棒的代码编辑器，内建常见的web语言。[官网](http://icecoder.net/)
*   jotgit：Git支持的实时协作代码编辑。[官网](https://github.com/jdleesmiller/jotgit)
*   Light Table：下一代代码编辑器。[官网](http://www.lighttable.com/)
*   Lime：旨在提供一个Sublime Text的开源替代方案。[官网](http://limetext.org/)
*   TextMate：OS X下的图形文本编辑器。[官网](https://github.com/textmate/textmate/)
*   Vim：一个高可配置的文本编辑器，用于高效编辑。[官网](http://www.vim.org/)

## 时事通讯

*   Servers for Hackers：程序员的时事通讯，发现他们需要知道的服务器相关内容。[官网](http://serversforhackers.com/)

## 存储

软件包存储

*   Dotdeb：Debian下LAMP更新包的存储。[官网](http://www.dotdeb.org/)
*   Remi：RHEL/Centos/Fedora下LAMP更新包的存储。[官网](http://rpms.famillecollet.com/)

## 网站

有用的系统管理员相关的网站

*   Ops School：全面的计划,将帮助你成为一名运维工程师。[官网](http://www.opsschool.org/)
*   Digital Ocean Tutorials：一个非常庞大资源，获得基本的应用程序，工具,甚至是系统管理主题。[官网](https://www.digitalocean.com/community/tutorials)

<h3 id="weibo-weixin">微信公众号</h3>
* Linux爱好者：专注分享 Linux/Unix 相关内容，包括：工具资源、使用技巧、课程、书籍等。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2ca88pfj20460463ym.jpg" width=150 height=150>

* 数据库开发者：专注分享数据库相关内容，包括：各种主流 DB 的最佳实践、数据库基础知识、性能优化、数据安全等。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c5mk0jj2046046my6.jpg" width=150 height=150>
