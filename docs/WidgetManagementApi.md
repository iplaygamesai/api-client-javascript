# IPlayGamesApi.WidgetManagementApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**bulkRevokeTokens**](WidgetManagementApi.md#bulkRevokeTokens) | **POST** /api/v1/widget/tokens/bulk-revoke | Bulk revoke tokens
[**generateAWidgetToken**](WidgetManagementApi.md#generateAWidgetToken) | **POST** /api/v1/widget/tokens | Generate a widget token
[**getDomainDetails**](WidgetManagementApi.md#getDomainDetails) | **GET** /api/v1/widget/domains/{id} | Get domain details
[**getTokenDetails**](WidgetManagementApi.md#getTokenDetails) | **GET** /api/v1/widget/tokens/{id} | Get token details
[**listRegisteredDomains**](WidgetManagementApi.md#listRegisteredDomains) | **GET** /api/v1/widget/domains | List registered domains
[**listWidgetTokens**](WidgetManagementApi.md#listWidgetTokens) | **GET** /api/v1/widget/tokens | List widget tokens
[**regenerateDomainToken**](WidgetManagementApi.md#regenerateDomainToken) | **POST** /api/v1/widget/domains/{id}/regenerate-token | Regenerate domain token
[**registerANewDomain**](WidgetManagementApi.md#registerANewDomain) | **POST** /api/v1/widget/domains | Register a new domain
[**removeADomain**](WidgetManagementApi.md#removeADomain) | **DELETE** /api/v1/widget/domains/{id} | Remove a domain
[**revokeAToken**](WidgetManagementApi.md#revokeAToken) | **DELETE** /api/v1/widget/tokens/{id} | Revoke a token
[**updateDomainSettings**](WidgetManagementApi.md#updateDomainSettings) | **PUT** /api/v1/widget/domains/{id} | Update domain settings



## bulkRevokeTokens

> BulkRevokeTokens200Response bulkRevokeTokens(bulkRevokeTokensRequest)

Bulk revoke tokens

Revoke multiple widget tokens at once

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let bulkRevokeTokensRequest = new IPlayGamesApi.BulkRevokeTokensRequest(); // BulkRevokeTokensRequest | 
apiInstance.bulkRevokeTokens(bulkRevokeTokensRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkRevokeTokensRequest** | [**BulkRevokeTokensRequest**](BulkRevokeTokensRequest.md)|  | 

### Return type

[**BulkRevokeTokens200Response**](BulkRevokeTokens200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## generateAWidgetToken

> GenerateAWidgetToken201Response generateAWidgetToken(generateAWidgetTokenRequest)

Generate a widget token

Generate a new widget token for embedding. Requires domain_token for authentication.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let generateAWidgetTokenRequest = new IPlayGamesApi.GenerateAWidgetTokenRequest(); // GenerateAWidgetTokenRequest | 
apiInstance.generateAWidgetToken(generateAWidgetTokenRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateAWidgetTokenRequest** | [**GenerateAWidgetTokenRequest**](GenerateAWidgetTokenRequest.md)|  | 

### Return type

[**GenerateAWidgetToken201Response**](GenerateAWidgetToken201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## getDomainDetails

> GetDomainDetails200Response getDomainDetails(id)

Get domain details

Get details of a specific registered domain

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The domain ID.
apiInstance.getDomainDetails(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The domain ID. | 

### Return type

[**GetDomainDetails200Response**](GetDomainDetails200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getTokenDetails

> GetTokenDetails200Response getTokenDetails(id)

Get token details

Get details of a specific widget token

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The token ID.
apiInstance.getTokenDetails(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The token ID. | 

### Return type

[**GetTokenDetails200Response**](GetTokenDetails200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## listRegisteredDomains

> ListRegisteredDomains200Response listRegisteredDomains()

List registered domains

Get all registered widget domains for the authenticated operator

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
apiInstance.listRegisteredDomains().then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ListRegisteredDomains200Response**](ListRegisteredDomains200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## listWidgetTokens

> ListWidgetTokens200Response listWidgetTokens(opts)

List widget tokens

Get all widget tokens for the authenticated operator

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let opts = {
  'domainId': 1, // Number | optional Filter by domain ID.
  'active': true // Boolean | optional Filter by active status.
};
apiInstance.listWidgetTokens(opts).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainId** | **Number**| optional Filter by domain ID. | [optional] 
 **active** | **Boolean**| optional Filter by active status. | [optional] 

### Return type

[**ListWidgetTokens200Response**](ListWidgetTokens200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## regenerateDomainToken

> RegenerateDomainToken200Response regenerateDomainToken(id)

Regenerate domain token

Generate a new domain_token (invalidates all existing widget tokens)

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The domain ID.
apiInstance.regenerateDomainToken(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The domain ID. | 

### Return type

[**RegenerateDomainToken200Response**](RegenerateDomainToken200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## registerANewDomain

> RegisterANewDomain201Response registerANewDomain(registerANewDomainRequest)

Register a new domain

Register a domain that can embed widgets. Returns a domain_token used to generate widget tokens.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let registerANewDomainRequest = new IPlayGamesApi.RegisterANewDomainRequest(); // RegisterANewDomainRequest | 
apiInstance.registerANewDomain(registerANewDomainRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **registerANewDomainRequest** | [**RegisterANewDomainRequest**](RegisterANewDomainRequest.md)|  | 

### Return type

[**RegisterANewDomain201Response**](RegisterANewDomain201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## removeADomain

> RemoveADomain200Response removeADomain(id)

Remove a domain

Remove a registered domain and revoke all its tokens

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The domain ID.
apiInstance.removeADomain(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The domain ID. | 

### Return type

[**RemoveADomain200Response**](RemoveADomain200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## revokeAToken

> RevokeAToken200Response revokeAToken(id)

Revoke a token

Revoke a widget token (cannot be undone)

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The token ID.
apiInstance.revokeAToken(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The token ID. | 

### Return type

[**RevokeAToken200Response**](RevokeAToken200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## updateDomainSettings

> UpdateDomainSettings200Response updateDomainSettings(id, opts)

Update domain settings

Update a registered domain&#39;s settings

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.WidgetManagementApi();
let id = 1; // Number | The domain ID.
let opts = {
  'updateDomainSettingsRequest': new IPlayGamesApi.UpdateDomainSettingsRequest() // UpdateDomainSettingsRequest | 
};
apiInstance.updateDomainSettings(id, opts).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The domain ID. | 
 **updateDomainSettingsRequest** | [**UpdateDomainSettingsRequest**](UpdateDomainSettingsRequest.md)|  | [optional] 

### Return type

[**UpdateDomainSettings200Response**](UpdateDomainSettings200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

