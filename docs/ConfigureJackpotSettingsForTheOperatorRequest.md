# IPlayGamesApi.ConfigureJackpotSettingsForTheOperatorRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**isEnabled** | **Boolean** |  | [optional] 
**poolTypes** | **[String]** |  | [optional] 
**casinoCutPercentage** | **Number** | Must be at least 0. Must not be greater than 0.9. | [optional] 
**winnerCount** | **Number** | Must be at least 1. Must not be greater than 10000. | [optional] 
**distributionMethod** | **String** |  | [optional] 
**weightCalculation** | **String** |  | [optional] 
**prizeTiers** | [**[ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner]**](ConfigureJackpotSettingsForTheOperatorRequestPrizeTiersInner.md) |  | [optional] 
**gameFilterEnabled** | **Boolean** |  | [optional] 
**webhookEnabled** | **Boolean** |  | [optional] 
**reminderHoursBefore** | **Number** | Must be at least 1. Must not be greater than 168. | [optional] 



## Enum: [PoolTypesEnum]


* `daily` (value: `"daily"`)

* `weekly` (value: `"weekly"`)

* `monthly` (value: `"monthly"`)

* `grand_prize` (value: `"grand_prize"`)





## Enum: DistributionMethodEnum


* `weighted` (value: `"weighted"`)

* `random` (value: `"random"`)





## Enum: WeightCalculationEnum


* `contribution_sum` (value: `"contribution_sum"`)

* `bet_count` (value: `"bet_count"`)




