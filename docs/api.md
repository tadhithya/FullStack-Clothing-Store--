# API Documentation

## Get Products

GET /api/products

### Response

```json
[
  {
    "name": "T-Shirt",
    "price": 499
  }
]
```

---

## Add Product

POST /api/products

### Request

```json
{
  "name": "Hoodie",
  "price": 999
}
```

---

## Create Order

POST /api/orders

### Request

```json
{
  "userId": "123",
  "products": []
}
```
