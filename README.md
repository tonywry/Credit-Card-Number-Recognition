## Credit-Card-Number-Recognition
OpenCV to identify Credit Card Number from a picture of Card

#### Method
Code in this project take reference from the link below. The refenrence code is only able to identify the Credit Card of VISA/Master which consists 16 digits in 4 groups of numbers. This project modified the code of it to make it capable of reading other credit card format as below.

Steps of identifying the number:
1. Detecting the four groups of four numbers on the credit card via various image processing techniques, including morphological operations, thresholding, and contour extraction.
2. Extracting each of the individual digits from the four groupings, leading to 16 digits that need to be classified.
3. Applying template matching to each digit by comparing it to the OCR-A font to obtain our digit classification.
4. Examining the first digit of the credit card number to determine the issuing company.

#### Result



#### Reference: 
https://www.pyimagesearch.com/2017/07/17/credit-card-ocr-with-opencv-and-python/






