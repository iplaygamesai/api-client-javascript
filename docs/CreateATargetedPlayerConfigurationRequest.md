# IPlayGamesApi.CreateATargetedPlayerConfigurationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**playerId** | **String** | Must not be greater than 100 characters. | 
**poolType** | **String** |  | 
**currency** | **String** | Must be 3 characters. | 
**thresholdAmount** | **Number** | Must be at least 1. | 
**thresholdVariance** | **Number** | Must be at least 0. | [optional] 
**metadata** | **Object** |  | [optional] 



## Enum: PoolTypeEnum


* `grand_prize` (value: `"grand_prize"`)

* `mega` (value: `"mega"`)

* `major` (value: `"major"`)

* `minor` (value: `"minor"`)

* `mini` (value: `"mini"`)




