# t(:enums)
t(:ENUMs_para)

## Account type (`from_account_type`/`to_account_type`)
* `CONTRACT`  t(:accountType_contract)
* `SPOT`      t(:accountType_spot)
* `INVESTMENT` t(:accountType_investment)
* `OPTION` t(:accountType_option)
* `UNIFIED` t(:accountType_unified)

## Withdraw status(`status`)
* `SecurityCheck` t(:withdrawStatus_securityCheck)
* `Pending` t(:withdrawStatus_pending)
* `success` t(:withdrawStatus_success)
* `CancelByUser` t(:withdrawStatus_cancelByUser)
* `Reject` t(:withdrawStatus_Reject)
* `Fail` t(:withdrawStatus_Fail)
* `BlockchainConfirmed` t(:withdrawStatus_BlockchainConfirmed)

## Currency (`currency`/`coin`)
* `BTC`
* `ETH`
* `EOS`
* `XRP`
* `USDT`
* `DOT`
* `DOGE`
* `LTC`
* `XLM`
* `USD`

## Operator type
* `SYSTEM`
* `USER`
* `ADMIN`
* `AFFILIATE_USER`

## Transfer type (`type`)
* `IN` t(:in)
* `OUT` t(:out)

## Transfer status (`status`)
* `SUCCESS`
* `PENDING`
* `FAILED`

## Page direction (`direction`)
* `Prev`
* `Next`