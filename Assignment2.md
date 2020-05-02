A Bayesian Geostatistical Approach for Improved Prediction of Child and Adolescent Educational Attainment throughout Somalia
By Abdi Hassan
April 4, 2020
Introduction
The purpose of this work is to improve upon the use of satellite and census data to generate more realistic population density estimates of the country of Somalia that also accurately account for demographic variation. With a defined research goal of increasing child and adolescent educational achievement, it is integral to develop data that accurately reflects the population densities of these groups and their distributions across the various regions. I will achieve this goal through meeting the following objectives.
Compiling survey data that more accurately reflects settlement and migration patterns of the Somali people
Applying Bayesian statistics to create a model for predicting demographic makeups of regions, particularly those that are rural and hardest to integrate
This work will build on previous research by Alegana et al. and will incorporate new methods to implement a two pronged door to door and geospatial and data based approach as well as recent advances towards inferring population densities in rural and underserved areas.
Access to Education
	It is no doubt that education is one of the many pillars of a successful childhood and adolescence. Now, with [2] 37% of children in Somalia reporting to have never been to school, what can be said of their success? What’s more, what can be said of their potential to achieve success? In developed nations across the globe education is a necessity, even a requirement, and understood to be a prerequisite to meaningfulness whether it be simple job attainment or some abstract form of societal contribution. Therefore, lack of education can be seen as creating an inability for one to contribute to society, to be meaningful, and to even just better their position. Furthermore, that 63% of children that have reported some sort of schooling is itself a misnomer and a misleadingly optimistic statistic. Of the 63% of Somali children that reported having been schooled on some level, [2] 27% were referring to Koranic schooling. Beyond this, the schooling was certainly not evenly distributed with “girls, nomads, and children in rural areas” being underserved by what little schooling did exist (Moyi).
	If we see human development through the lens of Amartya Sen and value the expansion of freedoms, then education is no doubt a priority. In fact, education is the 4th Sustainable Development Goal on the UN webpage as it is integral for development. An educated man (or woman) is a force for positive change as it means they can take advantage of opportunities and create opportunities and bolster a positive momentum in the exchange of ideas and communication with those around them and even beyond their immediate communities. It is also worth mentioning that “education” does not necessarily refer to the highest form of post secondary achievement but rather simply literacy, numeracy, and the expansion of ones ability to think critically. Thus the importance of a childhood and adolescent focus as opposed to the adult literacy approach that is usually pursued.

Child and Adolescent Educational Attainment
	Now, for a more specific glance at the problem itself, we see many more obstacles in the pursuit of child and adolescent educational attainment than first meets the eye. For one, infrastructure. There just aren’t the proper property, plant, and equipment present for the goal to be realizable at, at least, the same proportions as the global average. Furthermore, there is a noticeable lack of human capital as well. With roughly only [1] 64% of primary school teachers who are actually formally trained in sub saharan Africa, the form of education that reaches those who do acquire access is ultimately fragmented and follows no outlined pedagogical approach. This presents difficult moving up the educational ladder as there is no sound or consistent foundation for those to build upon. At the very least the foundations are different enough that it prohibits large scale mass teaching and requires individuality, another strain on the limited human capital resources present. These problems are only exacerbated by the rural child’s environment as they are even more likely to lack all of the aforementioned.
	With all this in mind we can begin to form some semblance of a conceptualization of what we would want a realistic approach to the educational void in the nation to look like. We know we want to address the underserved amongst the underserved, that is, girls and the rural poor. We also know we must avoid ethnocentrism in our approach. The delivery of education in the nation can perhaps best be seen as a complex adaptive system and, thus, rigidity rejected. We know the country is dealing with a history of colonialism, dictatorship, and religious impact on education so it is beyond us to know what the effects of this will look like in the advent of a mass education system. Furthermore, we may want to remember these principles in any attempts to scale said system. What works for one local or one tribe may not be optimal for another and instead, a case by case, evaluate and restrategize, approach may be more favorable.

Geospatial Data Science Methods
	Survey data was amongst the most formidable of the data used to quantify the education situation in Somalia. Specifically, the Somalia 2006 Multiple Indicator Cluster Survey (MICS) was helpful as it was a nationally representative sample survey covering 5969 households with very nearly equal male and female populations. The survey asked respondents questions about the household composition and influences on decisions regarding schooling. This data was quantified using a [3] multinomial logistic regression and stratified based on zones (northeast, northwest, and central south).  This survey data is complemented by high resolution spatial population mapping. Such maps were created by integrating a bevy of mapping software and data [3] including but not limited to: land cover classification software, a dataset depicting urban and settlement polygon outlines from detailed imagery, 2005 Landsat imagery, and road and river data obtained from Vector Map level Zero. This data was aggregated using both on screen interpretation and hierarchical clustering techniques which led to higher spatial detail than the national and, at best, regional subnational units provided by large scale census data. The resulting maps yielded [3] gridded population datasets at 100 x 100 meters spatial resolution.

References
[1] Social Council, E. A. (2018, July 26). Special edition: progress towards the 
     Sustainable Development Goals [PDF]. Retrieved from https://undocs.org/E/ 
     2019/68
[2] Moyi, P. (2012). Who goes to school? School enrollment patterns in Somalia [PDF 
     e-book]. Retrieved from https://www.sciencedirect.com/science/article/pii/
     S0738059310001343
[3] Linard, C., Alegana, V.A., Noor, A.M. et al. A high resolution spatial population database of Somalia for disease risk mapping. Int J Health Geogr 9, 45 (2010). https://doi.org/10.1186/1476-072X-9-45