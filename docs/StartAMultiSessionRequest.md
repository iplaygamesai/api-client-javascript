# IPlayGamesApi.StartAMultiSessionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**playerId** | **String** | Player&#39;s ID in your system. | 
**currency** | **String** | Three-letter currency code (ISO 4217). | 
**countryCode** | **String** | Two-letter country code (ISO 3166-1 alpha-2). | 
**ipAddress** | **String** | Player&#39;s IP address. | 
**gameIds** | **[String]** | optional Specific game IDs to include. If not provided, picks random games from each available provider. | [optional] 
**locale** | **String** | optional Player&#39;s language preference (ISO 639-1). | [optional] 
**device** | **String** | optional Device type: desktop, mobile, tablet. | [optional] 


