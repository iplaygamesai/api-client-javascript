# IPlayGamesApi.EndpointsApi

All URIs are relative to *https://api.iplaygames.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addAContributionToAJackpotPool**](EndpointsApi.md#addAContributionToAJackpotPool) | **POST** /api/v1/jackpot/contribute | Add a contribution to a jackpot pool
[**addGamesToAJackpotPoolType**](EndpointsApi.md#addGamesToAJackpotPoolType) | **POST** /api/v1/jackpot/games | Add games to a jackpot pool type
[**bulkCreateExternalGamesFromJSONArray**](EndpointsApi.md#bulkCreateExternalGamesFromJSONArray) | **POST** /api/v1/external-games/bulk | Bulk create external games from JSON array
[**bulkDeleteExternalGamesByIDs**](EndpointsApi.md#bulkDeleteExternalGamesByIDs) | **DELETE** /api/v1/external-games/bulk | Bulk delete external games by IDs
[**configureJackpotSettingsForTheOperator**](EndpointsApi.md#configureJackpotSettingsForTheOperator) | **POST** /api/v1/jackpot/configure | Configure jackpot settings for the operator
[**configureLiveModeSettingsForAPool**](EndpointsApi.md#configureLiveModeSettingsForAPool) | **PUT** /api/v1/jackpot/pools/{poolId}/live-mode | Configure live mode settings for a pool
[**createANewPromotion**](EndpointsApi.md#createANewPromotion) | **POST** /api/v1/promotions | Create a new promotion
[**createASingleExternalGame**](EndpointsApi.md#createASingleExternalGame) | **POST** /api/v1/external-games | Create a single external game
[**createATargetedPlayerConfiguration**](EndpointsApi.md#createATargetedPlayerConfiguration) | **POST** /api/v1/jackpot/targeted-players | Create a targeted player configuration
[**deactivateATargetedPlayerConfiguration**](EndpointsApi.md#deactivateATargetedPlayerConfiguration) | **DELETE** /api/v1/jackpot/targeted-players/{targetedPlayerId} | Deactivate a targeted player configuration
[**deleteAPromotion**](EndpointsApi.md#deleteAPromotion) | **DELETE** /api/v1/promotions/{id} | Delete a promotion
[**deleteAnExternalGame**](EndpointsApi.md#deleteAnExternalGame) | **DELETE** /api/v1/external-games/{id} | Delete an external game
[**getASingleExternalGame**](EndpointsApi.md#getASingleExternalGame) | **GET** /api/v1/external-games/{id} | Get a single external game
[**getASpecificPromotion**](EndpointsApi.md#getASpecificPromotion) | **GET** /api/v1/promotions/{id} | Get a specific promotion
[**getApiV1Producers**](EndpointsApi.md#getApiV1Producers) | **GET** /api/v1/producers | 
[**getApiV1ProducersId**](EndpointsApi.md#getApiV1ProducersId) | **GET** /api/v1/producers/{id} | 
[**getApiV1TransactionExportsExportIdDownload**](EndpointsApi.md#getApiV1TransactionExportsExportIdDownload) | **GET** /api/v1/transaction-exports/{export_id}/download | 
[**getCurrentConfigurationWithGames**](EndpointsApi.md#getCurrentConfigurationWithGames) | **GET** /api/v1/jackpot/configuration | Get current configuration with games
[**getGamesForAPoolTypeOrAllPoolTypes**](EndpointsApi.md#getGamesForAPoolTypeOrAllPoolTypes) | **GET** /api/v1/jackpot/games | Get games for a pool type or all pool types
[**getLeaderboardForAPromotion**](EndpointsApi.md#getLeaderboardForAPromotion) | **GET** /api/v1/promotions/{id}/leaderboard | Get leaderboard for a promotion
[**getPlayerContributionHistory**](EndpointsApi.md#getPlayerContributionHistory) | **GET** /api/v1/jackpot/contributions | Get player contribution history
[**getPoolDetails**](EndpointsApi.md#getPoolDetails) | **GET** /api/v1/jackpot/pools/{poolId} | Get pool details
[**getPoolWinners**](EndpointsApi.md#getPoolWinners) | **GET** /api/v1/jackpot/pools/{poolId}/winners | Get pool winners
[**getTargetedPlayerDetails**](EndpointsApi.md#getTargetedPlayerDetails) | **GET** /api/v1/jackpot/targeted-players/{targetedPlayerId} | Get targeted player details
[**getUniqueProducerNamesForFiltering**](EndpointsApi.md#getUniqueProducerNamesForFiltering) | **GET** /api/v1/external-games/producers | Get unique producer names for filtering
[**getWinnersForAPromotion**](EndpointsApi.md#getWinnersForAPromotion) | **GET** /api/v1/promotions/{id}/winners | Get winners for a promotion
[**importExternalGamesFromCSVFile**](EndpointsApi.md#importExternalGamesFromCSVFile) | **POST** /api/v1/external-games/import/csv | Import external games from CSV file
[**importExternalGamesFromJSONPaste**](EndpointsApi.md#importExternalGamesFromJSONPaste) | **POST** /api/v1/external-games/import/json | Import external games from JSON paste
[**listExternalGamesForOperator**](EndpointsApi.md#listExternalGamesForOperator) | **GET** /api/v1/external-games | List external games for operator
[**listOperatorsJackpotPools**](EndpointsApi.md#listOperatorsJackpotPools) | **GET** /api/v1/jackpot/pools | List operator&#39;s jackpot pools
[**listPromotionsForTheOperator**](EndpointsApi.md#listPromotionsForTheOperator) | **GET** /api/v1/promotions | List promotions for the operator
[**listTargetedPlayersForOperator**](EndpointsApi.md#listTargetedPlayersForOperator) | **GET** /api/v1/jackpot/targeted-players | List targeted players for operator
[**manageGamesForAPromotion**](EndpointsApi.md#manageGamesForAPromotion) | **POST** /api/v1/promotions/{id}/games | Manage games for a promotion
[**manuallyDistributePrizesForAPeriod**](EndpointsApi.md#manuallyDistributePrizesForAPeriod) | **POST** /api/v1/promotions/{id}/periods/{periodId}/distribute | Manually distribute prizes for a period
[**manuallyTriggerPoolRelease**](EndpointsApi.md#manuallyTriggerPoolRelease) | **POST** /api/v1/jackpot/pools/{poolId}/release | Manually trigger pool release
[**optInOperatorToAPlatformnetworkPromotion**](EndpointsApi.md#optInOperatorToAPlatformnetworkPromotion) | **POST** /api/v1/promotions/{id}/opt-in | Opt-in operator to a platform/network promotion
[**optOutOperatorFromAPlatformnetworkPromotion**](EndpointsApi.md#optOutOperatorFromAPlatformnetworkPromotion) | **POST** /api/v1/promotions/{id}/opt-out | Opt-out operator from a platform/network promotion
[**postApiV1GameTransactionsExport**](EndpointsApi.md#postApiV1GameTransactionsExport) | **POST** /api/v1/game-transactions/export | 
[**removeGamesFromAJackpotPoolType**](EndpointsApi.md#removeGamesFromAJackpotPoolType) | **DELETE** /api/v1/jackpot/games | Remove games from a jackpot pool type
[**setGrandPrizeExpirationDate**](EndpointsApi.md#setGrandPrizeExpirationDate) | **PUT** /api/v1/jackpot/pools/{poolId}/expiration | Set grand prize expiration date
[**updateAPromotion**](EndpointsApi.md#updateAPromotion) | **PUT** /api/v1/promotions/{id} | Update a promotion
[**updateAnExternalGame**](EndpointsApi.md#updateAnExternalGame) | **PUT** /api/v1/external-games/{id} | Update an external game



## addAContributionToAJackpotPool

> addAContributionToAJackpotPool(addAContributionToAJackpotPoolRequest)

Add a contribution to a jackpot pool



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let addAContributionToAJackpotPoolRequest = new IPlayGamesApi.AddAContributionToAJackpotPoolRequest(); // AddAContributionToAJackpotPoolRequest | 
apiInstance.addAContributionToAJackpotPool(addAContributionToAJackpotPoolRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addAContributionToAJackpotPoolRequest** | [**AddAContributionToAJackpotPoolRequest**](AddAContributionToAJackpotPoolRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## addGamesToAJackpotPoolType

> addGamesToAJackpotPoolType(addGamesToAJackpotPoolTypeRequest)

Add games to a jackpot pool type



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let addGamesToAJackpotPoolTypeRequest = new IPlayGamesApi.AddGamesToAJackpotPoolTypeRequest(); // AddGamesToAJackpotPoolTypeRequest | 
apiInstance.addGamesToAJackpotPoolType(addGamesToAJackpotPoolTypeRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addGamesToAJackpotPoolTypeRequest** | [**AddGamesToAJackpotPoolTypeRequest**](AddGamesToAJackpotPoolTypeRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## bulkCreateExternalGamesFromJSONArray

> bulkCreateExternalGamesFromJSONArray(bulkCreateExternalGamesFromJSONArrayRequest)

Bulk create external games from JSON array



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let bulkCreateExternalGamesFromJSONArrayRequest = new IPlayGamesApi.BulkCreateExternalGamesFromJSONArrayRequest(); // BulkCreateExternalGamesFromJSONArrayRequest | 
apiInstance.bulkCreateExternalGamesFromJSONArray(bulkCreateExternalGamesFromJSONArrayRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkCreateExternalGamesFromJSONArrayRequest** | [**BulkCreateExternalGamesFromJSONArrayRequest**](BulkCreateExternalGamesFromJSONArrayRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## bulkDeleteExternalGamesByIDs

> bulkDeleteExternalGamesByIDs(opts)

Bulk delete external games by IDs



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'bulkDeleteExternalGamesByIDsRequest': new IPlayGamesApi.BulkDeleteExternalGamesByIDsRequest() // BulkDeleteExternalGamesByIDsRequest | 
};
apiInstance.bulkDeleteExternalGamesByIDs(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkDeleteExternalGamesByIDsRequest** | [**BulkDeleteExternalGamesByIDsRequest**](BulkDeleteExternalGamesByIDsRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## configureJackpotSettingsForTheOperator

> configureJackpotSettingsForTheOperator(opts)

Configure jackpot settings for the operator



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'configureJackpotSettingsForTheOperatorRequest': new IPlayGamesApi.ConfigureJackpotSettingsForTheOperatorRequest() // ConfigureJackpotSettingsForTheOperatorRequest | 
};
apiInstance.configureJackpotSettingsForTheOperator(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **configureJackpotSettingsForTheOperatorRequest** | [**ConfigureJackpotSettingsForTheOperatorRequest**](ConfigureJackpotSettingsForTheOperatorRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## configureLiveModeSettingsForAPool

> configureLiveModeSettingsForAPool(poolId, configureLiveModeSettingsForAPoolRequest)

Configure live mode settings for a pool



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let poolId = "architecto"; // String | 
let configureLiveModeSettingsForAPoolRequest = new IPlayGamesApi.ConfigureLiveModeSettingsForAPoolRequest(); // ConfigureLiveModeSettingsForAPoolRequest | 
apiInstance.configureLiveModeSettingsForAPool(poolId, configureLiveModeSettingsForAPoolRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolId** | **String**|  | 
 **configureLiveModeSettingsForAPoolRequest** | [**ConfigureLiveModeSettingsForAPoolRequest**](ConfigureLiveModeSettingsForAPoolRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## createANewPromotion

> createANewPromotion(createANewPromotionRequest)

Create a new promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let createANewPromotionRequest = new IPlayGamesApi.CreateANewPromotionRequest(); // CreateANewPromotionRequest | 
apiInstance.createANewPromotion(createANewPromotionRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createANewPromotionRequest** | [**CreateANewPromotionRequest**](CreateANewPromotionRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## createASingleExternalGame

> createASingleExternalGame(createASingleExternalGameRequest)

Create a single external game



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let createASingleExternalGameRequest = new IPlayGamesApi.CreateASingleExternalGameRequest(); // CreateASingleExternalGameRequest | 
apiInstance.createASingleExternalGame(createASingleExternalGameRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createASingleExternalGameRequest** | [**CreateASingleExternalGameRequest**](CreateASingleExternalGameRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## createATargetedPlayerConfiguration

> createATargetedPlayerConfiguration(createATargetedPlayerConfigurationRequest)

Create a targeted player configuration



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let createATargetedPlayerConfigurationRequest = new IPlayGamesApi.CreateATargetedPlayerConfigurationRequest(); // CreateATargetedPlayerConfigurationRequest | 
apiInstance.createATargetedPlayerConfiguration(createATargetedPlayerConfigurationRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createATargetedPlayerConfigurationRequest** | [**CreateATargetedPlayerConfigurationRequest**](CreateATargetedPlayerConfigurationRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## deactivateATargetedPlayerConfiguration

> deactivateATargetedPlayerConfiguration(targetedPlayerId)

Deactivate a targeted player configuration



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let targetedPlayerId = "architecto"; // String | 
apiInstance.deactivateATargetedPlayerConfiguration(targetedPlayerId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **targetedPlayerId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## deleteAPromotion

> deleteAPromotion(id)

Delete a promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.deleteAPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## deleteAnExternalGame

> deleteAnExternalGame(id)

Delete an external game



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the external game.
apiInstance.deleteAnExternalGame(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the external game. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## getASingleExternalGame

> getASingleExternalGame(id)

Get a single external game



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the external game.
apiInstance.getASingleExternalGame(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the external game. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getASpecificPromotion

> getASpecificPromotion(id)

Get a specific promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.getASpecificPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getApiV1Producers

> getApiV1Producers()





### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
apiInstance.getApiV1Producers().then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getApiV1ProducersId

> getApiV1ProducersId(id)





### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the producer.
apiInstance.getApiV1ProducersId(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the producer. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getApiV1TransactionExportsExportIdDownload

> getApiV1TransactionExportsExportIdDownload(exportId)





### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let exportId = 16; // Number | The ID of the export.
apiInstance.getApiV1TransactionExportsExportIdDownload(exportId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exportId** | **Number**| The ID of the export. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getCurrentConfigurationWithGames

> getCurrentConfigurationWithGames()

Get current configuration with games



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
apiInstance.getCurrentConfigurationWithGames().then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getGamesForAPoolTypeOrAllPoolTypes

> getGamesForAPoolTypeOrAllPoolTypes(opts)

Get games for a pool type or all pool types



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'getGamesForAPoolTypeOrAllPoolTypesRequest': new IPlayGamesApi.GetGamesForAPoolTypeOrAllPoolTypesRequest() // GetGamesForAPoolTypeOrAllPoolTypesRequest | 
};
apiInstance.getGamesForAPoolTypeOrAllPoolTypes(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getGamesForAPoolTypeOrAllPoolTypesRequest** | [**GetGamesForAPoolTypeOrAllPoolTypesRequest**](GetGamesForAPoolTypeOrAllPoolTypesRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## getLeaderboardForAPromotion

> getLeaderboardForAPromotion(id)

Get leaderboard for a promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.getLeaderboardForAPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getPlayerContributionHistory

> getPlayerContributionHistory(getPlayerContributionHistoryRequest)

Get player contribution history



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let getPlayerContributionHistoryRequest = new IPlayGamesApi.GetPlayerContributionHistoryRequest(); // GetPlayerContributionHistoryRequest | 
apiInstance.getPlayerContributionHistory(getPlayerContributionHistoryRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getPlayerContributionHistoryRequest** | [**GetPlayerContributionHistoryRequest**](GetPlayerContributionHistoryRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## getPoolDetails

> getPoolDetails(poolId)

Get pool details



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let poolId = "architecto"; // String | 
apiInstance.getPoolDetails(poolId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getPoolWinners

> getPoolWinners(poolId)

Get pool winners



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let poolId = "architecto"; // String | 
apiInstance.getPoolWinners(poolId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getTargetedPlayerDetails

> getTargetedPlayerDetails(targetedPlayerId)

Get targeted player details



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let targetedPlayerId = "architecto"; // String | 
apiInstance.getTargetedPlayerDetails(targetedPlayerId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **targetedPlayerId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getUniqueProducerNamesForFiltering

> getUniqueProducerNamesForFiltering()

Get unique producer names for filtering



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
apiInstance.getUniqueProducerNamesForFiltering().then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## getWinnersForAPromotion

> getWinnersForAPromotion(id)

Get winners for a promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.getWinnersForAPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## importExternalGamesFromCSVFile

> importExternalGamesFromCSVFile(file)

Import external games from CSV file



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let file = "/path/to/file"; // File | Must be a file. Must not be greater than 10240 kilobytes.
apiInstance.importExternalGamesFromCSVFile(file).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | **File**| Must be a file. Must not be greater than 10240 kilobytes. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined


## importExternalGamesFromJSONPaste

> importExternalGamesFromJSONPaste(importExternalGamesFromJSONPasteRequest)

Import external games from JSON paste



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let importExternalGamesFromJSONPasteRequest = new IPlayGamesApi.ImportExternalGamesFromJSONPasteRequest(); // ImportExternalGamesFromJSONPasteRequest | 
apiInstance.importExternalGamesFromJSONPaste(importExternalGamesFromJSONPasteRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **importExternalGamesFromJSONPasteRequest** | [**ImportExternalGamesFromJSONPasteRequest**](ImportExternalGamesFromJSONPasteRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## listExternalGamesForOperator

> listExternalGamesForOperator(opts)

List external games for operator



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'listExternalGamesForOperatorRequest': new IPlayGamesApi.ListExternalGamesForOperatorRequest() // ListExternalGamesForOperatorRequest | 
};
apiInstance.listExternalGamesForOperator(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listExternalGamesForOperatorRequest** | [**ListExternalGamesForOperatorRequest**](ListExternalGamesForOperatorRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## listOperatorsJackpotPools

> listOperatorsJackpotPools(opts)

List operator&#39;s jackpot pools



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'listOperatorsJackpotPoolsRequest': new IPlayGamesApi.ListOperatorsJackpotPoolsRequest() // ListOperatorsJackpotPoolsRequest | 
};
apiInstance.listOperatorsJackpotPools(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listOperatorsJackpotPoolsRequest** | [**ListOperatorsJackpotPoolsRequest**](ListOperatorsJackpotPoolsRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## listPromotionsForTheOperator

> listPromotionsForTheOperator()

List promotions for the operator



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
apiInstance.listPromotionsForTheOperator().then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## listTargetedPlayersForOperator

> listTargetedPlayersForOperator(opts)

List targeted players for operator



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let opts = {
  'listTargetedPlayersForOperatorRequest': new IPlayGamesApi.ListTargetedPlayersForOperatorRequest() // ListTargetedPlayersForOperatorRequest | 
};
apiInstance.listTargetedPlayersForOperator(opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **listTargetedPlayersForOperatorRequest** | [**ListTargetedPlayersForOperatorRequest**](ListTargetedPlayersForOperatorRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## manageGamesForAPromotion

> manageGamesForAPromotion(id, opts)

Manage games for a promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
let opts = {
  'manageGamesForAPromotionRequest': new IPlayGamesApi.ManageGamesForAPromotionRequest() // ManageGamesForAPromotionRequest | 
};
apiInstance.manageGamesForAPromotion(id, opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 
 **manageGamesForAPromotionRequest** | [**ManageGamesForAPromotionRequest**](ManageGamesForAPromotionRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## manuallyDistributePrizesForAPeriod

> manuallyDistributePrizesForAPeriod(id, periodId)

Manually distribute prizes for a period



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
let periodId = "architecto"; // String | 
apiInstance.manuallyDistributePrizesForAPeriod(id, periodId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 
 **periodId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## manuallyTriggerPoolRelease

> manuallyTriggerPoolRelease(poolId)

Manually trigger pool release



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let poolId = "architecto"; // String | 
apiInstance.manuallyTriggerPoolRelease(poolId).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolId** | **String**|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## optInOperatorToAPlatformnetworkPromotion

> optInOperatorToAPlatformnetworkPromotion(id)

Opt-in operator to a platform/network promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.optInOperatorToAPlatformnetworkPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## optOutOperatorFromAPlatformnetworkPromotion

> optOutOperatorFromAPlatformnetworkPromotion(id)

Opt-out operator from a platform/network promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
apiInstance.optOutOperatorFromAPlatformnetworkPromotion(id).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## postApiV1GameTransactionsExport

> postApiV1GameTransactionsExport(postApiV1GameTransactionsExportRequest)





### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let postApiV1GameTransactionsExportRequest = new IPlayGamesApi.PostApiV1GameTransactionsExportRequest(); // PostApiV1GameTransactionsExportRequest | 
apiInstance.postApiV1GameTransactionsExport(postApiV1GameTransactionsExportRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postApiV1GameTransactionsExportRequest** | [**PostApiV1GameTransactionsExportRequest**](PostApiV1GameTransactionsExportRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## removeGamesFromAJackpotPoolType

> removeGamesFromAJackpotPoolType(removeGamesFromAJackpotPoolTypeRequest)

Remove games from a jackpot pool type



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let removeGamesFromAJackpotPoolTypeRequest = new IPlayGamesApi.RemoveGamesFromAJackpotPoolTypeRequest(); // RemoveGamesFromAJackpotPoolTypeRequest | 
apiInstance.removeGamesFromAJackpotPoolType(removeGamesFromAJackpotPoolTypeRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **removeGamesFromAJackpotPoolTypeRequest** | [**RemoveGamesFromAJackpotPoolTypeRequest**](RemoveGamesFromAJackpotPoolTypeRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## setGrandPrizeExpirationDate

> setGrandPrizeExpirationDate(poolId, setGrandPrizeExpirationDateRequest)

Set grand prize expiration date



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let poolId = "architecto"; // String | 
let setGrandPrizeExpirationDateRequest = new IPlayGamesApi.SetGrandPrizeExpirationDateRequest(); // SetGrandPrizeExpirationDateRequest | 
apiInstance.setGrandPrizeExpirationDate(poolId, setGrandPrizeExpirationDateRequest).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **poolId** | **String**|  | 
 **setGrandPrizeExpirationDateRequest** | [**SetGrandPrizeExpirationDateRequest**](SetGrandPrizeExpirationDateRequest.md)|  | 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## updateAPromotion

> updateAPromotion(id, opts)

Update a promotion



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the promotion.
let opts = {
  'updateAPromotionRequest': new IPlayGamesApi.UpdateAPromotionRequest() // UpdateAPromotionRequest | 
};
apiInstance.updateAPromotion(id, opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the promotion. | 
 **updateAPromotionRequest** | [**UpdateAPromotionRequest**](UpdateAPromotionRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## updateAnExternalGame

> updateAnExternalGame(id, opts)

Update an external game



### Example

```javascript
import IPlayGamesApi from 'iplaygames-api-client';
let defaultClient = IPlayGamesApi.ApiClient.instance;
// Configure Bearer access token for authorization: default
let default = defaultClient.authentications['default'];
default.accessToken = "YOUR ACCESS TOKEN"

let apiInstance = new IPlayGamesApi.EndpointsApi();
let id = "architecto"; // String | The ID of the external game.
let opts = {
  'updateAnExternalGameRequest': new IPlayGamesApi.UpdateAnExternalGameRequest() // UpdateAnExternalGameRequest | 
};
apiInstance.updateAnExternalGame(id, opts).then(() => {
  console.log('API called successfully.');
}, (error) => {
  console.error(error);
});

```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| The ID of the external game. | 
 **updateAnExternalGameRequest** | [**UpdateAnExternalGameRequest**](UpdateAnExternalGameRequest.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

[default](../README.md#default)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

