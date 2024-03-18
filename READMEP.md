[\[English\]](README.md) [\[Português\]](#Introdução)
_______________________________________________________________________________________________________________________________________
## Introdução
Foram testados alguns dos serviços relacionados no Azure Vision Studio. Algumas imagens foram utilizadas para gerar o resultado conforme as tabelas mostradas em cada teste de funcionalidade.

## FACE

Detecte a localização de um ou mais rostos humanos em imagens, juntamente com atributos como pose, máscara facial e pontos de referência faciais.

| Imagem                                      | Resultado                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image1.jpg) | Face #1<br>Face mask: no<br><br>[Arquivo](Output/detectedAtributesImage1.txt) | [JSON](Output/detectedAtributesImage1.json) |
| ![Image](Input/image2.jpg) | Face #1<br>Face mask: no<br>Face #2<br>Face mask: no<br>Face #3<br>Face mask: no<br><br>[Arquivo](Output/detectedAtributesImage2.txt) | [JSON](Output/detectedAtributesImage2.json) |
| ![Image](Input/image3.jpg) | No face detected<br><br>[Arquivo](Output/detectedAtributesImage3.txt) | [JSON](Output/detectedAtributesImage3.json) |

## Análise de Imagem - Adicione legendas às imagens

Gere uma frase legível que descreva o conteúdo de uma imagem.

| Imagem                                      | Resultado                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image4.jpg)  | A cartoon of a pirate ship<br><br>[Arquivo](Output/detectedAtributesImage4.txt) | [JSON](Output/detectedAtributesImage4.json) |
| ![Image](Input/image5.jpeg) | A pineapple with sunglasses on the beach<br><br>[Arquivo](Output/detectedAtributesImage5.txt) | [JSON](Output/detectedAtributesImage5.json) |
| ![Image](Input/image6.jpeg) | A football ball on a field<br><br>[Arquivo](Output/detectedAtributesImage6.txt) | [JSON](Output/detectedAtributesImage6.json) |

## OCR (Reconhecimento Optico de Caracteres)

Use a API Read para extrair texto impresso e manuscrito em idiomas suportados de imagens, PDFs e arquivos TIFF. O recurso de reconhecimento óptico de caracteres (OCR) oferece suporte a imagens e documentos com idiomas mistos e não exige a especificação do idioma.

| Imagem                                      | Resultado                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| ![Image](Input/image7.jpg) | quesome<br>ALUGA-SE<br>ESTELOTE<br>396m<br>2<br>TRATARC/OPROP.<br>992<br>2001<br>62<br>UNBELIEVABLE<br><br>[Arquivo](Output/detectedAtributesImage7.txt) | [JSON](Output/detectedAtributesImage7.json) |
| ![Image](Input/image8.jpg) | CDV-2172<br><br>[Arquivo](Output/detectedAtributesImage8.txt) | [JSON](Output/detectedAtributesImage8.json) |
| ![Image](Input/image9.jpg) | NATIONALIDENTITYCARD<br>BIOMETRICS<br>NAME:JohnDoe<br>SEX:Male<br>HAIR:Brown<br>HEIGHT:5'10"<br>WEIGHT:165<br>BORN:13Dec1981<br>DRIVERSLICENSE:XXT55340H59<br>1003A2-107624-(*-102)440u28878976-(tf.7--19#3.c)<br><br>[Arquivo](Output/detectedAtributesImage9.txt) | [JSON](Output/detectedAtributesImage9.json) |

## Referências

[Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
