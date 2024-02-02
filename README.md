




















Human Disease Prediction Using Symptoms





Algorithms Used:
Random Forest
K-Nearest Algorithm
Naive Bayes Algorithm

 
ABSTRACT:
Major animal diseases pose a great threat to animal husbandry and human beings. Cattle animals are prone to many diseases, some of which can decrease productivity and lowers the quality of dairy products and if not identified at early stage, can also lead to the death of cattle which is greatly impeded by Sustainable development. Significant numbers of cattle are found in many dairies. It is just too hard to take care of them and track the health of dairy cow. Continuously seeing the health of individual cattle
,quickly diagnosing and handling sick cattle as early as possible is the main feature .We use sensor technologies to chart the basic aspects of animal activity such as heartbeat
,hotness etc.. This data is aggregated and submitted to a data mining model to validate whether any anticipated event of imminent disease is expected . 

Livestock Disease Prediction using Machine Learning is a cutting-edge initiative designed to revolutionize animal health management. Leveraging advanced algorithms, this project delves into extensive datasets encompassing various factors such as environmental conditions, animal behavior, and health records. By scrutinizing patterns within this data, the machine learning model becomes adept at identifying potential outbreaks and predicting disease occurrences in livestock populations.

The predictive power of the model lies in its ability to recognize subtle correlations that might elude human observation. Early detection is crucial in preventing the spread of diseases among livestock, minimizing economic losses for farmers and ensuring the overall well-being of the animals. Through continuous learning and adaptation, the system evolves to handle diverse scenarios, making it a proactive tool in safeguarding the health of livestock.

This initiative not only contributes to the advancement of precision agriculture but also underscores the potential for technology to address real-world challenges in the agricultural sector. By integrating machine learning into livestock management practices, we pave the way for a more resilient and efficient agricultural system that promotes sustainable farming and ensures the health and productivity of livestock populations

  KEY WORDS :

Animal husbandry, Disease , Machine Learning, Livestock ,Data, Tracking

INTRODUCTION:
Animal husbandry is an activity where food and non food items are nurtured by livestock .Milk and its substitutes ,eggs and beef are agricultural goods .Bone products
,pharmaceuticals ,wool etc.. contain non food products .This includes through care of the animals on a regular basis .A part of its productivity comes from animal husbandry as a branch of agriculture .In our country around 20.5 million people rely on livestock for their livelihoods meaning that 2/3 of the village population gets their livelihoods


 from dairy farming .From livestock animals we get variety of food and non-food products .
Cattle diseases can in terms of quality and quantities have a detrimental effect on productivity. parturient paresis, Ketonemia, tension, limping, fever etc. include major cattle diseases. These diseases can spread rapidly where thousands of cattle are raised together in vast farms, which can cause a significant drop in income.
In this project we will predict the diseases based on symptoms. It predicts using 2 different algorithms (Random Forest, Decision tree). So, the output is accurate.


PROBLEM STATEMENT:
A disease is a state of illness, it affects the functionality of the body parts. If disease is present in the cattle’s ,this intern causes problems like reduction in the yield of milk and the economy of the country .If the present disease is a Communicable disease, then the impact is very high. That might destroy all the cattle’s. The early detection of the disease present is very important to overcome the above problems.
In this we use the Machine Learning Algorithms to solve the problems. The model developed takes the symptoms of the cattle’s and output from the sensors as input and does the analysis using machine learning algorithms to predict the accurate disease. This model helps in early detection of some of the dangerous diseases.
The complexity of factors influencing livestock health, including environmental conditions, animal interactions, and emerging pathogens, necessitates a comprehensive solution. Conventional methods rely heavily on retrospective analysis and human observation, which can be limited in their ability to detect subtle patterns or predict future outbreaks. As a result, there is a gap in the ability to implement preventive measures and mitigate the impact of diseases on both the agricultural industry and global food security. Bridging this gap requires leveraging the capabilities of machine learning to analyze vast datasets and provide early, data-driven insights into potential disease threats within livestock populations.
 
