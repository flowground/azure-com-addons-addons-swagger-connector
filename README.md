# ![LOGO](logo.png) Azure Addons Resource Provider **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Addons Resource Provider API (version 2018-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/addons-addons-swagger/2018-03-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:05+03:00

## API Description

The service for managing third party addons.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Addons RP operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Returns the canonical support plan information for all types for the subscription.

*Tags:* `AddonStatus`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Cancels the Canonical support plan of type {type} for the subscription.

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `providerName` - _required_ - The support plan type. For now the only valid type is "canonical".
* `planTypeName` - _required_ - The Canonical support plan type.
    Possible values: Essential, Standard, Advanced.

### Returns whether or not the canonical support plan of type {type} is enabled for the subscription.

*Tags:* `AddonDetails`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `providerName` - _required_ - The support plan type. For now the only valid type is "canonical".
* `planTypeName` - _required_ - The Canonical support plan type.
    Possible values: Essential, Standard, Advanced.

### Creates or updates the Canonical support plan of type {type} for the subscription.

*Tags:* `AddonDetails`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `providerName` - _required_ - The support plan type. For now the only valid type is "canonical".
* `planTypeName` - _required_ - The Canonical support plan type.
    Possible values: Essential, Standard, Advanced.

## License

**flow**ground :- Telekom iPaaS / azure-com-addons-addons-swagger-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
