# Abstract

   The upward trajectory of clean energy deployment has been a prominent
trend in recent years. With technological advancements and policy
incentives, analyses have pointed to large expected increases in wind
and solar generation capacities. This paper quantifies the economic and
environmental impact of substituting lost wind and solar energy with
fossil fuel alternatives, estimating the cost of operating fossil fuels
and calculating the associated carbon emissions. Based on the results of
the study, solar and wind curtailment in 2022 resulted in $13.7 million
spent in operating fossil fuels to substitute lost renewable energy and
is associated with 221,288 metric tons of carbon emissions. More robust
study is needed to account for the intricacies of the existing
transmission infrastructure in ERCOT and evaluate long-term economic
implications. This paper serves as a foundational step in recognizing
the implications of curtailment.

# Introduction

   With the accelerated deployment of clean energy in recent years,
increased wind and solar generation capacity has caused strain on the
grid. Although renewable energy operates at very low marginal costs and
greatly reduces carbon emissions on the environment, energy produced by
wind and solar is unable to make it to market if there is not enough
transmission available. In 2022, the U.S. government passed the
Inflation Reduction Act (IRA), a notable piece of legislation designed
to address climate concerns. With tax credits, grants, loans, domestic
manufacturing incentives, and Infrastructure Bill incentives, the IRA
promotes the expansion of renewable energy and carbon management in the
country, and models have consistently shown that IRA leads to large
increases in wind and solar deployment (Bistline, et al. 2023).

   However, continued expansion of generation capacity for renewables
would be a challenge given present transmission issues, which is often
reported by the popular press (Shenk, 2023). Transmission investments in
the past have helped increased wind penetration. In Texas, high wind
penetration numbers benefit from Competitive Renewable Energy Zone
(CREZ) initiative that brought in $6.8 billion in investments in nearly
3,600-miles of new transmission lines with approximately 18,000 MW of
capacity to accomodate wind resources in West Texas. Although wind
generation makes up the majority of renewable energy generation in
Texas, ERCOT forecasted that a range of 14.5 GW to 28.1 GW of solar
generation capacity is to be added by 2031 (Tsai & Gulen, 2017). The
completion of the CREZ lines not only increased the number of wind
penetration hours but also helped mitigate negative pricing and helped
nodal price convergence (Tsai & Gulen, 2017). In general, transmission
investments has promoted wind and solar generation capacity expansion.

   Given the current circumstances within ERCOT, transmission
constraints continues to be a problem in regards to wind and solar
curtailment. The purpose of this paper is to quantify the economic and
environmental impact of substituting lost wind and solar energy with
fossil fuel alternatives, estimating the cost of operating fossil fuels
and calculating the associated carbon emissions. Although the findings
of this paper represents only a fraction of the broader landscape, the
insights gleaned from this analysis can offer valuable initial
perspectives.

# Literature Review

   The current literature provides different approaches in understanding
the relationship between transmission and renewable energy. Within this
expansive realm of research, various perspectives and methodologies
converge to shed light on the multifaceted dynamics at play.
Collectively, the diverse array of research available not only
underscores the complexity of the relationship between transmission
infrastructure and renewable energy but also highlights the
interdisciplinary nature at play.

   In a 2022 study by Jacob LaRiviere and Xueying Lyu, the authors used
the roll-out of a large transmission expansion in ERCOT to measure the
market impacts of the transmission expansion on benefits of increased
renewable capacity. They looked at the value of transmission expansion
and estimated that the annual benefits of CREZ conditional on installed
wind capacity was at a lower bound of roughly $370 million per year to
$645 million per year (LaRiviere & Lyu, 2022). They also performed a
back of the envelope calculation examining the benefits of mitigated
fossil fuel generation from increased trade of wind energy. If 10% of
wind generation was curtailed in their sample period, the non-market
impacts of CO2 using a price per ton estimate are roughly $115 million
per year (2022).

   A 2020 study by Liuzixuan Lin and Andrew A. Chien showed that
stranded power in ERCOT is a persistent issue. They found that as the
grid evolves, it has returned to a point where 15% of wind power is
curtailed or cleared at negative prices. The results of their study show
that stranded power is increasing alongside the growth of wind
generation and is related to factors such as transmission constraints,
grid load, and wind generation (Lin & Chien, 2020).

   In contrast to the comprehensive and intricate views presented in
existing literature, this paper adopts a more streamlined approach. It
endeavors to distill the complexity surrounding curtailed renewable
energy into a more accessible framework, aiming to quantify the economic
and environmental costs incurred when fossil fuels are employed as
substitutes for lost wind and solar energy.

