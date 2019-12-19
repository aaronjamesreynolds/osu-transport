Start: Diffusion and precursor concentration equations. 

Main assumption: <img src="https://tex.s2cms.ru/svg/%5Cphi(r%2Ct)%20%3D%20vn(t)%5Cpsi(r)" alt="\phi(r,t) = vn(t)\psi(r)" /> 

Start with diffusion equation

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7B1%7D%7Bv%7D%5Cfrac%7B%5Cpartial%20%5Cphi%7D%7B%5Cpartial%20t%7D%20-%20%5Cnabla%20%5Ccdot%20D%5Cnabla%5Cphi%20%2B%20%5CSigma_a%5Cphi%20%3D%20%5Cnu%20%5CSigma_f(1-%5Cbeta)%5Cphi%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i" alt="\frac{1}{v}\frac{\partial \phi}{\partial t} - \nabla \cdot D\nabla\phi + \Sigma_a\phi = \nu \Sigma_f(1-\beta)\phi+\sum_{i=1}^{6}\lambda_i C_i" />

Assume D is constant in space and <img src="https://tex.s2cms.ru/svg/%5Cnabla%5E2%5Cphi%20%2B%20B_g%5E2%5Cphi%20%3D%200" alt="\nabla^2\phi + B_g^2\phi = 0" />

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7B1%7D%7Bv%7D%5Cfrac%7B%5Cpartial%20%5Cphi%7D%7B%5Cpartial%20t%7D%20%2B%20DB_g%5E2%5Cphi%20%2B%20%5CSigma_a%5Cphi%20%3D%20%5Cnu%20%5CSigma_f(1-%5Cbeta)%5Cphi%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i" alt="\frac{1}{v}\frac{\partial \phi}{\partial t} + DB_g^2\phi + \Sigma_a\phi = \nu \Sigma_f(1-\beta)\phi+\sum_{i=1}^{6}\lambda_i C_i" />

Assume separability <img src="https://tex.s2cms.ru/svg/%5Cphi(r%2Ct)%20%3D%20vn(t)%5Cpsi(r)" alt="\phi(r,t) = vn(t)\psi(r)" /> and <img src="https://tex.s2cms.ru/svg/C_i(r%2Ct)%20%3D%20C_i(t)%5Cpsi(r)" alt="C_i(r,t) = C_i(t)\psi(r)" />

<img src="https://tex.s2cms.ru/svg/%5Cfrac%7B1%7D%7Bv%7D%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dvn(t)%5Cpsi(r)%20%2B%20DB_g%5E2%20vn(t)%5Cpsi(r)%20%2B%20%5CSigma_avn(t)%5Cpsi(r)%20%3D%20%5Cnu%20%5CSigma_f(1-%5Cbeta)vn(t)%5Cpsi(r)%20%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%5Cpsi(r)" alt="\frac{1}{v}\frac{\partial}{\partial t}vn(t)\psi(r) + DB_g^2 vn(t)\psi(r) + \Sigma_avn(t)\psi(r) = \nu \Sigma_f(1-\beta)vn(t)\psi(r) +\sum_{i=1}^{6}\lambda_i C_i(t)\psi(r)" />

Divide through by spatial dependence and simplify.

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20v%5B-DB_g%5E2%20-%20%5CSigma_a%20%2B%5Cnu%20%5CSigma_f(1-%5Cbeta)%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= v[-DB_g^2 - \Sigma_a +\nu \Sigma_f(1-\beta)]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

Pull out <img src="https://tex.s2cms.ru/svg/%5CSigma_a" alt="\Sigma_a" />. <img src="https://tex.s2cms.ru/svg/%5Cfrac%7BD%7D%7B%5CSigma_a%7D%20%3D%20L%5E2" alt="\frac{D}{\Sigma_a} = L^2" />.

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20-v%5CSigma_a%5BL%5E2B_g%5E2%20%2B%201%20-%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D(1-%5Cbeta)%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= -v\Sigma_a[L^2B_g^2 + 1 -\frac{\nu \Sigma_f}{\Sigma_a}(1-\beta)]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

