# ISM-DBA-Dissertation
My Files and Source Codes for My DBA Dissertation title Factors Influencing the Adoption of Solar Power in Nigeria
Acknowledgements

I would like to thank the following people / groups for inspiring me, guiding me, supporting me and helping me, in various ways, towards the completion of this dissertation. 

a)	Professor Joseph Onochie
b)	Professor Cesar Baena
c)	Dr Matthew Andrews
d)	My family: Xavier, Bryon, Yoana, Audra Zinia and Mercy
e)	All the responders to my survey questions
f)	The support team of SurveyGizmo
g)	All the research volunteers in Benin City, Abuja, Minna, Lagos, Port Harcourt and Aba
 

 
Abstract
Nigeria generates 4000MW of electricity for her 180 millionpeople. Per capital power is only 71W compared to South Africa’s 600W.  Less than 30% of the population’s energy requirement is supplied by the grid: the rest is from inefficient and environmentally hurtful fossil fuel generators (FFG), including those diesel-operated units deployed in pairs at each GSM (Global System for Mobile) Communications base station by the mobile phone operators, and the smaller petrol-driven units employed in households that can afford them. As they are not connected to the main grid, the excess power accruable to these generating sets cannot be harnessed.  They are expensive to procure and run, and they worsen the country’s carbon footprint.  The World Health Organisation ranked four Nigerian cities (Onitsha, Kaduna, Aba and Umuahia) are amongst those with the highest levels of two different sizes of particulate matter, PM10 and PM2.5 per cubic metre of air in the world as at 2017. Though, post COVID reduction in activity levels around the world as given a temporary reprieve, accumulated exposure to poor air quality is associated with increased risks of stroke, heart disease, lung cancer, and chronic and acute respiratory diseases, including asthma. (The Editor, The Punch, 2017).
Due to its location near the equator, Nigeria’s solar power potential is well known, and the progressive reduction in the cost of procuring solar equipment from year 2010 onwards, in dollar terms, has increased activity in the area of renewable energy space. It has also made the case for its adoption of solar power even more compelling, as initial costs of installation has been dropping. Fortunately, the Nigerian Government has reduced the import duties on solar systems. This has compensated, somewhat, for the depreciation in national currency (Naira). Taken together however, the costs of acquiring the form of clean energy is still a significant burden on the average Nigerian household.  The array of financial incentives commonly available in Europe and North America has not been available in Nigeria. This has remained the case even as government sets ambitious targets for the level of clean energy generation. Observers argue that the huge costs Nigerians spend every year on purchase, fuelling and maintenance of generators is a sufficient justification for switching. Nearly every month a family is lost in their sleep from inhalation of generator fumes. Regardless of these benefits, solar power adoption levels have not grown at the exponential rates expected. It is necessary to study the demand side because a faster rate of adoption is required for the sustainability of the renewable energy thrusts, development of local capacity and a further reduction in the costs of energy produced from this means. It is the one area where the people can seize the initiative and contribute to the goal of decarbonization of energy production.
In order to develop a set of questionnaires for measuring attitudes towards solar adoption, I adapted constructs from previous solar adoption studies conducted in other regions of the world. These questionnaires were deployed in 6 cities in Nigeria. They were deployed with the aid of SurveyMonkey, hand-held devices and paper copies. Some 6523 valid surveys were acquired, between 1st June and 21st June, 2019.   Analysis of the survey data was done with R statistical software customised with packages for conducting Exploratory Factor Analysis, variable selection, and ordinal logistics regression.  The Scree Plot results from our study recommended a total of 8 factors with a cumulative explanatory power of 34%. The overall reliability of the model was assessed with Cronbach's Alpha. A score of 0.88 was achieved which is Very Good on the George and Mallery (2003) assessment criteria. For each of the sub-tests their alpha ranged from 0.61 for Acceptance of Innovation (AI) and 0.77 for Norms, which are all within the Acceptable to Good range on the same criteria. The logistics regression carried out suggested a model of the form: Intent ~ Enve+Cost+MktEff+Norms+Cmplx (where Enve is Environment, Cost refers to Cost and Affordability, MktEff connotes Marketing Effectiveness and Cmplx is Complexity). The Acceptance-of-innovation factor dropped out for lack of statistical significance.

From these results, and those of ordinal logistics regression modeling, we were able to reach a decision on which of the hypotheses is supported (is TRUE) and those that can be REJECTED.  Supported hypotheses includes the following:
H1 is TRUE: Environmental stewardship is a significant driver of PV Solar Adoption in Nigeria.
H3B: A structure of incentives aimed at making solar power installation more affordable will stimulate its Adoption in Nigeria 
H3A: Perceived high initial cost of installation is a significant barrier to Solar Adoption in Nigeria.
H4B: Solar power messages that are culturally adapted to the audience will be more effective at stimulating adoption.
H4A: Adoption of solar power in Nigeria is related to the level of Awareness and Knowledge about their features.
H5: Social Conformity including peer pressure and family influence are significant factors in solar adoption process.
H6: Perceived ease of use and overall level of complexity is a significant factor in adoption of solar power in Nigeria.

The hypotheses that we could not find support for include the following:
H2: Higher levels of innovation acceptance leads to higher levels of solar power adoption in Nigeria
H7A: Solar power adoption in Nigeria is related to household income level.
H7B: Solar power adoption in Nigeria is related to house education level.

 
