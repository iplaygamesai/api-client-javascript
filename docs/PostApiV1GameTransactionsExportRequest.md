# IPlayGamesApi.PostApiV1GameTransactionsExportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**format** | **String** |  | 
**fromDate** | **String** | Must be a valid date. | 
**toDate** | **String** | Must be a valid date. Must be a date after or equal to &lt;code&gt;from_date&lt;/code&gt;. | 
**playerId** | **String** |  | [optional] 
**gameId** | **Number** | The &lt;code&gt;id&lt;/code&gt; of an existing record in the games table. | [optional] 
**type** | **String** |  | [optional] 
**includeSummary** | **Boolean** |  | [optional] 
**async** | **Boolean** |  | [optional] 



## Enum: FormatEnum


* `csv` (value: `"csv"`)

* `json` (value: `"json"`)

* `pdf` (value: `"pdf"`)





## Enum: TypeEnum


* `Win` (value: `"Win"`)

* `Lose` (value: `"Lose"`)

* `BetPlacing` (value: `"BetPlacing"`)

* `BetPayedAbort` (value: `"BetPayedAbort"`)

* `BetPlacingAbort` (value: `"BetPlacingAbort"`)

* `SportBetCancel` (value: `"SportBetCancel"`)

* `Tip` (value: `"Tip"`)

* `PromoWin` (value: `"PromoWin"`)

* `TechnicalFix` (value: `"TechnicalFix"`)

* `DropAndWin` (value: `"DropAndWin"`)

* `PromoStreamersDebit` (value: `"PromoStreamersDebit"`)

* `PromoStreamersCredit` (value: `"PromoStreamersCredit"`)

* `PromoStreamersBetPlacingAbort` (value: `"PromoStreamersBetPlacingAbort"`)

* `PromoStreamersBetPayedAbort` (value: `"PromoStreamersBetPayedAbort"`)




