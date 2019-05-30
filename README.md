# Hexcolor
A simple commandline color picker for Xorg using bash.

## How to use
When running hexcolor the cursor will change. After clicking a place on the screen the hex color code for the pixel where the mouse was will be returned.

Using this script will look something like this:
```bash
wouter@wouter-pc:~/Sources/hexcolor$ ./hexcolor 
#2DC450
```
The resulting color code can be used for web development or other purposes.

## Dependencies
The following dependencies will need to be installed to be able to use this script:
- Image Magick
- X11 Utils
- xdotool

In Ubuntu/Debian they can be installed with the following command:
```bash
apt-get install imagemagick x11-utils xdotool
```

