# pdfcrop
Crops the pdf as per the box defined by absolute x1, x2, y1, y2 co-ordinates

## Note
x1, x2, y1, y2 are defined in cartesian system with bottom left corner of the pdf page as the origin.

# Warning
If you use ghostscript to crop pdf file, you lose the OCR i.e., search functionality in the pdf.

I use this for cropping the plots properly. However, I have used this successfully in past to scrape data from pdf files by cropping them using pdfcrop followed by using pypdfcrop (https://pypi.python.org/pypi/pypdfocr) to reconstruct the OCR data.

Cheers!
