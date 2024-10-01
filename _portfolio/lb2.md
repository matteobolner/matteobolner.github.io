---
title: "Predicting secondary structure of proteins: a comparison between GOR method and Support Vector Machines"
excerpt: "Laboratory of Bioinformatics course project course<br/><img src='/images/portfolio/lb1_3d.png'>"
collection: portfolio
---
**Motivation:** The determination of protein structure is one of the most important open problems of
bioinformatics and a key passage for functional annotation. As the number of protein sequences available
steadily increases, the number of structures lags behind, since as of today there are still no methods for
the complete and accurate prediction of the tridimensional structure of a protein starting from its primary
sequence of residues. The prediction of the secondary structure could help bridge this gap; in this project,
two methods for secondary structure prediction, GOR and SVM, are implemented and tested on a set of
protein sequences with known structure, and compared in performance. The characteristics and potential
of such methods is discussed in depth.  
**Results:** The methods were succesfully implemented, and two models were produced. The models are
able to predict the secondary structure of a protein chain with only the primary sequence as input, with
a three-class accuracy of 62% (GOR) and 70% (SVM). While the accuracy of the SVM method is clearly
superior, the overall difference in performance is more nuanced.  
**Availability:** https://github.com/matteobolner/lb2_project