---
title: Azure Event Grid SDKs
description: Describes the SDKs for Azure Event Grid. These SDKs provide management, publishing and consumption.
ms.topic: reference
ms.date: 05/17/2021
---

# Event Grid SDKs for management and publishing

Event Grid provides SDKs that enable you to programmatically manage your resources and post events.

## Management SDKs

The management SDKs enable you to create, update, and delete event grid topics and subscriptions. Currently, the following SDKs are available:

* [.NET](https://www.nuget.org/packages/Microsoft.Azure.Management.EventGrid)
* [Go](https://github.com/Azure/azure-sdk-for-go)
* [Java](https://search.maven.org/#search%7Cga%7C1%7Cazure-resourcemanager-eventgrid)
* [Node](https://www.npmjs.com/package/@azure/arm-eventgrid)
* [Python](https://pypi.python.org/pypi/azure-mgmt-eventgrid)
* [Ruby](https://rubygems.org/gems/azure_mgmt_event_grid)

## Data plane SDKs

The data plane SDKs enable you to post events to topics by taking care of authenticating, forming the event, and asynchronously posting to the specified endpoint. They also enable you to consume first party events. Currently, the following SDKs are available:

| Programming language | SDK | 
| -------------------- | ---------- | 
| .NET | Latest stable SDK: [Azure.Messaging.EventGrid](https://www.nuget.org/packages/Azure.Messaging.EventGrid/)<p>Legacy SDK: [Microsoft.Azure.EventGrid](https://www.nuget.org/packages/Microsoft.Azure.EventGrid) |
| Java | Latest stable SDK: [azure-messaging-eventgrid](https://search.maven.org/artifact/com.azure/azure-messaging-eventgrid/)<p>Legacy SDK: [azure-eventgrid](https://mvnrepository.com/artifact/com.microsoft.azure/azure-eventgrid)</p> |  
| Python | [azure-eventgrid](https://pypi.org/project/azure-eventgrid/) |
| JavaScript | [@azure/eventgrid](https://www.npmjs.com/package/@azure/eventgrid/) | 
| Go | [Azure SDK for Go](https://github.com/Azure/azure-sdk-for-go) |
| Ruby | [azure_event_grid](https://rubygems.org/gems/azure_event_grid) |


## Next steps

* For example applications, see [Event Grid code samples](https://azure.microsoft.com/resources/samples/?sort=0&service=event-grid).
* For an introduction to Event Grid, see [What is Event Grid?](overview.md)
* For Event Grid commands in Azure CLI, see [Azure CLI](/cli/azure/eventgrid).
* For Event Grid commands in PowerShell, see [PowerShell](/powershell/module/az.eventgrid).
