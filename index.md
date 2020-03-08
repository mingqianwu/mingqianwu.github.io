## Welcome to My Personal Page
![useful image]({{ mingqianwu.github.io }}/ProfessionalPicture.jpg){:height="280px" width="210px"}

My name is Mingqian Wu. I'm currently a senior in University of Illinois at Urbana-Champaign. My major is Industrial Engineering and I also have a minor in Statistics. I plan to pursue Quantitative Finance in a graduate school after I finish my undergraduate study.

For more information, you can either see my [resume]({{ mingqianwu.github.io }}/Resume%20for%20work.pdf) or visit my [Linkedin page](https://www.linkedin.com/in/mingqian-wu-65718b14b).

My Gihub profile link is [here](https://github.com/mingqianwu).

## Blog Post
### Project I worked on
Last year I participated in Research Experience for Undergraduate (REU) program. The research topic is to predict volatility of S&P 500 index using different approaches such as Black-Scholes implied volatility, GARCH model and regression-based methods. The performances and limitations of each method were also analyzed and studied. A report for this project is [here]({{ mingqianwu.github.io }}/REU%20report_final_Mingqian_Wu.pdf). 

### Current Course

I'm currently taking STAT 385 Statistics Programming Methods. It is a course about programming in R. So far, we have learned many topics such as Data Type, Vectorizing and plotting. Here are some codes we learned: 

```{r}
# Vectorize
vec <- c(1, -2, 3, -4, 5, -6, 7, -8, 9, -10)
vec[vec<0] <- vec[vec<0]*-1
vec[vec<5] <- vec[vec<5]*2
vec
# [1]  2  4  6  8  5  6  7  8  9 10

# plot a histogram and a scatter as a 1*2 matrix
par(mfrow=c(1,2))
hist(x=faithful$waiting,main = "Histogram of Waiting Time",xlab = "Waiting Time (mins)",ylab = "Density",border = "dodgerblue", probability = TRUE)
box()
grid()
plot(x=faithful$waiting,y=faithful$eruptions,main = "Waiting Time vs. Eruption Time",col="blue",xlab = "Waiting Time (min)",ylab = "Erupyion Time (min)",pch=16)
box()
grid()
```
![useful image]({{ mingqianwu.github.io }}/plot.png)


