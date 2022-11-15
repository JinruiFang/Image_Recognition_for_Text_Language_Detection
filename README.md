# Image categorization

This project is to do image recognition tasks, in particular detect the language of written text by using convolutional networks, and understand the effect of the networks structure to the model capabilities and training time.

## Task 
Develop neural network that is as good as to distinguishing between these languages. On top of these files, there are approximately one fourth as many validation images. 

## Data
The training data consists of excerpts of printed text, 4100 images of Danish, 8500 images of English, 6500 images of Russian, 7425 images of Thai, and 5300 images of Chinese text. 

The images can be downloaded from Google drive https://drive.google.com/drive/folders/1G2uTLHEcdAaP8tpY8oXmCblxsWw7D66C?usp=sharing, The files are split into two (zipped) folders: train (1.3G) and validation (300M). Besides of thenumber of files in these folders, there is no real differences between training and testing images.

The files are named as source_LANG-xxx.jpg. source refers to the source text (e.g. author and bookname), LANG is language (DA: Danish, EN : English, RU : Russian, TH : Thai, ZN : Chinese), and xxx refers to alphabetically ordered chunk id. See Figure 1 for an example. 

It is is easy to distinguish between English and Chinese, but much harder to separate English and Danish. 
The images are of different size,but 500 ×200 is a fairly common measure. All images are grayscale only, and all text is printed in the same point size (19 pt I believe).

## This is my testing summary table:
| Test1 EN & ZN    | Test2 EN & TH & ZN  | Test 3 without RU & DA | Test 4 without DA & with cropped image
| -----------------| ------------------- | ---------------------  | -------------------------------------- |
| Number of epochs | Some more data      | data                   |                                        |
| Number of models            | Some long data here | more data              | 
| Number of convolutionalfilters(for two model)| Some long data here | more data              | 
| kernel_size(for two model) | Some long data here | more data              | 
| strides           | Some long data here | more data              | 
| Dense(relu)           | Some long data here | more data              | 
| Dense(softmax)           | Some long data here | more data              | 
| Trainable params            | Some long data here | more data              | 
| Accuracy           | Some long data here | more data              | 
