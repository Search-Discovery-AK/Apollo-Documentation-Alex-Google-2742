# Back-End Order Import

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "backend_order_import",
  "apollo_event": "Back-End Order Import",
    "event_data": {
        "backend_orders": "<backend_orders>",
        "backend_quantity": "<backend_quantity>",
        "backend_value": "<backend_value>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|backend_orders|string|Indicates the sequence of payment application within a transaction||||||||
|backend_quantity|string|Captures a unique payment ID for a transaction.||||||||
|backend_value|string|Captures the payment methods used for a transaction \(i.e. credit card, Visa, MasterCard, Amex, Paypal, purchase order, etc\).||||||||




