# Image-compression-and-Face-recognition
A practical example of Linear Algebra and just how strong matrices are in real life<br/>
<br/>
Image compression<br/>
<br/>
We compare different compression ratios by how much information is retained in the image as we use less and less memory. To reduce the memory we use the Singular Value Decomposition (SVD) algorithm on the matrices. We can retain a smaller part of the singular values obtained in the S matrix of the SVD algorithm and by doing this we lose some image quality.<br/>
<br/>
Face recognition<br/>
<br/>
We take a few images that we know contain faces and extract the eigenvalues of the images (that are after all only matrices of values). After this we check on other images that we give as input to obtain a certain percentage of the eigenvalues similar and after a certain threshold, we consider there are no faces in that image.<br/>
<br/>
More detailes can be found in the "Tema2_MN_2019.pdf" file.
