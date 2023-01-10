---
description: To Fetch Transaction List
---

# Transaction List

Path :&#x20;

```
BaseUrl+/transaction/list
```

Method :&#x20;

```
GET
```

Params：

```json
{
    pageSize: 1 , // The size of page data
    pageNum : 1 , // The page you want to visit
}
```

Returns:

```json
{
    "code": 200,
    "data": {
        "totalNum": 372142,
        "totalPage": 372143,
        "data": 
        [
            {
            "transaction_id": "at1hl04whcvmnve40fmfur0a3gfjvfjwpwcuc0p2kpt2p4pcptdaursnluy8s",
            "timestamp": "1673334721",
            "block_id": 372136,
            "block_height": "372135",
            "type": "Execute",
            "fee": 0
            }
        ]
    }
}
```

Example :&#x20;

```
https://api.aleoscan.info/transaction/list?pageSize=1&pageNum=1
```

