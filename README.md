# BatchNorm Calculation:
Use the [Google BatchNorm Paper](https://arxiv.org/pdf/1502.03167) to find these equations:

<!--
Input: Values of x over a mini-batch: B = {x<sub>1...m</sub>}; <br />
Parameters to be learned: γ, β <br />
Output: {y<sub>i</sub> = BN<sub>&gamma;,&beta;</sub>(x<sub>i</sub>)} <br /> <br />
&mu;<sub>B</sub> &larr; $\frac{1}{m} \sum_{i=1}^{m} x_i$ (mean over batch) <br />
&sigma;<sub>B</sub><sup>2</sup> &larr; $\frac{1}{m} \sum_{i=1}^{m}(x_i - \mu_B)^2$ (variance over batch) <br /> <br />
$\hat{x}$<sub>i</sub> &larr; $\frac{x_i - \mu_B}{\sqrt{\sigma_B^2 + \epsilon}}$
-->
<img src="https://github.com/user-attachments/assets/0e8c4774-13d4-4dc5-8092-522a8562ae17" alt="bnpaper" width="400" />

