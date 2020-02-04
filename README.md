# Maximum-Variance-Unfolding
#### Name: Sam Longenbach & Caleb Ralphs

#### Files:
- **MVU_Teapot_Code.ipynb** - *Code to implement landmark MVU on teapot dataset varying (k) nearest neighbors and (l) landmarks.*
- **Maximum_Variance_Unfolding.pdf** - *Report detailing MVU derivation, summary of implementation, and discussion of further extensions.*
- **Teapots.mat** - *Data of 400 ordered images of rotated teapot.*



## Formulation
![MVU](readme_imgs/Formulation.png)

Maximum variance unfolding (MVU), also known as semi-definite embedding,is a non-linear dimension reduction technique.  It can be viewed as nonlineargeneralization of the linear dimension reduction technique, principal componentanalysis (PCA). Like many dimension reduction algorithms, MVU looks to maphigh dimensional inputs to low dimensional outputs. The visual intuition behindMVU is this idea we connect neighboring points in the high dimensional space byrigid rods.  The amount of connections or number of rods is a chosen parameter(k)  we  will  discuss  later  on.   With  that  said,  the  points  connected  to  their  kclosest neighbors creates this lattice like structure.  MVU can be seen as pullingthis structure apart and flattening the structure without breaking or stretchingthe rigid rods.  In other words, MVU looks to maximize the pairwise distancesbetween input points subject to the constraints of maintaining the distances ofthese local rigid connections 

## Data


## Implementation

