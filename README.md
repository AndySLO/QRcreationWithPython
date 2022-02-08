# QRcreationWithPython


QR Code Generation using Python

QR meaning Quick Response Code. These codes may look simple but they are capable of storing lots of data.
For QR code generation using python, we should use a python module called QRcode.

Link: https://pypi.org/project/qrcode/

Command to install it: pip install qrcode

We will generate a QR Code for encoding the LinkedIn link and we will also explore more. QR code generation is simple. Just pass the text, link, or any content to ‘make’ function of QRcode module.

Necessary to mention is that it’s not necessary that you always have to give a link to qrcode.make() function. We can provide simple text as well.

You can encode: Slovenia is a country with many places to visit. I love Slovenia.


If we want to read this QR Code i.e., now we want to know what was encoded in the QR Code without scanning it. For this, we will use OpenCV. 
OpenCV is a library of programming functions focused on real-time computer vision tasks.

Install opencv: pip install opencv-python

The code is attached.
