# How much Ukrainian economy will contract?

*This is my final project at the KSE Summer Data School (10.06.2022 - 17.06.2022) prepared in one day (one night, actually).*

My goal is to estimate a contraction of Ukrainian GDP due to russian invasion using various nowcasting models based on ML algorithms.

For this project, I use quarterly data on 17 macroeconomics indicators. Time series were seasonaly adjusted if necessary. Sources for the data are National Bank of Ukraine and State Statistical Service of Ukraine.

It is estimated that mean estimated Real GDP shrinkage in 2022 due to the war is **-33.8%** comparing to 2021.

Project's slides are available at *Environments -> github-pages* or via [*this link*](https://horovoi.github.io/final-project-Horovoi/).

The project is made in R, slides are prepared with [Quarto](https://quarto.org).

**Post presentation update (27 March 2023):**
- According to preliminary estimates of the Ministry of Economy of Ukraine, the GDP decline in 2022 is [estimated](https://www.kmu.gov.ua/en/news/minekonomiky-poperedno-otsiniuie-padinnia-vvp-v-2022-rotsi-na-rivni-304) at **30.4%**.
- Thus, the forecast error on a validation data is **-3.4%**.
