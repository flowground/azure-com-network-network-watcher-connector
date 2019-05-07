# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-networkWatcher/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:32+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets all network watchers by subscription.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all network watchers by resource group.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified network watcher resource.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the specified network watcher by resource group.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a network watcher tags.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a network watcher in the specified resource group.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all available internet service providers for a specified Azure region.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the network watcher resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the relative latency score for internet service providers from a specified location to Azure regions.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the network watcher resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Configures flow log  and traffic analytics (optional) on a specified resource.

*Tags:* `NetworkWatchers` `TrafficAnalytics`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the network watcher resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all connection monitors for the specified Network Watcher.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified connection monitor.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name of the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a connection monitor by name.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name of the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a connection monitor.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name of the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Query a snapshot of the most recent connection states.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name given to the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Starts the specified connection monitor.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name of the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Stops the specified connection monitor.

*Tags:* `ConnectionMonitors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group containing Network Watcher.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `connectionMonitorName` - _required_ - The name of the connection monitor.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Verifies the possibility of establishing a direct TCP connection from a virtual machine to a given endpoint including another VM or an arbitrary remote server.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the network watcher resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Verify IP flow from the specified VM to a location given the currently configured NSG rules.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Get network configuration diagnostic.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the next hop from the specified VM.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all packet capture sessions within the specified resource group.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified packet capture session.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `packetCaptureName` - _required_ - The name of the packet capture session.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a packet capture session by name.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `packetCaptureName` - _required_ - The name of the packet capture session.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create and start a packet capture on the specified VM.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `packetCaptureName` - _required_ - The name of the packet capture session.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Query the status of a running packet capture session.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the Network Watcher resource.
* `packetCaptureName` - _required_ - The name given to the packet capture session.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Stops a specified packet capture session.

*Tags:* `PacketCaptures`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `packetCaptureName` - _required_ - The name of the packet capture session.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Queries status of flow log and traffic analytics (optional) on a specified resource.

*Tags:* `NetworkWatchers` `TrafficAnalytics`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the network watcher resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Get the last completed troubleshooting result on a specified resource

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the configured and effective security group rules on the specified VM.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the current network topology by resource group.

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Initiate troubleshooting on a specified resource

*Tags:* `NetworkWatchers`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `networkWatcherName` - _required_ - The name of the network watcher resource.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-network-watcher-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
