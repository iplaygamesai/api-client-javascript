# IPlayGamesApi.CreateAStandaloneFreespinRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gameId** | **Number** | The internal game ID. | 
**playerId** | **String** | The player&#39;s ID in your system. | 
**currency** | **String** | Three-letter currency code (ISO 4217). | 
**freespinId** | **String** | Your unique identifier for this freespin campaign. | 
**freespinCount** | **Number** | Number of free spins to award (1-1000). | 
**freespinBetAmount** | [**Numeric**](Numeric.md) | optional Bet amount per free spin (0.01-1000). | [optional] 
**expireDays** | **Number** | optional Expiration in days, default 7, max 30. | [optional] 
**provider** | **String** | optional Specific provider slug to use. | [optional] 


