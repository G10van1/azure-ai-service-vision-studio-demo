[\[English\]](#Introduction) [\[Português\]](#READMEP.md)
_______________________________________________________________________________________________________________________________________
## Introduction
We tested some of the related services in Azure Vision Studio. Some images were used to generate the result according to the tables shown in each functionality test.

## FACE

Detect the location of one or more human faces in images, along with attributes such as pose, facial mask, and facial landmarks.

| Image                                      | Result                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image1.jpg)         | [Attributes detected](Output/detectedAtributesImage1.txt)         | [JSON](Output/detectedAtributesImage1.json)         |
| ![Image](Input/image2.jpg)         | [Attributes detected](Output/detectedAtributesImage2.txt)         | [JSON](Output/detectedAtributesImage2.json)         |
| ![Image](Input/image3.jpg)         | [Attributes detected](Output/detectedAtributesImage3.txt)         | [JSON](Output/detectedAtributesImage3.json)         |

## Image Analysis - Add captions to images

Generate a readable sentence that describes the content of an image.

| Image                                      | Result                                  | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image4.jpg)         | [Attributes detected](Output/detectedAtributesImage4.txt)         | [JSON](Output/detectedAtributesImage4.json)         |
| ![Image](Input/image5.jpeg)         | [Attributes detected](Output/detectedAtributesImage5.txt)         | [JSON](Output/detectedAtributesImage5.json)         |
| ![Image](Input/image6.jpeg)         | [Attributes detected](Output/detectedAtributesImage6.txt)         | [JSON](Output/detectedAtributesImage6.json)         |

## OCR (Optical Character Recognition)

Use the Read API to extract printed and handwritten text in supported languages from images, PDFs, and TIFF files. The optical character recognition (OCR) capability supports both images and documents with mixed languages, and doesn't require specifying the language.

| Image                                      | Result                                  | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image7.jpg)         | [Attributes detected](Output/detectedAtributesImage7.txt)         | [JSON](Output/detectedAtributesImage7.json)         |
| ![Image](Input/image8.jpg)         | [Attributes detected](Output/detectedAtributesImage8.txt)         | [JSON](Output/detectedAtributesImage8.json)         |
| ![Image](Input/image9.jpg)         | [Attributes detected](Output/detectedAtributesImage9.txt)         | [JSON](Output/detectedAtributesImage9.json)         |

## References

[Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
