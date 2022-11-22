# Producing Data and Sampling
# Introduction
**What is statistical inference?**
- What percentage of voters approve of the way the U.S. President is handling his job?
- This is difficult to determine exactly as there are more than 250 million people of voting age in the U.S.
- But it's not difficult to *estimate* this percentage quite well:
- Sample 1,000 (say) voters at random. Then use the approval percentage among those voters as an estimate for the approval percentage of all voters.

- **Population**: the entire group of subjects about which we want information. Ex: all U.S. voters
- **Parameter**: the quantity about the population we are interested in . Ex: approval percentage among all U.S. voters
- **Sample** is the part of the population from which we collect information. Ex: the 1,000 voters which were selected at random.
- **Statistic (estimate)**: the quantity we are interested in as measured in the sample. Ex: approval percentage among the sampled voters
- Key point: even a relatively small sample (100 or 1,000) will produce an estimate that is close to the parameter of a very large population of 250 million subjects.

# Simple Random Sampling and Other Random Plans
# Simple Random Sampling and Stratified Random Sampling

### Sampling correctly is very important
- It's tempting to sample 1,000 voters in your hometown.
- This is a **sample of convenience**. Not a good way to sample because voters will be different from the population of U.S. voters
- This will introduce **bias**, i.e., this sampling will favor  a certain outcome
- **selection bias**: a sample of convience makes it more likely to sample certain subjects than others
- **non-responsive bias**: the people who choose to respond to the question may be different from the non-responders. e.g. parents are less likely to answer a survey request at 6 pm because busy with children...
- **voluntary responses bias**: websites that post reviews of businesses are more likely to get responses from customers who had very bad or very good experiences

### Sampling designs
- The best methods for sampling use chance in a planned way:
- a **simple random sample** selects subjects at random without replacement
- a **stratified random sample** divides the population into groups of similar subjects called *strata* (e.g. urban, suburban, and rural voters). Then one chooses a simple random sample in each stratum and combines these.
- This sampling can result in a more precise estimate than with simple random sampling. However, it's more complicated to execute.

## Bias and Chance Error
Since the sample is drawn at random, the estimate will be different from the parameter due to chance error. Drawing another sample will result in a different chance error.
> estimate = parameter + bias + chance error

The chance error(sampling error) will get smaller as teh sample size gets bigger. Moreover, we can compute how large the chance error will be.

The bias (systematic error): Increasing the sample size repeats the error on a larger scale, and typically we don't know how large the bias is.

# Randomized Controlled Experiments and Observation Studies
## Observation vs. Experiment, Confounding, and the Placebo Effect

### Observational Studies
People who eat red meat have higher rates of certain cancers than people who don't eat red meat
- This means that there is an **association** between red meat consumption and cancer: there is a link between these two.
- But this does **not** mean that eating red meat *causes* cancer: people who don't eat red meat are known to exercise more and drink less alcohol, and it could be the latter two sides that cause the difference in cancer rates.

This is an **observational study**. It measures outcomes of interest and this can be used to establish association.

But **association is not causation**, because there may be **confounding factors** such as exercise that are associated both with red meat consumption and cancer.

### Randomized controlled experiments
- To establish causation, an **experiment** is required:
- A **treatment** (e.g. eating red meat) is *assigned* to people in the **treatment group** but not to people in the **control group**.
- Then the outcomes in the two groups are compared. To rule out confounders, both groups should be similar, apart from the treatment. To this end:
	- The **subjects** are assigned into treatment and control groups at **random**.
	- When possible, subjects in the control group get a **placebo**: it resembles the treatment but is neutral. Assigning a placebo makes sure that both groups are equally affected by the **placebo effect**: the idea of being treated may have an effect by itself.
	- The experiment is **double-blind**: neighter the subjects nor the evaluators know the assignments to treatment and control.

## The Logic of Randomized Controlled Experiments

Randomization serves two purpose:
- It makes the treatment group similar to the control group. Therefore influences other than the treatment operate equally on both groups, apart from differences due to chance.
- It allows to assess how relevant the treatment effect is, by calculating the size of chance effects when comparing the outcomes in the two groups.