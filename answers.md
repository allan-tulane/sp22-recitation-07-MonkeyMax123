# CMPS 2200 Recitation 7
## Answers

**Name:**
Max Curl and Mikey Sison


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

| File         | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length |
|--------------|---------------------|----------------|--------------------------|
| f1.txt       | 1340                | 826            | 0.616                    |
| alice29.txt  | 1039367             | 676374         | 0.651                    | 
| asyoulik.txt | 876253              | 606448         | 0.692                    | 
| grammar.lsp  | 26047               | 17356          | 0.666                    | 
| fields.c     | 78050               | 56206          | 0.720                    | 
|              |                     |                | avg: 0.669               |                               

The consistent trend is that the huffman encoding is always smaller than the fixed length coding and on average it is about 2/3 the size.


- **e.**

The expected cost for each letter is consistent across all documents given that the frequencies are all equal.  For example, if we used every letter in the English alphabet then the encoding would either be 4 or 5 bits.  Regardless of the frequencies though the encoding remains the same.  The total cost of the document would still be variable based on the frequencies of each letter.

