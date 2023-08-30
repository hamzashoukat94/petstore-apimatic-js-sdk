
# Order

## Structure

`Order`

## Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `bigint \| undefined` | Optional | - |
| `petId` | `bigint \| undefined` | Optional | - |
| `quantity` | `number \| undefined` | Optional | - |
| `shipDate` | `string \| undefined` | Optional | - |
| `status` | [`Status1Enum \| undefined`](../../doc/models/status-1-enum.md) | Optional | Order Status |
| `complete` | `boolean \| undefined` | Optional | - |

## Example (as JSON)

```json
{
  "id": 112,
  "petId": 152,
  "quantity": 68,
  "shipDate": "2016-03-13T12:52:32.123Z",
  "status": "delivered"
}
```

