# singular-value-decomposition-image-compression

Images contain data. They are comprised of pixels on the screen and are a combination of red, green and blue on a scale from 0-255. Human eyes see many colors, but in fact, a combination of red, blue and green is what the computer reads so that it can produce a color image on screen. As such, images can be written as a matrix of numbers from 0-255 but in 3 dimensions. As you can imagine, an image can hold a significant amount of storage memory. Because of this, we can use dimension reduction techniques, primarily Singlar Value Decomposition SVD from Linear Algebra, to reduce the dimensionality of the image and then output an image that (from human's perspective) looks qualitatively similar while significantly reducing the storage memory from the orginal size.

The Notebook will explore the reduction of singular values based on the user choice and output:

-a reduced dimension color image

-an output ratio that demonstrates the reduction of storage size from the original

-a compression ratio

-an error calculated from the original matrix and the truncated matrix of compressed image
