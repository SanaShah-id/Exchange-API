# Exchange-API

# Retrieve markets and current prices.

## Resource URL
https://api.blockchain.com/v3/exchange/l2/BTC-USD

## Resource description
Level 2 Order Book data is available through the l2 channel. Each entry in bids and asks arrays is a price level, along with its price (px), quantity (qty) and number of orders (num) attributes.

## Endpoints and methods
[GET]  exchange/l2/BTC-USD
through the 12 channel.

## Parameters

| Parameter | Required/optional | Description | Type |
| ------ | ------ | ------ | ------ |
| BTC-USD | Required | Bitcoin to Dollar pair - BTC is the base currency and the USD is the counter currency | Integer | 

## Request example

##_Curl_
curl -X GET "https://api.blockchain.com/v3/exchange/l2/BTC-USD" -H  "accept: application/json"

## Response body

```json
{
  "symbol": "BTC-USD",
  "bids": [
    {
      "px": 26603.15,
      "qty": 0.18868212,
      "num": 1
    },
    {
      "px": 26602.45,
      "qty": 0.03796643,
      "num": 1
    },
    {
      "px": 26601.46,
      "qty": 0.34171057,
      "num": 1
    },
    {
      "px": 26600.13,
      "qty": 0.56954609,
      "num": 1
    },
    {
      "px": 26598.8,
      "qty": 0.94929095,
      "num": 1
    },
    {
      "px": 26597.47,
      "qty": 1.89867683,
      "num": 1
    },
    {
      "px": 25402.9,
      "qty": 0.2,
      "num": 1
    },
    {
      "px": 25400,
      "qty": 0.00204937,
      "num": 1
    },
    {
      "px": 25000,
      "qty": 0.01492352,
      "num": 2
    },
    {
      "px": 24800,
      "qty": 0.00051,
      "num": 1
    },
    {
      "px": 24500,
      "qty": 1.0026,
      "num": 3
    },
    {
      "px": 24000,
      "qty": 0.00267671,
      "num": 2
    },
    {
      "px": 23500,
      "qty": 0.01212,
      "num": 2
    },
    {
      "px": 23200,
      "qty": 5.87527923,
      "num": 1
    },
    {
      "px": 23189,
      "qty": 0.00662466,
      "num": 1
    },
    {
      "px": 23100,
      "qty": 0.00051,
      "num": 1
    },
    {
      "px": 23000,
      "qty": 0.00321613,
      "num": 2
    },
    {
      "px": 22950,
      "qty": 0.00051,
      "num": 1
    },
    {
      "px": 22850,
      "qty": 1.00163748,
      "num": 1
    },
    {
      "px": 22500,
      "qty": 0.0614,
      "num": 1
    },
    {
      "px": 22101,
      "qty": 1.04550076,
      "num": 1
    },
    {
      "px": 21200,
      "qty": 0.01,
      "num": 1
    },
    {
      "px": 20300,
      "qty": 0.16784887,
      "num": 2
    },
    {
      "px": 20250,
      "qty": 0.11943244,
      "num": 1
    },
    {
      "px": 20150,
      "qty": 0.00076399,
      "num": 1
    },
    {
      "px": 20100,
      "qty": 0.00051,
      "num": 1
    },
    {
      "px": 20000,
      "qty": 0.76551616,
      "num": 1
    },
    {
      "px": 19665,
      "qty": 0.00096319,
      "num": 1
    },
    {
      "px": 19500,
      "qty": 2.00766214,
      "num": 2
    },
    {
      "px": 19302,
      "qty": 0.00439903,
      "num": 1
    },
    {
      "px": 18902,
      "qty": 0.00898422,
      "num": 1
    },
    {
      "px": 18702,
      "qty": 0.00454015,
      "num": 1
    },
    {
      "px": 17727.7,
      "qty": 0.294596,
      "num": 1
    },
    {
      "px": 17200,
      "qty": 0.0008,
      "num": 1
    },
    {
      "px": 16200,
      "qty": 0.00062004,
      "num": 1
    },
    {
      "px": 15250,
      "qty": 0.15859063,
      "num": 1
    },
    {
      "px": 14185,
      "qty": 1.23017521,
      "num": 1
    },
    {
      "px": 11362,
      "qty": 1.34878668,
      "num": 1
    },
    {
      "px": 3500,
      "qty": 0.18753069,
      "num": 1
    },
    {
      "px": 1200,
      "qty": 0.22284197,
      "num": 1
    },
    {
      "px": 75,
      "qty": 4.412,
      "num": 1
    },
    {
      "px": 60,
      "qty": 0.15,
      "num": 1
    },
    {
      "px": 30,
      "qty": 0.25,
      "num": 1
    },
    {
      "px": 8,
      "qty": 0.00098921,
      "num": 1
    },
    {
      "px": 4.44,
      "qty": 7.39733902,
      "num": 2
    },
    {
      "px": 1.8,
      "qty": 7.45715496,
      "num": 1
    },
    {
      "px": 1,
      "qty": 0.69,
      "num": 1
    },
    {
      "px": 0.67,
      "qty": 1.01088184,
      "num": 1
    }
  ],
  "asks": [
    {
      "px": 26605.64,
      "qty": 0.03796188,
      "num": 1
    },
    {
      "px": 26606.64,
      "qty": 0.34164404,
      "num": 1
    },
    {
      "px": 26607.97,
      "qty": 0.56937827,
      "num": 1
    },
    {
      "px": 26609.3,
      "qty": 0.94891636,
      "num": 1
    },
    {
      "px": 26610.63,
      "qty": 1.89773786,
      "num": 1
    },
    {
      "px": 27399.99,
      "qty": 1.33277323,
      "num": 1
    },
    {
      "px": 27400,
      "qty": 0.56474721,
      "num": 1
    },
    {
      "px": 27500,
      "qty": 0.035,
      "num": 1
    },
    {
      "px": 28000,
      "qty": 0.4,
      "num": 1
    },
    {
      "px": 28450.33,
      "qty": 0.00055713,
      "num": 1
    },
    {
      "px": 28725.21,
      "qty": 0.00055713,
      "num": 1
    },
    {
      "px": 28800,
      "qty": 0.00139104,
      "num": 1
    },
    {
      "px": 29000,
      "qty": 0.00601544,
      "num": 2
    },
    {
      "px": 29137.54,
      "qty": 0.00055713,
      "num": 1
    },
    {
      "px": 29356,
      "qty": 0.38747427,
      "num": 1
    },
    {
      "px": 29500,
      "qty": 0.0115,
      "num": 1
    },
    {
      "px": 29687.31,
      "qty": 0.00055713,
      "num": 1
    },
    {
      "px": 29850,
      "qty": 0.01152369,
      "num": 2
    },
    {
      "px": 30000,
      "qty": 0.12110141,
      "num": 4
    },
    {
      "px": 30298.99,
      "qty": 0.00506853,
      "num": 1
    },
    {
      "px": 30413,
      "qty": 0.00132171,
      "num": 1
    },
    {
      "px": 31000,
      "qty": 1.2216185,
      "num": 3
    },
    {
      "px": 31233,
      "qty": 0.0013,
      "num": 1
    },
    {
      "px": 31500,
      "qty": 0.23760456,
      "num": 3
    },
    {
      "px": 31501.37,
      "qty": 0.02862438,
      "num": 1
    },
    {
      "px": 31785.03,
      "qty": 0.07532276,
      "num": 1
    },
    {
      "px": 32000,
      "qty": 0.03088302,
      "num": 1
    },
    {
      "px": 32465,
      "qty": 0.02821033,
      "num": 1
    },
    {
      "px": 32500,
      "qty": 0.22644795,
      "num": 1
    },
    {
      "px": 34500,
      "qty": 0.1,
      "num": 1
    },
    {
      "px": 35000,
      "qty": 0.00119092,
      "num": 1
    },
    {
      "px": 36501,
      "qty": 0.092434,
      "num": 1
    },
    {
      "px": 40000,
      "qty": 0.03843818,
      "num": 1
    },
    {
      "px": 50468.41,
      "qty": 0.00055713,
      "num": 1
    },
    {
      "px": 60000,
      "qty": 0.19842298,
      "num": 1
    },
    {
      "px": 75000,
      "qty": 0.3001255,
      "num": 1
    },
    {
      "px": 100000,
      "qty": 0.00067163,
      "num": 1
    },
    {
      "px": 7848964,
      "qty": 0.04662908,
      "num": 1
    }
  ]
}
```
