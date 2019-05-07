# ![LOGO](logo.png) Content API for Shopping **flow**ground Connector

## Description

A generated **flow**ground connector for the Content API for Shopping API (version v2.1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/content/v2.1/swagger.json<br/>
Generated at: 2019-05-07T17:41:29+03:00

## API Description

Manages product items, inventory, and Merchant Center accounts for Google Shopping.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns information about the authenticated user.

*Tags:* `accounts`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves, inserts, updates, and deletes multiple Merchant Center (sub-)accounts in a single request.

*Tags:* `accounts`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves multiple Merchant Center account statuses in a single request.

*Tags:* `accountstatuses`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves and updates tax settings of multiple accounts in a single request.

*Tags:* `accounttax`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### content_datafeeds_custombatch

*Tags:* `datafeeds`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### content_datafeedstatuses_custombatch

*Tags:* `datafeedstatuses`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves and/or updates the LIA settings of multiple accounts in a single request.

*Tags:* `liasettings`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of POS data providers that have active settings for the all eiligible countries.

*Tags:* `liasettings`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Batches multiple POS-related calls in a single request.

*Tags:* `pos`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves, inserts, and deletes multiple products in a single request.

*Tags:* `products`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the statuses of multiple products in a single request.

*Tags:* `productstatuses`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates regional inventory for multiple products or regions in a single request.

*Tags:* `regionalinventory`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves and updates the shipping settings of multiple accounts in a single request.

*Tags:* `shippingsettings`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the sub-accounts in your Merchant Center account.

*Tags:* `accounts`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of accounts to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a Merchant Center sub-account.

*Tags:* `accounts`

#### Input Parameters
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a Merchant Center sub-account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the account.
* `force` - _optional_ - Flag to delete sub-accounts with products. The default value is false.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account, and accountId must be the ID of a sub-account of this account.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a Merchant Center account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the account.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a Merchant Center account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the account.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Claims the website of a Merchant Center sub-account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the account whose website is claimed.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `overwrite` - _optional_ - Only available to selected merchants. When set to True, this flag removes any existing claim on the requested website by another account and replaces it with a claim from this account.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Performs an action on a link between a Merchant Center account and another account.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - The ID of the account that should be linked.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the statuses of the sub-accounts in your Merchant Center account.

*Tags:* `accountstatuses`

#### Input Parameters
* `destinations` - _optional_ - If set, only issues for the specified destinations are returned, otherwise only issues for the Shopping destination.
* `maxResults` - _optional_ - The maximum number of account statuses to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the status of a Merchant Center account. No itemLevelIssues are returned for multi-client accounts.

*Tags:* `accountstatuses`

#### Input Parameters
* `accountId` - _required_ - The ID of the account.
* `destinations` - _optional_ - If set, only issues for the specified destinations are returned, otherwise only issues for the Shopping destination.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the tax settings of the sub-accounts in your Merchant Center account.

*Tags:* `accounttax`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of tax settings to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the tax settings of the account.

*Tags:* `accounttax`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get/update account tax settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the tax settings of the account.

*Tags:* `accounttax`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get/update account tax settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the configurations for datafeeds in your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of products to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that manages the datafeeds. This account cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Registers a datafeed configuration with your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a datafeed configuration from your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `datafeedId` - _required_ - The ID of the datafeed.
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a datafeed configuration from your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `datafeedId` - _required_ - The ID of the datafeed.
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a datafeed configuration of your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `datafeedId` - _required_ - The ID of the datafeed.
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Invokes a fetch for the datafeed in your Merchant Center account.

*Tags:* `datafeeds`

#### Input Parameters
* `datafeedId` - _required_ - The ID of the datafeed to be fetched.
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the statuses of the datafeeds in your Merchant Center account.

*Tags:* `datafeedstatuses`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of products to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that manages the datafeeds. This account cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the status of a datafeed from your Merchant Center account.

*Tags:* `datafeedstatuses`

#### Input Parameters
* `country` - _optional_ - The country for which to get the datafeed status. If this parameter is provided then language must also be provided. Note that this parameter is required for feeds targeting multiple countries and languages, since a feed may have a different status for each target.
* `datafeedId` - _required_ - The ID of the datafeed.
* `language` - _optional_ - The language for which to get the datafeed status. If this parameter is provided then country must also be provided. Note that this parameter is required for feeds targeting multiple countries and languages, since a feed may have a different status for each target.
* `merchantId` - _required_ - The ID of the account that manages the datafeed. This account cannot be a multi-client account.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the LIA settings of the sub-accounts in your Merchant Center account.

*Tags:* `liasettings`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of LIA settings to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the LIA settings of the account.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get or update LIA settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the LIA settings of the account.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get or update LIA settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the list of accessible Google My Business accounts.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to retrieve accessible Google My Business accounts.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Requests access to a specified Google My Business account.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which GMB access is requested.
* `gmbEmail` - _required_ - The email of the Google My Business account.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Requests inventory validation for the specified country.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `country` - _required_ - The country for which inventory validation is requested.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the inventory verification contract for the specified country.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `contactEmail` - _required_ - The email of the inventory verification contact.
* `contactName` - _required_ - The name of the inventory verification contact.
* `country` - _required_ - The country for which inventory verification is requested.
* `language` - _required_ - The language for which inventory verification is requested.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets the POS data provider for the specified country.

*Tags:* `liasettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to retrieve accessible Google My Business accounts.
* `country` - _required_ - The country for which the POS data provider is selected.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `posDataProviderId` - _optional_ - The ID of POS data provider.
* `posExternalAccountId` - _optional_ - The account ID by which this merchant is known to the POS data provider.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a charge invoice for a shipment group, and triggers a charge capture for non-facilitated payment orders.

*Tags:* `orderinvoices`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a refund invoice for one or more shipment groups, and triggers a refund for non-facilitated payment orders. This can only be used for line items that have previously been charged using createChargeInvoice. All amounts (except for the summary) are incremental with respect to the previous invoice.

*Tags:* `orderinvoices`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a report for disbursements from your Merchant Center account.

*Tags:* `orderreports`

#### Input Parameters
* `disbursementEndDate` - _optional_ - The last date which disbursements occurred. In ISO 8601 format. Default: current date.
* `disbursementStartDate` - _required_ - The first date which disbursements occurred. In ISO 8601 format.
* `maxResults` - _optional_ - The maximum number of disbursements to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a list of transactions for a disbursement from your Merchant Center account.

*Tags:* `orderreports`

#### Input Parameters
* `disbursementId` - _required_ - The Google-provided ID of the disbursement (found in Wallet).
* `maxResults` - _optional_ - The maximum number of disbursements to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `transactionEndDate` - _optional_ - The last date in which transaction occurred. In ISO 8601 format. Default: current date.
* `transactionStartDate` - _required_ - The first date in which transaction occurred. In ISO 8601 format.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists order returns in your Merchant Center account.

*Tags:* `orderreturns`

#### Input Parameters
* `createdEndDate` - _optional_ - Obtains order returns created before this date (inclusively), in ISO 8601 format.
* `createdStartDate` - _optional_ - Obtains order returns created after this date (inclusively), in ISO 8601 format.
* `maxResults` - _optional_ - The maximum number of order returns to return in the response, used for paging. The default value is 25 returns per page, and the maximum allowed value is 250 returns per page.
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderBy` - _optional_ - Return the results in the specified order.
    Possible values: returnCreationTimeAsc, returnCreationTimeDesc.
* `pageToken` - _optional_ - The token returned by the previous request.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an order return from your Merchant Center account.

*Tags:* `orderreturns`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `returnId` - _required_ - Merchant order return ID generated by Google.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the orders in your Merchant Center account.

*Tags:* `orders`

#### Input Parameters
* `acknowledged` - _optional_ - Obtains orders that match the acknowledgement status. When set to true, obtains orders that have been acknowledged. When false, obtains orders that have not been acknowledged.
We recommend using this filter set to false, in conjunction with the acknowledge call, such that only un-acknowledged orders are returned.
* `maxResults` - _optional_ - The maximum number of orders to return in the response, used for paging. The default value is 25 orders per page, and the maximum allowed value is 250 orders per page.
Known issue: All List calls will return all Orders without limit regardless of the value of this field.
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderBy` - _optional_ - The ordering of the returned list. The only supported value are placedDate desc and placedDate asc for now, which returns orders sorted by placement date. "placedDate desc" stands for listing orders by placement date, from oldest to most recent. "placedDate asc" stands for listing orders by placement date, from most recent to oldest. In future releases we'll support other sorting criteria.
    Possible values: placedDate asc, placedDate desc.
* `pageToken` - _optional_ - The token returned by the previous request.
* `placedDateEnd` - _optional_ - Obtains orders placed before this date (exclusively), in ISO 8601 format.
* `placedDateStart` - _optional_ - Obtains orders placed after this date (inclusively), in ISO 8601 format.
* `statuses` - _optional_ - Obtains orders that match any of the specified statuses. Multiple values can be specified with comma separation. Additionally, please note that active is a shortcut for pendingShipment and partiallyShipped, and completed is a shortcut for shipped , partiallyDelivered, delivered, partiallyReturned, returned, and canceled.

### Retrieves an order from your Merchant Center account.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Marks an order as acknowledged.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Cancels all line items in an order, making a full refund.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order to cancel.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Cancels a line item, making a full refund.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Notifies that item return and refund was handled directly by merchant outside of Google payments processing (e.g. cash refund done in store).

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Rejects return on an line item.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Returns and refunds a line item. Note that this method can only be called on fully shipped orders.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sets (or overrides if it already exists) merchant provided annotations in the form of key-value pairs. A common use case would be to supply us with additional structured information about a line item that cannot be provided via other methods. Submitted key-value pairs can be retrieved as part of the orders resource.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Marks line item(s) as shipped.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sandbox only. Creates a test return.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates ship by and delivery by dates for a line item.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the merchant order ID for a given order.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates a shipment's status, carrier, and/or tracking ID.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the order.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves an order using merchant order ID.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `merchantOrderId` - _required_ - The merchant order ID to be looked for.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Submit inventory for the given merchant.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Submit a sale event for the given merchant.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the stores of the target merchant.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Creates a store for the given merchant.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a store for the given merchant.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `storeCode` - _required_ - A store code that is unique per merchant.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves information about the given store.

*Tags:* `pos`

#### Input Parameters
* `merchantId` - _required_ - The ID of the POS or inventory data provider.
* `storeCode` - _required_ - A store code that is unique per merchant.
* `targetMerchantId` - _required_ - The ID of the target merchant.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the products in your Merchant Center account.

*Tags:* `products`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of products to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that contains the products. This account cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Uploads a product to your Merchant Center account. If an item with the same channel, contentLanguage, offerId, and targetCountry already exists, this method updates that entry.

*Tags:* `products`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that contains the product. This account cannot be a multi-client account.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Deletes a product from your Merchant Center account.

*Tags:* `products`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that contains the product. This account cannot be a multi-client account.
* `productId` - _required_ - The REST ID of the product.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves a product from your Merchant Center account.

*Tags:* `products`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that contains the product. This account cannot be a multi-client account.
* `productId` - _required_ - The REST ID of the product.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Update the regional inventory of a product in your Merchant Center account. If a regional inventory with the same region ID already exists, this method updates that entry.

*Tags:* `regionalinventory`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that contains the product. This account cannot be a multi-client account.
* `productId` - _required_ - The REST ID of the product for which to update the regional inventory.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the statuses of the products in your Merchant Center account.

*Tags:* `productstatuses`

#### Input Parameters
* `destinations` - _optional_ - If set, only issues for the specified destinations are returned, otherwise only issues for the Shopping destination.
* `maxResults` - _optional_ - The maximum number of product statuses to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the account that contains the products. This account cannot be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Gets the status of a product from your Merchant Center account.

*Tags:* `productstatuses`

#### Input Parameters
* `destinations` - _optional_ - If set, only issues for the specified destinations are returned, otherwise only issues for the Shopping destination.
* `merchantId` - _required_ - The ID of the account that contains the product. This account cannot be a multi-client account.
* `productId` - _required_ - The REST ID of the product.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Lists the shipping settings of the sub-accounts in your Merchant Center account.

*Tags:* `shippingsettings`

#### Input Parameters
* `maxResults` - _optional_ - The maximum number of shipping settings to return in the response, used for paging.
* `merchantId` - _required_ - The ID of the managing account. This must be a multi-client account.
* `pageToken` - _optional_ - The token returned by the previous request.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves the shipping settings of the account.

*Tags:* `shippingsettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get/update shipping settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Updates the shipping settings of the account.

*Tags:* `shippingsettings`

#### Input Parameters
* `accountId` - _required_ - The ID of the account for which to get/update shipping settings.
* `merchantId` - _required_ - The ID of the managing account. If this parameter is not the same as accountId, then this account must be a multi-client account and accountId must be the ID of a sub-account of this account.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves supported carriers and carrier services for an account.

*Tags:* `shippingsettings`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account for which to retrieve the supported carriers.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieves supported holidays for an account.

*Tags:* `shippingsettings`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account for which to retrieve the supported holidays.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sandbox only. Creates a test order.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that should manage the order. This cannot be a multi-client account.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sandbox only. Moves a test order from state "inProgress" to state "pendingShipment".

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the test order to modify.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sandbox only. Cancels a test order for customer-initiated cancellation.

*Tags:* `orders`

#### Input Parameters
* `merchantId` - _required_ - The ID of the account that manages the order. This cannot be a multi-client account.
* `orderId` - _required_ - The ID of the test order to cancel.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Sandbox only. Retrieves an order template that can be used to quickly create a new order in sandbox.

*Tags:* `orders`

#### Input Parameters
* `country` - _optional_ - The country of the template to retrieve. Defaults to US.
* `merchantId` - _required_ - The ID of the account that should manage the order. This cannot be a multi-client account.
* `templateName` - _required_ - The name of the template to retrieve.
    Possible values: template1, template1a, template1b, template2.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-content-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
