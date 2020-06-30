# StudiOCR
StudiOCR is an application to index notes and make them searchable by using OCR.

- Select .JPG or .PNG files to create a document
- Search through a document to see if it has any matching text

# Main Window 

- Click the Add New Document button to open the add new document window interface
- Enable remove mode to switch to removing existing documents instead
- Search for a document by name by typing in the search bar with the DOC bullet selected
- Search for a document by matching OCR text by typing in the search bar with the OCR bullet selected  

## Add New Document Window
- Choose .JPG or .PNG files to be processed by OCR into a document in the database
- Input the document name 
- Select the processing model you wish to use: Best (for accuracy) or Fast (for speed)
- Select whether you wish to do image preprocessing: convert to grayscale and increase text contrast 
- PSM Number:

PSM Number | Value
------------ | -------------
3 | Fully automatic page segmentation, but no OSD. (Default)
4 | Assume a single column of text of variable sizes.
5 | Assume a single uniform block of vertically aligned text.
6 | Assume a single uniform block of text.
7 | Treat the image as a single text line.
8 | Treat the image as a single word.
9 | Treat the image as a single word in a circle.
10 | Treat the image as a single character.
11 | Sparse text. Find as much text as possible in no particular order.
12 | Sparse text with OSD.
13 | Raw line. Treat the image as a single text line, bypassing hacks that are Tesseract-specific.




