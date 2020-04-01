# BookUp
Take a picture of a book shelf and get an organized list of the books on it.


## Tools Brainstorm

### Book APIs
- [Google Books API](https://www.programmableweb.com/api/google-books-rest-api-v1): Search books with string, retrieve organized book info
- [Goodreads API](https://www.programmableweb.com/api/goodreads-feed-api): Can be used for book reviews as an added feature

### Computer Vision Tools for OCR
The challenge of extracting text from images of documents has traditionally been referred to as Optical Character Recognition (OCR). This term may be useful when researching for this project :) Also, here's an [interesting article](https://medium.com/capital-one-tech/learning-to-read-computer-vision-methods-for-extracting-text-from-images-2ffcdae11594).

- Tesseract
  - python, javascript
  - may not work with low contrast images
  - [review with examples](https://medium.com/datadriveninvestor/review-for-tesseract-and-kraken-ocr-for-text-recognition-2e63c2adedd0)
  - [github](https://github.com/naptha/tesseract.js)
- OpenCV
  - C++, python
  - [review with examples](https://www.learnopencv.com/deep-learning-based-text-detection-using-opencv-c-python/)
  - [about rotated text](https://github.com/Hellowlol/opencv-text-detection)
  - [helpful youtube tutorial](https://www.youtube.com/watch?v=nmDiZGx5mqU) which combines opencv with tesseract
- GoogleVision
- AWS Textract
- Azure OCR
- Dropbox
- MarkRCNN (we may need this one since our images will be highly unstructured)