The probability of non-leakage is <img src="https://tex.s2cms.ru/svg/P_%7BNL%7D%20%3D%20%5Cfrac%7B1%7D%7BL%5E2B_g%5E2%20%2B%201%7D" alt="P_{NL} = \frac{1}{L^2B_g^2 + 1}" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20-v%5CSigma_a%5B%5Cfrac%7B1%7D%7BP_%7BNL%7D%7D%20-%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D(1-%5Cbeta)%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= -v\Sigma_a[\frac{1}{P_{NL}} -\frac{\nu \Sigma_f}{\Sigma_a}(1-\beta)]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20-%5Cfrac%7Bv%5CSigma_a%7D%7BP_%7BNL%7D%7D%5B1%20-P_%7BNL%7D%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D(1-%5Cbeta)%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= -\frac{v\Sigma_a}{P_{NL}}[1 -P_{NL}\frac{\nu \Sigma_f}{\Sigma_a}(1-\beta)]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

The prompt neutron lifetime is <img src="https://tex.s2cms.ru/svg/%5Cell%20%3D%20%5Cfrac%7BP_%7BNL%7D%7D%7Bv%5CSigma_a%7D" alt="\ell = \frac{P_{NL}}{v\Sigma_a}" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20-%5Cfrac%7B1%7D%7B%5Cell%7D%5B1%20-P_%7BNL%7D%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D(1-%5Cbeta)%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= -\frac{1}{\ell}[1 -P_{NL}\frac{\nu \Sigma_f}{\Sigma_a}(1-\beta)]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20%5Cfrac%7B1%7D%7B%5Cell%7D%5BP_%7BNL%7D%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D(1-%5Cbeta)-1%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= \frac{1}{\ell}[P_{NL}\frac{\nu \Sigma_f}{\Sigma_a}(1-\beta)-1]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

The multiplication factor is <img src="https://tex.s2cms.ru/svg/k%3DP_%7BNL%7D%5Cfrac%7B%5Cnu%20%5CSigma_f%7D%7B%5CSigma_a%7D" alt="k=P_{NL}\frac{\nu \Sigma_f}{\Sigma_a}" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20%5Cfrac%7B1%7D%7B%5Cell%7D%5Bk(1-%5Cbeta)-1%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= \frac{1}{\ell}[k(1-\beta)-1]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

Prompt neutron lifetime is <img src="https://tex.s2cms.ru/svg/%5Cell%3D%5Cfrac%7B1%7D%7Bk%5CLambda%7D" alt="\ell=\frac{1}{k\Lambda}" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20%5Cfrac%7B1%7D%7Bk%5CLambda%7D%5Bk-k%5Cbeta)-1%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= \frac{1}{k\Lambda}[k-k\beta)-1]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20%5Cfrac%7B1%7D%7B%5CLambda%7D%5B%5Cfrac%7Bk-1%7D%7Bk%7D-%5Cfrac%7Bk%5Cbeta%7D%7Bk%7D%5Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= \frac{1}{\Lambda}[\frac{k-1}{k}-\frac{k\beta}{k}]n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

Reactivity is <img src="https://tex.s2cms.ru/svg/%5Crho%3D%5Cfrac%7Bk-1%7D%7Bk%7D" alt="\rho=\frac{k-1}{k}" />. The following is the first equation of the PRKEs.

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7Dn(t)%3D%20%5Cfrac%7B%5Crho-%5Cbeta%7D%7B%5CLambda%7Dn(t)%2B%5Csum_%7Bi%3D1%7D%5E%7B6%7D%5Clambda_i%20C_i(t)%0A" alt="
\frac{\partial}{\partial t}n(t)= \frac{\rho-\beta}{\Lambda}n(t)+\sum_{i=1}^{6}\lambda_i C_i(t)
" />