LITERATURE SURVEY

S.NO.	TITLE	AUTHORS	YEAR	DESCRIPTION	ADVANTAGES	ISSUES
1	Integrat ing diverse Data sources to predict disease risk in dairy cattle-a machin e laernin g approac h	Jana Lasser, Caspar Matzhold, Christa Egger- Danner,Birg it Fuerst- Walti	2021	Precision livestock farming approach, bringing together information streams from a variety of life domains of dairy cattle to study whether including more and diverse data sources improves the quality of predictions for eight diseases and whether using more complex prediction algorithms can, to some extent, compensate for less diverse data.	1)	Using more diverse sets of independent variables (independent variables) and a larger number of observations (rows) will generally improve prediction performance
2)	Improved health and
herd management on dairy farms by enabling individualized data-driven point- of-care interventions through the reuse and integration of information from a multitude of different
sources around a farm and application of machine learning (ML)
algorithms to predict disease occurrences.	1)	Ensuring quality and consistency of data .
2)	Merging and transforming data from diffferent formats.
2	The Early predicti on of commo n disorde rs in dairy cows monitor
ed by	Xiaojing Zhou,Chuan g Xu, Hao Wang,Wei xu,Zixuan Zhao	2022	Identifying cows with a higher risk of health disorders such as clinical mastitis, subclinical ketosis, lameness, and metritis could be advantageous for farms to prevent and ameliorate the
negative effects of	1) Six
parameter s were presented to evaluate the performan ce metrics of the models, with the Rpart	1)	Number of samples in one class is significantly smaller than the number of samples.
2)	Imbalanced data leads to biased models
 
	automat ic systems with machin e learnin g algorith ms			these disorders in a timely manner.	algorithm
outperfor ming others and indicating a strong generaliza tion ability of this algorithm.
2) The early
detection of cows at risk of disorders could allow for timely interventio n, thus decreasing their negative
effects.	
3	Predicti ng Disease in Transiti on Dairy Cattle Based on behavio urs Measur ed Before Calving	Mohammad
W. Sahar
,Annabelle Beaver , Marina A.G.von keyserlingk	2020	To use prepartum behavior to predict which cows have an increased risk of developing these conditions after calving. The behavior of 213 multiparous and 105 primiparous Holsteins was recorded for approximately three weeks before calving by an electronic feeding system.	1)	Separate models were
developed for primiparo us and multiparo us animals.
2)	Developin g tools for the early identificati on of animals at risk of transition- period diseases may help in prevention and
treatment.	Reduced feed intake and time spent feeding before calving are associated with metritis and Ketosis after calving.
2)Decreased agonistic behaviour prepartum is associated with increased disease risk postpartum for metritis.
 
4	Cattle Disease Identifi cation using Predicti on techniq ues	Noone Vijay Kishan ,Sai Trinath Y,Sandeep Kavalur , Sangamesha
,
Mr.Sumanth Reddy	2021	In raising a country's economic standing, agriculture plays a significant part. In India itself, Almost 18 percent of the gross domestic product is provided for by the agricultural sector. Agriculture and the husbandry of livestock both go in parallel. Animal husbandry is an activity where food and non-food items are nurtured by livestock.	1)	Technol ogies for automatio n have the ability to allow scientific informatio n and to advance it.
2)	The dataset is broken down into small and small subsets by studying the sequence of explicit rules(if- then) on function values, where the target value(in our case disease) is
predicted as a result.	1)	If disease is present in the cattles, this intern causes problems like reduction in the yield of milk, and the economy of the country.
2)	If the present disease is a communicable disease, then the impact is very high. That might destroy all the cattles.
5	Cattle health monitor ing system using Arduin o and LabVIE W for early detectio n of disease s	Kunja Bihari Swain, Satyasopan Mahato, Meerina patro, sudeepta kumar pattnayak	2017	Farmers who endure recurrent suffering owing to the ill health of their cattle and the lack of competent veterinarians nearby may benefit from effective online cattle health monitoring. In this study, we provide a tool that enables farmers to track and contrast the current health
parameters of the cattle with the	1) Online
cattle health monito ring system provid es accura te and real time health param eters of the
cattle which	Due to the unavailability of veterinarians in rural areas people with their cattle’s visits the veterinarians by travelling a far distance which costs them a lot.
 
				typical reference healthy parameters, allowing them to detect any decline in the cattle's health. Arduino UNO, Arduino NANO, an Xbee module, as well as several types of sensors have been utilised to build such a device for real-time use. This essay mostly focuses on cattle- related metrics including heart rate, temperature, rumination, and body humidity.	are incredi bly helpful in monito ring the health conditi on and detecti ng any change in behavi or and health proble ms.
