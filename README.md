# What's Pix?

Pix is an image hosting service with no size limitation and does not degrade image quality. Entirely secured by [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) and [PBKDF2](https://tools.ietf.org/html/rfc2898#section-5.2), the images sent are therefore only visible to those who have the full link. It is not possible to extract images from the server database.
Pix removes [EXIF](https://en.wikipedia.org/wiki/Exif) metadata from the sent images.
The source code is royalty-free and available at this [address](https://cgit.serveur.io/cgit.cgi/pix/).

So since I like this service and I didn't find a script to use this service with ShareX I decided to do it myself.

# How to use it

Download this [file](https://raw.githubusercontent.com/binksxela/pix-sharex/master/pix.sxcu).
Then open ShareX, go to `Destinations` then `Destination Settings` then scroll all the way down and click on `Custom Online Services` then click on `Import from File` and choose the file `pix.sxcu` and it's done!