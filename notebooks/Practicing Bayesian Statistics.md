# <center>Practicing Bayesian Statistics<center>

## Contents
- Introduction
- Two staistical philosophies
    - Frequentist Statistics
    - Bayesian Statistics
- Bayes Thereom
    - prior
    - Likelihood
    - Posterior
- Effect indices
   - Credible intervals
- MArkov chain Monte Carlo (MCMC)

## Introduction
When Efron and Hastie (2016) Identify that “Statistical inference is an unusually wide-ranging discipline, located as it is at the triple-point of mathematics, empirical science, and philosophy” (pp. xv) they make its multidisciplinary nature and complexity clear. This complexity has led to misinterpretation of the standardly taught analysis (frequentist) methods by applied by researchers (Hoekstra, Morey, Rouder, & Wagenmakers, 2014; Lyu, Xu, Zhao, Zuo, & Hu, 2020), that seemingly result due primarily due to the “philosophy” section of Efron and Hastie’s quote above. That being that when researchers interpret their data under the standard frequentist tools they seemingly want to interpret the outputs under the Bayesian framework (Etz, Bartlema, Vanpaemel, Wagenmakers, & Morey, 2019), but what is Bayesian statistics?

## The two philosophies of statistical inference
“The numbers have no way of speaking for themselves. We speak for them. We Imbue them with meaning.” Silver (2012)

“Technical mathematical arguments and formula, though valid and of interest, must always assume, tacitly or explicitly, a philosophy.”Briggs (2019)

“An important insight that would seem desirable for any statistical philosophy: Conclusions are only as plausible as the subjective foundations on which they are based.”
                                                                                                                               Western (1999)

As the quotes above point out there is no free lunch when analyzing data and conducting statistical inference, but this is often forgotten or ritualised (Gigerenzeer, 2004). Crucially, statistical inference is only possible at all because of the application of probability theory and the interpretation of probability when the data are analysed. However, heated debates about what interpretation of probability to apply have occurred since the inception of statistical analysis and have resulted in what has been termed “The statistics Wars” within the statistical literature (Gigerenzer et al., 1983; Mayo, 2020; Salsburg, 2002).
The interpretations of probability is what separates the Frequentist and Bayesian frameworks of statistical inference. These interpretations of probability are known as objective and subjective probability. Lambert (2018), describes it as a difference in world view by the analyst, and by applying either framework the analyst's making assumptions about how to model the world through these different views of probability.
Frequentist Statistics (objective probability).
The philosophical grounding of Frequentist statistics is objective probability. The meaning of objective probability to data is expressed by the view that any set of observed data is a sample that has been generated from an infinite replication of that data generating process. A result of this view if any inference that is made on that part of the analyst is that the observed sample is one with a long-run view of repeated sampling. This is shown with the way that the data is treated as random but the statistical models that are fit to data are an attempt to estimate fixed population parameters. Frequentist statistics application in science is dominated by Null hypothesis significance testing (NHST). In terms of inference, this allows statements in terms of  p-value.
Bayesian statistics (subjective probability).
Bayesian statistics applies probability as an expression of the analyst’s belief and as an expression of their uncertainty around what they are analyzing. This is expressed in the reversal of what the Frequentists do by treating the parameters of the statistical models that they fit as random and the data as fixed. Under this framework, the use of Bayes theorem and data can be used to update beliefs about phenomena being studied through data analysis. Bayesian statistics allows for inference statements that follow . This is achieved by the application of Bayes rule.

## Bayes Thereom
$$P(A,B) = P(B,A)\: \:\: \: \: \:(1)$$
 $$P(B|A)P(A) = P(A|B)P(B)\: \:\: \: \: \:(2) $$
 $$P(A|B) = \frac{P(B|A)P(A)}{P(B)}\: \:\: \: (3)$$
## MCMC
### <center>References<center>
