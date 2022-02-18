# Format
Best hero image format is: 
- Fullscreen desktop: 16:9, 1280x720 or 1600x1200 
- Fullscreen mobile: 800x1200 
- Banner desktop: 1600x500 Pixel

The image schould be smaller than 400kb. 

# Tooling
Resize image to exactly 1200 pixel height, keeping geometry and 
compress by reducing to a quality of 40
~~~
convert $inputfile -auto-orient -resize x1200 -quality 40 $outputfile
~~~

