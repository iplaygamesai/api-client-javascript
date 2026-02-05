# IPlayGamesApi.MultiSessionsApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**endMultiSession**](MultiSessionsApi.md#endMultiSession) | **POST** /api/v1/multi-sessions/{token}/end | End multi-session
[**getMultiSessionStatus**](MultiSessionsApi.md#getMultiSessionStatus) | **GET** /api/v1/multi-sessions/{token}/status | Get multi-session status
[**startAMultiSession**](MultiSessionsApi.md#startAMultiSession) | **POST** /api/v1/multi-sessions/start | Start a multi-session



## endMultiSession

> EndMultiSession200Response endMultiSession(token)

End multi-session

Close all active game sessions in a multi-session.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.MultiSessionsApi();
let token = "550e8400-e29b-41d4-a716-446655440000"; // String | The multi-session token.
apiInstance.endMultiSession(token).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **String**| The multi-session token. | 

### Return type

[**EndMultiSession200Response**](EndMultiSession200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getMultiSessionStatus

> GetMultiSessionStatus200Response getMultiSessionStatus(token)

Get multi-session status

Retrieve the current status and game list for a multi-session.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.MultiSessionsApi();
let token = "550e8400-e29b-41d4-a716-446655440000"; // String | The multi-session token.
apiInstance.getMultiSessionStatus(token).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **String**| The multi-session token. | 

### Return type

[**GetMultiSessionStatus200Response**](GetMultiSessionStatus200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## startAMultiSession

> StartAMultiSession201Response startAMultiSession(startAMultiSessionRequest)

Start a multi-session

Create multiple game sessions at once for a swipeable interface. Returns a URL that can be loaded in the player&#39;s browser for a TikTok-style game discovery experience.

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.MultiSessionsApi();
let startAMultiSessionRequest = new IPlayGamesApi.StartAMultiSessionRequest(); // StartAMultiSessionRequest | 
apiInstance.startAMultiSession(startAMultiSessionRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startAMultiSessionRequest** | [**StartAMultiSessionRequest**](StartAMultiSessionRequest.md)|  | 

### Return type

[**StartAMultiSession201Response**](StartAMultiSession201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

