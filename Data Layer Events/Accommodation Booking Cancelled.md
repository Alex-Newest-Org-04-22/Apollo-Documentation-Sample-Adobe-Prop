# Accommodation Booking Cancelled

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Accommodation Booking Cancelled",
    "booking": {
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                }
            }
        ]
    },
    "transaction": {
        "item": [
            {
                "productInfo": {
                    "productLine": "<productLine>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|booking.roomList[n].location.locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
|transaction.item[n].productInfo.productLine|string|Describes the product Line of a product. |Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||




