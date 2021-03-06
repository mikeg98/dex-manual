# Supply

## query

To query the total supply of tokens.

```BASH
Query total supply of coins that are held by accounts in the
			chain.
Example:
$ cetcli query supply total

To query for the total supply of a specific coin denomination use:
$ cetcli query supply total cet

Usage:
  cetcli query supply total [denom] [flags]

```

Parameter:

| Parameter   | Name            | Type   | Required | Default Value | Comment                    |
| ------------| --------------- | ------ | -------- | ------------  | -------------------------- |
| Parameter 1 | denom           | string |          |               | name of a token |

If `denom` is specified, only the specified token's supply is queried.

```bash
cetcli query supply total cet --chain-id=coinexdex

"586884903761317189"
```

If `denom` is not specified, all the issued tokens' supply will be queried.

```BASH
cetcli q supply total  --chain-id=coinexdex

- denom: aaa
  amount: "10000000000000000"
- denom: ai
  amount: "10000000000000000000"
- denom: ali
  amount: "10000000000000000000"
- denom: apple
  amount: "1000000000000000000"
- denom: bbs
  amount: "10000000000000000000"
- denom: bch
  amount: "2100000000000000"
- denom: btc
  amount: "2100000000000000"
- denom: buy
  amount: "10000000000000000000"
- denom: cat
  amount: "8888888800000000"
- denom: ccc
  amount: "500000000000000000"
- denom: cet
  amount: "586884903761317189"
- denom: cetdac
  amount: "1000000000000000"
- denom: cetdex
  amount: "10000000000000000"
- denom: dac
  amount: "1000000000000000"
- denom: dactest
  amount: "1000000000000000"
- denom: dex
  amount: "10000000000000000000"
- denom: doll
  amount: "10000000000000000000"
- denom: fxt
  amount: "10000000000000000"
- denom: game
  amount: "10000000000000000000"
- denom: go
  amount: "10000000000000000000"
- denom: good
  amount: "10000000000000000000"
- denom: google
  amount: "10000000000000000000"
- denom: gys
  amount: "1000000000000000000"
- denom: happy
  amount: "1000000000000000000"
- denom: hffptest
  amount: "1000000000000000"
- denom: hfr
  amount: "1000000000000000000"
- denom: hi
  amount: "10000000000000000000"
- denom: hrsb
  amount: "1000000000000000000000000"
- denom: huo
  amount: "10000000000000000000"
- denom: ift
  amount: "210000000000000000"
- denom: ios
  amount: "10000000000000000000"
- denom: iphone
  amount: "10000000000000000000"
- denom: jct
  amount: "2100000000000000"
- denom: jhw
  amount: "1000000000000000000"
- denom: jihan
  amount: "1000000000000000000"
- denom: jihanwu
  amount: "1000000000000000000"
- denom: jjz
  amount: "1000000000000000000"
- denom: joy
  amount: "1000000000000000000"
- denom: kaaso
  amount: "3000000000000000"
- denom: key
  amount: "1000000000000000000"
- denom: kfc
  amount: "10000000000000000000"
- denom: lcet
  amount: "1000000000000000000"
- denom: lol
  amount: "10000000000000000000"
- denom: love
  amount: "1000000000000000000"
- denom: lucky
  amount: "1000000000000000000"
- denom: lv
  amount: "10000000000000000000"
- denom: mba
  amount: "10000000000000000000"
- denom: nba
  amount: "10000000000000000000"
- denom: niu
  amount: "10000000000000000000"
- denom: ok
  amount: "100000000000000000000"
- denom: pin
  amount: "10000000000000000000"
- denom: qq
  amount: "10000000000000000000"
- denom: stream
  amount: "84000000000000000"
- denom: taobao
  amount: "10000000000000000000"
- denom: tiffany
  amount: "10000000000000000000"
- denom: token
  amount: "10000000000000000000"
- denom: usdh
  amount: "6022300000000"
- denom: vip
  amount: "10000000000000000000"
- denom: wallet
  amount: "10000000000000000000"
- denom: wechat
  amount: "10000000000000000000"
- denom: weibo
  amount: "10000000000000000000"
- denom: wjh
  amount: "1000000000000000000"
- denom: wujihan
  amount: "1000000000000000000"
- denom: xiaomi
  amount: "10000000000000000000"
- denom: "yes"
  amount: "10000000000000000000"
- denom: yhp
  amount: "1000000000000000000"
- denom: ysg
  amount: "1000000000000000000"
- denom: yuan
  amount: "1000000000000000000"
```

