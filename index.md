## Welcome to My Personal Page
![useful image]({{ mingqianwu.github.io }}/ProfessionalPicture.jpg){:height="280px" width="210px"}

My name is Mingqian Wu. I'm currently a senior in University of Illinois at Urbana-Champaign. My major is Industrial Engineering and I also have a minor in Statistics. I plan to pursue Quantitative Finance in a graduate school after I finish my undergraduate study.

For more information, you can either see my [resume]({{ mingqianwu.github.io }}/Resume%20for%20work.pdf) or visit my [Linkedin page](https://www.linkedin.com/in/mingqian-wu-65718b14b).

My Gihub profile link is [here](https://github.com/mingqianwu).

### Current Course

I'm currently taking STAT 385 Statistics Programming Methods. It is a course about programming in R. So far, we have learned many topics such as Data Type, Vectorizing and plotting. Here are some codes we learned: 

```{r}
par(mfrow=c(1,2))
hist(x=faithful$waiting,main = "Histogram of Waiting Time",xlab = "Waiting Time (mins)",ylab = "Density",border = "dodgerblue", probability = TRUE)
box()
grid()
plot(x=faithful$waiting,y=faithful$eruptions,main = "Waiting Time vs. Eruption Time",col="blue",xlab = "Waiting Time (min)",ylab = "Erupyion Time (min)",pch=16)
box()
grid()
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/mingqianwu/mingqianwu.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
