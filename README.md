# CNN_in_chess
A brief look into chess, specialising in using CNN models for several applications towards the game.

A list of the contained **projects**:
1. **SCREENSHOT TO FEN**: Extracting the positional chess notation (FEN) from a screenshot of a chess board (whether that be mobile or from a PC). Therefore being able to recreate the position on chess platforms, and by proxy, find the next best move, play/ analyse further or find the score of the position. The image recognition model was a CNN.
1. **STYLISH BOARDS**: Using transfer learning from imagenets CNN model named VGG, we can unblock some layers in the pretrained model. Adapting those layers and therefore the ones after to the *content* we want it to copy. Whilst teaching one of the final layers with the *style* we wish it to transfer onto the *content*.
1. **GENERATED PIECES**: Creating new piece outlines using a GAN. Trained on the piece outlines of many different board types 
