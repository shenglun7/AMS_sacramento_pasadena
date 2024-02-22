# AMS_sacramento_pasadena

Shenglun Wu

Correspondance should be addressed to shlwu@ucdavis.edu

## Summary
This repository is for data analysis of results from AMS measurements from UCD Mobile Smog Chamber Systems in Sacramento (2020), and Pasadena (2021). The goal of this project is to understand the response of aerosol formation (i.e., SOA, inorganic aerosols) to the perturbation of NOx and VOCs in the ambient air in California.
This repository contains data, code, result.
- code
    - src
    - script
- data
    - raw
      - log_sheet_pasadena: the log sheet file for Pasadema measurements
      - Summary_O3_PA:
         - bag1_int = intercept of linear regression coefficient of O3 concentration in bag1
         - bag1_sl = slope of linear regression coefficient of O3 contration in bag1
         - bag1_t0 = initial measured O3 concentration in bag 1
         - bag1_3hr = 3-hour projected O3 concentration in bag1
         - b1_b2_3hr = delta O3 (bag1 - bag2)
         - b3_b2_3hr = delta O3 (bag3 - bag2)
    - intermediate
    - final
      - box_model_input_sacramento: ambient temperature profile in Sacramento (input file of box model)
      - box_model_output_isopleth: modelled data file for plot isoplth
          - O3: final O3 concentration
          - NOx: initial NOx concentration
          - VOC(OFP): VOC level, Ozone formation potential
          - N(V): final nitrate concentration
          - S(VI): final sulfate concentration
- result
