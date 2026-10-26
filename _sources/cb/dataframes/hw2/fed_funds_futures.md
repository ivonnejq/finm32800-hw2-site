# Dataframe: `hw2:fed_funds_futures` - 30-Day Fed Funds Futures

Daily contract OHLCV bars. Outright ZQ prices imply monthly average effective fed funds rates in percent as 100 minus price. Filter spread symbols before calculating rates; thinly traded contracts may lack a bar on the latest date.


## DataFrame Glimpse

```
Rows: 11707
Columns: 7
$ date   <datetime[ns]> 2026-10-23 00:00:00
$ symbol          <str> 'ZQF7'
$ open            <f64> 95.9
$ high            <f64> 95.905
$ low             <f64> 95.875
$ close           <f64> 95.9
$ volume          <u64> 43615


```

## Dataframe Manifest

| Dataframe Name                 | 30-Day Fed Funds Futures                                                          |
|--------------------------------|--------------------------------------------------------------------------------------|
| Dataframe ID                   | [fed_funds_futures](../dataframes/hw2/fed_funds_futures.md)                                       |
| Sources                        | CME Globex                                          |
| Providers                      | Databento                                        |
| Provider Links                 | https://databento.com/                                   |
| Tags                           | Futures, Monetary Policy, Fedwatch                                             |
| Access Types                   |                                       |
| How is data pulled?            | Databento historical API, GLBX.MDP3, ohlcv-1d, ZQ.FUT parent                                                   |
| Data available up to (min)     | 2026-10-23 00:00:00                                                             |
| Data available up to (max)     | 2026-10-23 00:00:00                                                             |
| Dataframe Path                 | /home/leo/ljq/32800/hw2-ivonnejq/_data/fed_funds_futures.parquet                                             |


**Linked Charts:**


- [hw2:fedwatch_latest_forecast](../../charts/hw2.fedwatch_latest_forecast.md)



## Pipeline Manifest

| Pipeline Name                   | HW 2: The Yield Curve and the Policy Path                       |
|---------------------------------|--------------------------------------------------------|
| Pipeline ID                     | [hw2](../../../index.md)              |
| Maintainer                      | Jeremiah Bejarano               |
| Contributors                    | Jeremiah Bejarano |
| Repository                     | https://github.com/hw-finm-32800/hw2                  |
| Pipeline Web Page               | <a href="file:///home/leo/ljq/32800/hw2-ivonnejq/docs/index.html">Pipeline Web Page      |
| Date of Last Code Update        | 2026-10-26 13:09:03           |
| OS Compatibility                | Windows, Linux, macOS |
| Linked Dataframes               |  [hw2:crsp_treasury_consolidated](../../dataframes/hw2/crsp_treasury_consolidated.md)<br>  [hw2:fed_yield_curve](../../dataframes/hw2/fed_yield_curve.md)<br>  [hw2:fed_funds_futures](../../dataframes/hw2/fed_funds_futures.md)<br>  |


**Build Commands:**
```
doit

```

