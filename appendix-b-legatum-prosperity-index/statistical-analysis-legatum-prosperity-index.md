# Statistical analysis : Legatum Prosperity Index

![2020 Economic Freedom Index vs the 2019 Legatum Prosperity Index ](https://lh4.googleusercontent.com/d63cP9YzuQzjLTR19HoGs1-suhDMAVe7e8jtgMbET_S-_Etz3-7iBR4CiobMF3HQckKbtJRMacMP3h26NfP_OVCBzXknTAh1Kd2ZjLA_wI1AkQjpvV0rl7t1YUTeHvvYo9wRvIjf)

_Our mission at the Legatum Institute is to create the pathways from poverty to prosperity, by focussing on understanding how prosperity is created and perpetuated. Prosperity entails much more than wealth: it reaches beyond the financial into the political, the judicial, and the wellbeing and character of a nation — it is about creating an environment where a person is able to reach their full potential. A nation is prosperous when it has effective institutions, an open economy, and empowered people who are healthy, educated, and safe._   
****- Baroness Philippa Stroud, Legatum Prosperity Report, 2019

In this section

1. [Strong liberalization hypothesis](statistical-analysis-legatum-prosperity-index.md#strong-liberalization-hypothesis)
2. [Legatum Prosperity Index](statistical-analysis-legatum-prosperity-index.md#legatum-prosperity-index)
3. [Dominant signal : general national success](statistical-analysis-legatum-prosperity-index.md#dominant-signal-general-national-success)

The Figure above presents a statistical relationship between national level measures of Economic Freedom and the Legatum Prosperity Index. The measure covers aspects of economy, heath, education, environment, and psychological/social indicators of well being.  This simple statistical relationship may help to provide legitimacy and political support for market liberalization policies associated with the Economic Freedom Index.

## Strong liberalization hypothesis

_By all measures of prosperity, at all stages of development those societies which have embraced all the policies that support greater economic freedom and unrestrained operation of capital markets are better off than those that do not._

This section aims to explore the statistical relationships between economic policies and the prosperity measures in mode detail and whether there are more complex relationships. Specifically, the aim is to examine to what extent the data supports or refutes the strong version of the hypothesis of liberalization policies. 

Three lines of enquiry into the liberalization hypothesis:

1. [Competing objectives : trade-off of measures of prosperity](competing-objectives-trade-offs.md)
2. [Dependency of relationships on stage of development](dynamic-role-of-the-state.md)
3. [Subset of liberalization policies which have stronger evidence than others.](uneven-evidence-for-subsets-of-policies.md)

## Summary of analysis

The conclusion of the analysis finds evidence supporting all three of these inquiries, thus rejecting the strong hypothesis.  In contrast the evidence would be stronger for a weaker, conditional version of the hypothesis which incorporates these considerations. First, there appears to be one single “hidden” feature that closely links many of the measures of prosperity and development of modern societies.  The statistics still support the general hypothesis that open markets and their institutional features - property rights, domestic and financial markets - have a strong relationship with society-wide goals. Such goals cover a range of “good” outcomes from education, to basic material needs to health and also to making environmental improvements.  There are a number of exceptions however - existence of trade-offs, variance in significance of a subset of policies and variation of the relationships with development stage.  

While strong institutions of markets - property rights, contract enforcement may be beneficial, other claims of liberalization policy on labor and foreign direct investment \(FDI\) do not appear to have as strong of a statistical relationship.  The statistical relationships of market liberalization vs other institutional factors like governance, social capital is generally strong across all development levels, but for each cohort of development the relationship varies - with the strongest link to markets in the transition period, and stronger links to governance for developing and advanced economies.  While many society-wide goals are complimentary, including local, noxious environmental objectives, climate change and greenhouse gas emissions is an unusual challenge possibly because it is negatively associated with energy consumption and its consequences are diffuse in time and space.  The ability to draw strong conclusions is limited but the first pass analysis of statistical structures can be used as a screening method to develop more focused follow-up analysis.

## Appendix sections

1. [Statistical relationships between measures of success](generic-success-and-labor-productivity.md)
2. [Competing objectives : trade-offs between metrics](competing-objectives-trade-offs.md)
3. [Dynamic role of the state](dynamic-role-of-the-state.md)
4. [Uneven evidence for subset of policies](uneven-evidence-for-subsets-of-policies.md)
5. [Institutions that balance trade-offs](institution-that-balance-trade-offs.md)

## Legatum Prosperity index

The Prosperity Index assesses prosperity organized into 3 domains - empowering people, open economies, and inclusive societies. Each domain is further divided into 12 pillars and 65 elements.  Finally the elements are composed of 294 measures. 

![Elements of the Legatum Prosperity Index : Source : Legatum Institute](https://lh5.googleusercontent.com/_qu6vpf8vgk3uU2LLfDt-qtSX8Gd-70--M8joegqC9DZi2oSO0ugaKMR1_rgfVWzmZMYJi1jWfjyjJBFM8m2pm_MGmNPTuiNVhx9ODSD_Fg3jD5y4btQJxYDpCdjNJWt6Eg1TmTT)

An example of how two measures - unemployment and carbon emissions are organized in the index.  Each measure has its own unique units such as tons of carbon dioxide \(CO2\), and then that measure is converted to a raw score and normalized on a scale from 0 to 1, where 0 is considered bad and 1 is considered good.  This raw score is then well suited for statistical analysis with other measures of different units.

![](../.gitbook/assets/image%20%2834%29.png)

The measures are then aggregated into the Elements using weights and similarly the Elements are aggregated into Pillars using weights.  The dataset is available for 167 countries and 10 years from 2009 to 2019.  While the dataset is incomplete for the measures - some values are missing with blanks for certain measure-country-year combinations - it is complete at the Element level.  Details of the methodology and weights is explained in the methodology report on the Legatum institute website.

## Dominant signal : general national success

![Graph visualization of statistical correlations between parameters](../.gitbook/assets/image%20%28103%29.png)

The first observation is that when comparing a wide range of different countries, there is a strong signal of “good” and “bad” outcomes across a range of measures in the database.  This is a common observation in any database of real systems and when using the statistical analysis technique of Principal Component Analysis, usually there are one or two strong signals that have a high rank.  The interpretation is that there is one important factor that separates successful from unsuccessful societies and that feature expresses itself in many of these measures of progress.  For example, the equally weighted Pillar “living conditions” shows a strong positive correlation to a wide number of other Pillars, Elements and measures - health, education and labor productivity.

![X-Y statistical relationships between parameters](../.gitbook/assets/image%20%2893%29.png)

Multivariable regression is a technique which can help to isolate the relationships from this dominant signal.  For example, if there is a dominant hidden feature that is shared between health and education in their relationship to labor productivity, a multivariable regression of living conditions, health and education on labor productivity may help to isolate just the effects of health which are uncorrelated with living conditions on labor productivity.

