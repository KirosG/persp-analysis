##### MACS 30000

##### Fangfang Wan

##### Assignment 1

1. Introduction

​        In behavioral economics, social norm is a theory stating that observing other people's behaviors can influence an individual's decision, while standard economics theories rule out such psychological effect from behaviors of surrounding human beings. In this research, I plan to conduct an experiment to investigate how social information about friends' usage of Venmo (a money transfer app on smartphones) on Facebook can alter individual's behaviors of using Venmo in the United States, including downloads, linkage of Venmo account to Facebook account, usage frequency and transfer amount. There are similar studies concerning social norms using data from Facebook, but in different scenarios. For instance, Bond et al.

[^ Robert M. Bond, Christopher J. Fariss, Jason J. Jones, Adam DI Kramer, Cameron Marlow, Jaime E. Settle, and James H. Fowler]: *A 61-million-person experimentin social influence and political mobilization.* (Nature 489, no. 7415(2012)): 295-298.

 conducted a randomized controlled trial during 2010 congress election, and concluded that receiving social messages on Facebook regarding friends’ voting, especially close friends’ voting, significantly increased actual voting. However, unlike voting, usage of Venmo is an economic behavior. Will people be more "rational" in the standard economic sense when they make economic decisions, even if facing with pressure from comparing with peers? Does social norm still significantly alters people’s behavior when economic budget constraint is in the scenario? These are the questions that this research is intending to answer. 

2. Experimental Design

​        The experimental design aims to investigate whether the information on friends' usage of Venmo can affect individual's Venmo usage. I will divide active user population on Facebook into 3 subgroups - those have linked their Venmo account to Facebook, those have Venmo account but have not linked their account to Facebook, and those who do not have a Venmo account at the time when the experiment starts. I will gain these user information in collaboration with Facebook, Venmo and banks. Each subgroup is divided into treatment and control groups. Treatment group receives information about their friends’ usage on Venmo, which shows who downloaded Venmo, who linked Venmo to their account, and transferred money to whom without showing the amount due to privacy issues. In contrast, control group will not receive any information about friend’s usage of Venmo. The division into treatment and control groups is based on controlling factors they provided on Facebook including age, gender, education and geographical location of residence. The experiment will last for 1 year. 

​       Over the 1 year time span, I will track 4 indicators that measure people’s usage of Venmo, including downloads, linkage to Facebook, usage frequency and transfer amount. Using difference-in-difference method, I will track and compare changes in these measures between treatment and control groups once per week over the 1 year time span. I will also further compare changes in these measurements of population associated with different genders, age groups, educational levels and states of residence. The measurement methods for these four usage indicators are included below:

* Downloads - change in the number of individuals who have Venmo on their smartphones. One individual can contribute at most 1 to this measurement to exclude scenarios like replacing phones, etc. Data comes from smartphone app stores, such as Apple store.
* Linkage to Facebook - change in the number of individuals who linked their Venmo accounts to Facebook accounts. Data comes from Venmo and/or Facebook.
* Usage frequency - change in the average usage frequency per month per person over the 1 year span. Data comes from Venmo.
* Usage amount - change in the amount transferred per month, including delivered and received amount per person, which are recorded separately, over the 1 year span. 
  3. Big Data Analysis

​       In this section, I will analyze the advantages and disadvantages of bigdata proposed by Salganik 

[^ Matthew J. Salganik]: *Bit by Bit: Social Research in the Digital Age.*  (Princeton University Press, 2017), Chapter 2.3 Common characteristics of big data. <http://www.bitbybitbook.com/>

in this research context. As for advantages, to begin with, the scale of data is big in terms of population, information per person, and time span. The population on Facebook in the United States is very large, and such large population can be beneficial to subgroup analysis since population in each subgroup is still fairly large, and even small while systematic variations in usage amount indicators will be captured due to such large data scale. Besides, since the project will last for 1 year, there will also be substantial longitudinal information per person throughout the whole year. Moreover, because we use a randomized controlled trial research design, and due to the scale of data, concluding causality from the effect of social norms to Venmo usage with big data is easier than with smaller scale data. In addition to the bigness characteristic, the always-on feature of the data allows us to track user behaviors over time. Once we have compiled data from the whole year, we can further analyze the whole dataset, and may discover some new features in user behaviors that we did not capture while tracking data. Furthermore, the non-reactive characteristic can rule out potential Hawthorne effect, thus providing authentic data of user behaviors. 

​       However,big data can also negatively impact this research. The most prominent problem is that data is not complete. Some people don’t provide their full demographic and education information, so the division into treatment and control groups in each subgroup might not be proven random. Therefore, I will use computing algorithms to impute their age, gender, region of residence (on state level) and educational level based on their profile picture, friend’s demographic information, pages they liked, other demographic information that are available,etc. If due to severe lack of information it is still difficult to impute demographic and educational information of some users, I will omit them from the experiment. Incompleteness also brings dirtiness to data, so it requires substantial and careful data cleaning before starting working on it. Moreover, some people may have small number of friends, or Venmo is not popular in their regions or age groups. Therefore, even if they are assigned to treatment group, they might not have received information regarding their friends’ Venmo usage. As a result, in the first month, I will track who has seen social information about their friends’ Venmo usage and who has not, exclude those people in treatment group but does not receive any social messages about Venmo usage, and then exclude some people from control group to control for demographic and educational indicators to re-randomize, if necessary. Moreover, data might be difficult to obtain due to privacy and commercial issues, but it is still possible to obtain through proper negotiations. Financial data can be sensitive, but making only population level available to public rather than individual level can largely solve this problem. In addition, the non-representativeness of population might also lead to problems in the universality nature of experimental results. On Facebook, the ratio of teenagers and young adults is very likely to be larger than the ratio of people of elder ages, and due to peer pressure, mental and personality development, it is likely that young people tend to be affected by their friends’ behavior more than older people. Therefore, we might not be able to apply the research result to the whole population, since the resulted social norm effect will likely to be upward biased, if we apply the result to the whole population in the United States. Besides, the lack of universality does not solely come from the divergence of population on Facebook from population in the real world. Since this experiment will be conducted on population who live in the United States, due to difference in cultures, conducting similar experiment in other countries may yield different results. If the experiment is conducted in some cultures that require higher conformity to social norms and encourage less individual traits, results may reflect significantly higher social norm effects. In contrast, in cultures that require less conformity, such effect might not even be obvious. 

 

Bibliography

Bond, Robert M., Christopher J. Fariss, Jason J. Jones, Adam DI Kramer, Cameron Marlow, Jaime E. Settle, and James H. Fowler. *A 61-million-person experiment in social influence and political mobilization.* Nature* 489, no. 7415(2012): 295-298.

Salganik, Matthew J. *Bit by Bit: Social Research in the Digital Age*. Princeton University Press,2017. Chapter 2.3 Common characteristics of big data. http://www.bitbybitbook.com/ 