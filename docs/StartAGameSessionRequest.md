# IPlayGamesApi.StartAGameSessionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gameId** | **Number** | The ID of the game to start. | 
**playerId** | **String** | The player&#39;s ID in your system. | 
**currency** | **String** | Three-letter currency code (ISO 4217). | 
**ipAddress** | **String** | The player&#39;s IP address. | 
**countryCode** | **String** | Two-letter country code (ISO 3166-1 alpha-2). | 
**returnUrl** | **String** | optional URL to redirect the player after game ends. | [optional] 
**locale** | **String** | optional Player&#39;s language preference (ISO 639-1). | [optional] 
**provider** | **String** | optional Provider slug to use for this session. Requires can_override_provider enabled. | [optional] 
**freespinId** | **String** | optional Free spin bonus ID. | [optional] 
**freespinCount** | **Number** | optional Number of free spins. | [optional] 
**freespinBetAmount** | [**Numeric**](Numeric.md) | optional Bet amount per free spin. | [optional] 
**expireDays** | **Number** | optional Free spin expiration in days (1-30). | [optional] 
**device** | **String** | optional Device type (desktop, mobile). | [optional] 


