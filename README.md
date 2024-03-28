QR Code Generator
=================

Assignment Summary
-------------------

With the help of Python and Docker, this assignment creates a QR code generator that will redirect the user to a GitHub homepage when they scan it using the camera.

Instructions
---------------


1.  Clone the Repository :

    `git clone https://github.com/etikalarahul/Assignment7`

2.  Copy `.env.sample` file to `.env` file.

3.  Open the project directory and run the following command to create the Docker container:

    `docker build -t qr-code-generator .`

4.  Once the image has been created, launch the container using:

    `docker run --name qr-generator -d qr-code-generator`
    
### Logging

Below is a sceenshot of log message:

![Log message](./Screenshot_log.png)

### QR Code
 Scanning the QR code below will redirect you to the `https://github.com/etikalarahul/`.

![QR Code](qr_code/qr_code_20240327223028.png)



