Data-Infra-Projects
====================

This is an attempt to list out all the interesting projects.

TODO:
Add ~~links and~~ licenses. 

##Abstractions
* [RDD](https://www.cs.berkeley.edu/~matei/papers/2012/nsdi_spark.pdf)
* [MapReduce](http://en.wikipedia.org/wiki/MapReduce)
* [Bulk Synchronous Parallel - BSP](http://en.wikipedia.org/wiki/Bulk_synchronous_parallel)


##Distributed Coordination

This are implementations/libraries to help write distributed applications which require some form of coordination.

* [ZooKeeper](zookeeper.apache.org)
* [Raft](http://raftconsensus.github.io/)
* [etcd](https://github.com/coreos/etcd)
* [Serf](http://www.serfdom.io/)
* [Doozer](https://github.com/ha/doozerd)

##Infrastructure Management
* [Yarn](http://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html)
* [Mesos](http://mesos.apache.org)
* [OpenStack](http://www.openstack.org/)
* [CloudStack](http://cloudstack.apache.org/)
* [Ganeti](https://code.google.com/p/ganeti/)

##File Systems
* [HDFS](http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
* [GlusterFS](http://www.gluster.org/)
* [Ceph](https://github.com/ceph/ceph)
* [QFS](http://quantcast.github.io/qfs/)

##Distribtued Databases
* [Swift](https://github.com/openstack/swift)
* [Riak](https://github.com/basho/riak)

##Infrastrcuture Logging/Monitoring
* [Nagios](http://www.nagios.org/)
* [Ganglia](http://ganglia.sourceforge.net/)
* [Chukwa](https://chukwa.apache.org/)
* [Netflix Suro](https://github.com/Netflix/suro)

##Infrastructure Helpers
* [Aurora](http://aurora.incubator.apache.org/)
* [Marathon](https://github.com/mesosphere/marathon)
* [Cronos](https://github.com/airbnb/chronos)
* [Fleet](https://github.com/coreos/fleet)

## MultiCloud/CrossCloud utilities
* [Fog](http://fog.io/)
* [Multistack](http://multistack.org/)
* [jClouds](https://jclouds.apache.org/)
* [Whirr](https://whirr.apache.org/)

##Virtualization
* [LXC](https://linuxcontainers.org/)
* [ZeroVM](http://www.zerovm.org/)
* [CoreOS](https://coreos.com/)
* [KVM](http://www.linux-kvm.org/)
* [XEN](http://www.xenproject.org/)
* [Solaris Zones](http://en.wikipedia.org/wiki/Solaris_Containers)
* [BSD Jails](http://en.wikipedia.org/wiki/FreeBSD_jail)

##Virtualization++
* [Docker](https://www.docker.com/)
* [CloudFoundry](http://cloudfoundry.org/)
* [Redhat Project Atomic](http://www.projectatomic.io/)

##Generalized Data Processing
* [Hadoop](http://hadoop.apache.org/)
* [Spark](https://spark.apache.org/)
* [REEF](http://www.reef-project.org/)
* [Flink](http://flink.incubator.apache.org/) (previously know as Stratosphere)
* [Tez](http://tez.apache.org/)
* [Dryad](http://research.microsoft.com/en-us/projects/dryad/)
* [Hyracks](https://code.google.com/p/hyracks/)
* [Naiad](http://research.microsoft.com/en-us/projects/naiad/)

#####comparisons
* [Tez vs Dryad](http://yhemanth.wordpress.com/2013/11/07/comparing-apache-tez-and-microsoft-dryad/)
* Hadoop vs Spark - Too many differences, no good link.

##Largescale Distributed ML
* [MLBase/MLlib](http://www.mlbase.org/)
* [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/)
* [Jubatus](http://jubat.us/en/)
* [Mahout](https://mahout.apache.org/)
* [h2o](http://0xdata.com/h2o/)
* [Oryx](https://github.com/cloudera/oryx) and [Oryx 2.0](https://github.com/OryxProject/oryx)

##pub-sub / messaging 
* [Kafka](http://kafka.apache.org/)
* [RabbitMQ](http://www.rabbitmq.com/)
* [ZeroMQ](http://zeromq.org/)
* [ActiveMQ](http://activemq.apache.org/)
* [hornetq](http://hornetq.jboss.org/)

##Data Ingest
* [Sqoop](http://sqoop.apache.org/)
* [Flume](http://flume.apache.org/)


##Graph Storing and/or Processing
* [GraphLab](http://graphlab.org/)
* [Giraph](http://giraph.apache.org/)
* [Neo4j](http://www.neo4j.org/)

## SQL Engines
* [Hive](https://hive.apache.org/)
* [Impala](http://impala.io/)
* [Shark](http://shark.cs.berkeley.edu/)
* [Spark-SQL](https://spark.apache.org/sql/)
* [Tajo](http://tajo.incubator.apache.org/)

##RealTime Processing (Time-constrained Processing)

##Stream Processing
* [Storm](https://storm.incubator.apache.org/)
* [Spark Streaming](https://spark.apache.org/streaming/)
* [Samza](http://samza.incubator.apache.org/)
* [Borealis](http://cs.brown.edu/research/borealis/public/)

##Security

##Performance Analysis

##Workflow engines/DAG-executors/Pipelines
* [Oozie](http://oozie.apache.org/)
* [Luigi](https://github.com/spotify/luigi)
* [Azkaban](https://azkaban.github.io/)
* [Cascading](http://www.cascading.org/)
* [Hmake](https://code.google.com/p/hamake/)
* [Crunch](https://crunch.apache.org/) (Modeled after [FlumeJava](http://pages.cs.wisc.edu/~akella/CS838/F12/838-CloudPapers/FlumeJava.pdf))

#####Comparisons
  * [Oozie vs Crunch](http://mail-archives.apache.org/mod_mbox/incubator-general/201205.mbox/%3CCAH29n6MPf4Qxb--9Ayv+U9xoJuJC_QRYkqC+ADisy=YkjjV=Vg@mail.gmail.com%3E)
  * [Oozie vs Azkaban](http://www.quora.com/What-are-the-differences-advantages-disadvantages-of-Azkaban-vs-Oozie) 
  * [Feature comparison](http://sarveshspn.blogspot.in/2012/02/comparison-of-hadoop-workflow-engines.html)

##Configuration management 
* [Chef](http://www.getchef.com/chef/)
* [Puppet](http://puppetlabs.com/puppet)
* [Salt](https://github.com/saltstack/salt)
* [Ansible](https://github.com/ansible/ansible)
* [Vagrant](http://www.vagrantup.com/)

##Search
* [Lucene+Solr](http://lucene.apache.org/)
* [ElasticSearch](http://www.elasticsearch.org/)

## others
* [Nutch](http://nutch.apache.org/) - web crawler
* [Ambari](http://ambari.apache.org/) - Hadoop Deployment + Management 
* [Hue](http://gethue.com/) - Hadoop Web UI
* [Bigtop](http://bigtop.apache.org/) - Hadoop Packaging 


