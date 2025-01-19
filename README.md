HR PROMOTION SUMMARY								
								
INTRODUCTION								
PROBLEM STATEMENT=  to identify if there is biasness in the appraisal cycle and make sure it does not happen in next cycle.								
								
DATA OVERVIEW								
we have total 54808 columns and 14 rows in the given data								
Null values of 2 columns 'EDUCATION' and 'previous_year_rating' are filled								
Sum of total promotion done-			4668					
								
DATA VISUALIZATION								
								
                                                                                                                                 ON THE BASIS OF DEPARTMENT								
								
	department	is_promoted_sum	is_promoted_count	promotion_rate				
	Analytics	512	5352	9.566517				
	Finance	206	2536	8.123028				
	HR	136	2418	5.624483				
	Legal	53	1039	5.101059				
	Operations	1023	11348	9.014804				
	Procurement	688	7138	9.638554				
	R&D	69	999	6.906907				
	Sales & Marketing	1213	16840	7.203088				
	Technology	768	7138	10.759316				
	sum	4668	54808	8.517004817				
								
								
CONCLUSION=Technology department has highest promotion rate by 10.75%  and procurement has the second highest promotion rate.								
R&D has the lowest promotion rate.								
								
                                                                                                                                 ON THE BASIS OF AGE								
								
		age_group	is_promoted_sum	is_promoted_count	promotion_rate			
		(19.999, 28.0]	932	11048	8.435916			
		(28.0, 32.0]	1225	14138	8.664592			
		(32.0, 35.0]	888	8997	9.869957			
		(35.0, 40.0]	864	9963	8.672087			
		(40.0, 60.0]	759	10662	7.118739			
		sum	4668	54808	8.517004817			
								
								
								
								
								
								
CONCLUSION=people with age group (32.0, 35.0] has highest rate of promotion by 9.8% and (40.0, 60.0] has the lowest promotion rate i.e.7.11%								
								
								
                                                                                                                                 ON THE BASIS OF previous_year_rating								
								
		previous_year_rating	is_promoted_sum	is_promoted_count	promotion _rate			
		1	88	6223	1.414109			
		2	181	4225	4.284024			
		3	1355	18618	7.277903			
		4	784	9877	7.937633			
		5	1921	11741	16.361468			
		sum	4329	50684	8.541156973			
								
								
								
								
								
								
								
								
CONCLUSION=PROMOTIONS HAS IMPROVED ON THE BASIS OF RATING. 5 RATING OF PREVIOUS_YEAR_GOT THE HIGHEST PROMOTION RATE by 16.35.								
								
                                                                                                                                 ON THE BASIS OF length_of_service								
								
		Length_of_service_group	is_promoted_sum	is_promoted_count	promotion_rate			
		(0.999, 2.0]	972	11231	8.654617			
		(2.0, 3.0]	609	7033	8.659178			
		(3.0, 4.0]	598	6836	8.747806			
		(4.0, 5.0]	475	5832	8.144719			
		(5.0, 6.0]	401	4734	8.470638			
		(6.0, 7.0]	464	5551	8.358854			
		(7.0, 10.0]	702	7705	9.110967			
		(10.0, 37.0]	447	5886	7.594292			
		sum	4668	54808	8.517004817			
								
								
								
								
								
								
CONCLUSION=length_of_service_group(7.0, 10.0] has the highest promotion rate i.e 9.11%.								
								
                                                                                                                                 ON THE BASIS OF no_of_trainings								
								
		no_of_trainings	is_promoted_sum	is_promoted_count	promotion_rate			
		1	3910	44378	8.810672			
		2	605	7987	7.574809			
		3	122	1776	6.869369			
		4	26	468	5.555556			
		5	3	128	2.34375			
		6	2	44	4.545455			
		7	0	12	0			
		8	0	5	0			
		9	0	5	0			
		10	0	5	0			
		sum	4668	54808	8.517004817			
								
								
								
								
