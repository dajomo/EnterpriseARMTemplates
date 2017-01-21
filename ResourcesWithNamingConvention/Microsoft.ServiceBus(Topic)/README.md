# Azure Service Bus with Topic

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpascalnaber%2FEnterpriseARMTemplates%2Fmaster%2FResourcesWithNamingConvention%2FMicrosoft.ServiceBus(Topic)%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fpascalnaber%2FEnterpriseARMTemplates%2Fmaster%2FResourcesWithNamingConvention%2FMicrosoft.ServiceBus(Topic)%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template deploys an Azure Service Bus with Topic. The template decides the namingconvention. The convention uses the metadata which is passed as a parameter to the template. See the parameter file for an example. The metadata is also used to add tags to the resources. 

`Tags: Service Bus, Topic, Subscription`

## supports

Besides the standard configuration

- Two authorization rules are added to the Topic. A Listen and a Send AuthorizationRule.

