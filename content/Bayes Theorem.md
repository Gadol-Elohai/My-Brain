# Bayes's theorem tells us how to modify our expectations based on new knowledge.

Date: 2021-10-31 

Bayes's theorem is a theorem in probability that tells us how to modify probabilities, or change our expectations of something being true, based on some other related fact. 

The form is 
$$P(A|B)=P(B|A)P(A)/P(B)$$
where _P(A|B)_ means "How likely is it that A is true if B is true?", _P(A)_ is "how likely is it that A is true?", and _P(B)_ is "how likely is it that _B_ is true?"

It was devised by Thomas Bayes (theologian and mathematician), published in 1763. It is the basis of [Bayesian Probability](<Bayesian Probability.md>). 

## Example
The prevalence of cancer in the total population is 5%, and terminal cancer in the general population is 0.3%, and we have a perfect test for cancer (all cancer-positives are given positive and all cancer-negatives are given negative): If we know that the individual in front of us has cancer, how likely is it that it is terminal cancer?

_P(A|B)_ = the likelihood that the patient has terminal cancer if they have cancer.
_P(B|A)_ = the likelihood that the patient has cancer if they have terminal cancer. _= 100%_. Every person with terminal cancer also has cancer.
_P(A)_ = 0.3%
_P(B)_ = 5%

The theorem says:
$$P(A|B) = P(B|A)*P(A)/P(B)$$
$$P(A|B) = 1 * 0.003 / 0.05$$
$$P(A|B) = 0.06$$

So, there is a 6% likelihood that the cancer patient in front of us has cancer.