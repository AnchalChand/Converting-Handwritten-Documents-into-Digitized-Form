# CONVERTING-HANDWRITTEN-DOCUMENTS-INTO-DIGITIZED-FORM


# ABSTRACT

•	This project is mainly built to convert handwritten documents into a digitize text format. I have used Python programming language to build the code. Along with, this project uses the concept of computer vision. Computer vision is making the computer visualize as humans do. Basic steps for a typical computer vision application are image acquisition, image manipulation, obtaining relevant information and decision making.
•	The stepwise approach of turning the manually written data into digitize data is as follows:  
  1.	Taking image as input for text extraction. 
  2.	The next step involves pre-processing of this text data. Feature extraction is performed to identify key information of an individual character.
  3.	These generated features are then used to extract text from the image. 

•	The conversion of the captured text into an audio file is a prominient feature of this project. This feature is an example of application of AI for people with vision disability.


# INTRODUCTION 

•	As the name suggests “Turning Handwritten Documents into Digitize Version”, this project converts the documents which are written manually or which are even in some other already digitize format, into a convenient digitized form. This kind of mechanism seems beneficial for anyone who prefer the traditional manual way to note down some stuffs but need a more convenient method to store them. 


# MOTIVATION

•	I have chosen this project because this is the era where almost every field has been digitized. Still, we prefer to manually write stuffs most of the times but want to store them in a more convenient and organized manner. Working on this project gave me an opportunity to develop the mechanism for the same and to explore more in the field of computer vision, to work with various Python libraries and methods, and to explore brief Machine Learning features. 


# METHODOLOGY FOLLOWED

•	Optical character recognition or the text recognition uses automated data capture solutions and document classification. It involves the electronical conversion of images of text, either types, handwritten or printed format, into machine-encoded text.

•	There OCR system is a combination of software and hardware to convert physical documents into readable characters for machines.
 
      o	Hardware : optical scanner or specialized circuit board to read or copy text
  
      o	Software : executes advanced processing and uses AI for advanced ways of ‘Intelligence Character Recognition’ (ICR) 

•	It includes language identification and handwriting styles.

•	Tesseract — is an optical character recognition engine with open-source code.

•	Pytesseract is also an OCR tool for Python and is based on Google’s OCR API.

•	OCR uses artificial intelligence for text search and its recognition on images.

•	gTTS stands for GOOGLE TEXT TO SPEECH. It’s a Python library and CLI tool to interface with Google text to speech API.

•	OpenCV is an  open-source library for Computer Vision and image processing. Cv2 is used to read image and video to process them.

•	Comma Separated Variable, abbreviated as CSV, is a library used to read and write tabular data in  CSV format.

•	In this project, pre-scanned data in form of images is used rather than any specific OCR scanner.


# WORKING

•	The handwritten documents or the images are used as an input source. 

•	The OpenCV Python library is used to read and pre-process the image.

•	The image is then pre-processed which involves following steps :
  1. Converting the image color into grey or commonly known as black and white image color
  2. Highlighting required part of the image : by creating rectangular boxes around the detected text in image
  
•	Using the pytesseract Python library, the text is extracted from the image.

•	The format_text function provides a proper format to the extracted text.

•	The write_text function saves the extracted and properly formatted text into a file and saves it.

•	This output screen of the code also displays this text.

•	At last, using the gTTS Python library, the text is converted and save into audio file.





### Input Image With Handwritten Text
![image](https://user-images.githubusercontent.com/82054687/179369233-421977c1-e6c0-4c45-aed6-6cadad1b804a.png)

### Digitized Text
![image](https://user-images.githubusercontent.com/82054687/179369246-8914ace0-28bc-4765-aa23-b24ff0608aca.png)

### Input Image With Typed Text
![image](https://user-images.githubusercontent.com/82054687/179369289-9a539655-9d16-43bb-bac4-08dd4780fd73.png)


### Digitized Text
![image](https://user-images.githubusercontent.com/82054687/179369293-e651af23-9877-4a83-b8d8-823e90536685.png)

# FUTURE GOALS
•	To improve the project by adding pure feature of Machine Learning. This will be achieved by making a model that will be trained using an appropriate dataset, using a proper Machine Learning algorithm and implementing a neural network which will train the model for most accurate result. This will enhance the accuracy of identifying handwritten data by the model. \
•	To deploy the well-trained model and make it a web-based application.


# REFERENCE
1.	https://www.wikipedia.org
2.	https://www.geeksforgeeks.org
3.	https://stackoverflow.com/
4.	https://www.youtube.com 
5.	https://towardsdatascience.com
6.	https://nanonets.com
