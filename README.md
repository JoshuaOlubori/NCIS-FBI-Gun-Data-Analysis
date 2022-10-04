# Project: Analyzing Trends in Gun Sales Data across the U.S.

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

## Introduction

The data comes from the FBI's
National Instant Criminal Background
Check System. The NICS is used by to
determine whether a prospective
buyer is eligible to buy firearms or
explosives. Gun shops call into this
system to ensure that each customer
does not have a criminal record or
isn’t otherwise ineligible to make a
purchase. The data has been
supplemented with state level data
from census.gov.

``Mandated by the Brady Handgun Violence Prevention Act of 1993 and launched by the FBI on November 30, 1998, NICS is used by Federal Firearms Licensees (FFLs) to instantly determine whether a prospective buyer is eligible to buy firearms or explosives. Before ringing up the sale, cashiers call in a check to the FBI or to other designated agencies to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. More than 100 million such checks have been made in the last decade, leading to more than 700,000 denials.``

These statistics represent the number of firearm background checks initiated through the NICS. They do not represent the number of firearms sold

## Research Questions

*In this analysis, I will answer the following research questions*:

> - *How many guns were sold in the U.S. in selected years?*
> - *What kind of gun was bought the most in those years?*
> - *What are the overall monthly trends of gun purchases in those years?*

> - *What are the top 5 states in terms of gun purchases in the U.S. in those years?*
> - *What are the most bought gun types in those states?*
> - *What kind of gun was bought the most in one of those states?*
> - *What are the overall monthly trends of gun purchases in those states?*
>
> - *Which states had the highest growth in gun sales over the span of a decade?*

<a id='conclusions'></a>
# Conclusions

Caveats!<br>
**The findings of these analysis are summarised below. These are tentative and do indicate any causal relationship between variables.**<br>



> - *The most populous states in the United States in 2016 are California, Texas, Florida, New York and Illinois.* <br>
> - *The least populous states are Wyoming, Vermont, Alaska, North Dakota and South Dakota.*

> - *States with the highest median household income in 2016 are Maryland, Alaska, New Jersey, Connecticut and  Hawaii.*<br>
> - *States with the lowest median household income in 2016 are Mississippi, Arkankas, West Virginia, Alabama, and Kentucky.*

> - *States with the highest black population in 2016 are Mississippi, Louisiana, Georgia, Maryland and South Carolina.*<br>
> - *States with the lowest black population in 2016 are Montana, Idaho, Vermont, Wyoming and Utah.*

### 2006
> - *Long guns were sold the most in 2006 with about 5,268,550 units sold.*

> - *In 2006, handgun sales varied between 200 thousand and 300 thousand units throughout the year. However, long-gun sales started strongly at around 400 thousand  units in January, started sinking  in March till a year-low of just below 300 thousand units before dramatically  shooting up to about 800 thousand units at    the end of the year*

> - *The top 5 states in terms of gun sales are Texas, Pennsylvania, California, Florida and Ohio.*

> - *Among these states, only in Florida were handgun sales greater than long-gun sales.*

> - *All these states experience a remarkable dip in sales in the middle of the year.*

### 2015
> *9 years later in 2015, handguns became most bought gun types with a total of about 8 million units sold across all states in the U.S.*<br>

> *The same trend of a dip in sales around the middle of the year and a sharp rise in purchases towards the end of the year persists.*<br>

> *Texas remains the top state in terms of gun purchases.*

### 2016
> *A year later in 2016, total gun sales reached a little short of 16 million units. Handguns led the way at more than 8 million units.*<br>

> *Gun sales started relatively high compared to the previous years. I note the double dip in sales with second dip occuring around September. This double dip was mostly prominent in Florida. Another trend of note is that long-gun sales almost superceded handgun sales country-wise in November.*

>  *Texas, California, Florida, Pennsylvania and Ohio remains the top states in terms of gun purchases*
> - *Guam, Illinois, New Jersey, Connecticut and Massachusetts show the highest percentage increase in gun sales over the span of a decade (2006 - 2016). Hawaii, Mariana Islands, Iowa and Nebraska actually had gun sales reduced.*

> - *Gun sales per capita is weakly negatively correlated with `persons per household`; `persons without health insurance` (positive); `bachelor degree holder or higher` (negative)*; *`median housing unit costs` (negative)*; *`median gross rent` (negative)*