Now, consider the delayed neutron precursor equation.

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%20C_i%7D%7B%5Cpartial%20t%7D%20%3D%20%5Cnu%5CSigma_f%5Cbeta_i%5Cphi-%5Clambda_i%20C_i%20%5Cquad%20i%3D1...6%0A" alt="
\frac{\partial C_i}{\partial t} = \nu\Sigma_f\beta_i\phi-\lambda_i C_i \quad i=1...6
" />

Assume separability <img src="https://tex.s2cms.ru/svg/%5Cphi(r%2Ct)%20%3D%20vn(t)%5Cpsi(r)" alt="\phi(r,t) = vn(t)\psi(r)" /> and <img src="https://tex.s2cms.ru/svg/C_i(r%2Ct)%20%3D%20C_i(t)%5Cpsi(r)" alt="C_i(r,t) = C_i(t)\psi(r)" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%5Cpsi(r)%20%3D%20%5Cnu%5CSigma_f%5Cbeta_i%20vn(t)%5Cpsi(r)-%5Clambda_iC_i(t)%5Cpsi(r)%0A" alt="
\frac{\partial}{\partial t}C_i(t)\psi(r) = \nu\Sigma_f\beta_i vn(t)\psi(r)-\lambda_iC_i(t)\psi(r)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%20%3D%20%5Cnu%5CSigma_f%5Cbeta_i%20vn(t)-%5Clambda_iC_i(t)%0A" alt="
\frac{\partial}{\partial t}C_i(t) = \nu\Sigma_f\beta_i vn(t)-\lambda_iC_i(t)
" />

Consider <img src="https://tex.s2cms.ru/svg/%5Cell%20%3D%20%5Cfrac%7BP_%7BNL%7D%7D%7Bv%5CSigma_a%7D" alt="\ell = \frac{P_{NL}}{v\Sigma_a}" /> from before. Neutron velocity is <img src="https://tex.s2cms.ru/svg/v%20%3D%20%5Cfrac%7BP_%7BNL%7D%7D%7B%5Cell%5CSigma_a%7D" alt="v = \frac{P_{NL}}{\ell\Sigma_a}" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%20%3D%20%5Cfrac%7B%5Cbeta_i%7D%20%7B%5Cell%7DP_%7BNL%7D%5Cfrac%7B%5Cnu%5CSigma_f%7D%7B%5CSigma_a%7Dn(t)-%5Clambda_iC_i(t)%0A" alt="
\frac{\partial}{\partial t}C_i(t) = \frac{\beta_i} {\ell}P_{NL}\frac{\nu\Sigma_f}{\Sigma_a}n(t)-\lambda_iC_i(t)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%20%3D%20%5Cfrac%7B%5Cbeta_i%7D%20%7B%5Cell%7Dkn(t)-%5Clambda_iC_i(t)%0A" alt="
\frac{\partial}{\partial t}C_i(t) = \frac{\beta_i} {\ell}kn(t)-\lambda_iC_i(t)
" />

Again, <img src="https://tex.s2cms.ru/svg/%5Cell%3D%5Cfrac%7B1%7D%7Bk%5CLambda%7D" alt="\ell=\frac{1}{k\Lambda}" />.

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%20%3D%20%5Cfrac%7B%5Cbeta_i%7D%20%7Bk%5CLambda%7Dkn(t)-%5Clambda_iC_i(t)%0A" alt="
\frac{\partial}{\partial t}C_i(t) = \frac{\beta_i} {k\Lambda}kn(t)-\lambda_iC_i(t)
" />

<img src="https://tex.s2cms.ru/svg/%0A%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7DC_i(t)%20%3D%5Cfrac%7B%5Cbeta_i%7D%7B%5CLambda%7Dn(t)-%5Clambda_iC_i(t)%20%5Cquad%20i%3D1...6%0A" alt="
\frac{\partial}{\partial t}C_i(t) =\frac{\beta_i}{\Lambda}n(t)-\lambda_iC_i(t) \quad i=1...6
" />

Above is the second equation of the PRKEs.
