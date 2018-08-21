Apache Sling Distribution Core 0.2.11-SNAPSHOT Services
=======================

The Apache Sling Distribution Core bundle provides the basic code infrastructure and API implementations for the
        Sling Content Distribution module

Copyright &copy; 2007 - 2018 [The Apache Software Foundation](http://www.apache.org/). All Rights Reserved.

# Table of contents

  * org
    * apache
      * sling
        * distribution
          * agent
            * impl
              * [PrivilegeDistributionRequestAuthorizationStrategyFactory](./org/apache/sling/distribution/agent/impl/PrivilegeDistributionRequestAuthorizationStrategyFactory.md)
          * component
            * impl
              * [DefaultDistributionComponentProvider](./org/apache/sling/distribution/component/impl/DefaultDistributionComponentProvider.md)
              * [DefaultDistributionConfigurationManager](./org/apache/sling/distribution/component/impl/DefaultDistributionConfigurationManager.md)
              * [DistributionComponentFactoryMap](./org/apache/sling/distribution/component/impl/DistributionComponentFactoryMap.md)
          * event
            * impl
              * [DefaultDistributionEventFactory](./org/apache/sling/distribution/event/impl/DefaultDistributionEventFactory.md)
          * impl
            * [DefaultDistributor](./org/apache/sling/distribution/impl/DefaultDistributor.md)
          * monitor
            * [DistributionQueueHealthCheck](./org/apache/sling/distribution/monitor/DistributionQueueHealthCheck.md)
          * packaging
            * impl
              * exporter
                * [AgentDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/AgentDistributionPackageExporterFactory.md)
                * [LocalDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/LocalDistributionPackageExporterFactory.md)
                * [RemoteDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/RemoteDistributionPackageExporterFactory.md)
              * importer
                * [LocalDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/LocalDistributionPackageImporterFactory.md)
                * [RemoteDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RemoteDistributionPackageImporterFactory.md)
                * [RepositoryDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RepositoryDistributionPackageImporterFactory.md)
          * resources
            * impl
              * [DistributionConfigurationResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionConfigurationResourceProviderFactory.md)
              * [DistributionServiceResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionServiceResourceProviderFactory.md)
          * serialization
            * impl
              * [DefaultDistributionPackageBuilderProvider](./org/apache/sling/distribution/serialization/impl/DefaultDistributionPackageBuilderProvider.md)
              * [DistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/DistributionPackageBuilderFactory.md)
              * vlt
                * [VaultDistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/vlt/VaultDistributionPackageBuilderFactory.md)
          * servlet
            * [DistributionAgentCreationFilter](./org/apache/sling/distribution/servlet/DistributionAgentCreationFilter.md)
            * [DistributionAgentLogServlet](./org/apache/sling/distribution/servlet/DistributionAgentLogServlet.md)
            * [DistributionAgentQueueServlet](./org/apache/sling/distribution/servlet/DistributionAgentQueueServlet.md)
            * [DistributionAgentServlet](./org/apache/sling/distribution/servlet/DistributionAgentServlet.md)
            * [DistributionPackageExporterServlet](./org/apache/sling/distribution/servlet/DistributionPackageExporterServlet.md)
            * [DistributionPackageImporterServlet](./org/apache/sling/distribution/servlet/DistributionPackageImporterServlet.md)
            * [DistributionTriggerServlet](./org/apache/sling/distribution/servlet/DistributionTriggerServlet.md)
          * transport
            * impl
              * [UserCredentialsDistributionTransportSecretProvider](./org/apache/sling/distribution/transport/impl/UserCredentialsDistributionTransportSecretProvider.md)
          * trigger
            * impl
              * [DistributionEventDistributeDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/DistributionEventDistributeDistributionTriggerFactory.md)
              * [JcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/JcrEventDistributionTriggerFactory.md)
              * [PersistedJcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/PersistedJcrEventDistributionTriggerFactory.md)
              * [RemoteEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/RemoteEventDistributionTriggerFactory.md)
              * [ResourceEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ResourceEventDistributionTriggerFactory.md)
              * [ScheduledDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ScheduledDistributionTriggerFactory.md)