CONCLUSION=more the no.of trainings, less the promotions. people with 1 training has the highest promotion rate.								
								
                                                                                                                                 ON THE BASIS OF avg_training_score								
								
		avg_training_score_group	is_promoted_sum	is_promoted_count	promotion_rate			
		(38.999, 48.0]	262	6606	3.966091			
		(48.0, 50.0]	212	5397	3.928108			
		(50.0, 53.0]	219	5527	3.962367			
		(53.0, 58.0]	377	6274	6.008926			
		(58.0, 60.0]	283	4219	6.707751			
		(60.0, 64.0]	438	5058	8.659549			
		(64.0, 71.0]	596	5813	10.252881			
		(71.0, 79.0]	552	5390	10.241187			
		(79.0, 83.0]	547	5208	10.503072			
		(83.0, 99.0]	1182	5316	22.234763			
			4668	54808	8.517004817			
								
								
								
								
CONCLUSION=PROMOTION RATE HAS INCREASED WITH INCREASING TRAINING SCORE. (83.0, 99.0]avg_training_score_group HAS THE HIGHEST PROMOTION RATE.								
								
                                                                                                                                 ON THE BASIS OF education								
								
								
	education	is_promoted_sum	is_promoted_count	promotion_rate				
	Bachelor's	3130	39078	8.009622				
	Below Secondary	67	805	8.322981				
	Master's & above	1471	14925	9.855946				
	sum	4668	54808	8.517004817				
								
								
								
								
								
								
								
								
								
								
								
CONCLUSION=PROMOTION RATE HAS INCREASED WITH HIGHER EDUCATION. Master's & above education have the highest promotion rate by 9.8%								
								
                                                                                                                                 ON THE BASIS OF gender								
								
	gender	is_promoted_sum	is_promoted_count	promotion_rate				
	female	1467	16312	8.993379				
	male	3201	38496	8.31515				
	sum	4668	54808	8.517004817				
								
								
								
								
								
								
								
								
								
								
								
CONCLUSION=female has the highest promotion rate as compared to males by 8.9%								
								
                                                                                                                                 ON THE BASIS OF recruitment_channel								
								
	recruitment_channel	is_promoted_sum	is_promoted_count	promotion_rate				
	other	2556	30446	8.395191				
	referred	138	1142	12.084063				
	sourcing	1974	23220	8.501292				
	sum	4668	54808	8.517004817				
								
								
								
								
								
								
								
								
								
								
								
CONCLUSION='referred' recruitment_channel has the highest promotion rate by 12.08%								
FINAL CONCLUSIONS																								
																								
1.  Technology department has highest promotion rate i.e 10.75%  and legal has the lowest promotion rate i.e 5%.  whereas base promotion rate in the organization is just 8.5%																								
																								
2.  people with age group (32.0, 35.0] has highest rate of promotion i.e 9.8% and (40.0, 60.0] has the lowest promotion rate i.e.7.11% .																								
																								
3.  5 RATING OF PREVIOUS_YEAR_GOT THE HIGHEST PROMOTION RATE i.e 16.35. and lowest rating got the least promotion i.e 1% and 3 and 4 rating has the same promotion rate.																								
																								
3.  length_of_service_group(7.0, 10.0] years has the highest promotion rate i.e 9.11%.																								
																								
4.  people underwent upskill trainings has lower promotion rate than the ones who did'nt undergo. people with 1 training has the highest promotion rate  i.e 8%.																								
																								
5.  PROMOTION RATE HAS INCREASED WITH INCREASING TRAINING SCORE.                    (83.0, 99.0]avg_training_score_group HAS THE HIGHEST PROMOTION RATE.																								
																								
6.  PROMOTION RATE HAS INCREASED WITH HIGHER EDUCATION. Master's & above education have the highest promotion rate i.e 9.8%																								
																								
7.  female has the highest promotion rate as compared to males i.e 8.9%																								
																								
8.    'referred' recruitment_channel has the highest promotion rate i.e 12.08%																								
																								
9.  Promotion rate is highest for the awards winning people by 44.0%																								
![image](https://github.com/user-attachments/assets/d8adb185-7e30-4b9f-8320-01c5aa1118bd)
FINAL CONCLUSIONS	
	
	
HR analysis=	
1. BIASNESS IS DONE IN REFERRED RECRUITMENT, PREVIOUS YEAR RATING AND AVG.TRAINING SCORE. 	
	
EMPLOYE analysis=	
1. EMPLOYE SHOULD CONSIDERED THESE FACTORS IMPORTANT TO GET PROMOTION=	
	REFERRED RECRUITMENT, PREVIOUS YEAR RATING AND AVG.TRAINING SCORE.
![image](https://github.com/user-attachments/assets/afd0278b-ef9c-43d8-ba63-b4a591ec09f9)

