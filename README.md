# Digital_Image_Processing_convert-one-space-to-another.
# AIM: WAP to convert one space to another
# Requirements: setting up all the libraries after installing Python.

# Source code: 

# Converting from one color space into another


im = imread("../images/parrot.png")

im_hsv = color.rgb2hsv(im)

plt.gray()

plt.figure(figsize=(10,8))

plt.subplot(221), plt.imshow(im_hsv[...,0]), plt.title('h', size=20),

plt.axis('off')

plt.subplot(222), plt.imshow(im_hsv[...,1]), plt.title('s', size=20),

plt.axis('off')

plt.subplot(223), plt.imshow(im_hsv[...,2]), plt.title('v', size=20),

plt.axis('off')

plt.subplot(224), plt.axis('off')

plt.show()

<matplotlib.figure.Figure at 0x24b3a51fb00>
