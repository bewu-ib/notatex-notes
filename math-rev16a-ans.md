# Review set 16A

## 1.
$H_0$: The buses’ arrival follow expected distribution – they are on time

**Null hypothesis is always the “positive” one**.

## 2.
a) $p = 0.0794$ – chance for observed data to happen given $H_0$ 
b) significance level – the lowest value of p with which we don’t have to reject $H_0$
c) we reject $H_0$, because p-value – $0.0794 <$ significance level – 0.10

## 3.
Expected:
$\mu_{0}= 13$

Observed:
$n = 30$
$\bar{x} = 12.8$
$\sigma=1.6$

significance level – 0.05

$H_0$: Mean number of shaves is 13 – $\mu = \mu_{0}$
$H_1$: Mean number of shaves is not 13 – $\mu \neq \mu_0$

Test: t-test – 1 sample – variable

$p = 0.4989 > 0.05$ – **no need to reject $H_0$**

## 4.
Expected:
$\mu_{0} = 90$

$H_0$: Mean weight of apricots didn’t change – $\mu = \mu_0$
$H_1$: The weight of apricots got reduced – $\mu < \mu_0$

Observed: *some data*

Test: t-test – 1 sample – list
significance level – 0.01

$p = 9.67 \cdot 10^{-4} < 0.01$ – reject $H_0$

## 5.
Observed:
n = 12

$\bar{x_{1}}= 10.9$
$\bar{x_{2}}= 10.25$

$\sigma_{1}= 3.34$
$\sigma_{2}= 2.26$

Expected:
$H_0$: Joe and Ruben are on the same level – $\mu_{1}=\mu_{2}$
$H_1$: Joe is better than Ruben – $\mu_{1}>\mu_{2}$

Test: t-test – 2 sample – variable
significance level – 0.05

$p = 0.291 > 0.05$ – no need to reject $H_0$ – Joe isn’t better than Ruben

## 6.
Observed (time of shopping in minutes):
| Supermarket A | Supermarket B |
| ------------- | ------------- |
| 12            | 14            |
| 28            | 35            |
| 13            | 32            |
| 7             | 21            |
| 22            | 14            |
| 19            | 8             |
| 4             | 2             |
| 13            | 16            |
| 6             | 24            |
| 11            | 27            |
|               | 19            |
|               | 42            | 
Test: t-test – 2 sample – list
significance level – 0.1

$H_0$: mean time spent in both shops is the same – $\mu_{1}= \mu_{2}$
$H_1$: $\mu_{1} \neq \mu_{2}$

$p = 0.0863 < 0.10$ – reject $H_0$ – mean time spent in both shops is different

## 7.
Expected (n = 70):
| Small | Medium | Large | X-Large | XX-Large |
| ----- | ------ | ----- | ------- | -------- |
| 7     | 14     | 24.5  | 17.5    | 7        | 

Observed:
| Small | Medium | Large | X-Large | XX-Large |
| ----- | ------ | ----- | ------- | -------- |
| 4     | 7      | 22    | 24      | 13       | 


Test: $\chi^2$ goodness of fit
significance level – 0.05

$H_0$: Data follows expected distribution
$H_1$: Data doesn’t follow expected distribution.

$df = 4$

$p = 0.0134 < 0.05$ – reject $H_0$ → the store should change the distribution of shirt sizes

## 8.
Expected (n = 250):
| Super rare | Rare | Uncommon | Common |
| ---------- | ---- | -------- | ------ |
| 12.5       | 25   | 62.5     | 150    | 

Observed:
| S. rare | Rare | Uncommon | Common |
| ------- | ---- | -------- | ------ |
| 5       | 17   | 76       | 152    | 

Test: $\chi^2$ goodness of fit
significance level – 0.01
$df = 3$

$H_0$: Data follows the expected distribution
$H_1$: Data doesn’t follow the expected distribution

$p = 0.0185 > 0.01$ – no need to reject $H_0$

## 9.
Observed:
|             | 18-30 | 31 - 54 | 55+ |
| ----------- | ----- | ------- | --- |
| Increase    | 234   | 169     | 134 |
| No increase | 156   | 191     | 233 | 

significance level – 0.1
Test: $\chi^{2}$ test for independence *(2way on calculator)*

$H_0$: age and opinion about speed limit are independent
$H_1$: age and opinion about speed limit are dependent

$p = 7.37 \cdot 10^{-10} < 0.1$ – reject $H_0$ – there is an association between the age of the driver and their opinion on the speed limit
