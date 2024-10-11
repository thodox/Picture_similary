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



## FUTURE
To enhance the predictive and analytical capabilities of our application, we plan to integrate OpenAI's API into our workflow. First, we will use OpenAI's models to generate more detailed and vivid image descriptions. This will help improve accuracy when comparing automatically generated descriptions with those provided by users.

We will also apply natural language processing (NLP) techniques to summarize, classify, and analyze the sentiment of text, thereby enhancing the quality of the descriptions. A keyword suggestion system based on image content will assist users in creating more accurate descriptions.

Additionally, we aim to develop interactive features like chatbots, allowing users to ask questions and receive feedback from the AI model easily. Finally, we will leverage the API to evaluate the performance of current models and extend the application to other platforms such as web or mobile.

