# icdar2013_baselines
This repository holds the PAGE format files for the 2013 ICDAR competition data set test partition. 

Each xml file holds a text region for the whole image plus an individual baseline for each of the text lines present in the text. 
The required image files and evaluation software to measure the quality of the extraction polygon yielded by your system can
be adquired from: http://users.iit.demokritos.gr/~nstam/ICDAR2013HandSegmCont/resources.html 

The baselines were created with minimal detail: two control points were set up to span the complete length of the text line
and if required up to two additional control points could be added in order to follow any large changes in the text line slope. 

In this way this baselines grountruth act as something that could be the output yielded by a baseline detection system and have
its use in order to compare text line extraction solutions that use as input already detected text line baselines. 

This groundtruth can also be used to measure the precission of the baselines detected of a system with the use of the Transkribus
Base Line Evaluation Scheme software that can be found in: https://github.com/Transkribus/TranskribusBaseLineEvaluationScheme
