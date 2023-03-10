# Free electron energy bands - Reduced Zone Scheme


Free electron energy bands of fcc, bcc and sc crystal lattice in the approximation of an empty lattice for different directions.


By using the appropriate $\mathbf{K}$ for the lattice and putting different values for miller indices energy simplifies to a set of parabolas of $\mathbf{k}$. The bands can be calculated for different direction of $\mathbf{k}$ using Symmetry points in the Brillouin zone. 



In the following calculation we set $2\pi/a$ and $\hbar^2/2m$ to one. The simulation was done in Python 3.8.5 using libraries such as mathplotlib, numpy, pandas and itertools.


For putting different miller indices in Eq.4 we must first calculate different family of directions using permutations from itertools library. For the following plots, miller indices in the families of <000>, <100>, <110>, <111>, <200> and <220> was used. A table containing band energy and its corresponding indices is given. The color in each row of the table connects the line in the plot with its corresponding index.


### SC - ky=kz=0 , kx= mu 2pi/a for mu between -1/2 and 1/2

![download (1)](https://user-images.githubusercontent.com/89476798/224403288-124cbc81-44f6-468a-9fc3-86a904cac5b3.png)

## FCC - Bands for the path $\mathbf{\Gamma}-\mathbf{X}-\mathbf{W}-\mathbf{L}-\mathbf{\Gamma}-\mathbf{K}- \mathbf{X}$

![fcc_bands](https://user-images.githubusercontent.com/89476798/224403724-f4cc7d3c-234a-47c4-926a-332f2a110fb2.png)

## BCC - Bands for the path $\mathbf{H}-\mathbf{\Gamma}-\mathbf{P}-\mathbf{N}-\mathbf{\Gamma}-\mathbf{H}-\mathbf{P}$ 

![bcc_bands](https://user-images.githubusercontent.com/89476798/224403937-a43a9ae9-dea4-424f-b372-e578f4832be0.png)
