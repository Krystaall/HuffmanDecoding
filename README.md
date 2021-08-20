# HuffmanDecoding
Huffman coding assigns variable length codewords to fixed length input characters based on their frequencies. More frequent characters are assigned shorter codewords and less frequent characters are assigned longer codewords. All edges along the path to a character contain a code digit. If they are on the left side of the tree, they will be a 0 (zero). If on the right, they'll be a 1 (one). Only the leaves will contain a letter and its frequency count. All other nodes will contain a null instead of a character, and the count of the frequency of all of it and its descendant characters.


Function Description

Complete the function decode_huff in the editor below. It must return the decoded string.
decode_huff has the following parameters:
root: a reference to the root node of the Huffman tree
s: a Huffman encoded string
