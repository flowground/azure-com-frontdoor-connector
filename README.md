# ![LOGO](logo.png) FrontDoorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the FrontDoorManagementClient API (version 2018-08-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/frontdoor/2018-08-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:11+03:00

## API Description

Use these APIs to manage Azure Front Door resources through the Azure Resource Manager. You must make sure that requests made to these resources are secure.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Check the availability of a Front Door resource name.

*Tags:* `CheckFrontDoorNameAvailability`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Check the availability of a Front Door subdomain.

*Tags:* `CheckFrontDoorNameAvailabilityWithSubscription`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all of the Front Doors within an Azure subscription.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all of the Front Doors within a resource group under a subscription.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.

### Deletes an existing Front Door with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Gets a Front Door with the specified Front Door name under the specified subscription and resource group.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Creates a new Front Door with a Front Door name under the specified subscription and resource group.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Lists all of the Backend Pools within a Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Deletes an existing Backend Pool with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `backendPoolName` - _required_ - Name of the Backend Pool which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Gets a Backend Pool with the specified Pool name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `backendPoolName` - _required_ - Name of the Backend Pool which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Creates a new Backend Pool with the specified Pool name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `backendPoolName` - _required_ - Name of the Backend Pool which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Lists all of the frontend endpoints within a Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Deletes an existing frontend endpoint with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `frontendEndpointName` - _required_ - Name of the Frontend endpoint which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Gets a Frontend endpoint with the specified name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `frontendEndpointName` - _required_ - Name of the Frontend endpoint which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Creates a new frontend endpoint with the specified host name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `frontendEndpointName` - _required_ - Name of the Frontend endpoint which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Disables a frontendEndpoint for HTTPS traffic

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `frontendEndpointName` - _required_ - Name of the Frontend endpoint which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Enables a frontendEndpoint for HTTPS traffic

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `frontendEndpointName` - _required_ - Name of the Frontend endpoint which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Lists all of the HealthProbeSettings within a Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Deletes an existing HealthProbeSettings with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `healthProbeSettingsName` - _required_ - Name of the health probe settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Gets a HealthProbeSettings with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `healthProbeSettingsName` - _required_ - Name of the health probe settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Creates a new HealthProbeSettings with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `healthProbeSettingsName` - _required_ - Name of the health probe settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Lists all of the LoadBalancingSettings within a Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Deletes an existing LoadBalancingSettings with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `loadBalancingSettingsName` - _required_ - Name of the load balancing settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Gets a LoadBalancingSettings with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `loadBalancingSettingsName` - _required_ - Name of the load balancing settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Creates a new LoadBalancingSettings with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `loadBalancingSettingsName` - _required_ - Name of the load balancing settings which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Removes a content from Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Lists all of the Routing Rules within a Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

### Deletes an existing Routing Rule with the specified parameters.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `routingRuleName` - _required_ - Name of the Routing Rule which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Gets a Routing Rule with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `routingRuleName` - _required_ - Name of the Routing Rule which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Creates a new Routing Rule with the specified Rule name within the specified Front Door.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `routingRuleName` - _required_ - Name of the Routing Rule which is unique within the Front Door.
* `api-version` - _required_ - Client API version.

### Validates the custom domain mapping to ensure it maps to the correct Front Door endpoint in DNS.

*Tags:* `FrontDoors`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `frontDoorName` - _required_ - Name of the Front Door which is globally unique.
* `api-version` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-frontdoor-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
