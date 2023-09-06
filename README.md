# Anisotropic viscoelasticity (matrix-fiber composite)

Numerical model in FEniCS and FEniCSx for matrix-fiber composite materials. Details of the model in Liu et al. (2019) [[1]](#1).

The results using the numerical implementation presented in [1] are exact.

The work of Liu et al. (2019) [[1]](#1) is conditioned for the relaxation case.

Alternatively, I also solve the viscoelasticity of the matrix and fibers with generalized methods to allow the modeling of creep or any phenomena.

For matrix viscoelasticity i test the method of Reese and Govindjee [[2]](#2). 

In the case of fibers viscoelasticity, i used a linear ODE as in Nguyen et al. (2007) [[3]](#3), or Nedjar (2007) [[4]](#4).

The difference with the results of the paper [[1]](#1) is mainly in the fiber response.

### References

- <a id="1">[1]</a>  https://www.sciencedirect.com/science/article/abs/pii/S0022509618303223
- <a id="2">[2]</a>  https://www.sciencedirect.com/science/article/abs/pii/S0020768397002175
- <a id="3">[3]</a> https://www.sciencedirect.com/science/article/pii/S0020768307002582 
- <a id="4">[4]</a> https://www.sciencedirect.com/science/article/abs/pii/S0045782506003045

