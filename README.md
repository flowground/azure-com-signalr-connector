# ![LOGO](logo.png) SignalRManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SignalRManagementClient API (version 2018-10-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/signalr/2018-10-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:59+03:00

## API Description

REST API for Azure SignalR Service

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available REST API operations of the Microsoft.SignalRService provider.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.

### Handles requests to list all resources in a subscription.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Checks that the SignalR name is valid and is not already in use.

*Tags:* `SignalR`

#### Input Parameters
* `location` - _required_ - the region
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### List usage quotas for Azure SignalR service by location.

*Tags:* `SignalR`

#### Input Parameters
* `location` - _required_ - the location like "eastus"
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Handles requests to list all resources in a resource group.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.

### Operation to delete a SignalR service.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

### Get the SignalR service and its properties.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

### Operation to update an exiting SignalR service.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

### Create a new SignalR service and update an exiting SignalR service.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

### Get the access keys of the SignalR resource.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

### Regenerate SignalR service access key. PrimaryKey and SecondaryKey cannot be regenerated at the same time.

*Tags:* `SignalR`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
    Possible values: 2018-03-01-preview, 2018-10-01.
* `subscriptionId` - _required_ - Gets subscription Id which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group that contains the resource. You can obtain this value from the Azure Resource Manager API or the portal.
* `resourceName` - _required_ - The name of the SignalR resource.

## License

**flow**ground :- Telekom iPaaS / azure-com-signalr-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