# Data

   In this paper, the data for ERCOT system-wide wind and solar output
is extracted from Arcus Power’s NRGStream, which is a service that
amalgamates data from sources such as ERCOT. In order to calculate
curtailed energy, I use ERCOT wind and solar generation curtailment
percentages reported by the Energy Information Administration (EIA). In
2022, ERCOT curtailed 5% of total wind generation and 9% of total solar
generation. By 2035, the EIA projects that ERCOT will curtail 13% of
wind generation and 19% of solar generation (U.S. EIA, 2023). The 2022
curtailment percentages represent the lower-bound estimates in
calculations, while the 2035 projections represent the upper-bound
estimates in calculations.

   To calculate the cost of operating fossil fuels, I use the Average
Power Plant Operating Expense values that were provided by EIA. The
values accounted for expenses for major U.S. Investor-Owned Electric
utilities from 2012 to 2022. In this paper, we use the total cost of
operating, maintaining, and fueling fossil steam. To calculate the
carbon emissions associated with operating fossil fuels, I use to the
national marginal emission factor that is provided by the United States
Environmental Protection Agency (U.S. EPA). The emission factor is based
on the 2019 U.S. national weighted average CO2 marginal emission rate.

 

<table>
<caption>Solar and Wind Production (MW)</caption>
<thead>
<tr class="header">
<th style="text-align: center;">year</th>
<th style="text-align: center;">wind_total</th>
<th style="text-align: center;">solar_total</th>
<th style="text-align: center;">combined_total</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">2017</td>
<td style="text-align: center;">2,594,728</td>
<td style="text-align: center;">87,961.96</td>
<td style="text-align: center;">2,682,690</td>
</tr>
<tr class="even">
<td style="text-align: center;">2018</td>
<td style="text-align: center;">2,910,708</td>
<td style="text-align: center;">124,661.09</td>
<td style="text-align: center;">3,035,369</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2019</td>
<td style="text-align: center;">3,197,172</td>
<td style="text-align: center;">166,990.75</td>
<td style="text-align: center;">3,364,162</td>
</tr>
<tr class="even">
<td style="text-align: center;">2020</td>
<td style="text-align: center;">3,629,837</td>
<td style="text-align: center;">345,723.30</td>
<td style="text-align: center;">3,975,560</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2021</td>
<td style="text-align: center;">3,977,897</td>
<td style="text-align: center;">635,095.84</td>
<td style="text-align: center;">4,612,993</td>
</tr>
<tr class="even">
<td style="text-align: center;">2022</td>
<td style="text-align: center;">4,474,928</td>
<td style="text-align: center;">983,321.48</td>
<td style="text-align: center;">5,458,250</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2023</td>
<td style="text-align: center;">4,075,484</td>
<td style="text-align: center;">1,224,860.46</td>
<td style="text-align: center;">5,300,344</td>
</tr>
</tbody>
</table>

Solar and Wind Production (MW)

   From Table 1, we see that there is a steady increase in combined
solar and wind production from 2017 to 2022. It is important to note
that 2023 values in the table only include production values until
November 26, 2023. Because the year is not yet over, the combined wind
and solar production value for 2023 is lower in comparison to 2022.

 

![](FinalReport_files/figure-markdown_strict/summary_plots-1.png)![](FinalReport_files/figure-markdown_strict/summary_plots-2.png)

   Figure 1 plots energy production for wind and solar. From this
figure, we see that wind produces significantly more energy than solar,
although we see a higher spike in solar energy production in 2023.
However, wind production appears to be facing a decrease in production
in the recent months in 2023. This drop in wind energy production can be
attributed to the effect of El Niño, which is known to significantly
decrease wind speed and power generation (Watts et al., 2017). Figure 2
represents the combined total energy production by wind and solar, which
shows a general upwards trend.

# Methods

   In this paper, I attempt to estimate the cost implicated with
substituting wasted renewable energy for traditional fossil fuels. To
calculate curtailed energy, multiply the production output of wind and
solar with their respective curtailment percentages. 2022 curtailment
percentages represents the lower bound in this paper’s calculations,
while 2035 percentages represent the upper bound calculations. In order
to find the cost of operating fossil fuels in lieu of wind or solar, we
would multiply total energy curtailed by the average cost to operate
fossil fuel power plants.

