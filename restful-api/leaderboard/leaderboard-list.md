# LeaderBoard List

Path :&#x20;

```
BaseUrl+/leaderboard/list
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
    "totalNum": 32024,
    "totalPage": 32025,
    "data": 
    [
        {
        "address": "aleo1548889twyay7cl50cnk6x6hjlsv6hzs603ylcqhswf5kt5pvzvxqk8xexu",
        "total_reward": 652279.9295249999,
        "total_incentive": 652279.9295249999,
        "rank": 0,
        "mainnet_reward": 130455.98590499998
        }
    ]
    }
}
```

Example :&#x20;

```
https://api.aleoscan.info/leaderboard/list?pageSize=1&pageNum=1
```

