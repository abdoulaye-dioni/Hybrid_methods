# Hybrid methods for missing categorical covariates in Cox model

When handling missing data under the MAR assumption, many studies compare classical methods. 
However, several questions remain: Is parametric multiple imputation an ideal benchmark? 
Is non-parametric multiple imputation sufficient to effectively handle missing values? 
The same question applies to semi-parametric methods. The answer is not always straightforward. 
Indeed, just as a single imputed value may struggle to fully capture the notion of plausible values **Little and Rubin (2020)**, 
a single approach may also struggle to capture the complexity of real data. 
To overcome these limitations, hybrid methods that combine the strengths of classical methods are emerging as a promising alternative. 
Hybrid methods integrate at least two classical methods of handling missing data into a unified procedure. 
They offer great flexibility and robustness by combining methods with different implementations.

The motivation for introducing hybrid methods is based on several important considerations in the literature.

1. **Absence of a single ideal method**.

2. **Complexity of real data**.

3. **Reduction of mis-specification effects**.

4. **Independence of Rubin's rule**.
