# IPlayGamesApi.FreespinsApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cancelAStandaloneFreespin**](FreespinsApi.md#cancelAStandaloneFreespin) | **POST** /api/v1/freespins/{freespin_id}/cancel | Cancel a standalone freespin
[**createAStandaloneFreespin**](FreespinsApi.md#createAStandaloneFreespin) | **POST** /api/v1/freespins | Create a standalone freespin



## cancelAStandaloneFreespin

> CancelAStandaloneFreespin200Response cancelAStandaloneFreespin(freespinId, opts)

Cancel a standalone freespin

Cancel an existing freespin for a player. This will attempt to cancel the freespin at the provider level (if supported) and mark it as cancelled in our system.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.FreespinsApi();
let freespinId = "campaign_abc"; // String | The freespin campaign ID.
let opts = {
  'cancelAStandaloneFreespinRequest': new IPlayGamesApi.CancelAStandaloneFreespinRequest() // CancelAStandaloneFreespinRequest | 
};
apiInstance.cancelAStandaloneFreespin(freespinId, opts).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freespinId** | **String**| The freespin campaign ID. | 
 **cancelAStandaloneFreespinRequest** | [**CancelAStandaloneFreespinRequest**](CancelAStandaloneFreespinRequest.md)|  | [optional] 

### Return type

[**CancelAStandaloneFreespin200Response**](CancelAStandaloneFreespin200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## createAStandaloneFreespin

> CreateAStandaloneFreespin201Response createAStandaloneFreespin(createAStandaloneFreespinRequest)

Create a standalone freespin

Issue free spins to a player for a specific game without starting a game session. The player can use these freespins when they next start a game session.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.FreespinsApi();
let createAStandaloneFreespinRequest = new IPlayGamesApi.CreateAStandaloneFreespinRequest(); // CreateAStandaloneFreespinRequest | 
apiInstance.createAStandaloneFreespin(createAStandaloneFreespinRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAStandaloneFreespinRequest** | [**CreateAStandaloneFreespinRequest**](CreateAStandaloneFreespinRequest.md)|  | 

### Return type

[**CreateAStandaloneFreespin201Response**](CreateAStandaloneFreespin201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

