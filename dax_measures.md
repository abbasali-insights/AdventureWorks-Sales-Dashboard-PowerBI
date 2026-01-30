# Key DAX Measures

Below are examples of measures typically used in this dashboard:

## Total Sales
```DAX
Total Sales = SUM(Sales[SalesAmount])
```

## Total Profit
```DAX
Total Profit = SUM(Sales[Profit])
```

## Profit Margin %
```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

## Total Returns
```DAX
Total Returns = SUM(Returns[ReturnQuantity])
```
