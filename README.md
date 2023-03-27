# Advanced Project - Health Classifier

University project - Carmen Werrlein, Adetola Oluwatayo, Oluwaseyifunmi Alfred Olaniyan, Ben Puhalski

## Resources

CDC - 2021 BRFSS Survey Data [Documentation](https://www.cdc.gov/brfss/annual_data/annual_2021.html)

Description of variables in dataset: [PDF](https://www.cdc.gov/brfss/annual_data/2021/pdf/codebook21_llcp-v2-508.pdf)

## Setup

1. [Download](https://www.cdc.gov/brfss/annual_data/2021/files/LLCP2021ASC.zip) the dataset and extract into the ``data/`` directory.
2. Run through ``clean_and_reduce.ipynb`` to get **brfss_reduced.csv**
3. Run through ``brfss_imputed.ipynb`` to get **brfss_imputed.csv**

## Building html

```bash
jupyter nbconvert --to html main.ipynb ; mv main.html html/index.html
jupyter nbconvert --to html data_clean.ipynb ; mv data_clean.html html/data_clean.html
jupyter nbconvert --to html preprocessing.ipynb ; mv preprocessing.html html/pre.html
jupyter nbconvert --to html playground.ipynb ; mv playground.html html/play.html
```
<a href="https://ai.benpuhalski.com">ai.benpuhalski.com</a>

<a href="https://ai.benpuhalski.com/data_clean.html">ai.benpuhalski.com/data_clean.html</a>

<a href="https://ai.benpuhalski.com/play.html">ai.benpuhalski.com/play.html</a>

<a href="https://ai.benpuhalski.com/pre.html">ai.benpuhalski.com/pre.html</a>
