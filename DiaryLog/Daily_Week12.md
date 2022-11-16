# Week 12   
## 1. Create covid4.md and use file metadata_snpeff_tidy_1000K_downsampled.rds

## 2. dNdS in different lineages
![dNdS_lineages](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/dNdS_lineages.png?raw=true) 

**Method as below**

## 3. Slope of Count_N/Count_S == 0 doesn't mean of neutral selection

Obs:
![slope_not_dnds](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/slope_not_dnds.jpg?raw=true)
Proof:
![slope_not_dnds_proof](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/slope_not_dnds_proof.jpg?raw=true)

## How to count dNdS
![dnds_basic](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/dNdS_basic.jpg?raw=true)
### Implement
![dnds_method](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/dNdS_method.jpg?raw=true)

## 4. Some Concern Lineages
![lineages](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/ConcernLineages.jpg?raw=true)
reference: https://www.ecdc.europa.eu/en/covid-19/variants-concern

## 5. dNdS_new of Concern Lineages
I did linear regression on all 455 Omicron lineages, and picked a subset of them to plot. Those plotted lineages are lineages of concern.

![inDifferentLineages](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/dNdS_in_different_concern_lineages.png?raw=true)   
**Blue: >1, positive   
Red: <1, negative**

XBB has not many data, very noisy.   
_dNdS of XBB: 11.26744_

## 6. Distribution of these lineages
一. Slope of Count_N   
![slope_N](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/Slope_CN.png?raw=true)   
二. Slope of Count_S   
![slope_S](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/Slope_CS.png?raw=true)   
三. Point plot of Count_N   
![point_N](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/Count_N.png?raw=true)   
四. Point plot of Count_S   
![point_S](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week%2012/Count_S.png?raw=true)

## 7.Conclusion   
Those "popular" lineages were mostly positive selected by environment. Thus, for BQ.1.1, we should focus on if it will continue been positively selected. And for XBB, with more data, dNdS would get lower, but will it still be positive?   

While result of BA.2 is "interesting". What happened to that? Non_Syn increased fast at first, while got flat after.

## 8. Continue   
I could take a look on the trend of dNdS on each lineages, that since when BA.2 changed from positive to negative?   

And I think BA.1 has been positively selected till end, it could mean that all BA.1 have been mutated to another lineage(some aa_change has been fixed.)