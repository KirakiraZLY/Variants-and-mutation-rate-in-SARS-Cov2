# Project in Bioinfo Note
### Zhang Leyi

## Some previous works   
Num of different types of variants   
![MutationOfTime](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Mutations%20during%20time.png?raw=true)   
VOC   
![VOC](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/VOC.png?raw=true)
## Week 4
-[x] count_S synonmous   
-[x] AA substitution
### 2022.9.18
By 6.synonmous based on !annotated, I found that most significant VOC skal vare:   
**VOC Alpha GRY, VOC Delta GK, VOC Omicron GRA.**  

P.S. Before 2021.6, there were many variants had no identified name, so all were NA.   
In CDC article, VOC are dragged to be: 
> Omicron(B.1.1.529, BA.1, BA.1.1, BA.2, BA.3, BA.4, BA.5)   
![Pic1](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Synonmous%20against%20date.png?raw=true)   
![NonsynonmousAgainstDate](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Non%20Synonmous%20against%20date.png?raw=true)
### 2022.9.19   
To get all the variants with AA Substitutions == "Spike_E484Q"
![E484Q](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/Spike_E484Q_Synonmous.png?raw=true)   
**It's interesting that E484Q only appeared from 2021-1 to 2022-1, before Omicron.**   
***So what are the major differences between Omicron and previous variants?***   
Guess: E484Q's dissappear is correlated to the advantage of Omicron, or to the escaping from immunity?
   
**Computing the slope**  
Using linear regression:<center> $y=WX+b$</center>    
Find out that:   
- For VOC Alpha GRY,  the slope is: 1.087e-02
- For VOC Delta GK,   the slope is: 1.289e-02
- For VOC Omicron GRA,the slope is: 4.326e-02
   

**GC Content**    
It shows that the stability of RNA of different variants are not changed significantly, so the different mutation rate would come from other reasons.
![GCContent](https://github.com/KirakiraZLY/Variants-and-mutation-rate-in-SARS-Cov2/blob/main/Img/GCContent.png?raw=true)   

🐰