*l**o**w**e**r*<sub>*b**o**u**n**d*</sub> = *o**u**t**p**u**t*<sub>*w**i**n**d*</sub> \* 0.05 + *o**u**t**p**u**t*<sub>*s**o**l**a**r*</sub> \* 0.13

*u**p**p**e**r*<sub>*b**o**u**n**d*</sub> = *o**u**t**p**u**t*<sub>*w**i**n**d*</sub> \* 0.09 + *o**u**t**p**u**t*<sub>*s**o**l**a**r*</sub> \* 0.19

   To calculate the carbon emissions associated with operating fossil
fuels, I use to the national marginal emission factor that is provided
by the U.S. EPA. The emission factor is represented by the following.
Carbon emission is found by multiplying total curtailed energy with the
emissions factor.

$$
emissionfactor = \frac{1562lbsCO\_2}{MWh}\*\frac{1ton}{2204.6lbs}=0.7087
$$

# Results

   Calculating the lower and upper bounds for curtailed energy, we get
an estimation of curtailed wind and solar energy using the EIA’s 2022
curtailment estimation for the lower bound and the EIA’s projected 2035
curtailment for the upper bound. It is important to note that the most
accurate values from these estimations are 2022 lower bound estimations.
This is because we have the most accurate curtailment percentages for
this particular year.

 

<table>
<caption>Curtailment for Solar and Wind (MW)</caption>
<colgroup>
<col style="width: 2%" />
<col style="width: 15%" />
<col style="width: 15%" />
<col style="width: 15%" />
<col style="width: 15%" />
<col style="width: 17%" />
<col style="width: 17%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: center;">Year</th>
<th style="text-align: center;">Solar Curtailment<br />
(Lower Bound)</th>
<th style="text-align: center;">Solar Curtailment<br />
(Upper Bound)</th>
<th style="text-align: center;">Wind Curtailment<br />
(Lower Bound)</th>
<th style="text-align: center;">Wind Curtailment<br />
(Upper Bound)</th>
<th style="text-align: center;">Combined Curtailment<br />
(Lower Bound)</th>
<th style="text-align: center;">Combined Curtailment<br />
(Upper Bound)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">2017</td>
<td style="text-align: center;">7,916.576</td>
<td style="text-align: center;">16,712.77</td>
<td style="text-align: center;">129,736.4</td>
<td style="text-align: center;">337,314.6</td>
<td style="text-align: center;">137,653.0</td>
<td style="text-align: center;">354,027.4</td>
</tr>
<tr class="even">
<td style="text-align: center;">2018</td>
<td style="text-align: center;">11,219.498</td>
<td style="text-align: center;">23,685.61</td>
<td style="text-align: center;">145,535.4</td>
<td style="text-align: center;">378,392.0</td>
<td style="text-align: center;">156,754.9</td>
<td style="text-align: center;">402,077.6</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2019</td>
<td style="text-align: center;">15,029.167</td>
<td style="text-align: center;">31,728.24</td>
<td style="text-align: center;">159,858.6</td>
<td style="text-align: center;">415,632.3</td>
<td style="text-align: center;">174,887.8</td>
<td style="text-align: center;">447,360.6</td>
</tr>
<tr class="even">
<td style="text-align: center;">2020</td>
<td style="text-align: center;">31,115.097</td>
<td style="text-align: center;">65,687.43</td>
<td style="text-align: center;">181,491.8</td>
<td style="text-align: center;">471,878.8</td>
<td style="text-align: center;">212,606.9</td>
<td style="text-align: center;">537,566.2</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2021</td>
<td style="text-align: center;">57,158.626</td>
<td style="text-align: center;">120,668.21</td>
<td style="text-align: center;">198,894.9</td>
<td style="text-align: center;">517,126.6</td>
<td style="text-align: center;">256,053.5</td>
<td style="text-align: center;">637,794.8</td>
</tr>
<tr class="even">
<td style="text-align: center;">2022</td>
<td style="text-align: center;">88,498.933</td>
<td style="text-align: center;">186,831.08</td>
<td style="text-align: center;">223,746.4</td>
<td style="text-align: center;">581,740.7</td>
<td style="text-align: center;">312,245.3</td>
<td style="text-align: center;">768,571.8</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2023</td>
<td style="text-align: center;">110,237.441</td>
<td style="text-align: center;">232,723.49</td>
<td style="text-align: center;">203,774.2</td>
<td style="text-align: center;">529,812.9</td>
<td style="text-align: center;">314,011.6</td>
<td style="text-align: center;">762,536.4</td>
</tr>
</tbody>
</table>

Curtailment for Solar and Wind (MW)

 

