# IPlayGamesApi.GenerateAWidgetTokenRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domainToken** | **String** | The domain token from domain registration. | 
**poolTypes** | **[String]** | optional Allowed jackpot pool types. Default: [\&quot;daily\&quot;,\&quot;weekly\&quot;,\&quot;monthly\&quot;]. | [optional] 
**playerId** | **String** | optional Lock token to specific player (anonymous mode if omitted). | [optional] 
**currency** | **String** | optional Player&#39;s currency (required if player_id provided). | [optional] 
**expiresAt** | [**Datetime**](Datetime.md) | optional Token expiration time (null &#x3D; never expires). | [optional] 
**configuration** | **Object** | optional Additional widget configuration. | [optional] 


