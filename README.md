opinion-miner
=============

Opinion miner based on machine learning that can be trained using a list of KAF/NAF files. It is important to notice that the opinion miner module will not call to any external module to obtain features. It will read all the features from the input KAF/NAF file, so you have to make sure that your input file contains all the required information in advance (tokens, terms, polarities, constituents, entitiess, dependencies...).

The task is general divided into 2 steps

Detection of opinion entities (holder, target and expression): using Conditional Random Fields
Opinion entity linking (expression<-target and expression-<holder): using binary Support Vector Machines

https://github.com/cltl/opinion_miner_deluxe

This module was developed at VU University Amsterdam.
