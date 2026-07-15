# MySQL Operators

## MySQL Operator for Kubernetes (Oracle)

- Official: <https://dev.mysql.com/doc/mysql-operator/en/>
- GitHub: <https://github.com/mysql/mysql-operator>

Oracle's official operator for managing MySQL InnoDB Cluster with Group Replication and MySQL Router. Some advanced features (such as enterprise backup and data-at-rest encryption) require a MySQL Enterprise license.

## Percona Operator for MySQL

- Official: <https://docs.percona.com/percona-operator-for-mysql/>
- GitHub: <https://github.com/percona/percona-operator-for-mysql>

Percona's Apache-2.0 operators for production-grade MySQL. One is based on Percona XtraDB Cluster (synchronous Galera replication); the other on Percona Server for MySQL (asynchronous replication with Orchestrator-based failover), with PMM monitoring and backups.

## MOCO

- Official: <https://cybozu-go.github.io/moco/>
- GitHub: <https://github.com/cybozu-go/moco>

Cybozu's open source operator focused on high compatibility with vanilla MySQL 8, using asynchronous/semi-synchronous replication instead of Group Replication to avoid its large-transaction limitations.

## Vitess Operator

- Official: <https://vitess.io/>
- GitHub: <https://github.com/planetscale/vitess-operator>

PlanetScale's operator for Vitess, the CNCF Graduated database clustering system for horizontal scaling and sharding of MySQL. Originally developed at YouTube.

## Bitpoke MySQL Operator

- Official: <https://www.bitpoke.io/docs/mysql-operator/>
- GitHub: <https://github.com/bitpoke/mysql-operator>

Open source operator for asynchronous MySQL replication clusters, using Percona Server and Openark's Orchestrator, with Percona XtraBackup-based backups. Development has slowed (infrequent releases); evaluate maintenance status before adopting.

## KubeDB

- Official: <https://kubedb.com/>
- GitHub: <https://github.com/kubedb/operator>

AppsCode's Kubernetes operator for many databases (MySQL, PostgreSQL, MongoDB, etc.), with backups, TLS, and lifecycle automation.

## OpenEverest

- Official: <https://openeverest.io/>
- GitHub: <https://github.com/percona/everest>

CNCF Sandbox cloud-native database platform (formerly Percona Everest) that automates provisioning and multi-database orchestration on Kubernetes, using the Percona operators (MySQL, PostgreSQL, MongoDB) underneath behind a unified API and web UI.

## Tungsten Operator (Continuent)

- Official: <https://www.continuent.com/>
- Documentation: <https://docs.continuent.com/tungsten-operator-8.0.html>

Continuent's commercial operator for advanced cross-datacenter and cross-cloud MySQL replication and disaster-recovery topologies.
