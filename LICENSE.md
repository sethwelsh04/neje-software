ser.write(im.getdata())
[...]
im = Image.open( name_image ).convert("1")
im = im.resize((512, 512))
[...]
ser.write(im.getdata())