2) Online cattle health monito ring system which enable s the people to monito r the health conditi on and recogn ize any signs of health deterio ration
in cattle.	
6	Title Lumpy Skin disease: Review of literatur e	K. A. Al-
Salihi	2014	In the livestock business, lumpy skin disease (LSD) results in	1) the virus is susceptibl e to	1) LSD
Causes considerabl e economic
 
				significant financial losses. It is brought on by the Poxviridae- family member Lumpy skin disease virus (LSDV), of which the Neethling strain is the prototype.
LSDV is a member of the Capripoxvirus genus, which also includes the sheep pox and goat pox viruses. Cattle are susceptible to the infectious, eruptive, and rarely fatal LSD illness, which is characterised by skin nodules. The only impacted animal species are cattle and water buffalo, both of which have high morbidity rates but low mortality.
Nevertheless, mortality rates are higher in calf populations.	sunlight and detergents containing lipid solvents, while, in dark environme ntal conditions
, such as contamina ted animal sheds, it can persist for many months.
2) The
colinearity is disrupted and poxvirus homologu es are either absent or share a lower percentage of amino acid identity (average of 43%) in the
terminal regions.	losses due to emaciation, damage to hides, infertility, mastitis, loss of milk production, and mortality of up to 20%.
2) The incubation period in the field is believed to be two to five weeks, and lesions first appear at the inoculation site in 4 to 20 days.
7	Assessi ng machin e learnin g techniq ues
in forec asting
lumpy	Ehsanalla Afshari Saf avi	2022	The LSDV (umpy skin disease virus) is an infectious illness that affects cattle. Geospatial and climatic factors are crucial in the epidemiology of the disease because of their direct
connection to the	1) ANN can
be used to forecast the occurrenc e of LSDV
infection with high precision
using	A warm and humid climate, environmental conditions that support an infux of vector populations, such as those seen during seasonal rains,
and the
 
	skin disease occurre nce based on mete orologi cal
and geo spatial feature s			survival of arthropod vectors. This study's aim was to evaluate the potential of different machine learning algorithms to predict the occurrence of LSDV infection based on climatic and geophysical characteristics. At the beginning, the ExtraTreesClassife r algorithm was used to choose the most crucial predictive features in order to forecast the presence of disease in test data involving meteorological and animal population density. With test data, several machine learning techniques showed up to 97% accuracy in predicting the presence of LSDV. The artificial neural network (ANN) algorithm beat other machine learning techniques in terms of area under curve (AUC) and F1 performance metric scores in predicting the occurrence of LSDV infection in unseen data with the corresponding
values of 0.97 and 0.94, respectively	geospatial and meteorolo gical parameter s.
2)		The LSDV is a double- stranded DNA
virus belonging to the Capripox v irus genus.	introduction of new animals to a herd are all risk factors for the spread of LSDV.
2)The accuracy score is not the preferred performance measure for classifers, particularly where certain classes are more frequent than others
 
