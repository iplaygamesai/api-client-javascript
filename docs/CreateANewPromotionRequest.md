# IPlayGamesApi.CreateANewPromotionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** | Must not be greater than 255 characters. | 
**description** | **String** |  | [optional] 
**imageUrl** | **String** | Must be a valid URL. | [optional] 
**termsAndConditions** | **String** |  | [optional] 
**promotionType** | **String** |  | 
**cycleType** | **String** |  | 
**startsAt** | **String** | Must be a valid date. | [optional] 
**endsAt** | **String** | Must be a valid date. Must be a date after &lt;code&gt;starts_at&lt;/code&gt;. | [optional] 
**timezone** | **String** |  | [optional] 
**prizeDistribution** | **Object** |  | [optional] 
**totalPrizePool** | **Number** | Must be at least 0. | [optional] 
**prizeCurrency** | **String** | Must be 3 characters. | [optional] 
**winnerCount** | **Number** | Must be at least 1. | [optional] 
**entryConfig** | **Object** |  | [optional] 
**gameFilterEnabled** | **Boolean** |  | [optional] 
**producerFilterEnabled** | **Boolean** |  | [optional] 
**webhookEnabled** | **Boolean** |  | [optional] 
**isFeatured** | **Boolean** |  | [optional] 
**gameIds** | **[Number]** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**producerIds** | **[Number]** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the producers table. | [optional] 


