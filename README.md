## receipts-crunching

### initial notes
* Wow, the raw tools out there are amazing
  * tesseract is so cool (https://github.com/tesseract-ocr/tesseract ) 
* I have been using Dropbox to scan receipts and they come out very nicely contrast adjusted
* Although my receipts are all `.pdf` and *tesseract* likes `.png`,  `pdftoppm` nicely extracts the raw image from `.pdf`s which dropbox produces.
  * But now maybe I'll reconsider using `png`.
* There is some line item parsing work that would be needed to make this pipeline useful.


