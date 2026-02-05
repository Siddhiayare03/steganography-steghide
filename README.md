# Image Steganography using Steghide

## Aim
To perform image steganography by embedding a secret text file into an image using Steghide.

## Tool Used
- Steghide (Windows)

## Commands Used

### Embed data into image
.\steghide.exe embed -cf cover.jpg -ef secret.txt

### Extract hidden data
.\steghide.exe extract -sf cover.jpg

## Result
The secret text file was successfully embedded into the image and extracted back using the correct passphrase.
