---
{"dg-publish":true,"permalink":"/resources-data/knowledge/science/chemistry/significant-figures/"}
---

Digits in any measurement that are known with ==certainty== with an additional one digit which is ==uncertain==.
## Rules
1. All nonzero digits are significant.
	   Example:
	   Measured numbers: **247**
	   Number of Significant figures: **3**
2. Zero between non-zero digits are significant:
	   Example:
	   Measured numbers: **20303**
	   Number of Significant figures: **5**
3. Zeros to the left of the first nonzero digit are **NOT** significant.
	   Example:
	   Measured numbers: **0.0200**
	   Number of Significant figures: **3**
4. If the number is less than 1, then only the zeros at the end of the number and the zero between nonzero digits are significant.
	   Example:
	   Measured numbers: **0.003560**
	   Number of Significant figures: **4**
5. If the number is greater than 1, then all zeros written to the right of the decimal point are significant.
	   Example:
	   Measured numbers: **3,560.00**
	   Number of Significant figures: **6**
6. For the numbers with trailing zeros that do not contain a decimal point, the zeros may or may **NOT** be significant. To correct this, express the number in a scientific notation form.
	   Example:
	   Measured numbers: $3 \times 10^3$
	   Number of Significant figures: **1**
> [!note]
> In scientific notation, $3 \times 10^3 = 3,000$
7. Zeros used as placeholders ($502 \times 10^-3$) in a large number without a decimal point are not significant.
	   Example:
	   Measured numbers: $1.243 \times 10^-3$
	   Number of Significant figures: **4**
> [!note]
> In scientific notation, $1.243 \times 10^-3 = .001243$


## Examples of Significant Figures
1. $2365mm = 4$
	* All nonzero digits are significant. 
2. $309cm = 3$
	* All nonzero digits are significant. 
3. $5.030g = 4$
	* All nonzero digits are significant.
	* Zeros between nonzero digits are significant.
	* Zeros to the right of the decimal point and a nonzero digit are significant.
4. $0.0670g - 3$
	* Zeros to the left of the first nonzero digit are not significant.
	* Zeros to the right of the decimal point and a nonzero digit are significant.
5. $3.60 \times 10^-4 = 3$
	* All nonzero digits are significant.
	* Zeros to the right of the decimal point and a nonzero digit are significant.\

> [!note]
> In scientific notation for number 5, $3.60 \times 10^-4 = .000360$