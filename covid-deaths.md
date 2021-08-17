# "Covid Deaths" number is statistically meaningless

The current definition in most western nations on "covid deaths" does not mean what most people think it means.  Most people *think* "covid death" means someone who died *because* of covid.  This is not accurate.

The exact definition varies, but in most western countries, the general definition of "covid death" means:
* anyone who died and tested positive within the recent 1-2 months (depends on the country) OR
* anyone who died recently where a medical professional opined the death may have involved covid, even if there was no positive test.

The exact standards vary from country to country, but the point is that nowhere does this actually require that covid **caused** the death, and in most cases, no positive test is actually even required.

Dr. Birx explained that "covid deaths" are just deaths with recent cases of covid, regardless of cause of death.  https://www.realclearpolitics.com/video/2020/04/08/dr_birx_unlike_some_countries_if_someone_dies_with_covid-19_we_are_counting_that_as_a_covid-19_death.html

Illinois Department of Public Health Director reiterates the same https://week.com/2020/04/20/idph-director-explains-how-covid-deaths-are-classified/

UK Public Health reiterates the same https://publichealthmatters.blog.gov.uk/2020/08/12/behind-the-headlines-counting-covid-19-deaths/

> For several months, the COVID-19 Data Dashboard has been reporting, for England, all deaths in people who have a positive test.

Instead of including proximate cause analyses, PHE-UK expanded the exact metric to more specifically define a better time limit.

> The additional indicators which will be used to calculate daily death figures are:
> the number of deaths in people with COVID-19 that occur within 28 days of a first positive laboratory-confirmed test. ...
> the number of deaths that occur within 60 days of a first positive test. Deaths that occur after 60 days will also be added to this figure if COVID-19 appears on the death certificate

This is why in many data reports, PHE-UK and the NHS are using a metric called "Deaths within 28 days of positive specimen date"

Covid need not actually be a proximate cause of death for the death to be included as a "covid death".

# Excess Deaths

The "excess deaths" number *should* be taken by analyzing the actual death totals by death certificate count, aggregated by day or week, and comparing those to prior years.  

This is *not* what the CDC data reflects though.  

The CDC did not posting the atomic death certificates with date of death and causes of death.  

Instead, the CDC published limited data aggregated by causes of death (rather than individual deaths) for certain causes of death.  There is no way to calculate overlaps of deaths or even raw daily or weekly death counts from the data the CDC makes available.  

Instead, the "excess deaths" number from the CDC takes the aggregated counts of death certificates including the word "covid" and adds that to historical estimates from other causes.  https://wwwnc.cdc.gov/eid/article/27/3/20-3925_article and https://www.cdc.gov/nchs/nvss/vsrr/covid19/excess_deaths.htm  

If a variation of the word "covid" was included on the death certificate, it was presumed a covid death in 95% of certificates:

> For the majority of deaths where COVID-19 is reported on the death certificate (approximately 95%), COVID-19 is selected as the underlying cause of death.

And then the rest of the deaths from other causes were estimated from historicals.

> Additionally, deaths from all causes excluding COVID-19 were also estimated.

The CDC uses a "quasi-Poisson regression" estimate for excess deaths, not actual death certificate counts, summed by day or week, compared to the prior year's stats.  Even worse, the estimation model excluded numerous causes of death, further increasing the margin of error: 

> Deaths due to all other natural causes were excluded (ICD-10 codes: A00–A39, A42–B99, D00–E07, E15–E68, E70–E90, F00, F02, F04–G26, G31–H95, K00–K93, L00–M99, N00–N16, N20–N98, O00–O99, P00–P96, Q00–Q99). External causes of death (i.e. injuries) were excluded, as the reporting lag is substantially longer for external causes of death (4). Additionally, causes of death where the underlying cause was unknown or ill-specified (i.e. R-codes) were excluded (except for R09.2, which is included under the Respiratory diseases category).

This is bad data science.  The proper method to calculate "excess deaths" would be to ignore causes of death entirely, and then just take actual daily death certificates and compare them to last year, as well as historical averages for maybe the last 3, 5, and 10 year periods.  The CDC's method incorrectly and unscientifically allows for double-counting of deaths.

# Examples of Blatant Misclassification

Washington State classified people who died from gunshot wounds as covid deaths https://www.freedomfoundation.com/washington/washington-health-officials-gunshot-victims-counted-as-covid-19-deaths/

Colorado officials classified a 35 year old man with blood-alcohol content of 0.55, nearly twice the lethal limit, as a covid death https://denver.cbslocal.com/2020/05/14/coronavirus-montezuma-county-coroner-alcohol-poisoning-covid-death/

# Incentives

Hospitals have the direct financial incentive to over-classify cases as covid, as reimbursement average over $40,000 as opposed to other conditions which are under a quarter of that https://www.factcheck.org/2020/04/hospital-payments-and-the-covid-19-death-count/.  Numerous officials and sources have claimed without evidence that there is no over-classifying, even though there is very substantial monetary incentive to do so, and testing was not required in the US to label a death as a covid death.
