Apache Sling Distribution Core 0.2.11-SNAPSHOT Metatypes
=======================

The Apache Sling Distribution Core bundle provides the basic code infrastructure and API implementations for the
        Sling Content Distribution module

Copyright &copy; 2007 - 2018 [The Apache Software Foundation](http://www.apache.org/). All Rights Reserved.

# Table of contents

`└── org`
`    └── apache`
`        └── sling`
`            └── distribution`
`                ├── agent`
`                │   └── impl`
`                │       ├── ` [ForwardDistributionAgentFactory](./org/apache/sling/distribution/agent/impl/ForwardDistributionAgentFactory.md)
`                │       ├── ` [PrivilegeDistributionRequestAuthorizationStrategyFactory](./org/apache/sling/distribution/agent/impl/PrivilegeDistributionRequestAuthorizationStrategyFactory.md)
`                │       ├── ` [QueueDistributionAgentFactory](./org/apache/sling/distribution/agent/impl/QueueDistributionAgentFactory.md)
`                │       ├── ` [ReverseDistributionAgentFactory](./org/apache/sling/distribution/agent/impl/ReverseDistributionAgentFactory.md)
`                │       ├── ` [SimpleDistributionAgentFactory](./org/apache/sling/distribution/agent/impl/SimpleDistributionAgentFactory.md)
`                │       └── ` [SyncDistributionAgentFactory](./org/apache/sling/distribution/agent/impl/SyncDistributionAgentFactory.md)
`                ├── monitor`
`                │   └── ` [DistributionQueueHealthCheck](./org/apache/sling/distribution/monitor/DistributionQueueHealthCheck.md)
`                ├── packaging`
`                │   └── impl`
`                │       ├── exporter`
`                │       │   ├── ` [AgentDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/AgentDistributionPackageExporterFactory.md)
`                │       │   ├── ` [LocalDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/LocalDistributionPackageExporterFactory.md)
`                │       │   └── ` [RemoteDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/RemoteDistributionPackageExporterFactory.md)
`                │       └── importer`
`                │           ├── ` [LocalDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/LocalDistributionPackageImporterFactory.md)
`                │           ├── ` [RemoteDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RemoteDistributionPackageImporterFactory.md)
`                │           └── ` [RepositoryDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RepositoryDistributionPackageImporterFactory.md)
`                ├── resources`
`                │   └── impl`
`                │       ├── ` [DistributionConfigurationResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionConfigurationResourceProviderFactory.md)
`                │       └── ` [DistributionServiceResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionServiceResourceProviderFactory.md)
`                ├── serialization`
`                │   └── impl`
`                │       ├── ` [DistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/DistributionPackageBuilderFactory.md)
`                │       └── vlt`
`                │           └── ` [VaultDistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/vlt/VaultDistributionPackageBuilderFactory.md)
`                ├── transport`
`                │   └── impl`
`                │       └── ` [UserCredentialsDistributionTransportSecretProvider](./org/apache/sling/distribution/transport/impl/UserCredentialsDistributionTransportSecretProvider.md)
`                └── trigger`
`                    └── impl`
`                        ├── ` [DistributionEventDistributeDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/DistributionEventDistributeDistributionTriggerFactory.md)
`                        ├── ` [JcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/JcrEventDistributionTriggerFactory.md)
`                        ├── ` [PersistedJcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/PersistedJcrEventDistributionTriggerFactory.md)
`                        ├── ` [RemoteEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/RemoteEventDistributionTriggerFactory.md)
`                        ├── ` [ResourceEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ResourceEventDistributionTriggerFactory.md)
`                        └── ` [ScheduledDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ScheduledDistributionTriggerFactory.md)
