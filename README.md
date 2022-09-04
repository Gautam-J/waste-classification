Classification of waste using MobileNetV3 small, fine-tuned on imagenet weights.

7 Categories:

-   cardboard
-   e-waste
-   glass
-   medical
-   metal
-   paper
-   plastic

Model exposed through API written in Flask.

## How to run

- `pip install -r requirements.txt`
- `python app.py`

POST - `/predict`

Body

```json
{
    "img": "Image File"
}
```

Response

```json
{
    "confidence": 99.87,
    "label": "plastic"
}
```
