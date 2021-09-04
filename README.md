# Graduation Research 1 Report
I apply UNet and SINet in a image segmentation problem - remove background from a human portrait. It is a web application which user can upload an image, select a segmentation model and background color. After a few seconds, a new image will be generated with its original background replaced by the selected color. This application is suitable for creating ID card's image or simply used to test the accuracy of my segmentation models.

## Local testing
Require Python 3
- Download ```Nukki``` folder from ```https://drive.google.com/drive/folders/1rM5A1IXpXXK2OUT9r0CJIyYAg1YlMtPg```
- Install requirements:
    ```pip install -r requirements.txt```
- Run:
    ```python server.py```
- Socket server and UI now available at localhost:8000
