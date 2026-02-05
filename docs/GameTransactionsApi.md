# IPlayGamesApi.GameTransactionsApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getTransactionDetails**](GameTransactionsApi.md#getTransactionDetails) | **GET** /api/v1/game-transactions/{id} | Get transaction details
[**getTransactionHistory**](GameTransactionsApi.md#getTransactionHistory) | **GET** /api/v1/game-transactions | Get transaction history



## getTransactionDetails

> String getTransactionDetails(id)

Get transaction details

Retrieve detailed information about a specific transaction

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GameTransactionsApi();
let id = 789; // Number | The ID of the transaction.
apiInstance.getTransactionDetails(id).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**| The ID of the transaction. | 

### Return type

**String**

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json


## getTransactionHistory

> GetTransactionHistory200Response getTransactionHistory(opts)

Get transaction history

Retrieve a list of game transactions for the authenticated operator

### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.GameTransactionsApi();
let opts = {
  'playerId': "player_456", // String | Filter by player ID.
  'gameId': 123, // Number | Filter by game ID.
  'type': "bet", // String | Filter by transaction type (bet, win, rollback).
  'fromDate': "2024-01-01T00:00:00Z", // String | Filter transactions from date (ISO 8601).
  'toDate': "2024-01-31T23:59:59Z", // String | Filter transactions to date (ISO 8601).
  'limit': 50, // Number | Number of results per page. Default: 100.
  'offset': 100 // Number | Number of results to skip. Default: 0.
};
apiInstance.getTransactionHistory(opts).then((data) => {
  console.log('API called successfully. Returned data: ' + data);
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **playerId** | **String**| Filter by player ID. | [optional] 
 **gameId** | **Number**| Filter by game ID. | [optional] 
 **type** | **String**| Filter by transaction type (bet, win, rollback). | [optional] 
 **fromDate** | **String**| Filter transactions from date (ISO 8601). | [optional] 
 **toDate** | **String**| Filter transactions to date (ISO 8601). | [optional] 
 **limit** | **Number**| Number of results per page. Default: 100. | [optional] 
 **offset** | **Number**| Number of results to skip. Default: 0. | [optional] 

### Return type

[**GetTransactionHistory200Response**](GetTransactionHistory200Response.md)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

