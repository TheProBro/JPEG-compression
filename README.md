# JPEG and LZW Compression
JPEG compression is a lossy algorithm which utilizes various techniques such as discrete cosine transform (DCT), quantization, and Huffman coding. During compression, the image is divided into small blocks, and the DCT is applied to each block to convert it from the spatial domain to the frequency domain. The resulting frequency coefficients are then quantized and encoded using Huffman coding. This process significantly reduces the amount of data required to represent the image.


LZW algorithm is a lossless algorithm which works by building a dictionary of frequently occurring patterns or sequences of data. It scans the input data and replaces repetitive sequences with references to the dictionary. This allows for efficient representation of data by replacing long sequences with shorter codes.

## Technologies Used
OpenCV library of Python was used extensively to make this project possible.

## Installation
To use this project, you need to have Python installed on your system. Follow these steps to get started:
1. Clone the repository: 
  ~~~~ 
  git clone https://github.com/TheProBro/JPEG-compression.git
  ~~~~
2. Install the following libraries: open-cv, numpy, matplotlib
~~~~
pip install opencv-python numpy matplotlib
~~~~

## Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. When contributing, please provide clear descriptions of the changes made and any relevant information or context.
