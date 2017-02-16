# Pulling-Images-from-FTP-location
Script to copy images from origin to target path.  When an image is created in target path, the creation date of this image is the creation date of the origin directory. This is because if exists a new folder in the origin path, all photos has highest priority to copy in the target path.  For check if one image on target path has a new image to replace it, get the last modified date of the target image and compare with the creation date of origin directory. If the directory creation date is greater than the last modified date of image, replace the image.