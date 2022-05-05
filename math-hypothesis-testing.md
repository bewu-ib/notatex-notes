# Hypothesis testing

## Correlation coefficient

r – correlation coefficient
$-1 \leq r \leq 1$

- $|r| > 0.9$ – strong correlation
- $|r| > 0.6$ – moderate correlation

 - $r = 1$ – perfect positive correlation
 - $r = -1$ – perfect negative correlation
 - $r \approx 0$ – no correlation

## — $\chi^2$ Test for independence

### Example
Is favourite music genre and age dependent?

**Observed data**:
| Music genre / Age | $\leq 20$ | 20-40 | 40+ | TOTAL |
| ----------------- | --------- | ----- | --- | ----- |
| Classical         | 15        | 21    | 42  | 78    |
| Rap               | 61        | 32    | 71  | 164   |
| Techno            | 31        | 27    | 25  | 83    |
| TOTAL             | 107       | 80    | 138 | 325   | 

**Expected data (if independent)**:
| Music genre / Age | $\leq 20$ | 20-40 | 40+  | TOTAL |
| ----------------- | --------- | ----- | ---- | ----- |
| Classical         | 25.7      | 19.2  | 33.1 | 78    |
| Rap               | 54        | 40.7  | 69.6 | 164   |
| Techno            | 27.3      | 20.4  | 35.2 | 83    |
| TOTAL             | 107       | 80    | 138  | 325   |

**$H_{0}$ – Null Hypothesis** – Age and favourite music genre are *independent*
$H_1$ – Age and favourite music genre are *dependent*

$p = 4.2184 \cdot 10^-3$ – probability for **observed data** given **$H_0$**
$\chi^{2} = 15.245$ – difference between *observed* and *expected* data given $H_0$
$df = 4$ – *degrees of freedom* – how many “free values” are there

$p <$ significance level → **reject $H_0$**
$\chi^{2} >$ critical value → **reject $H_0$**

## — $\chi^2$ Goodness of fit


### Example
Checking if a D6 (six-sided dice) is balanced

**$H_0$: D6 is balanced**

Observed data:
| Score | 1   | 2   | 3   | 4   | 5   | 6   |
| ----- | --- | --- | --- | --- | --- | --- |
| N     | 27  | 23  | 21  | 19  | 15  | 15  | 

Expected data:
| Score | 1   | 2   | 3   | 4   | 5   | 6   |
| ----- | --- | --- | --- | --- | --- | --- |
| N     | 20  | 20  | 20  | 20  | 20  | 20  |

Significance level – 5%
$df = 5$

$p = 35.8\% > sl = 5\%$ → No need to reject $H_0$ 

## — t-Test

### Example
Is one tree giving bigger apples than the other?

Observed data (weight in grams of apples):
| Tree 1 | Tree 2 |
| ------ | ------ |
| 137    | 152    |
| 141    | 158    |
| 161    | 163    |
| 157    | 142    |
| 142    | 139    |
| 171    | 151    |
|        | 162    |
|        | 171    |
|        | 169    | 

$\bar{t_{1}}= 151.5$ – mean weight of *sample of apples* from 1st tree
$\bar{t_2} = 156.3$ – mean weight of *sample of apples* from 2nd tree

**$H_0$**: Mean weight of apples from both trees is the same – $\mu_{1}=\mu_{2}$
**$H_1$**: Mean weight of apples from both trees are different – $\mu_{1} \neq \mu_{2}$

$p = 0.464 > 0.05$ – **no need to reject $H_0$**
