# IPlayGamesApi.ListGamesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**search** | **String** | Must not be greater than 255 characters. | [optional] 
**producerId** | **Number** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the game_producers table. | [optional] 
**provider** | **String** | The &lt;code&gt;slug&lt;/code&gt; of an existing record in the providers table. | [optional] 
**type** | **String** |  | [optional] 
**perPage** | **String** | Must match the regex /^(all. | [optional] 



## Enum: TypeEnum


* `slot` (value: `"slot"`)

* `table` (value: `"table"`)

* `live` (value: `"live"`)




