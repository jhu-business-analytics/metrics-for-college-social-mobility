# Interpreting Colleges’ Roles in Social Mobility Based on Student and Family Demographics and College

## Background

Johns Hopkins University President Ron Daniels recently [published an article](https://www.theatlantic.com/ideas/archive/2020/01/why-we-ended-legacy-admissions-johns-hopkins/605131/?utm_source=feed) in The Atlantic earlier this month \(January 2020\) announcing that Johns Hopkins now has more Pell grant-eligible students than Johns Hopkins legacy students after eliminating legacy favorability from the admissions process in 2014. Daniels cites a few research studies that illustrate how a university legacy system can hinder top universities from matriculating a more diverse student body, and, therefore, that JHU’s new policy underlines their commitment to promoting social mobility and granting broader education opportunities to minority, low-income, and other underrepresented groups.

While this appears to be a step [in the right direction](https://www.nytimes.com/2019/09/07/opinion/sunday/end-legacy-college-admissions.html) “to make a Johns Hopkins education accessible to all talented students, to mitigate the burdens of debt, and to ensure that students receive the supports and services that will help them thrive,” how will we know if Johns Hopkins \(or any university\) has been successful in these efforts? We’ll take a look at open data that the [Opportunity Insights](https://opportunityinsights.org/) group produced for their [research](http://www.equality-of-opportunity.org/papers/coll_mrc_paper.pdf) \(summary [here](http://www.equality-of-opportunity.org/assets/documents/coll_mrc_summary.pdf%20)\) analyzing higher education’s role in upward mobility, to further approximate how colleges might want to analyze and interpret their own data

## Business Question

_**How can Johns Hopkins University know if their recent decision to end legacy preferences will better equip them to “educate \[more\] qualified and promising students from all backgrounds and to help launch them up the social ladder,” and what metrics should the university measure to monitor their progress?**_

## Data Question - Open Data

We'l use open data from two sources: 

1. **Opportunity Insights**: this research group works to "identify barriers to economic opportunity and develop scalable solutions that will empower people throughout the United States to rise out of poverty and achieve better life outcomes." They characterized the role that college's play in intergenerational income mobility in a 2017 study, and have made this data publicly accessible through their website. We will use two datasets from this study:
   1. [College Level Characteristics from the IPEDS Database and the College Scorecard](https://opportunityinsights.org/data/?geographic_level=100&topic=0&paper_id=0#resource-listing) \(mrc\_table10\): this dataset contains data about 2,464 higher education institutions in the United States including location, sticker price, student demographics, major distributions, acceptance rate, among other data points. A full data dictionary of the column variables is available [here](https://opportunityinsights.org/wp-content/uploads/2018/04/Codebook-MRC-Table-10.pdf).
   2. [Baseline Cross-Sectional Estimates of Child and Parent Income Distributions by College](https://opportunityinsights.org/data/?geographic_level=100&topic=0&paper_id=0#resource-listing) \(mrc\_table02\): this dataset contains aggregated data of children's and parents' income distributions from each college in 2000 and the child's income distribution as income-earning adults in 2013.  A full data dictionary of the column variables is available [here](https://opportunityinsights.org/wp-content/uploads/2018/04/Codebook-MRC-Table-2.pdf).
   3. [Crosswalk from the Department of Education's College-Level OPEIDs to Super-OPEID Groups used in Income Segregation and Intergenerational Mobility Across Colleges in the United States ](https://opportunityinsights.org/data/?geographic_level=100&topic=0&paper_id=0#resource-listing)\(mrc\_table11\): this dataset contains the "key" for the US Department of Educations's OPEID \(Office of Postsecondary Education Identification\) numbers and Opportunity Insights' "super OPEID" values. A full data dictionary of the column variables is available [here](https://opportunityinsights.org/wp-content/uploads/2018/04/Codebook-MRC-Table-11.pdf).
2. **United States Department of Education**
   1. [CollegeScorecard Data](https://collegescorecard.ed.gov/data/) \(from original data: MERGED2008_09PP.csv, column \_\_PCTPELL,_ Pell-related data only in GitHub repository: [CollegeScorecard\_Pell\_data.csv](https://github.com/jhu-business-analytics/metrics-for-college-social-mobility/blob/master/original_datasets/CollegeScorecard_Pell_data.csv)\): the original open data from the US Department of Education on US colleges contains several csv files of data related to college costs, financial aid, and value of higher education in the US. The csv document in the GitHub repository contains the [Pell Grant](https://studentaid.gov/understand-aid/types/grants/pell) specific information from the 2008-2009 academic year as an estimate for the percentage of Pell Grant recipients in 2000, since 2008-09 is the earliest year that this data is publicly available. 

## Data Question - Analysis

We’ll use Microsoft Excel to answer:

* **What did the US college landscape look like in 2000 and 2013?** Exploring general college data regarding enrollment, sticker price, expenditures, and other related metrics per university "tier" or ranking
* **How do parents’ and kids’ income data relate college tier?** Exploring the relationship between income distributions of students/parents entering colleges at different types of higher education institutions
* **How do colleges contribute to social mobility?** Exploring how students' income distribution changes when they are around the age of 35 \(likely earning a stable income instead of in between jobs or in graduate school\)
* **Is 'percentage of Pell-eligible students' a good metric to define student income diversity? What other metrics should JHU monitor to continue to develop a more robust student body and subsequent alumni network?** Exploring specific metrics related to Pell grant recipients to see how colleges can use this percentage--or other--metric\(s\)--to measure their social mobility impact 

## Data Answer



## Business Answer

