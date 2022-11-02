# Week 11

## 1. What happened with the stratification of data?
![stratification](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Data_by_region.png?raw=true)   
In this plot, we can see that there are many n>50 before 2022-01, which looks weird. If this happened due to the limitation of detection condition?   
![countrylist](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Stratification_country.png?raw=true)   
It seems no? But we don't know why then.   

## 2. Non-syn and Syn number change during time
![non-syn](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Num_of_Nonsyn_with_date.png?raw=true)   
![syn](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Num_of_Syn_with_date.png?raw=true)   
It seems that both mutate gradually?   
Then do dn/ds test!!!   

## 3. alternative of dn/ds
Since we don't have the gene sequencial data, we cannot make count on number of syn or non-syn sites.   

### ZLY formula(rdNdS)
![zly_formula](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/ZLY_formula.jpg?raw=true)
rdNdS: ratio of dn/ds   
![rdNdS](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/rdNdS.png?raw=true)   
rdNdS in different lineages and variants. **Numerator represents the elder group, and Denominator represents the youth group.** It shows that Delta variants were better adapted to elder group, while Omicron are inverted.   
![rdNdS_in_diff_var](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/rdNdS_in_diff_var.png?raw=true)   
Grouping by different age, it's because generally we assume that elder group has weaker immune system than youth, thus we can regard them as two different immune environments.   
**But it's very surprising to see Omicron is better adapted to the youth.**

## Q1: In 2., count_S decreased in a period? why not gradually?   
## Q2: About rdNdS, why prefer youth group now?   
plausible reasons:   
1. in both groups, it is negative selected, while new variants get stronger adaptation in **youth group**.
2. dnds(youth) > 1, dnds(elder) < 1, but why?
3. both > 1, least possible, due to the selection in nature