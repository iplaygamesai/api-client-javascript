# IPlayGamesApi.GamesApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getApiV1GamesId**](GamesApi.md#getApiV1GamesId) | **GET** /api/v1/games/{id} | 
[**listGames**](GamesApi.md#listGames) | **GET** /api/v1/games | List games



## getApiV1GamesId

> getApiV1GamesId(id)





### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GamesApi();
let id = "architecto"; // String | The ID of the game.
apiInstance.getApiV1GamesId(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the game. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## listGames

> ListGames200Response listGames(opts)

List games

Get a list of available games for the operator

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GamesApi();
let opts = {
  'search': "sweet bonanza", // String | Search games by name.
  'producerId': 1, // Number | Filter by producer ID.
  'provider': "nuxgaming", // String | Filter by provider slug.
  'type': "slot", // String | Filter by game type.
  'perPage': "20", // String | Number of results per page or \"all\" for all results.
  'listGamesRequest': new IPlayGamesApi.ListGamesRequest() // ListGamesRequest | 
};
apiInstance.listGames(opts).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **search** | **String**| Search games by name. | [optional] 
 **producerId** | **Number**| Filter by producer ID. | [optional] 
 **provider** | **String**| Filter by provider slug. | [optional] 
 **type** | **String**| Filter by game type. | [optional] 
 **perPage** | **String**| Number of results per page or \&quot;all\&quot; for all results. | [optional] 
 **listGamesRequest** | [**ListGamesRequest**](ListGamesRequest.md)|  | [optional] 

### Return type

[**ListGames200Response**](ListGames200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