<table>
<caption>Cost of Operating Fossil Fuels (USD)</caption>
<colgroup>
<col style="width: 2%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 17%" />
<col style="width: 14%" />
<col style="width: 13%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: center;">Year</th>
<th style="text-align: center;">Curtailed Solar Cost<br />
(Lower Bound)</th>
<th style="text-align: center;">Curtailed Solar Cost<br />
(Upper Bound)</th>
<th style="text-align: center;">Curtailed Wind Cost<br />
(Lower Bound)</th>
<th style="text-align: center;">Curtailed Wind Cost<br />
(Upper Bound)</th>
<th style="text-align: center;">Combined Cost<br />
(Lower Bound)</th>
<th style="text-align: center;">Combined Cost<br />
(Upper Bound</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">2017</td>
<td style="text-align: center;">$280,326</td>
<td style="text-align: center;">$591,799</td>
<td style="text-align: center;">$4,593,966</td>
<td style="text-align: center;">$11,944,311</td>
<td style="text-align: center;">$4,874,292</td>
<td style="text-align: center;">$12,536,110</td>
</tr>
<tr class="even">
<td style="text-align: center;">2018</td>
<td style="text-align: center;">$402,331</td>
<td style="text-align: center;">$849,366</td>
<td style="text-align: center;">$5,218,899</td>
<td style="text-align: center;">$13,569,137</td>
<td style="text-align: center;">$5,621,230</td>
<td style="text-align: center;">$14,418,503</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2019</td>
<td style="text-align: center;">$550,969</td>
<td style="text-align: center;">$1,163,157</td>
<td style="text-align: center;">$5,860,416</td>
<td style="text-align: center;">$15,237,081</td>
<td style="text-align: center;">$6,411,385</td>
<td style="text-align: center;">$16,400,238</td>
</tr>
<tr class="even">
<td style="text-align: center;">2020</td>
<td style="text-align: center;">$1,084,672</td>
<td style="text-align: center;">$2,289,864</td>
<td style="text-align: center;">$6,326,805</td>
<td style="text-align: center;">$16,449,694</td>
<td style="text-align: center;">$7,411,478</td>
<td style="text-align: center;">$18,739,557</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2021</td>
<td style="text-align: center;">$2,038,277</td>
<td style="text-align: center;">$4,303,028</td>
<td style="text-align: center;">$7,092,590</td>
<td style="text-align: center;">$18,440,735</td>
<td style="text-align: center;">$9,130,867</td>
<td style="text-align: center;">$22,743,763</td>
</tr>
<tr class="even">
<td style="text-align: center;">2022</td>
<td style="text-align: center;">$3,883,333</td>
<td style="text-align: center;">$8,198,148</td>
<td style="text-align: center;">$9,817,993</td>
<td style="text-align: center;">$25,526,781</td>
<td style="text-align: center;">$13,701,326</td>
<td style="text-align: center;">$33,724,929</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2023</td>
<td style="text-align: center;">$4,837,219</td>
<td style="text-align: center;">$10,211,907</td>
<td style="text-align: center;">$8,941,611</td>
<td style="text-align: center;">$23,248,188</td>
<td style="text-align: center;">$13,778,830</td>
<td style="text-align: center;">$33,460,095</td>
</tr>
</tbody>
</table>

Cost of Operating Fossil Fuels (USD)

   Calculating the cost of operating fossil fuels due to renewable
energy curtailment is about $13.7 million in 2022 for combined wind and
solar curtailment. For solar curtailment alone, $3.9 million would go to
operating fossil fuels and $8.9 million would be spent because of wind
curtailment. If curtailment percentages remains the same from 2022 to
2023, solar curtailment has already resulted in an accumulated $4.8
million cost, which is higher than costs in 2022 even though the year
has not yet concluded. The spike in the cost for solar curtailment
results in a higher combined solar and wind cost for 2023 compared to
cost in 2022. Because the year has not concluded, we can assume that
combined cost for the full year would exceed the current cost
estimation.

 

<table style="width:100%;">
<caption>CO2 Emissions from Operating Fossil Fuels (metric
ton)</caption>
<colgroup>
<col style="width: 2%" />
<col style="width: 15%" />
<col style="width: 15%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 18%" />
<col style="width: 18%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: center;">Year</th>
<th style="text-align: center;">Emissions from Solar<br />
(Lower Bound)</th>
<th style="text-align: center;">Emissions from Solar<br />
(Upper Bound)</th>
<th style="text-align: center;">Emissions from Wind<br />
(Lower Bound)</th>
<th style="text-align: center;">Emissions from Wind<br />
(Upper Bound)</th>
<th style="text-align: center;">Emissions from Solar and Wind<br />
(Lower Bound)</th>
<th style="text-align: center;">Emissions from Solar and Wind<br />
(Upper Bound)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: center;">2017</td>
<td style="text-align: center;">5,610</td>
<td style="text-align: center;">11,844</td>
<td style="text-align: center;">91,944</td>
<td style="text-align: center;">239,055</td>
<td style="text-align: center;">97,555</td>
<td style="text-align: center;">250,899</td>
</tr>
<tr class="even">
<td style="text-align: center;">2018</td>
<td style="text-align: center;">7,951</td>
<td style="text-align: center;">16,786</td>
<td style="text-align: center;">103,141</td>
<td style="text-align: center;">268,166</td>
<td style="text-align: center;">111,092</td>
<td style="text-align: center;">284,952</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2019</td>
<td style="text-align: center;">10,651</td>
<td style="text-align: center;">22,486</td>
<td style="text-align: center;">113,292</td>
<td style="text-align: center;">294,559</td>
<td style="text-align: center;">123,943</td>
<td style="text-align: center;">317,044</td>
</tr>
<tr class="even">
<td style="text-align: center;">2020</td>
<td style="text-align: center;">22,051</td>
<td style="text-align: center;">46,553</td>
<td style="text-align: center;">128,623</td>
<td style="text-align: center;">334,420</td>
<td style="text-align: center;">150,675</td>
<td style="text-align: center;">380,973</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2021</td>
<td style="text-align: center;">40,508</td>
<td style="text-align: center;">85,518</td>
<td style="text-align: center;">140,957</td>
<td style="text-align: center;">366,488</td>
<td style="text-align: center;">181,465</td>
<td style="text-align: center;">452,005</td>
</tr>
<tr class="even">
<td style="text-align: center;">2022</td>
<td style="text-align: center;">62,719</td>
<td style="text-align: center;">132,407</td>
<td style="text-align: center;">158,569</td>
<td style="text-align: center;">412,280</td>
<td style="text-align: center;">221,288</td>
<td style="text-align: center;">544,687</td>
</tr>
<tr class="odd">
<td style="text-align: center;">2023</td>
<td style="text-align: center;">78,125</td>
<td style="text-align: center;">164,931</td>
<td style="text-align: center;">144,415</td>
<td style="text-align: center;">375,478</td>
<td style="text-align: center;">222,540</td>
<td style="text-align: center;">540,410</td>
</tr>
</tbody>
</table>

CO2 Emissions from Operating Fossil Fuels (metric ton)

   Table 4 illustrates the calculated estimations of carbon dioxide
emissions stemming from the utilization of fossil fuels required to
compensate for curtailed solar and wind energy. In 2022, the curtailed
solar energy led to the release of 62,719 metric tons of CO2 emissions
from fossil fuels, while curtailed wind energy contributed to emissions
amounting to 158,569 metric tons. As 2023 progresses, the estimation for
emissions resulting from solar curtailment surpasses the previous year’s
estimations. Similar to the results for operating costs, emissions from
solar curtailment in 2023 so far has already resulted in higher carbon
emissions compared to the estimation in 2022. Although 2023 has not yet
closed, solar curtailment emissions in addition to combined curtailment
emissions are higher than the estimation in 2022. This escalation could
signal a troubling trajectory, indicating potentially higher overall
emissions compared to the preceding year.

# Limitations

   The process of this project is not without its limitations. The time
horizon for this study was limited to due to the lack of data
availability on NRGStream. It would be insightful to be able to map the
changes in wind and solar energy production before, during, and after
the CREZ project. Another issue of the study is that accurate
curtailment percentages was not available for each year. Given more time
and closer study of the methods available in the literature, I would be
able to more accurately measure curtailed energy by year. However, given
the time constraints, achieving this level of granularity was not
realizable.

   Future studies on wind and solar energy curtailment could also
attempt to predict future curtailment. A more detailed project would
examine wind and solar curtailment in the different regions of Texas
where wind and solar farms are clustered and transmission is especially
constrained. Examining data based on location would provide a more
accurate representation of the cost of transmission constraints on wind
and solar. These potential avenues for future studies would not only
address the issues this project has encountered but also provide more
comprehensive and insightful analyses in the realm of renewable energy
curtailment.

# Conclusion

   The upward trajectory of clean energy deployment has been a prominent
trend in recent years, signaling a significant shift towards
sustainability in the energy sector. Wind and solar plants, in
particular, have emerged as frontrunners in this movement due to their
operational advantages. These renewable sources operate at remarkably
low marginal costs, positioning them as economically favorable options
for energy production. Their capacity to generate substantial power
without incurring high ongoing expenses has contributed significantly to
their growing prominence in the energy landscape, especially in Texas
where solar and wind resources are particularly high.

   The Inflation Reduction Act (IRA), a pivotal legislation enacted by
the U.S. government in 2022, stands as a testament to the nation’s
commitment toward mitigating climate change. While the IRA lays down the
groundwork for incentivizing and fostering the growth of renewable
energy, the ambitious goal of scaling up renewable energy production is
impeded by limitations in the existing transmission infrastructure,
especially within ERCOT. This paper attempts to estimate the cost of
substituting curtailed wind and solar energy given current constraints.

   The analysis conducted in this paper reveals substantial economic and
environmental impacts. Solar and wind curtailment in 2022 resulted in
$13.7 million spent in operating fossil fuels to substitute lost
renewable energy and is associated with 221,288 metric tons of carbon
emissions. The EIA projected that ERCOT would curtail 13% of wind
generation and 19% of solar generation by 2035. Imposing these
curtailment percentages on 2022 wind and solar generation values, the
cost of operating fossil fuels in lieu of lost renewable energy would be
$33.7 million with an associated 544,687 metric tons of carbon emissions
by 2035. If we assume that wind and solar generation capacity will
increase steadily over time due to technological and governmental
incentives, then these estimations are conservative estimates of the
economic and environmental costs of curtailed renewable energy.

   The limitations inherent in this study underscore the complexity of
evaluating the viability and cost-effectiveness of transmission
investments to facilitate the sustained growth of wind and solar
generation capacity in Texas. While the insights gleaned from this
analysis offer valuable initial perspectives, they represent a fraction
of the broader landscape that demands more comprehensive scrutiny. More
robust study is needed to account for the intricacies of the existing
transmission infrastructure in ERCOT and evaluate long-term economic
implications. Ultimately, while this study serves as a foundational step
in recognizing the implications of curtailment, it highlights the
necessity for a more expansive and detailed analysis that encompasses
the diverse dimensions inherent in enhancing transmission infrastructure
to facilitate the continued growth of wind and solar energy in Texas.

# References

Bistline, J., Blanford, G., Brown, M., Burtraw, D., Domeshek, M.,
Farbes, J., Fawcett, A.,  
  Hamilton, A., Jenkins, J., Jones, R., King, B., Kolus, H., Larsen, J.,
Levin, A., Mahajan,  
  M., Marcy, C., Mayfield, E., McFarland, J., McJeon, H., … Zhao, A.
(2023). Emissions  
  and energy impacts of the Inflation Reduction Act. Science, 380(6652),
1324–1327.  
  <https://doi.org/10.1126/science.adg3781>

 

LaRiviere, J., & Lyu, X. (2022). Transmission constraints, intermittent
renewables and  
  Welfare. Journal of Environmental Economics and Management, 112,
102618.  
  <https://doi.org/10.1016/j.jeem.2022.102618>

 

Lin, L., & Chien, A. A. (2020, June). Characterizing stranded power in
the Electric  
 Reliability Council of …
<https://newtraell.cs.uchicago.edu/files/tr_authentic/>  
 TR-2020-06.pdf

 

Shenk, M. (2023, October 19). Rising curtailments in Texas magnify grid,
storage shortfalls.  
  Reuters.
<https://www.reuters.com/business/energy/rising-curtailments-texas-magnify->  
  grid-storage-shortfalls-2023-10-19/

 

Tsai, C.-H., & Gülen, G. (2017). The ERCOT Experience with Integrating
Renewables.  
  International Association for Energy Economics, 42–45.

 

U.S. EIA. (2023, July). A Case Study of Transmission Limits on
Renewables Growth in  
  Texas. U.S. Energy Information Administration (EIA).
<https://www.eia.gov/electricity/>  
  markets/quarterly/archive/2023/transmission\_limits\_07\_2023.pdf

 

Watts, D., Durán, P., & Flores, Y. (2017). How does El Niño Southern
Oscillation impact  
  the wind resource in Chile? A techno-economical assessment of the
influence of El Niño  
  and La Niña on the Wind Power. Renewable Energy, 103, 128–142.  
  <https://doi.org/10.1016/j.renene.2016.10.031>
