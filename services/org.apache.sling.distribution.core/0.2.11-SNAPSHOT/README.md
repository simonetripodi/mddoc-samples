Apache Sling Distribution Core 0.2.11-SNAPSHOT Services
=======================

The Apache Sling Distribution Core bundle provides the basic code infrastructure and API implementations for the
        Sling Content Distribution module

Copyright &copy; 2007 - 2018 [The Apache Software Foundation](http://www.apache.org/). All Rights Reserved.

# Table of contents

 * [javax.servlet.Filter](#javax.servlet.Filter)
 * [javax.servlet.Servlet](#javax.servlet.Servlet)
 * [org.apache.sling.api.resource.ResourceProvider](#org.apache.sling.api.resource.ResourceProvider)
 * [org.apache.sling.api.resource.ResourceProviderFactory](#org.apache.sling.api.resource.ResourceProviderFactory)
 * [org.apache.sling.distribution.Distributor](#org.apache.sling.distribution.Distributor)
 * [org.apache.sling.distribution.agent.impl.DistributionRequestAuthorizationStrategy](#org.apache.sling.distribution.agent.impl.DistributionRequestAuthorizationStrategy)
 * [org.apache.sling.distribution.component.impl.DistributionComponentFactoryMap](#org.apache.sling.distribution.component.impl.DistributionComponentFactoryMap)
 * [org.apache.sling.distribution.component.impl.DistributionComponentProvider](#org.apache.sling.distribution.component.impl.DistributionComponentProvider)
 * [org.apache.sling.distribution.component.impl.DistributionConfigurationManager](#org.apache.sling.distribution.component.impl.DistributionConfigurationManager)
 * [org.apache.sling.distribution.event.impl.DistributionEventFactory](#org.apache.sling.distribution.event.impl.DistributionEventFactory)
 * [org.apache.sling.distribution.packaging.DistributionPackageBuilder](#org.apache.sling.distribution.packaging.DistributionPackageBuilder)
 * [org.apache.sling.distribution.packaging.impl.DistributionPackageBuilderProvider](#org.apache.sling.distribution.packaging.impl.DistributionPackageBuilderProvider)
 * [org.apache.sling.distribution.packaging.impl.DistributionPackageExporter](#org.apache.sling.distribution.packaging.impl.DistributionPackageExporter)
 * [org.apache.sling.distribution.packaging.impl.DistributionPackageImporter](#org.apache.sling.distribution.packaging.impl.DistributionPackageImporter)
 * [org.apache.sling.distribution.transport.DistributionTransportSecretProvider](#org.apache.sling.distribution.transport.DistributionTransportSecretProvider)
 * [org.apache.sling.distribution.trigger.DistributionTrigger](#org.apache.sling.distribution.trigger.DistributionTrigger)
 * [org.apache.sling.hc.api.HealthCheck](#org.apache.sling.hc.api.HealthCheck)

# javax.servlet.Filter <a id="javax.servlet.Filter"></a>

 * [org.apache.sling.distribution.servlet.DistributionAgentCreationFilter](./org/apache/sling/distribution/servlet/DistributionAgentCreationFilter.md)

# javax.servlet.Servlet <a id="javax.servlet.Servlet"></a>

 * [org.apache.sling.distribution.servlet.DistributionPackageExporterServlet](./org/apache/sling/distribution/servlet/DistributionPackageExporterServlet.md)
 * [org.apache.sling.distribution.servlet.DistributionAgentServlet](./org/apache/sling/distribution/servlet/DistributionAgentServlet.md)
 * [org.apache.sling.distribution.servlet.DistributionAgentLogServlet](./org/apache/sling/distribution/servlet/DistributionAgentLogServlet.md)
 * [org.apache.sling.distribution.servlet.DistributionPackageImporterServlet](./org/apache/sling/distribution/servlet/DistributionPackageImporterServlet.md)
 * [org.apache.sling.distribution.servlet.DistributionAgentQueueServlet](./org/apache/sling/distribution/servlet/DistributionAgentQueueServlet.md)
 * [org.apache.sling.distribution.servlet.DistributionTriggerServlet](./org/apache/sling/distribution/servlet/DistributionTriggerServlet.md)

# org.apache.sling.api.resource.ResourceProvider <a id="org.apache.sling.api.resource.ResourceProvider"></a>

 * [org.apache.sling.distribution.resources.impl.DistributionServiceResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionServiceResourceProviderFactory.md)

# org.apache.sling.api.resource.ResourceProviderFactory <a id="org.apache.sling.api.resource.ResourceProviderFactory"></a>

 * [org.apache.sling.distribution.resources.impl.DistributionConfigurationResourceProviderFactory](./org/apache/sling/distribution/resources/impl/DistributionConfigurationResourceProviderFactory.md)

# org.apache.sling.distribution.Distributor <a id="org.apache.sling.distribution.Distributor"></a>

 * [org.apache.sling.distribution.impl.DefaultDistributor](./org/apache/sling/distribution/impl/DefaultDistributor.md)

# org.apache.sling.distribution.agent.impl.DistributionRequestAuthorizationStrategy <a id="org.apache.sling.distribution.agent.impl.DistributionRequestAuthorizationStrategy"></a>

 * [org.apache.sling.distribution.agent.impl.PrivilegeDistributionRequestAuthorizationStrategyFactory](./org/apache/sling/distribution/agent/impl/PrivilegeDistributionRequestAuthorizationStrategyFactory.md)

# org.apache.sling.distribution.component.impl.DistributionComponentFactoryMap <a id="org.apache.sling.distribution.component.impl.DistributionComponentFactoryMap"></a>

 * [org.apache.sling.distribution.component.impl.DistributionComponentFactoryMap](./org/apache/sling/distribution/component/impl/DistributionComponentFactoryMap.md)

# org.apache.sling.distribution.component.impl.DistributionComponentProvider <a id="org.apache.sling.distribution.component.impl.DistributionComponentProvider"></a>

 * [org.apache.sling.distribution.component.impl.DefaultDistributionComponentProvider](./org/apache/sling/distribution/component/impl/DefaultDistributionComponentProvider.md)

# org.apache.sling.distribution.component.impl.DistributionConfigurationManager <a id="org.apache.sling.distribution.component.impl.DistributionConfigurationManager"></a>

 * [org.apache.sling.distribution.component.impl.DefaultDistributionConfigurationManager](./org/apache/sling/distribution/component/impl/DefaultDistributionConfigurationManager.md)

# org.apache.sling.distribution.event.impl.DistributionEventFactory <a id="org.apache.sling.distribution.event.impl.DistributionEventFactory"></a>

 * [org.apache.sling.distribution.event.impl.DefaultDistributionEventFactory](./org/apache/sling/distribution/event/impl/DefaultDistributionEventFactory.md)

# org.apache.sling.distribution.packaging.DistributionPackageBuilder <a id="org.apache.sling.distribution.packaging.DistributionPackageBuilder"></a>

 * [org.apache.sling.distribution.serialization.impl.vlt.VaultDistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/vlt/VaultDistributionPackageBuilderFactory.md)
 * [org.apache.sling.distribution.serialization.impl.DistributionPackageBuilderFactory](./org/apache/sling/distribution/serialization/impl/DistributionPackageBuilderFactory.md)

# org.apache.sling.distribution.packaging.impl.DistributionPackageBuilderProvider <a id="org.apache.sling.distribution.packaging.impl.DistributionPackageBuilderProvider"></a>

 * [org.apache.sling.distribution.serialization.impl.DefaultDistributionPackageBuilderProvider](./org/apache/sling/distribution/serialization/impl/DefaultDistributionPackageBuilderProvider.md)

# org.apache.sling.distribution.packaging.impl.DistributionPackageExporter <a id="org.apache.sling.distribution.packaging.impl.DistributionPackageExporter"></a>

 * [org.apache.sling.distribution.packaging.impl.exporter.RemoteDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/RemoteDistributionPackageExporterFactory.md)
 * [org.apache.sling.distribution.packaging.impl.exporter.LocalDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/LocalDistributionPackageExporterFactory.md)
 * [org.apache.sling.distribution.packaging.impl.exporter.AgentDistributionPackageExporterFactory](./org/apache/sling/distribution/packaging/impl/exporter/AgentDistributionPackageExporterFactory.md)

# org.apache.sling.distribution.packaging.impl.DistributionPackageImporter <a id="org.apache.sling.distribution.packaging.impl.DistributionPackageImporter"></a>

 * [org.apache.sling.distribution.packaging.impl.importer.LocalDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/LocalDistributionPackageImporterFactory.md)
 * [org.apache.sling.distribution.packaging.impl.importer.RemoteDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RemoteDistributionPackageImporterFactory.md)
 * [org.apache.sling.distribution.packaging.impl.importer.RepositoryDistributionPackageImporterFactory](./org/apache/sling/distribution/packaging/impl/importer/RepositoryDistributionPackageImporterFactory.md)

# org.apache.sling.distribution.transport.DistributionTransportSecretProvider <a id="org.apache.sling.distribution.transport.DistributionTransportSecretProvider"></a>

 * [org.apache.sling.distribution.transport.impl.UserCredentialsDistributionTransportSecretProvider](./org/apache/sling/distribution/transport/impl/UserCredentialsDistributionTransportSecretProvider.md)

# org.apache.sling.distribution.trigger.DistributionTrigger <a id="org.apache.sling.distribution.trigger.DistributionTrigger"></a>

 * [org.apache.sling.distribution.trigger.impl.ScheduledDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ScheduledDistributionTriggerFactory.md)
 * [org.apache.sling.distribution.trigger.impl.JcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/JcrEventDistributionTriggerFactory.md)
 * [org.apache.sling.distribution.trigger.impl.RemoteEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/RemoteEventDistributionTriggerFactory.md)
 * [org.apache.sling.distribution.trigger.impl.ResourceEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/ResourceEventDistributionTriggerFactory.md)
 * [org.apache.sling.distribution.trigger.impl.DistributionEventDistributeDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/DistributionEventDistributeDistributionTriggerFactory.md)
 * [org.apache.sling.distribution.trigger.impl.PersistedJcrEventDistributionTriggerFactory](./org/apache/sling/distribution/trigger/impl/PersistedJcrEventDistributionTriggerFactory.md)

# org.apache.sling.hc.api.HealthCheck <a id="org.apache.sling.hc.api.HealthCheck"></a>

 * [org.apache.sling.distribution.monitor.DistributionQueueHealthCheck](./org/apache/sling/distribution/monitor/DistributionQueueHealthCheck.md)

