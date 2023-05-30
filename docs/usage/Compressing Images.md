---
sidebar_label: 'Compressing Images'
---

To compress an image, you can send a POST request to the api/image/compress endpoint with an image file and the desired quality parameter.

- Image: The image file to resize.
- Quality: The desired quality of the compressed image.

```bash
curl -X POST -F "image=@/path/to/image.jpg" -F "quality=50" http://localhost:5000/api/v1/compress
```