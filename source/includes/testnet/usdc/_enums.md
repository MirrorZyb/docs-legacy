# t(:enums)
t(:ENUMs_para)

## Side (`side`)
* `Buy`
* `Sell`

## PlaceMode (`placeMode`)
* `1` - basic
* `2` - advanced

## PlaceType (`placeType`)
* `1` - price
* `2` - iv

## TimeInForce (`time_in_force`)
* `GoodTillCancel`
* `ImmediateOrCancel`
* `FillOrKill`
* `PostOnly`

## Symbol (`symbol`)
t(:usdc_trading_symbol_comment)


## Order type (`type`/`orderTypes`)
* `LIMIT`
* `MARKET`
* `LIMIT_MAKER`


## Currency (`currency`/`coin`)
* `USDC`

The transfer API also includes:

* `USDC`


## Order status (`status`)
* `NEW`
* `PARTIALLY_FILLED`
* `FILLED`
* `CANCELED`
* `PENDING_CANCEL`
* `PENDING_NEW`
* `REJECTED`

## Quantity (`qty`)
t(:usdcQuantity)

## Price (`price`)
t(:usdcPriceRule)


## Kline interval (`interval`)
* `1m` t(:interval_1)
* `3m` t(:interval_3)
* `5m` t(:interval_5)
* `15m` t(:interval_15)
* `30m` t(:interval_30)
* `1h` t(:interval_60)
* `2h` t(:interval_120)
* `4h` t(:interval_240)
* `6h` t(:interval_360)
* `12h` t(:interval_720)
* `1d` t(:interval_D)
* `1w` t(:interval_W)
* `1M` t(:interval_M)

## Transaction type (`Transaction type`)
* `TRANSFER_IN`
* `TRANSFER_OUT`
* `TRADE`
* `SETTLEMENT`
* `DELIVERY`
* `LIQUIDATION`

## Margin Mode
* `REGULAR_MARGIN`
* `PORTFOLIO_MARGIN`
