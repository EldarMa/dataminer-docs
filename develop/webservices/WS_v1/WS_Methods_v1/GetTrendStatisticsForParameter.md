---
uid: GetTrendStatisticsForParameter
---

# GetTrendStatisticsForParameter

Use this method to retrieve the trend statistics for a specified parameter. Available from DataMiner 9.5.8 onwards.

## Input

| Item | Format | Description |
|--|--|--|
| Connection | String | The connection ID. See [ConnectApp](xref:ConnectApp). |
| DmaID | Integer | The DataMiner Agent ID. |
| ElementID | Integer | The element ID. |
| ParameterID | Integer | The parameter ID. |
| TableIndex | String | The (optional) table index (which, if specified, must be the display column). |
| TrendingSpanType | String | The trending span type: *LastHour*, *LastDay*, *LastWeek*, *LastMonth*, *LastYear*, *CustomAmountHours* or *Custom*. |
| CustomAmountHours | Integer | The custom amount of hours for the trend span in case TrendSpan is set to *CustomAmountHours*. |
| UtcCustomStartTime | Long integer | The custom start time of the trend span in case TrendingSpanType is set to *Custom*. |
| UtcCustomEndTime | Long integer | The custom end time of the trend span in case TrendingSpanType is set to *Custom*. |

## Output

| Item | Format | Description |
|--|--|--|
| GetTrendStatisticsFor­ParameterResponse | Array | The parameter name and element name, the unit used for the parameter, and the minimum, average and maximum trend values. |
