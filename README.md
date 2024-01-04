Django-Image-Uploader-Website


In This Project  the two model fields that allow the user to upload the images and files. These fields are FileField and ImageField; basically ImageField is a specialized version of FileField that uses Pillow to confirm that file is an image.
Django provides the simple interface to perform image or file uploading. We just need to do some configuration and define an ImageField in the model form's field. We can also upload any file (.xml, .pdf, .word, .etc) by following the same procedure, but we will need to convert ImageField to FileField in the model's field.


 
