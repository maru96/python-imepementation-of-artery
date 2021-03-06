# Artery implemenation on the python
---
An implementation of finite difference methods (FDM) to solve partial differential equations (PDE).
The first method to be implemented is Richtmyer's 2 step Lax-Wendroff method.
Approximation solution on a joint condition is solved by The Newton's method.
# Papers
---
There are implementations of the common carotid and the aortic bifurcation introduced in "A Systematic Comparison between 1-D and 3-D Hemodynamics in Compliant Arterial Models "(https://pubmed.ncbi.nlm.nih.gov/24115509/). Data is available on "A benchmark study of numerical schemes for one‐dimensional arterial blood flow modelling"(https://onlinelibrary.wiley.com/doi/abs/10.1002/cnm.2732). 
I refered to vampy package(https://github.com/alexdiem/vampy).

# Installation
---
git clone https://github.com/akdiem/VaMpy.git 
To ensure all package dependencies, try to install packages written on "requirments.txt".

# Execute
---
There two running examples in main.py files.
Result will be stored in log directory.

# Result
---

Running output from aortic_bifuration. Results from referenced paper are preceded by Results from my implementation.

### Aortic bifurcation shape
---

![Aortic bifurcation shape](images/bif_shape.png)

### Child artery (pressure and flux)
---

![pressure of child artery from refered paper](images/bif_ans_c_P.png)

![flux of child artery from refered paper](images/bif_ans_c_Q.png)

![pressure and flux of child artery from refered paper](images/bif_exp_c.png)

### Parent artery (pressure and flux)
---

![pressure of parent artery from refered paper](images/bif_ans_p_P.png)

![flux of child artery from refered paper](images/bif_ans_p_Q.png)

![pressure and flux of parent artery from refered paper](images/bif_exp_p.png)

