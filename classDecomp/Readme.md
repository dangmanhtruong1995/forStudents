### Class Decomposition

One way to improve the learning processs is by applying class-decomposition to the dataset before applying Machine Leanring. Class decomposition describes the process of segmenting each class into a number of homogeneous subclasses. This is achieved through clustering. Utilising class decomposition can provide a number of benefits to supervised learning, especially ensembles. It can be a computationally efficient way to provide a **linearly separable data set** without the need for feature engineering required by techniques like support vector machines and deep learning. Medical data for patient diagnosis may greatly benefit from this technique, as the same disease can have a diverse of symptoms. 


#### Implementation 
This repo contains a set of functions  for [implementing CD](SourceFiles/classDecomp.Rmd) and apply it along with a Random Forest classifier to show its impact on RF performance. 

Pay attention to the function **clustSet** which does the followings: 

#### Relevant Publications

* **E. Elyan**,C.G. Moreno and C. Jayne, “Symbols classification in engineering drawings”, 2018 International Joint Conference on Neural Networks (IJCNN), Rio de Janeiro, Brazil, 2018, pp. 1-8. DOI [http://dx.doi.org/10.1109/IJCNN.2018.8489087](http://dx.doi.org/10.1109/IJCNN.2018.8489087)


* **E Elyan,**, Gaber, M.M. A fine-grained Random Forests using class decomposition: an application to medical diagnosis. Neural Comput & Applic 27, 2279–2288 (2016). [https://doi.org/10.1007/s00521-015-2064-z](https://doi.org/10.1007/s00521-015-2064-z)