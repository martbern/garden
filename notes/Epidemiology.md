# Epidemiology

## Multiple Comparisons Problem
[Stanford Lagunita Video](https://lagunita.stanford.edu/courses/Medicine/MedStats./Summer2015/courseware/ea998389c16042f399ccff01e5bab161/a6ea67a1a37643d68bbd6c686da33aef/)

Signifikansniveau = type-I fejlrate

## Does this apply to the litterature as a whole?
Put another way, when you look at the litterature as a whole, you expect 5% of all comparisons to turn out false-positives at a p ≤ 0,05 level, given complete independence between tests.

If tests are dependent, so that tests that are positive increase amount of tests in that area, you expect the rate of false-positives to be higher.

§ p(< 0.05 | H_0 true) = 0.05 §

However, if dependent tests are counted together as one test, you expect it to be lower. As such, individual comparisons are probably unreliable, but general conclusions are more reliable.

However, if we're interested in the probability of H0 being true given a p < 0,05, or whether it truly is a false positive, we have to consider the logical reversal. § p(H_0 true | <0.05 ) ≈ 0.50 §, due to bias etc. See "/Sterne JA and Smith GD. Sifting through the evidence./"

Replication improves statistical power *and /dramatically/* decreases the risk of experimenter-bias.

## How do I get around it?
One way of getting around "at least one positive finding" in a single paper is to choose primary outcomes and secondary outcomes. Primary outcomes carry the brunt of your significance (eg. fewer tests that you'll take seriously), whereas secondary results should be taken lightly.

If a primary outcome is significant, it's really interesting. If a secondary outcome is significant, it should weigh very lightly epistemiologically.

Or you can correct your secondary outcomes for multiple comparisons.

### P-value corrections
Basically moves the problem up one level. Makes it so that the probability of our paper having *one* false positive is 0,05, rather than the probability of any given test being a false-positive is 0,05.

#### Bonferroni
Simple, assumes complete independence between tests, way too conservative.

Divides significance level among tests. Eg., significance level .050 divided by 4 tests, .0125.

## Why is the p-value distribution uniform?
The P-value is the chance of getting a result that's as or more different from the H0 as your current result.

It's the probability of getting your current p-value given that H0 is true:

§ p(H_0 true | p(x)) §

If the H0 is true, there's no difference between estimates and, as such, estimates should be distributed around H0 in whichever way the current test accounts for. Any difference from H0 is going to be completely random. The distribution of complete randomness is near-uniform.

<!-- #Life -->

<!-- {BearID:C0C5CC4B-568F-4F82-810E-9D6B83EFBFD8-15756-000013035CABEFC3} -->
