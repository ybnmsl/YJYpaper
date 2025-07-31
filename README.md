<h1 align="center">Compilation of Issues in Yang Jingyuan's Thesis</h1>

&emsp;&emsp;This repository is dedicated to documenting the issues found in the **excellent** master's thesis by Yang Jingyuan, a student of International Economics and Trade at Wuhan University, titled "An Economic Analysis of the Impact of Fertility Behavior on Domestic Violence in China and India." I believe this repository is indeed<sup>[1]</sup> the **most comprehensive** record of errors on the entire internet. The original thesis can be found [here](./paper/YJYpaper.pdf). Everyone is welcome to comment and list more errors, or to provide addresses for reporting them. As shown below, this was declared by Dr. Yang herself!
![sm](./pic/sm.jpeg)

❗A blogger (Li Ranyuxin) has been visited late at night by "Pink-shirt Bro" and two "Gold Bros"!!! The video is on [Quark Cloud Drive](https://pan.quark.cn/s/10cebfa84661#/list/share), and I'm suddenly feeling a bit scared!!!

Friendly Link: [Pillar of Shame for Yang Jingyuan and Wuhan University](https://github.com/yangjingyuan0828/awesome-yangjingyuan)

## 📑TODO
- [x] Collect issues in the thesis (continuously updating...)
- [x] Provide a [tutorial](./doc/export2PDF.md) on converting this document to PDF 🔥🔥🔥
- [x] Report to the Ministry of Education of the People's Republic of China [as shown in the picture](./doc/jb1.jpeg)
- [ ] Report to the [Academic Committee of Wuhan University](xsxf@whu.edu.cn)
- [ ] Report to the [China Academic Degrees and Graduate Education Development Center (CDGDC) of the Ministry of Education](jdjb@cdgdc.edu.cn)
- [ ] Report on the Research Integrity Management Information System of the Ministry of Education
- [ ] Report to the Hubei Provincial Department of Education
- [ ] ...

## 🔧Main Issues
### Suspected Fabrication/Falsification

1.  Suspected content fabrication (Page 1, third to last line):

    >For example, the "Immediate Arrest Act"（“立即逮捕法案”） introduced in some countries and regions,

    No "Immediate Arrest Act" related to domestic violence could be found. This is suspected to be a reference to "Mandatory Arrest Laws"（“强制逮捕法案”）.

2.  Content fabrication (Page 2, fifth line):

    >And in 2001, with the introduction and promotion of the "Divorce Law"（“离婚法”）, 

    China has never enacted a "Divorce Law." This is a fabrication.

3.  Data fabrication (Page 14, Figure 2.1):

    >Figure 2.1 Histogram of Domestic Violence Incidence Rates in Countries Worldwide:
    >![plt](./pic/plt.jpeg)

    The y-axis represents frequency, which refers to the number of occurrences of xxx and can only be an integer. However, the figure in the thesis shows decimals, indicating that the data is fabricated.
    Even if each bar is calculated at its maximum value of 5, the total is only 60, which is far from the 100 countries claimed. This suggests data fabrication.

4.  Suspected data fabrication (Page 43, Table 5.1):

    >![t5.1](./pic/tab4.jpeg)

    The sum of urban and rural samples does not equal the total sample, suggesting data fabrication.
    For example: 5230 + 5287 = 10517 ≠ 10519
    &emsp;&emsp;&emsp;5510 + 5354 = 10864 ≠ 10867

5.  Suspected data fabrication (Page 45, Table 5.2):

    >![t5.2](./pic/tab5.jpg)

    The sum of urban and rural samples does not equal the total sample, suggesting data fabrication.

6.  Suspected data fabrication (Page 46, Table 5.3):

    >![t5.3](./pic/tab6.jpeg)

    The sum of urban and rural samples does not equal the total sample, suggesting data fabrication.

7.  Suspected data fabrication (Page 47, Table 5.4):

    >![t5.4](./pic/tab7.jpeg)

    The sum of urban and rural samples does not equal the total sample, suggesting data fabrication.

8.  Suspected data fabrication (Page 48, Table 5.5):

    >![t5.5](./pic/tab8.jpeg)

    The sum of high-caste and low-caste samples does not equal the total sample, suggesting data fabrication.

### Suspected Plagiarism

1.  Paragraph plagiarism (Page 2, last paragraph):

    >In India, according to the official report of the National Crime Records Bureau of India, of the 405,000 criminal cases against women in 2019, more than 30% were domestic violence cases. India's NFHS-5 data from 2021 shows that among Indian women aged 18-49, nearly one-third have experienced domestic violence, and 32% of married women have suffered physical, sexual, or emotional violence from their partners, of which 27% of women have experienced at least one form of violence in the year prior to the survey.

    This is suspected to be plagiarized from the paper: He Hui, Wang Linglin. "Practice and Effectiveness of Anti-Domestic Violence in India" [J]. Modern World Police, 2022(11):58-64.（何晖,王凌林.印度反家庭暴力的实践与成效[J].现代世界警察, 2022(11):58-64） No citation appears in Yang's original text.

    ![en_abstract](./pic/pap2.jpg)

2.  Paragraph plagiarism (Page 3, first paragraph):

    >The imperfect legal system and complex reporting procedures are external reasons for the high incidence of domestic violence in India. As early as 1983, Section 498A of the revised Indian Penal Code stipulated that if a husband or his relatives abuse a woman, they shall be sentenced to a maximum of three years in prison and a corresponding fine. In June 2005, India passed its first "Protection of Women from Domestic Violence Act". However, India's anti-domestic violence laws have not been amended to reflect social changes. At the same time, complex reporting evidence and procedures, coupled with a lack of strict enforcement, have rendered India's anti-domestic violence legal system a mere formality, with many cases left unresolved. By the end of 2020, the conviction rate based on Section 498A was less than 20%, and Indian courts had a total of 651,000 pending Section 498A domestic violence cases.

    This is suspected to be plagiarized from the paper: He Hui, Wang Linglin. "Practice and Effectiveness of Anti-Domestic Violence in India" [J]. Modern World Police, 2022(11):58-64. No citation appears in Yang's original text.

    ![en_abstract](./pic/pap1.jpg)

3.  Suspected incomplete deletion after plagiarism (Page 4, last paragraph):

    >In December 2013, the Standing Committee of the Twelfth National People's Congress passed the "Resolution on Adjusting and Improving Fertility Policies," **which stipulated, that is, the policy allowing couples where one parent is an only child to have two children**. Less than two years later, to further promote balanced population development and correct the gradually imbalanced population structure, in October 2015, the Fifth Plenary Session of the 18th CPC Central Committee explicitly proposed the implementation of a universal two-child policy, henceforth giving all couples the right to have two children.

    The phrase "which stipulated, that is, the policy allowing couples where one parent is an only child to have two children" (其中规定，即单独二孩政策) does not fit with the surrounding text and is suspected to be an artifact of incomplete deletion after plagiarism.

### Data Errors

1.  Numerical error (Page 3, sixth to last line):

    >Among more than two hundred countries in the world, 104 have a total fertility rate below the 2.1 required for intergenerational population balance.

    There are 193 UN member states and 2 observer states (Vatican and Palestine), not "more than two hundred countries." The author is suspected of counting Hong Kong SAR, Macau SAR, and Taiwan Provice as independent countries. This constitutes a serious **political error**, which should be thoroughly investigated.

2.  Year error (Page 4, seventh line):

    >After the founding of New China（People's Republic of Chine, 新中国）, due to the gradual stability and development of the social economy, the total national population grew from 542 million before 1049 to 830 million in 1970.

    People's Republic of China was founded in 1949, not 1049. This is the second serious **political error**.

3.  Common sense error (Page 15, last paragraph):

    >It is predicted that the world population will peak at 10.3 billion in 2087, after which it will slowly decline to 10.3 billion in 2100.

    God knows what was reduced here. One of these figures must be incorrect.

4.  Abnormal x-axis (Page 20, Figure 2.8, Figure 2.9):

    >![pic 2.8](./pic/img2.8.jpeg)

    It seems T_1 is missing.

5.  Table data error (Page 39, Table 4.1):

    >![tab 4.1](./pic/tab2.jpeg)

    The maximum values in Panel B and Panel C of Table 4.1 are abnormal.

6.  Table data error (Page 40, Table 4.2):

    >![tab 4.2](./pic/tab3.jpeg)

    The minimum, maximum, and range values in Table 4.2 are inconsistent.

7.  Year error (Page 45, last paragraph, fourth line):

    >The impact of fertility on domestic violence continuously weakened from 1990-201.

    A digit is missing from the year.

8.  Abnormal x-axis (Page 55, Figure 6.7):

    >![tab 4.2](./pic/pic.jpeg)

    It appears "post-event period 8" was written as "post-event period 7".

### Data Analysis Errors

1.  Common sense analysis error (Page 21, first paragraph, last three lines):

    >![idiot](./pic/img2.jpg)

    As shown in the figure, 0.01% should be one in 10,000 women.

2.  Abnormal data analysis (Page 24, Figure 2.15):

    >![idiot](./pic/v2.jpg)

    After extracting the data from Figure 2.15 (shown above as 2.1) on page 24 of the thesis and performing a linear fit (see above figure 2.2), the linear fit equation is y = 0.1067x with an R² of 0.1083. Detailed data can be found in the [attachment](./paper/testdata.csv).
    It has been verified that the R-squared of this data is only 0.1, proving that fertility rate and domestic violence incidence are almost unrelated.

3.  Analysis error (Page 25, sixth to last line):

    >This paper uses per capita Taoist temple data in each region to measure the degree of traditional thought in that region.

    Taoism is a religion, and the distribution of religions varies across regions. Therefore, the number of per capita Taoist temples has no direct relationship with the degree of traditional thought in a locality.

4.  Forced fitting (Page 26, Figure 2.18):

    >![idiot](./pic/img.jpeg)

    The points in the figure are too scattered, with no obvious linear relationship. The large disparity in domestic violence rates between Gansu and Fujian, both regions with traditional concepts and similar fertility rates, shows that this line is not suitable for demonstrating the relationship between concepts and domestic violence.

5.  Formula analysis error (Page 33, seventh line):

    >The increase is 1/2.

    The increase here should be ϕα/2.

6.  Incorrect model usage (Page 37):

    In Section 4, "Data and Empirical Strategy," 4.1, "Empirical Strategy," 4.1.1, "Empirical Strategy Based on Two-Way Fixed Effects Model."

    >![model](./pic/picc.jpeg)

    The dependent variable DV in this model represents whether an individual has experienced domestic violence. Since the dependent variable DV has only two possible values (a binary variable) - having experienced domestic violence or not - this is a classic "binary choice model."
    A basic principle of econometrics is that a linear model cannot be used to explain a binary choice variable. A Logistic regression or Probit regression model should be used.
    However, the so-called "two-way fixed effects regression model" 4.1 used in the thesis is a linear model. This is a serious error. The thesis used the wrong model, and its main empirical results are unreliable.

7.  Basic calculation error (Page 43, last line):

    >The incidence of domestic violence in the urban sample increased by 3.2%, while in the rural sample it increased by 5.4%, a difference of 2.1%.

    5.4% - 3.2% = 2.2%, not 2.1%.

### Writing and Expression Errors

1.  Abstract translation error:
    >Chinese keywords: 生育 (Fertility); 家庭暴力 (Domestic Violence); 母职惩罚 (Motherhood Penalty); 社会规范 (Social Norms)

    >English keywords: Fertility; Domestic Violence; Outside Option; Social Norm

    The translation of "母职惩罚" (Motherhood Penalty) and "Outside Option" do not correspond.

2.  Abstract translation issue:

    >![en_abstract](./pic/zhaiyao.jpeg)

    The characters for "关键词" (Keywords) were not translated into the English word "Keywords."

3.  Concept confusion (Page 1, second paragraph, first to third lines):

    >The "Global, Regional, and National Survey on the Prevalence of Domestic Violence Against Women" released by the World Health Organization in 2018 shows that the lifetime prevalence of domestic violence among women of childbearing age is as high as 27%, meaning 27% of women have experienced physical and/or sexual violence from a husband or male intimate partner at least once in their lifetime.

    If a male intimate partner is not married to the woman, it is not considered domestic violence.

4.  Typo (Page 3, caption for Figure 1.2):

    >Note: In the figure, the horizontal axis is the timeline, and the vertical axis is the domestic violence incidence rate. The domestic violence incidence rate for 1998-2021 was calculated using the Indian NFHS2-5 surveys. At the same time, Figure 1.2 marks the judicial reform times related to the incidence of domestic violence in India. In addition, since 2006, the Indian civil anti-domestic violence organization "Pink Bang" (粉红邦) has been active in northern India, also effectively reducing the incidence of domestic violence.

    Misspelled "粉红帮" (Gulabi Gang) as "粉红邦" (Pink State). In Chinese, both characters "帮" and "邦" are pronounced as "bang".

    The phrase "NFHS2-5次调查" (NFHS2-5 times survey) appears to be grammatically awkward.

5.  Typo (Page 4, first line):

    >Following the burst of the stock and real estate market bubbles in the 90s era (90 年带).

    Should be "年代" (decade/era), not "年带." In Chinese, both characters "带" and "代" are pronounced as "dai".


6.  Typo (Page 5, ninth to tenth lines):

    >These clinics were mainly responsible for distributing contraceptive-related drugs and (即) devices.

    Used "即" (that is) instead of "及" (and). In Chinese, both characters "即" and "及" are pronounced as "ji".


7.  Typo (Page 6, sixth to seventh to last lines):

    >And the key factors that determine a woman's outside choice (选则) include the woman's characteristics.

    Should be "选择" (option/choice), not "选则." In Chinese, both characters "择" and "则" are pronounced as "ze".


8.  Typo (Page 8, sixth to seventh lines):

    >At this time, there will only be expressive domestic violence (大家暴).

    The character "大" (big/large) is likely a typo for "的" (a possessive/descriptive particle).

9.  Incorrect character (Page 8):

    Page 8, in the section "Other Literature on Domestic Violence," sixth line:
    >For example, g it found through data from Vietnam that, 

    God knows what "g" means.

10. Missing word (Page 8, last line):

    >A transfer of resources _不一_ occur.

    Omitted a character from "不一定" (not necessarily).

11. Typo (Page 9, second to last line):

    >Childbirth will also 是的 women's 工资率 rates to decrease.

    Used "是的" (is/yes) instead of "使得" (cause/make); "工资率" (wage rate) is likely a typo for "工资" (wages).

12. Typo (Page 10, last paragraph):

    >Discussions in family economics on the mechanisms of domestic violence can mainly be divided into two 只 of literature. The first branch, starting from family bargaining power, discusses the price mechanism behind expressive domestic violence. The second branch, from the purpose of instrumental domestic violence, explains the potential rent-seeking nature of domestic violence.

    In Chinese, 只 (zhī) is the measure word for animals (like 'a cat'), while 支 (zhī) is the correct measure word for a branch of literature, making the error a common homophone typo.

1.  Typo (Page 13, 2.1.1, first paragraph):

    >![picture](./pic/picture.jpeg)

    Simultaneously used four different expressions: "家庭暴力的终身发生率" (lifetime prevalence of domestic violence), "终身家庭暴力发生率" (lifetime domestic violence prevalence), "家暴的终生发生率" (lifetime prevalence of domestic violence), and "家暴发生率" (domestic violence prevalence).
    Suspected confusion between "终身" and "终生" (both mean lifetime, but are used in slightly different contexts).

2.  Typo (Page 13, sixth to last line):

    >245 million - 307 million girls (女生) are experiencing domestic violence.

    Likely used "女生" (girls/female students) instead of "女性" (females).

3.  Incorrect time (Page 15, first paragraph, fourth line):

    >A sharp contrast to the dramatic increase between 1960 and -1665.

    Likely mistyped 1965 as 1665.

4.  Typo (Page 15, third to last line):

    >In the future, Africa's population win an award（获奖） 90% of the world's population growth.

    Likely used "获奖" (win an award) instead of "或将" (will likely).

5.  Grammatical error and typo (Page 16, seventh to last line):

    >I think (本人认为) there seems to be （似乎） and is indeed (确实) a positive relationship between fertility rate and domestic violence incidence.

    Likely meant "This paper argues" (本文认为) instead of "I think" (本人认为); "seems to be indeed" (似乎确实) is redundant and grammatically awkward.

6.  Typo (Page 18, third line):

    >...employment status, and other dimensions (纬度).

    Used "纬度" (latitude) instead of "维度" (dimension).

7.  Typo (Page 18, second paragraph, sixth line):

    >Childbirth indeed had (遭成) an impact on women's employment.

    Used "遭" (suffer) instead of "造" (cause/create).

8.  Typo (Page 18, second paragraph, last line):
    >...and the difference in relative income level with the husband, as well as the fertility situation, all had (遭成) an impact on domestic violence.

    Used "遭" (suffer) instead of "造" (cause/create).

9.  Typo (Page 18, last paragraph, third line):

    >...is 忽略不计 (忽略不及).

    This phrase may be grammatically awkward, and it misspells "忽略不计" (negligible).

10. Character order error (Page 22, sixth to last line):

    >It can be seen that when a woman's income is far less than her husband's (i.e., less than 1/4 of her husband's income when), the incidence of domestic violence is higher.

    The character "时" (when) should be moved after the closing parenthesis.

11. Typo (Page 24, first paragraph, third line):

    >This is consistent with the research framework pre-set between (之间) this paper.

    Likely used "之间" (between) instead of "之前" (before/previously).

12. Superfluous word (Page 24, second paragraph, first line):

    >Figure 2.16 through (通) shows the relationship between fertility quantity and average domestic violence incidence in our country.

    The character "通" is superfluous.

13. Punctuation error (p25):

    >Page 25, fifth to last line: "Gansu, Fujian Tibet and Liaoning, etc."

    A顿号 (enumeration comma) should be used between "Gansu" and "Fujian"; no punctuation between "Fujian" and "Tibet".

14. Inappropriate word choice (Page 26, sixth to last line):

    >This paper (本文) divides provinces into regions with strong clan ideology and weak clan ideology.

    Likely meant "The figure" (图中) instead of "This paper" (本文).

15. Incorrect figure caption (Page 26):

    Caption below Figure 2.19:
    >"Figure 2.19 Scatter Plot of Average Quantity and Average Domestic Violence Incidence (Classified by Degree of Clan Culture)"

    Omitted "Fertility" from "Average Fertility Quantity," resulting in "Average Quantity."

16. Incorrect figure note (Page 27, note below Figure 2.19):

    Note below Figure 2.19:
    >Note: In the figure, the horizontal axis represents the average fertility quantity of each province, and the vertical axis represents the average domestic violence incidence. This paper uses the measurement (横梁) variable for clan culture from Chen (2021), i.e., the per capita number of genealogies in each region, and classifies based on this variable. Solid dots and solid lines represent regions with stronger clan concepts, while hollow dots and dashed lines represent regions with weaker clan concepts. The results show that in regions with weaker clan concepts, there is a positive correlation between fertility quantity and domestic violence incidence.

    Misspelled "衡量" (measurement) as "横梁" (beam).

17. Incorrect abbreviation (Page 27, section 2.2.4):

    >Also known as Scheduled Castes (abbreviated as CS).

    The abbreviation is incorrect. It should be SCs or SC.

18. Repeated text, missing punctuation (Page 35, last line to Page 36, first line):

    >From an economic incentive perspective, the higher the probability of the husband's domestic violence of the husband's domestic violence

    The phrase "丈夫家暴的" (of the husband's domestic violence) is repeated, and a period is missing at the end.

19. Extra symbol (Page 40, third to last line):

    >Including whether the husband has ever beaten you, etc.,.

    An extra comma was added.

20. Misspelled word (Page 40, second to last line):

    >Descriptive statistics of respondents' answers in the NHHS4 survey are shown in Table 4.3. From the table, we can see

    Misspelled "NFHS4" as "NHHS4."

21. Inconsistent spacing in multiple places:

    Throughout the text, "NHHS4" and "NHHS 4" as well as "NHHS3" and "NHHS 3" are used interchangeably, with inconsistent spacing. For example, in the last paragraph of page 40.

22. Typo and incorrect character (Page 41, table):

    >![table](./pic/tab.jpeg)

    Likely wrote "x7." instead of "7."

    Wrote "被破" (broken) instead of "被迫" (forced).

23. Extra symbol (Page 43, fourth to last line):

    >3 (more than 5 births))), the probability of domestic violence increases by 4.4%.

    Two consecutive closing parentheses were used.

24. Inappropriate subject (Page 45, first line):

    >I (本人) still use whether the individual is 40 years old for grouping.

    Likely meant "This paper" (本文) instead of "I" (本人).

25. Typos (Page 45, fifth to sixth to last lines):

    >Therefore (因此) the outside option is worsened, making them more vulnerable to domestic violence, and when the offspring grow up to be adults (长大承认),

    Likely meant "Because" (因为) instead of "Therefore" (因此); misspelled "长大成人" (grow up to be adults) as "长大承认" (grow up to admit).

26. Repeated text (Page 48, second to last paragraph, second to third lines):

    >Whether it is the NFHS3 (2005-2006 survey) or the NFHS4 (2015 and 2017 survey) survey

    The word "survey" (调查) is repeated.

27. Repeated text (Page 49, first paragraph, fifth line):

    >Considering that at event time 0 (the year of the child's birth),

    The word "event" (事件) is repeated.

28. Typo (Page 50, second to last paragraph, second line):

    >In urban areas (诚征), there was a significant increase in domestic violence in the first period after childbirth,

    Misspelled "城镇" (urban areas) as "诚征" (sincere recruitment).

29. Typo (Page 56, middle paragraph, third line):

    >And in the population (人均) with an average level of education

    Misspelled "人群" (population/group) as "人均" (per capita).

30. Extra symbol (Page 56, third to last line):

    >...the motherhood penalty in populous states (accounting for over 95% of the total sample)).

    An extra closing parenthesis was added after "motherhood penalty."

31. Typo (Page 57, middle paragraph, second line):

    >...starting from the current period (档期) of childbirth and continuing until the eighth year after childbirth.

    Likely used "档期" (schedule slot, esp. in entertainment) instead of "当期" (current period).

32. Typo (Page 59, first paragraph, third line):

    >The incidence of domestic violence will immediately (即可) decrease after childbirth.

    Used "即可" (can then) instead of "即刻" (immediately).

33. Typo (Page 59, second paragraph, third line):

    >The group with a higher level of education (受教育群体较高的人群).

    Wrote "受教育群体较高" (higher educated group) instead of "受教育水平较高" (higher education level).

46. Typo (Page 61, policy implications, third paragraph, last line):

    >...can allow victims to more conveniently (方面) end the violent relationship.

    Used "方面" (aspect) instead of "方便" (convenient).

47. Typo (Page 67, acknowledgements, third paragraph, fourth line):

    >So I hope (希翼) to build a fertility-friendly society.

    Likely used "希翼" (a rare word for hope) instead of the more common "希冀" (hope/wish for).

48. Punctuation error (Page 67, acknowledgements, fourth paragraph, first line):

    >We often hear, isn't the status of Chinese women high enough already?,

    Used a question mark and a comma together.

49. Multiple name misspellings (Pages 17, 20, 25, 40, 42, 51, 55):

    1.  Misspelled "Kleven" as "Kelvin" multiple times, appearing on pages 17, 40, and 42.
    2.  Misspelled "Kleven" as "Kelven" multiple times, appearing on pages 20 and 55.
    3.  Misspelled "Kleven" as "Kelvev" on page 25.
    4.  Misspelled "Kleven" as "Kelevn" on page 51.

50. Multiple errors in figure notes (Pages 56, 57, 58):

    1.  In the note for Figure 6.8, "NFHS 3" is written as "NFHS3 年" (NFHS3 year).
    2.  In the note for Figure 6.9, "NFHS 3" is written as "NFHS3 年".
    3.  In the note for Figure 6.10, "NFHS 3" is written as "NFHS3 年".
    4.  In the note for Figure 6.11, "NFHS 3" is written as "NFHS3 年".

### Formatting and Standardization Errors

1.  Page number error:
    >![page](./pic/pg.jpeg)

    The format of the page numbers on the cover, declaration, abstract, and table of contents is incorrect.

2.  Indentation issue:
    >The beginning of each paragraph in the English abstract is not indented.

3.  Formatting error (p1):
    Page 1, second paragraph, second to third lines: "meaning 27% of women have experienced physical and/or sexual violence..."
    >There is no need to use "and/or"; "or" alone can also express the meaning of "and".

4.  Incorrect time (p15):
    Page 15, first paragraph, third to seventh lines: "According to Figure 2.2. Since the 1970s, the total fertility rate worldwide has begun to decline significantly, in sharp contrast to the dramatic increase between 1960 and -1665. The average number of children a woman would have during her childbearing years dropped from 4.79 in 1970 to 2.40 in 2019, a decrease of nearly half. As of 2021, the world's average total fertility rate has approached the 2.1 required for intergenerational population balance."
    >Bold text with unknown meaning.

5.  Figure caption formatting error (Page 44):

    >Figure 5.1: The Impact of the Number of Children on Domestic Violence

    A colon is used after "Figure 5.1," which is inconsistent with the formatting of other captions.

6.  Citation format error (Page 53, last paragraph, first line):

    >This paper is based on the regional clan variable constructed by Chen (2021 年)"

    The format of this citation is inconsistent with others in the text.

7.  Personal Question

    Are thesis references at Wuhan University's Economics and Management School sorted alphabetically by first letter? Are cross-references not used? It feels very strange. We request an official explanation of the format from Wuhan University.

### Academic Ethics Issues
This article discusses the correlation between domestic violence and fertility, traditional culture, religion, and female employment. By forcibly linking domestic violence with culture and religion when the data fit is low, this topic may involve serious **academic ethics issues**.

### Reference Citation Errors

1.  Figure/Table citation error (Page 26, seventh to last line):
    >Figure 2.19 reflects this phenomenon. This paper divides provinces into regions with strong and weak clan ideologies, and the results show that in regions with strong clan ideologies, an increase in fertility is often accompanied by a lower incidence of domestic violence.

    Figure 2.19 shows the relationship between domestic violence and fertility, not religion.

2.  Suspected duplicate citation (Page 63):

    >[43] Card D, Dahl G B. Family Violence and Football: The Effect of Unexpected Emotional Cues on Violent Behavior[J]. The Quarterly Journal of Economics, 2011, 126(1): 103-143.
    >[44] Card D, Dahl G B. Family Violence and Football: The Impact of Unexpected Emotional Cues on Violent Behavior[J]. Quarterly Journal of Economics 2011, 126(1): 103-143.

    In [44], "Effect" is suspected to be mistyped as "Impact."

3.  Suspected incorrect title (Page 63):

    >[46] Cesur R, Sabia J J. When War Comes Home: The Impact of Combat Service on Domestic Violence[J]. Review of Economics and Statistics, 2016, 98(2): 209-225.

    The title I found is "When War Comes Home: The Effect of Combat Service on Domestic Violence."

4.  Complete duplicate (Page 64):

    >[59] Dugan L, Nagin D S, Rosenfeld R. Explaining the Decline in Intimate Partner Homicide: The Effects of Changing Domesticity, Women's Status, and Domestic Violence Resources[J]. Homicide Studies, 1999, 3(3): 187-214.
    >[60] Dugan L, Nagin D S, Rosenfeld R. Explaining the Decline in Intimate Partner Homicide: The Effects of Changing Domesticity, Women's Status, and Domestic Violence Resources[J]. Homicide Studies, 1999, 3(3): 187-214.

5.  Incomplete citation (Page 65):

    >[72] Guo R. A Theory of Differential Fertility under Filial Piety[J].

    The name of the conference/journal and the year of publication are not specified.

    This paper cannot be found on Crossref, Google Scholar, or Google, and is suspected to be AI-generated.

6.  Complete duplicate (Page 65):

    >[87] McElroy M B, Horney M J. Nash-Bargained Household Decisions: Toward a Generalization of the Theory of Demand[J]. International Economic Review, 1981, 22(2): 333.
    >[88] McElroy M B, Horney M J. Nash-Bargained Household Decisions: Toward a Generalization of the Theory of Demand[J]. International Economic Review, 1981, 22(2): 333.

7.  Incomplete citation (Page 66):

    >[96] Ramos A. Household Decision Making with Violence: Implications for Conditional Cash Transfer Programs[J].

    The name of the conference/journal and the year of publication are not specified.

8.  Complete duplicate (Page 66):

    >[101]Tauchen H V, Witte A D, Long S K. Domestic Violence: A Nonrandom Affair[J]. International Economic Review, 1991, 32(2): 491.
    >[102]Tauchen H, Witte A, Long S. Domestic Violence - a Nonrandom Affair[J]. International Economic Review, 1991, 32(2): 491-511.

    The meaning of the hyphen "-" in [102] is unclear.

9.  Suspected citation of a chemistry paper (Page 66):
    >[105]Wilson W W, Haiges R, Christe K. Contents Lists Available at Sciencedirect[J]. 2023.

    The phrase "Contents Lists Available at Sciencedirect" in this citation is not a title of an article but an instruction. The source of this article is suspected to be a journal related to chemical materials.

10. It is difficult to find citations in the main text for some of the references listed in the bibliography.

    For example, I cannot find most of the papers cited in section 1.2.2 on pages 9-10 in the reference list.

## 🏗️My Demands
- Demand that Wuhan University revoke Yang Jingyuan's master's degree.
- Demand that Wuhan University revoke its punishment decision against student Xiao and issue a public apology.
- Demand that Wuhan University guarantee student Xiao's smooth graduation and not expel him on the grounds of physical or mental health issues or exceeding the study period.
- Demand the release of Yang Jingyuan's college entrance examination (Gaokao) admission information.
- Demand that Yang Jingyuan's party admission sponsors publicly state their evaluation of the incident where Yang falsely accused Xiao.

## 📖References
[1]Yang Jingyuan. An Economic Analysis of the Impact of Fertility Behavior on Domestic Violence in China and India. Wuhan University, 2024

## 🙏Acknowledge
- Thanks to everyone who submitted issues.
- Thanks to Zhihu user Yunshan.
- Thanks to Zhihu user TonggongSame.
- Thanks to Bilibili uploader "Shui Lunwen de Chengxuyuan" (The Programmer Who Pads Papers).
