---
sidebar_label: 'Converting Image'
---

To convert an image to a specific format, you can send a POST request to the api/v1/convert endpoint with an image file and the desired extension parameter.

#### Accepted extensions: 
- jpeg
- png
- webp
- tiff
- avif
- heif
- raw

```bash
curl -X POST -F "image=@/path/to/image.jpg" -F "extension=webp" http://localhost:5000/api/v1convert
```