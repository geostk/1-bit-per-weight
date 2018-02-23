# Training wide residual networks for deployment using a single bit for each weight

This code was used for experiments accepted for publication in ICLR 2018 (iclr.cc). The ICLR version of the paper and the double-blind open peer review can be found at https://openreview.net/forum?id=rytNfI1AZ.

This page will be populated fully in coming days.

For now, we provide here code written in Matlab and using the matconvnet package (http://www.vlfeat.org/matconvnet/) that will enable the reader to verify our strong error rate results using a single-bit for each weight in inference.

The test error rate for CIFAR-100 for this 20-4 plain all-convolutional network with 4.5 million single-bit weights is 24.5%. Our 1-bit result for a ResNet shown in Table 1 in our submitted paper is 24.06%. 

We chose to provide code for the plain network as our example, for the extra simplicity.
