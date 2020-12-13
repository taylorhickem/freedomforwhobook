# Generic success and labor productivity

![Irrigation machinery - a labor saving technique.  Photo credit : Anis Bouselmi](../.gitbook/assets/image%20%2880%29.png)

In this section

1. [Choosing a representative measure](generic-success-and-labor-productivity.md#choosing-a-representative-measure)
2. [Long run convergence with real wages](generic-success-and-labor-productivity.md#long-run-convergence-with-real-wages)
3. [Living conditions and productivity](generic-success-and-labor-productivity.md#living-conditions-and-productivity)

## Choosing a representative measure

The next challenge is to decide a meaningful subset of parameters to begin the analysis.  The high rank feature of the dataset means that there could be multiple measures that could work well.  There is one common “hidden parameter” which could be characterized by any of several redundant measures.  In this analysis living conditions and labor productivity are chosen as the dependent variable for analysis.  Labor productivity is the economic output - $ of Gross Domestic Product \(GDP\) per worker in the economy $/person on a purchasing power \(PPP\) basis.  The choice of this measure is threefold - close connection to the conventional measure of progress in political economy - real wages, ability to compare across different political economies, and theoretical strength as a universal measure of economic efficiency.  

Intuitively it would not be a surprise to observe a correlation between prosperity progress measures and labor productivity, especially in material outcomes such as food and shelter for developing economies.  Societies with higher labor productivity need to commit on average fewer total hours to provide sustenance like food and shelter and can be committed to other activities such as education and medical services.  Achieving above a threshold level may be a prerequisite condition for a society’s ability to provide surplus resources to public goods.  For example using a standard daily serving of 500 calorie of meat/person, game hunting trips in indigenous hunter gatherer societies in South America yield 20-40 standard serving units per 40 hrs worked \(Hooper, 2015\), whereas the caloric production of domestic meat in industrialized economies can be up to 20x higher than that rate. 

## Long run convergence with real wages

While productivity can measure the broad average of economic capacity, just as in real wage average, it does not measure how that capacity is distributed within society.  Unlike wages, it can potentially measure the economic capacity of the economy in a consistent way that is not obscured by the labor share of income or taxation and better suited to compare progress between different economic systems such as socialists and capitalists systems. While it is not a direct measure of wages, they are related.  Also, while the aggregate changes of real wages and labor productivity can move in opposite directions in the short term in the business cycle from effects of inflation, unemployment and labor share of income, in the long run the trend of % changes in real wages tracks the % gains in labor productivity.

Table B.1 summarizes the statistical regression of labor productivity against living conditions, health and education for 1837 observations of country-year pairs.  The year is added to isolate the time-independent effects. In many econometric series that measure progress, there is a tendency to observe a “general trend of improvement with time” which is not captured by any of the parameters and so the intention here is to isolate the effects which are contained within the dataset only.  A country identifier id is also added as a control to compare the significance threshold.

## Living conditions and productivity

![Table B.1 Regression labor productivity vs other test parameters](../.gitbook/assets/image%20%2858%29.png)

Two outputs from the regression are the summary statistics - the R square value which ranges from 0 to 1 and measures the “goodness of fit” of the regression, and the coefficients.  The P-value indicates how significant that relationship is with the dependent variable \(labor productivity\) with a small P-value meaning that the relationship is significant, and a high P-value meaning that there is little variance explained by that parameter.  A typical P-value significance threshold is &lt; 0.05.  The coefficients aren’t as meaningful unless they are scaled and normalized between 0 and 1.  When all of the independent variables are scaled between 0 and 1, then the coefficients can be interpreted as the relative weight of how well that parameter explains the variances in the dependent variable vs the other independent variables.  The P-value and the coefficient are related then that a variable with a higher P-value will have a coefficient closer to zero.  An extra column is added “coefficient scaled” where all of the coefficients are divided by the greatest magnitude coefficient \(in this case 1.32\) so that the largest coefficient is either +/- 1.  

The regression results in the table above are illustrated below in a Figure B.2 graph showing the relationship between these variables with a + for positive relationship and - for negative relationship, and the strength of the relationship associated with the line weight.

![](../.gitbook/assets/image%20%28105%29.png)

Living conditions is the strongest relationship, followed by a negative correlation between health and labor productivity and weak positive relationship to education.  Living conditions can be thought of as a list of the basic essential needs provided in modern settlements.  The measures included in the living conditions, education and health pillars are summarized in Table B.2.

![Table B.2 Measures included in Pillars for health, living conditions and education](../.gitbook/assets/image%20%2860%29.png)

The negative relationship between health may seem counter-intuitive since one might expect that a healthier workforce is better equipped at problem solving. One possible explanation could be Baumol’s cost disease, which is the observation that it is a feature of the service of providing healthcare that resists productivity improvements due to the low capital-labor substitution \(Nordhaus, 2006\).  In contrast however, education also shares this limitation but is an overall net positive, albeit weaker statistical relationship.  This analysis could be examined to further test the evidence of this explanation by subsequent tests to look at the relative contributions of health outcomes and health spending to productivity.

