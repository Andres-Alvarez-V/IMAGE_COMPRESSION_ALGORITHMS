# IMAGE COMPRESSION ALGORITHMS

### Seam Carving

Seam carving is an algorithm for content-aware image
resizing. It functions by establishing a number of seams
(paths of least importance) in an image and automatically
removes seams to reduce image size or inserts seams to
extend it. The process to transform the image is: 1. It start
reading an image. 2. It calculates the weight/density/energy
of each pixel; this is done by an algorithm called gradient
magnitude. 3. From the energy, make a list of seams. Seams
are ranked by energy, with low energy seams being of least
importance to the content of the image. 4. It removes low-
energy seams as needed 5. It returns the image transformed.

**Example:**

[![seam_carving](https://github.com/vivianhylee/seam-carving/raw/master/example/image05_video.gif "seam_carving")](https://github.com/vivianhylee/seam-carving/raw/master/example/image05_video.gif "seam_carving")


------------

###Huffman Algorithm

The Huffman algorithm used to compress data is based on
binary trees. Mostly used to compress files where the
frequency of appearance of each symbol is known. The
main idea of the algorithm is to calculate the appearances of
each symbol and based on this generate its respective
representation in binaries.
Main steps:
1.Create a Huffman tree based on the read file. 2. Go
through the tree and assign the corresponding codes. 3.
Save the symbol and its code in a table.
[![Huffman tree](https://cgi.luddy.indiana.edu/~yye/c343-2019/images/Huffman-tree-Fig5.24.png "Huffman tree")](https://cgi.luddy.indiana.edu/~yye/c343-2019/images/Huffman-tree-Fig5.24.png "Huffman tree")