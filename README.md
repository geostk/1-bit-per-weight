# 1-bit-per-weight
Training wide residual networks for deployment using a single bit for each weight

We provide here code written in Matlab and using the matconvnet package (http://www.vlfeat.org/matconvnet/) that will enable the reader to verify our strong error rate results using a single-bit for each weight in inference.

The test error rate for CIFAR-100 for this 20-4 plain all-convolutional network with 4.5 million single-bit weights is 24.5%. Our 1-bit result for a ResNet shown in Table 1 in our submitted paper is 24.06%. 

We chose to provide code for the plain network as our example, for the extra simplicity.