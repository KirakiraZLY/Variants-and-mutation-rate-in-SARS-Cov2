# Week 11

## Update the data before
### 1. L452R
![L452R,DELTA](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/L452R/L452R%2CDELTA.png?raw=true)   
![L452R,OMICRON](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/L452R/L452R%2COMICRON.png?raw=true)   
![L452R,BA.2](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/L452R/L452R%2CBA.2.png?raw=true)   
![L452R,BA.5](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/L452R/L452R%2CBA.5.png?raw=true)
![L452R,BF.7](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/L452R/L452R%2CBF.7.png?raw=true)

### 2. Prep Viral Lineage Among Infection
Date: after 2022-09-01
![PrepViralLineageAmongInfection](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/PrepViralLineageAmongInfection.png?raw=true)   

   
### 3. Mutation rate of different * 
$$ 
y=XW+b 
 $$ 
![Mutation_Variants](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/MutationRateofDifferentVariants.png?raw=true)   
![Mutation_Lineages](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/MutationRateofDifferentLineages.png?raw=true)

### 4. Symptoms via *   
![Symptoms_Variants](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Symptoms/Symptoms%20via%20Variant.png?raw=true)
![Symptoms_Omicron](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Symptoms/Symptoms%20via%20Lineages%20Omicron.png?raw=true)   
![Symptoms_Lineages](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/Symptoms/Symptoms%20via%20Lineages.png?raw=true)

### 5. dNdS by date   
$$
dNdS=\frac{NumN - NumN_\beta}{NumS - NumS_\beta} 
$$
![dnds_Delta](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dndsDelta.png?raw=true)
![dnds_Omicron](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dndsOmicron.png?raw=true)
![dnds_BA.2](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dnds_BA.2.png?raw=true)
![dnds_BA.5](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dnds_BA.5.png?raw=true)
![dnds_BF.7](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dnds_BF.7.png?raw=true)
![dnds_BQ.1.1](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dnds_BQ.1.1.png?raw=true)

We can infer that dNdS in most proportion of Delta are much higher that those of Omicron, while in Delta there are also more with negative value, meaning dnds_delta smaller than dnds_beta.
**While a strong stratification can be seen in point plot of Delta**   
![dNdS_Delta_point](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dNdS_point_Delta.png?raw=true)
![dNdS_Omicron_point](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/dNdSbyDate/dNdS_poing_Omicron.png?raw=true)

### rdNdS comparing to Delta
$rdNdS=\frac{dNdS_L}{dNdS_\delta}$
![rdNdS](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Week11/rdNdS_lineage_delta.png?raw=true)

## Next
1. How to improve on dNdS analysis?   
In articles I read, they just used dnds and MK test, with checking p-value(by which test?).   
Other than this, I don't have idea. Can I implement it with neural network or machine learning?

2. Quantify on others?
3. Other directions to analyze strength of selection?