8	Livesto ck Disease Predicti on System	Daksh Ashar, Amit Kanojia, Rahul Parihar , Prof.
Saniket Kudoo	2021	The LSDV (umpy skin disease virus)is an infectious illness that affects cattle. Geospatial and climatic factors are crucial in the epidemiology of the disease because of their direct connection to the survival of arthropod vectors. This study's aim was to evaluate the potential of different machine learning algorithms to predict the occurrence of LSDV infection based on climatic and geophysical characteristics. At the beginning, the ExtraTreesClassife r algorithm was used to choose the most crucial predictive features in order to forecast the presence of disease in test data involving meteorological and animal population density. With test data, several machine learning techniques showed up to 97% accuracy in predicting the presence of LSDV. The artificial neural network (ANN) algorithm
beat other machine learning techniques	1)	It is necessary to detect the disease outcome in the livestock to take the precaution ary measures in order to avoid spread amongst them.
2)	Livestock animals usually distribute in remote areas with relatively poor condition of diseases diagnosis rapidly and accurately.	Livestock animals usually distribute in remote areas, with relatively poor condition of disease diagnosis.
2) Animal owners are often unaware of whether the disease is mild or might prove fatal and precautions to be taken at appropriate time
 
				in terms of area under curve (AUC) and F1 performance metric scores in predicting the occurrence of LSDV infection in unseen data with the corresponding values of 0.97 and 0.94, respectively		
9	Survey on Dairy Livesto ck Disease Predicti on Syste	Prof. A.V. Brahmane, Purva Dekate, Gayatri Dike, Sneha Musmade, Rutuja Shinde	2022	The goal of this dissertation is to create an expert system for dairy farmers that can forecast livestock problems and recommend a nearby vet.
Methods: The projected system's major objective is to present a livestock disease prediction model for the forecasting of various diseases. A machine learning algorithm is employed for this purpose. This method uses a machine learning algorithm to predict the disease from the input of the symptoms. We employed a non- parametric decision tree technique and an application programming interface (API) for a local veterinarian to anticipate the disease. Findings: At the moment, a
veterinarian visit is required when	1)	The model deployed takes the symptoms of the Livestock as input and does the analysis using Machine Learning algorithms to predict the precise disease.
2)	Our proposed system will predict the livestock (Cow, Sheep and Goat) disease based on the symptoms and also provide the precaution ary measures on the
basis of disease	1)	Livestock disease is the great threat to the animal health as well as to human those are in direct contact with animals and who consumes the product of the animal who has been infected by certain disease.
2)	Animal owners are often unaware of whether the disease is mild or might prove fatal and precautions to be taken at appropriate time.
 
				livestock contract a certain disease, which is both time- consuming and expensive. Also, the farmer may have difficulties if the doctor is out of reach because it is impossible to diagnose the illness. So, if the aforementioned procedure could be carried out by an automated programme it might save time and effectively reduce cow losses by diagnosing and
treating diseases early on.	predicted	
10	Explorin g the predicti ve capabili ty of machin e learnin g models in identify ing foot and mouth disease outbrea k occurre nces in cattle farms in an endemi c setting
of Thailan	Veerasak Punyaporn withaya , Kunnanut Klaharn , Orapun Arjkumpa , Chalutwan Sansamur	2022	For the past ten years, outbreaks of foot and mouth disease (FMD) in cow farms in Thailand have seriously harmed the cattle business. For the authorities to create a plan for preventing the outbreaks, it is critical to predict FMD outbreaks based on pertinent risk variables with a high prediction accuracy. Although data-driven technologies are well-known for their predictive power, an application of these strategies to
FMD.It is difficult to predict	1)	FMD is respon sible for signifi cant losses in produc tion and produc tivity to cattle farmers, as well as resulting in trade embar goes and substa ntial overar ching.
2)	The predict ion models for livestock disease outbreaks based on classic al statistical and mathematical techniques have been widely demon strateg	Not only does the size of the data varies, but the number of predictors used also varies to develop models.
 
	d			outbreaks. In order to predict FMD outbreaks among cattle farms, this study developed prediction models using machine learning (ML) classification algorithms, such as classification trees (CT), random forests (RF), and Chi-squared automatic interaction detection (CHAID), and
compared the accuracy of the models' predictions		

