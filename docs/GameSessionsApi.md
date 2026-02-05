# IPlayGamesApi.GameSessionsApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**endAGameSession**](GameSessionsApi.md#endAGameSession) | **POST** /api/v1/game-sessions/{session_id}/end | End a game session
[**getSessionStatus**](GameSessionsApi.md#getSessionStatus) | **GET** /api/v1/game-sessions/{session_id}/status | Get session status
[**startAGameSession**](GameSessionsApi.md#startAGameSession) | **POST** /api/v1/game-sessions/start | Start a game session



## endAGameSession

> EndAGameSession200Response endAGameSession(sessionId)

End a game session

Terminate an active game session

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GameSessionsApi();
let sessionId = "abc123"; // String | The session ID to end.
apiInstance.endAGameSession(sessionId).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sessionId** | **String**| The session ID to end. | 

### Return type

[**EndAGameSession200Response**](EndAGameSession200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getSessionStatus

> GetSessionStatus200Response getSessionStatus(sessionId)

Get session status

Retrieve the current status of a game session

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GameSessionsApi();
let sessionId = "abc123"; // String | The session ID.
apiInstance.getSessionStatus(sessionId).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sessionId** | **String**| The session ID. | 

### Return type

[**GetSessionStatus200Response**](GetSessionStatus200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## startAGameSession

> StartAGameSession201Response startAGameSession(startAGameSessionRequest)

Start a game session

Initialize a new game session for a player

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GameSessionsApi();
let startAGameSessionRequest = new IPlayGamesApi.StartAGameSessionRequest(); // StartAGameSessionRequest | 
apiInstance.startAGameSession(startAGameSessionRequest).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startAGameSessionRequest** | [**StartAGameSessionRequest**](StartAGameSessionRequest.md)|  | 

### Return type

[**StartAGameSession201Response**](StartAGameSession201Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

