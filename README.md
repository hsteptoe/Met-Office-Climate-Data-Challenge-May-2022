# Met-Office-Climate-Data-Challenge-May-2022

Team 1A: Identify patterns of past seasonal variability in climate and crime
How will climate change impact crime and justice in the UK?

Here we examine London Borough crime for 2010 to 2022 across 12 categories (crime seas var main), cross examine data for climate dashboard.
Multiple climate variables (climate_data). 

See Regplots.zip and seasons.zip for applied cross correlation of variables and simple regression plots.

GAM model output in hack.zip 

more to follow

Literature review (Helen Roberts) below:

Towers, S. et al. (2018) 

Chicago, U.S. 

•	Battery is positively associated with temperature at all times of the year.

•	The only significantly negative association between temperature and crime is for burglary during the summer.

•	Wind speed is significantly negatively associated with both aggravated assaults and batteries, as is precipitation.

•	Days that are warmer than average significantly increase aggravated assaults and batteries in both street locations and domestic, but the effect is more pronounced in street locations. 

•	The reduced effect of temperature on household aggravated assaults and batteries may be due to the fact that most residences these days are air conditioned, and this fact needs to be considered when comparing these results to the results of analyses conducted in the 1970’s or 1980’s (and when projecting in the UK, as currently most properties do not have air con).

•	If the relationship between crime incidence, C, and temperature, T is quadratic, we have C = a + bT + cT2

•	Street assaults and batteries occur more often on warmer than average days - in concordance with previous research that has shown that aggression may be triggered by high temperatures

•	Negative Effect Escape Model, proposes that increasing discomfort from heat causes aggression to a point, but in very hot temperatures the motive to escape the heat becomes greater than the motive to aggress.

•	No significant dependence of crime incidence on atmospheric pressure, in agreement with other studies.

•	Higher relative humidity only has a significant negative effect on aggravated assaults and batteries. The effect is particularly pronounced on rainy days.

•	Wind has a significant negative effect on aggravated assaults and batteries (and no significant effect on any other type of crime examined here). Again, the effect is only significant for aggravated assaults and batteries occurring in the street, not in residences.

•	Precipitation has a significant negative effect on aggravated assaults, batteries, theft and criminal damage. Just like relative humidity and wind, the negative effect is only significant for aggravated assaults and batteries occurring on the street, not in residences.
 
Horrocks, J. and Menclova, A.K. (2011)

New Zealand

•	Temperature and precipitation are found to have a significant effect on the number of violent crimes recorded, and temperature also affects the number of property crimes recorded.

•	Inverse-U-shaped relationship between temperature and aggression (curvilinear)

•	Overall, we may expect ‘fine’ weather to be associated with more property crime, however, as people leave and come home more frequently in ‘fine’ weather, there is more movement in the streets, which increases the likelihood of being caught and thus mitigates the positive effect of ‘fine’ weather on property crime.
 
Baryshnikova, N., Davidson, S. and Wesselbaum, D. (2021)

Four major cities in U.S. - Chicago, Indianapolis, Los Angeles and New York

•	Find important differences in the results for the weather–crime relationship when we use hourly observations rather than daily observations.

•	The literature using daily observations overestimates the effect of temperature and underestimates the effect of precipitation.

•	For a 1 ◦C increase in temperature, we find an increase of 0.11 crimes per hour or 2.64 crimes per day.

•	One inch increase in hourly precipitation reduces property crimes by 6.9 crimes per hour (164 per day).

•	Temperature, humidity, and wind speed have no significant effect on property crimes.

•	Using hourly data, we find the following turning points (on curvilinear graph): 17.5◦C for violent crime and 20 ◦C for property crime.
 
Potgieter, A. et al. (2022)

South African Township

•	Hot days (defined as ≥ 25 °C) increased the cumulative relative risk of violent crime by up to 32% but were also found to be associated with a lagged increase in violent crime for at least a week thereafter. 

•	On very cold days (defined as risk of property crime increased by up to 50% whereas on very rainy days (defined as ≤ 7◦C ), the cumulative relative ≥ 20mm ) the risk of property crime surprisingly increased by 40%.

•	The risk of violent crime was found to increase with a rise in daily average temperatures, peaking at 30℃.
 
Trujillo, J.C. and Howley, P. (2021)

