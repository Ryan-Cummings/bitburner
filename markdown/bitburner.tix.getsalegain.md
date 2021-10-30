<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [TIX](./bitburner.tix.md) &gt; [getSaleGain](./bitburner.tix.getsalegain.md)

## TIX.getSaleGain() method

Calculates and returns how much you would gain from selling a given number of shares of a stock. This takes into account spread, large transactions influencing the price of the stock and commission fees.

<b>Signature:</b>

```typescript
getSaleGain(sym: StockSymbol, shares: number, posType: OrderPos): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  sym | [StockSymbol](./bitburner.stocksymbol.md) | Stock symbol. |
|  shares | number | Number of shares to sell. |
|  posType | [OrderPos](./bitburner.orderpos.md) | Specifies whether the order is a “Long” or “Short” position. |

<b>Returns:</b>

number

Gain from selling a given number of shares of a stock.

## Remarks

2 GB
