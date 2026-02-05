# IPlayGamesApi.AddAContributionToAJackpotPoolRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**playerId** | **String** | Must not be greater than 100 characters. | 
**currency** | **String** | Must be 3 characters. | 
**amount** | **Number** | Must be at least 0.01. Must not be greater than 10000000. | 
**type** | **String** | Max 10 million per contribution. | 
**transactionId** | **String** | Must not be greater than 255 characters. | 
**gameId** | **Number** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**externalGameId** | **String** | Must not be greater than 100 characters. | [optional] 
**gameSessionId** | **Number** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the game_sessions table. | [optional] 
**metadata** | **Object** |  | [optional] 



## Enum: TypeEnum


* `daily` (value: `"daily"`)

* `weekly` (value: `"weekly"`)

* `monthly` (value: `"monthly"`)

* `grand_prize` (value: `"grand_prize"`)




