---
description: To search different kinds of informations
---

# Search

Path :&#x20;

```
BaseUrl+/search
```

Method :&#x20;

```
GET
```

Params：

```json
{
    data:123 //The data you want to search
    // Currently , it supports :
    // 1. Block Height
    // 2. Block Hash
    // 3. Transaction Hash
    // 4. Leaderboard Hash
}
```

Returns:

```json
{
"code": 200,
"data": {
    "status": true,
    "type": "block",
    "data": 
        {
            "id": 1,
            "round": "0",
            "coinbase_target": "1023",
            "proof_target": "8",
            "last_coinbase_target": "1023",
            "last_coinbase_timestamp": "1663718400",
            "coinbase_reward": null,
            "height": "0",
            "block_hash": "ab1pfhf6r4e2cv3v9scmkgs8nrp3gfk2rs38rgl409p3ma9wkaprvzqpwlgpz",
            "timestamp": "1663718400",
            "transition_id": "",
            "target_sum": 0,
            "transaction_id": "",
            "coinbase": {
            "puzzle": "",
            "solutions_total": 0,
            "solutions_count": 0,
            "solutions": []
        },
        "network": 3,
        "epoch": "0",
        "epoch_base": 256,
        "epoch_num": 0
        }
    }
}
```

or

```json
{
    "code": 200,
    "data": {
    "status": true,
    "type": "leaderboard",
    "data": {
    "info": {
    "address": "aleo1548889twyay7cl50cnk6x6hjlsv6hzs603ylcqhswf5kt5pvzvxqk8xexu",
    "speed": 390358060.3333333
    },
    "count": {
    "solution_sum": "481600624175886",
    "reward_sum": "652311.707399",
    "mainnet_reward": 130462.34147979999,
    "total_coinbase_reward": 652311.707399
    },
    "data": [
    {
    "height": "372201",
    "epoch": "1453",
    "epoch_num": "233",
    "epoch_base": 256,
    "timestamp": "1673335656",
    "nonce": "2193536342397137414",
    "target": "984802838",
    "reward": "0.925360",
    "target_sum": "89522651164"
    },
    {
    "height": "372201",
    "epoch": "1453",
    "epoch_num": "233",
    "epoch_base": 256,
    "timestamp": "1673335656",
    "nonce": "6558853428391499502",
    "target": "879949157",
    "reward": "0.826835",
    "target_sum": "89522651164"
    },
    {
    "height": "372199",
    "epoch": "1453",
    "epoch_num": "231",
    "epoch_base": 256,
    "timestamp": "1673335633",
    "nonce": "12513466918958750890",
    "target": "503439796",
    "reward": "0.362944",
    "target_sum": "98802618200"
    },
    {
    "height": "372196",
    "epoch": "1453",
    "epoch_num": "228",
    "epoch_base": 256,
    "timestamp": "1673335588",
    "nonce": "6183041265436703994",
    "target": "966546280",
    "reward": "0.494258",
    "target_sum": "205315773626"
    },
    {
    "height": "372195",
    "epoch": "1453",
    "epoch_num": "227",
    "epoch_base": 256,
    "timestamp": "1673335573",
    "nonce": "17430317352136271111",
    "target": "1557040796",
    "reward": "0.433205",
    "target_sum": "433485698705"
    },
    {
    "height": "372194",
    "epoch": "1453",
    "epoch_num": "226",
    "epoch_base": 256,
    "timestamp": "1673335563",
    "nonce": "8258764656576122725",
    "target": "5784445700",
    "reward": "5.817434",
    "target_sum": "76964411562"
    },
    {
    "height": "372190",
    "epoch": "1453",
    "epoch_num": "222",
    "epoch_base": 256,
    "timestamp": "1673335513",
    "nonce": "9235675647683207435",
    "target": "631394137",
    "reward": "0.278749",
    "target_sum": "152633467926"
    },
    {
    "height": "372183",
    "epoch": "1453",
    "epoch_num": "215",
    "epoch_base": 256,
    "timestamp": "1673335410",
    "nonce": "14592329930820666865",
    "target": "1167635393",
    "reward": "1.152251",
    "target_sum": "80636853733"
    },
    {
    "height": "372183",
    "epoch": "1453",
    "epoch_num": "215",
    "epoch_base": 256,
    "timestamp": "1673335410",
    "nonce": "1176084006732502352",
    "target": "771429216",
    "reward": "0.761265",
    "target_sum": "80636853733"
    },
    {
    "height": "372180",
    "epoch": "1453",
    "epoch_num": "212",
    "epoch_base": 256,
    "timestamp": "1673335373",
    "nonce": "16691122609012755342",
    "target": "545950647",
    "reward": "0.526026",
    "target_sum": "112029232476"
    },
    {
    "height": "372179",
    "epoch": "1453",
    "epoch_num": "211",
    "epoch_base": 256,
    "timestamp": "1673335359",
    "nonce": "9055340661262860526",
    "target": "2665195520",
    "reward": "2.251411",
    "target_sum": "79769578005"
    },
    {
    "height": "372179",
    "epoch": "1453",
    "epoch_num": "211",
    "epoch_base": 256,
    "timestamp": "1673335359",
    "nonce": "4275006642378258994",
    "target": "797308263",
    "reward": "0.673522",
    "target_sum": "79769578005"
    },
    {
    "height": "372179",
    "epoch": "1453",
    "epoch_num": "211",
    "epoch_base": 256,
    "timestamp": "1673335359",
    "nonce": "12905798942225828720",
    "target": "536776869",
    "reward": "0.453439",
    "target_sum": "79769578005"
    },
    {
    "height": "372177",
    "epoch": "1453",
    "epoch_num": "209",
    "epoch_base": 256,
    "timestamp": "1673335328",
    "nonce": "5982615259668409015",
    "target": "500892376",
    "reward": "0.370259",
    "target_sum": "99069203701"
    },
    {
    "height": "372175",
    "epoch": "1453",
    "epoch_num": "207",
    "epoch_base": 256,
    "timestamp": "1673335300",
    "nonce": "3543576076605339424",
    "target": "3094188450",
    "reward": "3.138845",
    "target_sum": "70216394475"
    },
    {
    "height": "372175",
    "epoch": "1453",
    "epoch_num": "207",
    "epoch_base": 256,
    "timestamp": "1673335300",
    "nonce": "12955252741231642094",
    "target": "1246621804",
    "reward": "1.264613",
    "target_sum": "70216394475"
    },
    {
    "height": "372175",
    "epoch": "1453",
    "epoch_num": "207",
    "epoch_base": 256,
    "timestamp": "1673335300",
    "nonce": "1647571467669221534",
    "target": "580978037",
    "reward": "0.589363",
    "target_sum": "70216394475"
    },
    {
    "height": "372173",
    "epoch": "1453",
    "epoch_num": "205",
    "epoch_base": 256,
    "timestamp": "1673335271",
    "nonce": "17523188700761909003",
    "target": "1077450807",
    "reward": "0.066735",
    "target_sum": "737940991852"
    },
    {
    "height": "372173",
    "epoch": "1453",
    "epoch_num": "205",
    "epoch_base": 256,
    "timestamp": "1673335271",
    "nonce": "11853342089226326483",
    "target": "479520441",
    "reward": "0.029700",
    "target_sum": "737940991852"
    },
    {
    "height": "372170",
    "epoch": "1453",
    "epoch_num": "202",
    "epoch_base": 256,
    "timestamp": "1673335226",
    "nonce": "3215037471877963733",
    "target": "1088616210",
    "reward": "1.794404",
    "target_sum": "61954123192"
    }
    ]
    }
    }
}
```

