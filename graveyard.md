# Project Graveyard
During my PhD, like most others, many projects have been abandoned. Most often, either data limitations or the size of the contribution lead me to refocus my effort into new ideas. I think we should share these because others might try a similar idea and they can see why it didn't work. Either they come up with a solution or they abandon an idea sooner. Either way, I hope this saves someone time. If you'd like access to any of the data described, email me. 

### Mining Deaths and Voting 
While trying to come up with a final chapter for my disseration, I was trying to find employment data for Peru's mining industry dating back to 1945. As of writing this, I have not found that set of documents. However, I did find data on mortality within the mining industry since 2001. Mining is a very important industry, both historically and today, in Peru. It accounts for 10% of GDP and it has been estimated that each additional job in the sector creates 6 additional jobs in other sectors. There has been research devoted to social conflict that aries due to new and old projects, and one thing that stands out is that local communities often do not have a way to deter companies from mining. 

---

### School Board Elections and Superintendents
There are many papers on how school boards effect school outcomes. School board responsibilities include setting a vision and goals for their public schools, approving textbooks and other curriculum materials, and hiring a superintendent. This idea centers on the superintendent, as they're akin to CEO of the schools. Superintendents are the ones overseeing day-to-day operations, they recruit teachers and principals, and they are responsible for evaluating employees with duties related to tenure and termination. 

The questions I was most interested in asking were whether the racial composition of the school board influenced their decision on hiring a superintendent and if that could affect superintendent retention. I obtained the roster of superintendents dating back to 1997 in California and school board election data for the same period. My proposed method of identification was to use a regression discontinuity around close elections. Over the years, there would be elections with small margins of victories between white and non-white candidates so I would compare the length of tenure for superintendents in districts in which a non-white candidate wins by a few votes to those in districts where a non-white candidate lost by a few votes. I encountered two many issues with project.

1. The roster does not have ethnicity or race for most of the superintendents; I attempted to solve this by merging with census data. The 2000 Census includes the racial and ethnic distribution for the top 100 most common surnames, but I had high rate of false negatives for non-white candidates. This is particularly problematic because regression discontinuity requires many observations around the cut-off so losing observations is a major concern, but also any effect would be biased towards a null result since I would have treated units within my control group. 
2. I do not observe any additional information about the superintendents besides if they taught in CA in the data I have. Important information such as their education, experience, or why superintendents leave their position (fired,retired,etc).

To really pin down and explain hiring decisions and retention, much more information is needed. One solution would be to obtain data from another state, such as North Carolina that has much more data available about the individuals employed in its school districts. 

 [Slides](https://drive.google.com/file/d/1EyU29A9BA5E-_4G_vkFu5Z0XrgmvsLEJ/view?usp=sharing?){:target="_blank"}
 
---

### The Digital Divide and Consequences of Computer-Based Testing
This project started out of interest in learning and reading about the experiences of English Langauge Learners (EL) i.e., K-12 students in the US that did not speak English. I started with reading academic papers that were estimating differences in test scores by mode of instruction, which then moved to reading more about reclassification into mainstream classrooms. I learned that in the past few years, most states have transitioned to administering the test via computer as opposed to hand-written tests. From an administrative and grading persepective, this is a cost saving move, but what if students are not able to use the technology or typing slows them down, or even they make more mistakes when typing? I decided to test to see if switching from paper to computer hurts students. 

Most people working in this space use administrative records, accessing individual test scores. I am not in a position to attain such data so instead I looked for a state that had recently changed the test medium and had average test scores available at the school-grade level. The data is available for Connecticut, luckily I went grew up in Danbury, CT so I was also able to ask local EL teachers about their experiences teaching to better understand the context. In CT, all schools were forced to switch by the 2017-2018 academic year, but schools were able to switch earlier. Identifying an effect in this setting can be done by exploiting the staggered adoption of computer based testing. However, a two main problems arise. 

According to an education consultant from the Bureau of Student Assessment for CT's Department of Ed, there is not a list of when schools switched or a reason why.

* The first point can be overcome by emailing the person responsible for EL students in each district or school, but that would be quite labor intensive.
* The second point is very problematic as schools might select into switching before the deadline in a way that is unobservable and correlated with student achievement. For example, imagine the only reason schools switch earlier is if there are enough computers in a computer-lab for all the students to take the test at the same time. These schools are likely better funded and have more resources, and EL students may use computers more often in these schools for other activities or even for test prep. Therefore, comparing their test scores when switching from paper to computer to students in other schools would bias the estimate towards a null result. 

[Slides](https://drive.google.com/file/d/1dadyKR3FuzQR4HTd1PwVcbCzxcLxCFli/view?usp=sharing?){:target="_blank"}
