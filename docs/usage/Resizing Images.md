---
sidebar_label: 'Resizing Images'
---
To resize an image, you need to send a POST request to the api/image/resize endpoint of your server with the following parameters:

- image: The image file to resize.
- width: The desired width of the resized image.
- height: The desired height of the resized image.

```bash
curl -X POST -F "image=@/path/to/image.jpg" -F "width=500" -F "height=500" http://localhost:5000/api/v1/resize
```