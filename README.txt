Command to install tensorflow library:
>>pip install tensorflow 


The program will function in the following way:
1. The model is trained on multiple images of fake and real Indian currency.
2. Feature extraction is done by the following ways:
    a) input images are passed to 2 convolution layers and 2 max pool layers.
    b) The output from the second max pool is then flattened and passed to Full
       connected layer. 
    c) The output from Full connected layer is passed to output layer.
3. The CNN model is trained for 150 epochs.
4. Single prediction is made to detect whether the image is real currency or 
   fake currency