or

```json
    {
    "code": 200,
    "data": {
    "status": true,
    "type": "transaction",
    "data": {
    "data": {
    "transaction_type": "Execute",
    "transaction_id": "at1vpc95mvx5cl8dqgd4lkwlvf9y086qun07zkjgzc3udpu6yketqzsrkr0es",
    "block_height": "372208",
    "timestamp": "1673335740",
    "transition_id": "as1thektl67nta0h6vfv20dg00kjr50yddjl4wqqdfej62jgcxfmszqf3tfqz",
    "transition_subid": 372215,
    "program_id": "credits.aleo",
    "function_name": "transfer",
    "proof": "proof1qqqqzqqqqqqqqqqqhlstqa8v3fwfpml0ss7svmexkat4qttft3ylvtg8cj6agpsugkdp0t4wehuk55dmhwu2rqsm7ckgph8tzfgr6yz48d9punrad634j8x2g935sfn5ft9uhn22lmwhwddpr86x0eaupqmttqeh6tkqtvmaq90l2gq4lz7nfqnvk7x3hk26tv4u4fksnvv7l2mxwy5jtwh43d8chrhmgqedyd2fjkplhx82pu2jhqgpzjxndc7npng84umw8sdgcqjk5ffcpzawtqvknu4vpegznue697uu0xjum9l9hu9tksufzrvadsscqh4ccfcgl32s9qp94rj547uq7rvw6mcr9cegs0z9y22m2zlkh062vhpq884q0vqj9n8dwf9xjx5qs9twg95dye76um0hpanv8dguaa6dnym8xvr83axxcz3cz5qprtex9t9acdcuvm5p29082klw0nq8jqfghs8j0kj4vt079tday9h5l0cxtk2e0tkapaxcvwrxfjahgh4y7a5ysz7f2990mh4z5v5vlvzmy2qlz60ugjc0gv99pp9eevewrsn6xkyh0j8ptgwlnxsuk5n9wchrkql87qshk0xmeljvczzf2d5qu4qps9r5cs695t9agk726j4ngzhgf5eyhsz9zs2j0jz335vev3tquvymmqfrcmc8nxtpx7d3knmkmapgzwy50xdyx6g92fag90j7gf5cw6wmfmm4vg228cq0vkx3d26ayayu479rq799apvrc99063860pexqp9pcdtjxxk6k7naazjx94zhsrrfhv9p7uvs80m5kkufdrsamxxqlwvlmn3ef3y2zs3ruwqsxdfwtpxadrxxseezyms0nekwj36ac2q99le0jedclav8fqpzzqqv5n6ez09ntjt3ehcz6jt9nah0cfnhnsyll083y7cjmfa2mcqjrcqf99q7efuzkl54tntez2elp7kgacckupgvd3ewjvq8xerl54yg4aa9q8qc6an3h6p25pw7wg6s55lua4m9pc04sr0jfpymnuexg445c6ue3l3tp9gaqx2944snd3kj5f52sfcqy7ehae55rrqkdeyjfeg0extu639zfll9d2vxaurlr8jmfyhvsyqrna7k3jjfgsdtcfyakevpsf2vahrdc2pzc5mvar8mnfz307mxnqqsyqqqqqqqqqqqfze5z68e58lap5j45huu8t2v8pc462cp0jcuv86xuacpv7ut5069hce5cvuyp0y6tjnwg4au0xzgzqw29ldwt4d9jrf8hwwn6annjpnuqv3smjsujkrcw3htzs7xnsq2zqkwkc9tua32msrz7302278vchx0yxh7wymzs58arp5y3snqah64038qxxnyy8wkuy07xu902alu9qqqqql7y4u8",
    "tpk": "6928550651546109592424415191552104270118516249979809482045554329449988049311group",
    "tcm": "4578079719866394835554737280630319843809079065102585195464058784344291064316field",
    "fee": "0",
    "transaction_exec_id": 372215,
    "global_state_root": "ar1gvlga7tltv8wfuxjgyhkzwpse69k6eve6yjtlv979u6xprzzjurqjve2ed",
    "inclusion_proof": "proof1qqqqzqqqqqqqqqqqsja8vrn8dyz3nf0r4er9ssggwwlnk2x0ax39y5t72vyetdtffe6a0r03hjgfl2z9p46eh2u6c8xsqmskystpvdxfyj6qhmr54hcywc6s25sjl4975ygnfxm8mt7fqy0nzm70kfsn2hdh7xucutkc3z3fsqplr7q4660wyk5rpcec8x4rtgzjy4dmrpnyqlr88al37mncjh8d5qxd9qufqc6d3majfxgyhtdrgqqp084dje8xe7x6jhl8l4ss6sqqw9nw6ucq537cyrqlvjntjknzz4x85kt9hggy02pgmm39egtd8g4gr37mzc8q84ucl2lra3cjrrrp775xx93vwxwklyykk2xx8p78qus72u2yqwmlgjpzl4qmpa4y8svdsxrac4an9fftp6fgdghstxnmrp8mnghm6vvqyxz0yr4jnq8amesxydd37n8qqkqa0z6xlu7z0q5y4q9qa3an49m878mhjtx5kuday6urn45zfmacgshhf8uzgweyf83cuczaylud8uxx9fa2utfgapf877qgm5vdepl4jag7xqns97udpg659h6tlgp0qyuyajla8v6gnr7pa5zfual8q5d5ylsennfa0qgnd0gqz2l56km8mh755rpucg0x4nplpd23n58arx5e4ahcemyw9yadcp8e6k2fsy23lryyzkghmtfge6fsqj0u64jmmwzfmnz88de07trn6lx5djhj3m08m9uwaf0ja6cy2wf2nv4r3urqqccrc97k6yk0f9mnszlllp5rmd59597qegkykq7gzqgvkyz9zrymxsv5wfr3un2rvq7prvsexdl4cme7r7d5r3p66z2pjztral7z8vm95nargszz20hdpdqr6sslxm85dwt8yh2x2rvap6k0ulf0v43wlxqd0eh5xz3ugrr6lqq7ea98j039tdd98yyag2nl2hppldcnjh8kgwzjrnl5fmcx25te5qkx9twtfpatu4lpwdh0yzelslug8e4s3udn2y99s96szeeyxhg6qda9euy4232ffcpc4xqmpzj6cytjqk2x963ke2dseljtmwwt5ykqfcy27mdevyckrl5txsw2v2tulqmcyxptljas05vxwff9mp9jqhcz9s3gpcrk8t8ep7fjcy3k56cx09fca5v336zvc9x547ugrj2ejvpqyqqqqqqqqqqqca9dq64hc3fn29j5cdvrq5ku32jy3cx2y7zyex4x6jcz7hfrxawdkul4rtv65et5tyc9klnjl6dczqw59uu0ulh4adf78ngqjzhwayucmka9xn8zgkyun36j8eeqj4nezfj4c222rzdprhj6te2rj29ah8c35dqfxnhtaajtq0w43vka4eejh3sjv5maea5pkk87g8dxn2yygqqqqq46h79h",
    "transition": {
    "transition_id": "as1thektl67nta0h6vfv20dg00kjr50yddjl4wqqdfej62jgcxfmszqf3tfqz",
    "program_id": "credits.aleo",
    "function_name": "transfer",
    "proof": "proof1qqqqzqqqqqqqqqqqhlstqa8v3fwfpml0ss7svmexkat4qttft3ylvtg8cj6agpsugkdp0t4wehuk55dmhwu2rqsm7ckgph8tzfgr6yz48d9punrad634j8x2g935sfn5ft9uhn22lmwhwddpr86x0eaupqmttqeh6tkqtvmaq90l2gq4lz7nfqnvk7x3hk26tv4u4fksnvv7l2mxwy5jtwh43d8chrhmgqedyd2fjkplhx82pu2jhqgpzjxndc7npng84umw8sdgcqjk5ffcpzawtqvknu4vpegznue697uu0xjum9l9hu9tksufzrvadsscqh4ccfcgl32s9qp94rj547uq7rvw6mcr9cegs0z9y22m2zlkh062vhpq884q0vqj9n8dwf9xjx5qs9twg95dye76um0hpanv8dguaa6dnym8xvr83axxcz3cz5qprtex9t9acdcuvm5p29082klw0nq8jqfghs8j0kj4vt079tday9h5l0cxtk2e0tkapaxcvwrxfjahgh4y7a5ysz7f2990mh4z5v5vlvzmy2qlz60ugjc0gv99pp9eevewrsn6xkyh0j8ptgwlnxsuk5n9wchrkql87qshk0xmeljvczzf2d5qu4qps9r5cs695t9agk726j4ngzhgf5eyhsz9zs2j0jz335vev3tquvymmqfrcmc8nxtpx7d3knmkmapgzwy50xdyx6g92fag90j7gf5cw6wmfmm4vg228cq0vkx3d26ayayu479rq799apvrc99063860pexqp9pcdtjxxk6k7naazjx94zhsrrfhv9p7uvs80m5kkufdrsamxxqlwvlmn3ef3y2zs3ruwqsxdfwtpxadrxxseezyms0nekwj36ac2q99le0jedclav8fqpzzqqv5n6ez09ntjt3ehcz6jt9nah0cfnhnsyll083y7cjmfa2mcqjrcqf99q7efuzkl54tntez2elp7kgacckupgvd3ewjvq8xerl54yg4aa9q8qc6an3h6p25pw7wg6s55lua4m9pc04sr0jfpymnuexg445c6ue3l3tp9gaqx2944snd3kj5f52sfcqy7ehae55rrqkdeyjfeg0extu639zfll9d2vxaurlr8jmfyhvsyqrna7k3jjfgsdtcfyakevpsf2vahrdc2pzc5mvar8mnfz307mxnqqsyqqqqqqqqqqqfze5z68e58lap5j45huu8t2v8pc462cp0jcuv86xuacpv7ut5069hce5cvuyp0y6tjnwg4au0xzgzqw29ldwt4d9jrf8hwwn6annjpnuqv3smjsujkrcw3htzs7xnsq2zqkwkc9tua32msrz7302278vchx0yxh7wymzs58arp5y3snqah64038qxxnyy8wkuy07xu902alu9qqqqql7y4u8",
    "tpk": "6928550651546109592424415191552104270118516249979809482045554329449988049311group",
    "tcm": "4578079719866394835554737280630319843809079065102585195464058784344291064316field",
    "fee": "0"
    }
    },
    "function_call_input": [
    {
    "id": 1116642,
    "transition_id": 372215,
    "type": "Record",
    "data": {
    "id": 372214,
    "transition_input_id": 1116642,
    "serial_number": "6193200281341081867859123659836992608456242972524801826034705563577030708967field",
    "tag": "4347629828537231380939048172723657087510502296459077805316596261646964171486field",
    "index": 0
    }
    },
    {
    "id": 1116643,
    "transition_id": 372215,
    "type": "Private",
    "data": {
    "id": 744429,
    "transition_input_id": 1116643,
    "ciphertext_hash": "5890934381212633485237200567365204365743043181627529467122180330542008166588field",
    "ciphertext": "ciphertext1qgq80thu9myzmsynrpcys09sd52c50yerwv6duukxkcmmvxcr59tupxns3zjn3avxalqxeawekqu6290lxewk7auflnr7fr4mq8vayqxqg0tkjpv",
    "index": 1
    }
    },
    {
    "id": 1116644,
    "transition_id": 372215,
    "type": "Private",
    "data": {
    "id": 744430,
    "transition_input_id": 1116644,
    "ciphertext_hash": "3502960312088644099944307019061775164231187447333628165665730923111613579022field",
    "ciphertext": "ciphertext1qyqgzkgyrthy850v24s8t9q4flqmwk6nzr4fm50gtq2je5m2k99qvpce5c5yn",
    "index": 2
    }
    }
    ],
    "function_call_output": [
    {
    "id": 744428,
    "transition_id": 372215,
    "type": "Record",
    "data": {
    "id": 744428,
    "transition_output_id": 744428,
    "commitment": "6601270768830113426397823020461716526007597927357720773772965136036871361220field",
    "checksum": "7178552183796192098014464263177357637606944312071635897705060964785409358238field",
    "record_ciphertext": "record1qyqsq7zfzyzkgwm62rn3hhtd4y3zte7gtgxeuu54ah0gwqcr5lhlm3qsqyqspgl27qrsps5c73mxrm82gdd7xhaervyslz55n94pa3k55xsg7hcsqzuhvf0e409cjzwrawj47jhh3dxq2cjraceer7tjewf5f8crge6scf594fh",
    "index": 0
    }
    },
    {
    "id": 744429,
    "transition_id": 372215,
    "type": "Record",
    "data": {
    "id": 744429,
    "transition_output_id": 744429,
    "commitment": "1532693792142829393095203544035233378463692255623148685659136228018839727179field",
    "checksum": "6927226496264270796399308315745821308639037435636400431819444357456702702557field",
    "record_ciphertext": "record1qyqspvzlwz20259t27h3rmcrdzg3n0u7xsc82l8z4kc672t7fhfpryqtqyqsqvgmpj4dkfhyce0t29r3qza4n6v8evvqlxj2cgsdsdzux2sf6cqsqr8x9lcfgyjd5cxa8su6vk7uawpasf6x4rrjtcs3rgmj332sk56pznnsphv",
    "index": 1
    }
    }
    ]
    }
    }
}
```

Example :&#x20;

```
https://api.aleoscan.info/block/list?pageSize=1&pageNum=1
```