Torrid Urban Zone – Columbia

•	Weather can be an important predictor of interpersonal violence in this area.

•	Significant and positive correlation between temperature and interpersonal violence. 

•	Humidity and precipitation were both significantly and negatively related with interpersonal violence. 

•	No significant correlation between any of the weather variables and homicides, except windspeed, which was positively correlated with both homicides and interpersonal violence.
 
Blakeslee, D. et al. (2021) 

Karnataka, India

•	Violent crimes respond to both daily and seasonal variation in temperatures and rainfall.

•	Property crimes only respond to seasonal variation.

•	An increase of 1 ◦C in daily maximum temperature is associated with a 0.5% increase in the expected crime count on a given day. 

•	This effect is driven by violent crimes, for which we estimate a 0.8% increase in probability of an additional crime with each 1 ◦C temperature increase.
•	Small decline in property crimes with higher temperatures (above 40 ◦C).

•	1 mm increase in rainfall causing a 0.3% decline in the probability of an additional crime.

•	This study is that it takes place in a region with persistently high temperatures, with seasonal temperatures ranging between 30–35 ◦C throughout most of the year. Despite being accustomed to perennially high temperatures, individuals nonetheless continue to display a strong tendency for violence when a single day’s temperature makes an unexpected rise. This may indicate that physiological acclimatization has limited potential to reduce the future impacts of rising temperatures on the incidence of crime.
 
Ranson, M. (2014)
U.S.

•	Short-term relationship between crime and weather show that higher temperatures cause substantial increases in crime, implying that climate change could have important impacts on criminal activity. 

•	Between 2010 and 2099, climate change will cause an additional 22,000 murders, 180,000 cases of rape, 1.2 million aggravated assaults, 2.3 million simple assaults, 260,000 robberies, 1.3 million burglaries, 2.2 million cases of larceny, and 580,000 cases of vehicle theft in the United States.

•	Results suggest that in the year 2090, crime rates for most offense categories will be 1.5–5.5% higher because of climate change.

•	An immediate and permanent 4% increase in the size of the US police force would be required to offset the aggregate climate-related increases in murder, manslaughter, robbery, burglary, and vehicle theft that are likely to occur over the next century.

•	These simulations are based on the IPCC's A1B scenario, a “middle-of-the-road” climate change scenario that assumes eventual stabilization of atmospheric CO2 levels at 720 ppm
 
I also came across this Guardian article which mentions the London riots of 2011, and cites Workman, who suggests that crime and riots increase between 27C and 32C – but after 32C, “it’s as though people are too hot to bother”.
 
 
References:

Baryshnikova, N., Davidson, S. and Wesselbaum, D. (2021) ‘Do you feel the heat around the corner? The effect of weather on crime’, Empirical economics [Preprint]. doi:10.1007/s00181-021-02130-3.

Blakeslee, D., Chaurey, R., Fishman, R and Malghan, D. (2021) ‘In the heat of the moment: Economic and non-economic drivers of the weather-crime relationship’, Journal of economic behavior & organization, 192, pp. 832–856. doi:10.1016/j.jebo.2021.11.003.

Horrocks, J. and Menclova, A.K. (2011) ‘The effects of weather on crime’, New Zealand economic papers, 45(3), pp. 231–254. doi:10.1080/00779954.2011.572544.

Potgieter, A., Fabris-Rotelli, I. N., Breetzke, G. and Wright, C. Y. (2022) ‘The association between weather and crime in a township setting in South Africa’, International journal of biometeorology, 66(5), pp. 865–874. doi:10.1007/s00484-022-02242-0.

Ranson, M. (2014) ‘Crime, weather, and climate change’, Journal of environmental economics and management, 67(3), pp. 274–302. doi:10.1016/j.jeem.2013.11.008.

Towers, S., Chen, S., Malik, A. and Ebert, D. (2018) ‘Factors influencing temporal patterns in crime in a large American city: A predictive analytics perspective’, PloS one, 13(10), pp. e0205151–e0205151. doi:10.1371/journal.pone.0205151.

Trujillo, J.C. and Howley, P. (2021) ‘The Effect of Weather on Crime in a Torrid Urban Zone’, Environment and behavior, 53(1), pp. 69–90. doi:10.1177/0013916519878213.
