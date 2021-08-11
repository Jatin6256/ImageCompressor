# ImageCompressor

It is image compressor that will compress image by quantifying colors using k-means clustering algorithm. It shows example by compressing tiger.png.
Even decompressed image from compressed image has smaller size than original image, This is because decompressed image use fewer color(only 64 colors in our example) 
than original image.
<br>
original image -> (tiger.png) = 807 KB
<br>
Compressed image size -> ( codebook.npy + compressed_tiger.png) = 208 KB
<br>
decompressed image -> (decompressed_image.png) = 368 KB
<br>


<img src ="https://github.com/Jatin6256/ImageCompressor/blob/master/Screenshot.png">
