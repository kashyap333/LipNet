# LipNet
## Predicts text from Lip movement from a video stream

Based on the paper 'LipNet: End-to-End Sentence-level Lipreading': https://arxiv.org/abs/1611.01599

Based on Pytorch instead of Keras. 

### Things to note:
1) The model is not trained on all the data available at: http://spandh.dcs.shef.ac.uk/gridcorpus/ , due to heardware constraints ( donot have a discrete gpu and online gpu availabilities time out in between)
2) Couldnt train for more epochs and fine-tuning is not carried out, again due to hearware limitations
3) The inculded training is only 10 epochs and trained on gpu available on colab.(before it timed out). But on eval it can be noticed that the model had actually started to learn the first couple of words.(check the last sheet of code) 

PS: If anybody having a gpu could train the model and share the weights. I would be very thankfull. :)


