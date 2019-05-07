# ![LOGO](logo.png) StorageManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorageManagementClient API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-shares/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:34+03:00

## API Description

The Admin Storage Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of storage shares.

*Tags:* `Shares`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Returns a storage share.

*Tags:* `Shares`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.

### Returns a list of metric definitions for a storage share.

*Tags:* `Shares`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.

### Returns a list of metrics for a storage share.

*Tags:* `Shares`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `shareName` - _required_ - Share name.
* `api-version` - _required_ - REST Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-shares-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
