Question 1 | Frequentist vs. Bayesian Statistics
Suggested time: 7 minutes
A researcher is investigating whether an astronomical detector is reliable. A frequentist researcher and a Bayesian researcher analyze the same observations.
Prompt. Explain how the two researchers would approach estimating the detector’s reliability differently. Discuss how each approach interprets probability, incorporates prior information, and quantifies uncertainty.
Response:


Question 2 | Applying Bayes’ Theorem
Suggested time: 10 minutes
An astronomical detector searches for rare stellar events. The probability of a stellar event is 0.02. The detector correctly identifies an event 95% of the time and produces a false positive 5% of the time.
Prompt. Using Bayes’ theorem, calculate the probability that a stellar event actually occurred given a positive detection. Show your calculations and explain why this probability differs from the detector’s 95% sensitivity.
Response:

Question 3 | Prior and Posterior Distributions
Suggested time: 10 minutes
A researcher begins with a Beta(1,1) prior for the probability of heads. After 20 coin flips, the researcher observes 14 heads and 6 tails.
Prompt. Calculate the posterior Beta parameters and posterior mean probability of heads. Explain how the data changed the initial belief. Use αposterior = αprior + H, βposterior = βprior + T, and E[p | data] = αposterior / (αposterior + βposterior).
Response:

Question 4 | Sample Size and Bayesian Uncertainty
Suggested time: 10 minutes
Two researchers estimate an astronomical detector’s success probability, both using a Beta(1,1) prior. Researcher A observes 7 successes and 3 failures; Researcher B observes 70 successes and 30 failures.
Prompt. Calculate the posterior mean for each researcher. Although both observed a 70% success rate, explain why their posterior distributions have different uncertainty. Which estimate is more precise, and why?
Response:


Question 5 | Bayesian Statistics and Machine Learning
Suggested time: 8 minutes
Conventional neural networks typically learn one set of weights and biases. Bayesian neural networks instead use probability distributions to represent uncertainty in model parameters.
Prompt. Explain why parameter uncertainty can be valuable in scientific machine learning. Give one astronomical or other scientific application in which understanding predictive uncertainty is especially important.


Response:

## Solutions Key**
Instructor Note: Use these as model responses. Equivalent explanations and correctly reasoned calculations should receive credit.

Question 1 | Frequentist vs. Bayesian Statistics
Frequentist interpretation
A frequentist treats the detector’s unknown long-run success probability as a fixed parameter and uses repeated-sampling methods to estimate it, for example with a sample proportion and confidence interval. The frequentist approach does not assign a posterior probability distribution to the fixed parameter.
Bayesian interpretation
A Bayesian represents uncertainty about the detector’s success probability using a prior distribution, combines it with the likelihood of the observations, and obtains a posterior distribution. Posterior probabilities and credible intervals quantify parameter uncertainty conditional on the model, prior, and observed data.
Scientific interpretation
Prior information might come from earlier detector calibrations. The posterior updates that information with new observations. Both approaches use observed data; the key distinction is how uncertainty about the parameter is expressed.

Question 2 | Applying Bayes’ Theorem
Let E denote a true stellar event and + a positive detector result.
Prior: P(E) = 0.02; sensitivity: P(+ | E) = 0.95; false-positive rate: P(+ | not E) = 0.05.
Total probability of a positive result: P(+) = (0.95 × 0.02) + (0.05 × 0.98) = 0.019 + 0.049 = 0.068.
Bayes’ theorem: P(E | +) = P(+ | E)P(E) / P(+) = 0.019 / 0.068 = 0.2794 ≈ 27.94%.
The posterior is much lower than 95% because the event is rare: false positives among the many non-events outnumber true positives. Sensitivity is P(+ | E), not P(E | +).

Question 3 | Prior and Posterior Distributions
Beta(1,1) is uniform on probabilities between 0 and 1: it does not favor any particular value of the probability of heads.
After 14 heads and 6 tails: αposterior = 1 + 14 = 15; βposterior = 1 + 6 = 7.
Posterior: p | data ~ Beta(15,7).
Posterior mean: 15 / (15 + 7) = 15/22 ≈ 0.6818 (68.18%).
The observed sample proportion is 14/20 = 0.70. The posterior shifts from a uniform prior to a distribution favoring probabilities near 0.7. The posterior mean is slightly pulled toward the prior mean of 0.5.

Question 4 | Sample Size and Bayesian Uncertainty
Researcher A: Beta(1+7, 1+3) = Beta(8,4); posterior mean = 8/12 = 0.6667 (66.67%).
Researcher B: Beta(1+70, 1+30) = Beta(71,31); posterior mean = 71/102 ≈ 0.6961 (69.61%).
Both observed 70% success rates, but the posterior means are NOT identical because the common Beta(1,1) prior has a greater relative effect on the smaller sample.
Researcher B has the more concentrated (narrower) posterior and therefore the more precise estimate: 100 observations provide more information than 10. For reference, the Beta posterior variance is αβ / [(α+β)²(α+β+1)], which is smaller for Researcher B.


Question 5 | Bayesian Statistics and Machine Learning
A conventional point estimate gives one fitted parameter value, while a Bayesian approach can represent multiple plausible parameter values with a posterior distribution. Propagating that uncertainty into predictions can help researchers recognize when a model is less certain and avoid overstating its conclusions.
Example: A model classifying faint astronomical transients can report uncertainty when a signal is weak or unlike the training examples. Researchers can prioritize uncertain cases for follow-up observations rather than treating every high classification score as equally reliable.
Accept other well-reasoned applications, such as exoplanet detection, climate projections, or medical diagnostics. Distinguish uncertainty in model parameters from the model’s predicted class probability: a 90% class probability alone does not fully characterize parameter or model uncertainty.



