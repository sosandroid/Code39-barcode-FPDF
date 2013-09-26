Code39-barcode-FPDF
===================

PHP class to draw Code39 bar codes in PDF files using FPDF library
This class supports both standard and extended Code 39 barcodes. The extended mode provides access to the full ASCII range (from 0 to 127). The class also gives the possibility to add a checksum.

## Usage


Code39(float x, float y, string code [, boolean ext [, boolean cks [, float w [, float h [, boolean wide]]]]])

x: abscissa
y: ordinate
code: barcode value
ext: indicates if extended mode must be used (true by default)
cks: indicates if a checksum must be appended (false by default)
w: width of a narrow bar (0.4 by default)
h: height of bars (20 by default)
wide: indicates if ratio between wide and narrow bars is high; if yes, ratio is 3, if no, it's 2 (true by default) 
