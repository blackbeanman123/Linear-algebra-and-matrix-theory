## Singular Value Decomposition(SVD)

### definition

**_Any matrix_** ![](./res/A.gif) can be written as ![](./res/4.gif)  
![](./res/A.gif) is an m x n real or complex matrix <br/>
![](./res/U.gif) is an m x m real or complex **_unitary matrix_** called left-singular vectors   
![](./res/V.gif) is an n x n real or complex **_unitary matrix_** called right-singular vectors<br/>
![](./res/Sigma.gif) is an m x n rectangular diagonal matrix, with **_non-negative real numbers_** on the diagonal 

For **_real matrix_** ![](./res/A.gif)<br/>
![](./res/U.gif) and ![](./res/V.gif) are **_unitary real orthogonal matrixs_**, which means they're matrixs of rotation transformation<br/>
![](./res/Sigma.gif) is an **_real rectangular diagonal matrix_**, which means it is a matrix of translation transformation<br/>
![](./res/440px-Singular-Value-Decomposition.svg.png)(wiki)<br/>
![](./res/Vstar.gif) = ![](./res/VT.gif)<br/>
![](./res/Sigma.gif) consists of r(rank) singular values


**_Uniqueness_**<br/>
The SVD is not unique. It is always possible to choose the decomposition so that the singular values ![](./res/sigmai.gif)(= ![](./res/Sigmaii.gif)) are in decending order. In this case, ![](./res/Sigma.gif) (but not always ![](./res/U.gif) and ![](./res/V.gif)) is uniquely determined by ![](./res/A.gif).   (wiki)


### calculation

![](./res/calV.gif)<br/>
similarily ![](./res/calU.gif)<br/>
So ![](./res/V.gif) are the eigenvectors of ![](./res/ATA.gif), ![](./res/U.gif) are the eigenvectors of ![](./res/AAT.gif)<br/>
the singularvalue ![](./res/Sigmaii.gif) corresponds to the square root of  eigenvalue ![](./res/lambdaii.gif) of ![](./res/ATA.gif) or ![](./res/AAT.gif), which means that ![](./res/sigmai.gif) = ![](./res/5.gif)<br/>
e.g. TODO

### application

#### Moore-Penrose Pseudoinverse

#### Principal Components Analysis
See PCA
