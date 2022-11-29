# Short Form Blog 1
Violence against women and girls is still one of the most widespread human rights violations in the world––in fact, in March, the UN chief stated that violence against women and girls may be the world’s “longest, deadliest pandemic” ([UN News](https://news.un.org/en/story/2022/03/1114472
)). Why has this pandemic of violence endured? By looking into data regarding this issue, we can help shed light on why this violence has such strong roots and what can be done to turn the vicious trend around.

It is difficult to get up-to-date and accurate data in the area of domestic violence because of the social stigma and potential danger that prevent females from reporting. However, [there is a dataset I accessed through Kaggle with survey data from the past decade that spans 70 countries](https://www.kaggle.com/datasets/andrewmvd/violence-against-women-and-girls). The dataset is from a Demographic and Health Survey ([DHS](https://dhsprogram.com/data/data-collection.cfm
)), which, according to The DHS Program website, is a “nationally representative population-based survey with a large sample size (usually between 5,000 and 30,000 households)” (DHS). This data could give some important insight into the intricacy of violence against women worldwide.

There are many factors that lead to the unjust treatment of women, many of which are known and some of which still need to be studied. To have the best chance at coming up with solutions to the issue of this violence, it is important to dive deep into potentially causal issues. **In this dataset, the focus is on the perception of whether a husband hitting or beating a wife is justified.** The respondents were given a list of statements and instructed to indicate whether they agree or disagree. The statements were as follows:

“A husband is justified in hitting or beating his wife…:
* ...if she burns the food”
* ...if she argues with him”
* ...if she goes out without telling him”
* ...if she neglects the children”
* ...if she refuses to have sex with him”
* ...for at least one specific reason”

I mentioned in my introduction that there is social stigma attached to domestic violence––but what are the intricacies of this social stigma? Who really thinks that violence is deserved, who thinks it is something to be ashamed of, and who is against it? The answers to these questions will help us understand the complex public landscape of this sensitive issue. In addition, a greater understanding of who believes domestic violence is justified will illuminate where social perception needs to change. To bring about a change in societal expectations of gendered violence, it would be extremely helpful to be able to target specific demographics contributing to societal acceptance. So, who are the people who are agreeing with the statements in the survey?

In order to narrow down the dataset for analysis and visualization, I focused on the country of Afghanistan. Therefore, my targeted question is:

## Are there patterns among Afghan demographic groups that indicate who is likely to agree with the justification of using violence against women?

The first graph explores the responses to the statement  “A husband is justified in hitting or beating his wife if she burns the food.” Respondents were instructed to choose between two options: “Agree” or “Disagree.” The graph below demonstrates the percentage of respondents who indicated that they agree with the statement regarding use of violence against women. The responses are broken down by gender and by age group, as seen on the x-axes. 

<img src="https://user-images.githubusercontent.com/114178058/201834451-b5bf5b28-7c25-4e6c-8e48-3ca91128b4cb.png" width=75% height=75%>

We can see here that the group with the highest response rate is surprising––it’s females ages 35-49. And, overall, all of the female age groups have higher response rates than all of the male groups. The rate for females in the age group 35-49 is 18.8%, which means that almost 1 in every 5 women survey respondents in Afghanistan believe that a woman deserves to be hit or beat if they burn the food they are cooking. The highest rate of agreement among men in response to this question is in the age group 15-24, and the response rate is 9.4%, which is only half of the women’s rate. This means that in the two older men’s age groups, **the amount of men who agreed with the statement was less than half of that of women in the oldest age group.** This begins to show that the perception of violence against women may differ between genders, and may actually be justified in the minds of more women than men. 



The next graph shows the distribution of responses to the statement “A husband is justified in hitting or beating his wife if she goes out without telling him.” The responses are broken down by gender and by geographic demographic (i.e. whether the respondent lives in a rural or urban area.)

<img src="https://user-images.githubusercontent.com/114178058/201834429-8716da15-3469-4e52-bf77-349df71ca82d.png" width=75% height=75%>

Here we can see a much higher rate of responses than the rate of responses to the previous question. WIthin rural populations, over 60% of men and women agree that a woman going out without telling her husband means she deserves to be treated with violence. In both male and female populations, we see that a lower rate of respondents from urban areas agree with the statement. Between genders, the rates for women are, again, slightly higher in both geographic demographics than for men. A few takeaways can be made from this graph, one being that a woman going out without telling her husband is perceived to be a very justifiable reason for women to be treated with violence by their husbands. Next, we see that this justification is just as, if not more, rooted in female perception as in men’s. Finally, we see that this perception is heightened in rural areas.



The next graph displays the responses to the statement “A husband is justified in hitting or beating his wife if she refuses to have sex with him.” The responses are broken down, again, by gender, and also this time by education level. 

<img src="https://user-images.githubusercontent.com/114178058/201834439-f5caef3c-ad22-45f4-9216-8f90939f10c9.png" width=75% height=75%>

Here, we see that there is a pattern in education level. In general, it appears that the higher the education level of the respondent group, the lower the rate of agreement with the statement. We see the largest jump in reaction from women with a secondary education to women who have received a higher education: the data show that around 1 in 4 women with a secondary education believes in the justification of violence for refusal to have sex whereas just about 1 in 10 women with a high education think the same. 




The final graph shows the distribution of responses to the statement “A husband is justified in hitting or beating his wife if she neglects the children.” This graph is broken down by gender and age group.

<img src="https://user-images.githubusercontent.com/114178058/201834460-5cbe5665-48ec-4889-85ab-1eb09def763c.png" width=75% height=75%>

The graph displays the stark difference in gendered responses here. In every age group, about double the number of female respondents agree with the statement about the use of violence in response to the wife’s child neglect than men. 



Overall, there are several limitations with the data. There is no way to know that the men and women responding to these surveys were in complete privacy and able to respond fully honestly. Along with the possibility of response bias, there is always the possibility of survey error, and because I am accessing this dataset from Kaggle, I don’t have access to all of the information about how the survey was conducted and where the possible survey error might come from. 



Given the data that we have, the visualizations provided above begin to delve into the question “in what groups is the use of violence against women justified?”. Looking at the graphs above, we see that in general, there is more justification of violence against women among women. This can start to target efforts of education and cultural stigma change. Going further, we can look into specific populations of women based on demographics such as age, geographic demographic, and education level. Narrowing down the populations where the justification of violence is most prevalent can help target efforts to reverse this justification. While the ultimate goal would be to reduce all of the response levels for men and women down to zero, starting in areas where the data may indicate that the stigma is the worst could be an impactful strategy. Also, targeting these areas, we can look into other specific aspects of these populations’ lifestyles to see more causal attributes that may lead to the mindset of violence justification and make steps to reverse these causal attributes.





Sources Cited:

Data set from The DHS Program accessed through Kaggle: 
https://www.kaggle.com/datasets/andrewmvd/violence-against-women-and-girls

Other sources:
https://news.un.org/en/story/2022/03/1114472
https://dhsprogram.com/data/data-collection.cfm


