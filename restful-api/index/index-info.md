---
description: The mainly index info of Aleoscan
---

# Index Info

Path :&#x20;

```
BaseUrl+/index/info
```

Method :&#x20;

```
GET
```

Params：

```json
{
}
```

Returns:

```json
{
        "code": 200,        
        "data": {
        "totalNum": 372111,
        "totalPage": 372112,
        "data": 
        [
                {
                "round": "372110",
                "coinbase_target": "61118657681",
                "proof_target": "477489514",
                "last_coinbase_target": "61118657681",
                "last_coinbase_timestamp": "1673334354",
                "coinbase_reward": "104.9920765",
                "id": 372111,
                "height": "372110",
                "block_hash": "ab1vspuv4rdz45pxg9c7hy5d2uz5w6q4dqeq3ags54pn5uf67d2ycrsrwtyqa",
                "timestamp": "1673334354",
                "transaction_id": "at1u30s6a06s8y0q28h3k0ve8nhma6matstad5rhkfefp3ts8ge2cqqv3qfhe",
                "transition_id": "as1agf7w2rd86vffhf8j27td3xfkuldjj4gqvrjryqm090pxetfzy9sr42rws",
                "target_sum": "73591299965",
                "coinbase_solutions": "29",
                "epoch": "1454",
                "epoch_base": 256,
                "epoch_num": 142
                }
        ]
}
}
```

Example :&#x20;

```
https://api.aleoscan.info/index/info
```

