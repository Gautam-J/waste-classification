# FOR TEMP PURPOSES ONLY

# CREATE NEW REPO DURING HACKATHON

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
