# Picture_similary

## setup
!pip install transformers
!pip install torch torchvision
!pip install pillow
!pip install pytesseract
!apt-get install -y tesseract-ocr


## Miêu tả

Image Captioning:

The program uses the BLIP (Bootstrapping Language-Image Pre-training) model, which is a deep learning model designed for generating captions from images. It leverages advanced techniques in natural language processing (NLP) and computer vision.
The model processes the image and predicts a descriptive caption, effectively translating visual content into text.
Optical Character Recognition (OCR):

The program utilizes Tesseract OCR to extract any text present within the image. This is another form of AI application, as OCR systems use machine learning to identify and interpret characters from images.
The extracted text can provide additional context or information related to the image.
Text Similarity Measurement:

The program calculates the similarity between the automatically generated caption and a user-provided description using SpaCy, a natural language processing library. This involves comparing semantic meanings and understanding the context of the text, which is a common NLP task.




![image](https://github.com/user-attachments/assets/e5058a49-81d6-477d-8066-2eb0988aacd5)

Automatically generated description of the image: this is a black and white photo of a puppy running in the grass
Enter your description:  a dog
Detailed automatic description of the image: this is a black and white photo of a puppy running in the grass
Your description: a dog
Similarity between the description and the image: 42.92%
