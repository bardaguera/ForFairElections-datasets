| QNo  | Question | ColName / Code |
| ------------- | ------------- |------------- |
| q1 | Age | **q1_age_src** |
| | | |
| q2 | Gender | **q2_gender_code** |
| | | |
| q3 | Education | **q3_education_code** |
| | 1. Secondary | 1_secondary_school |
| | 2. Undergraduate | 2_student |
| | 3. Technical school | 3_vocational_school |
| | 4. Graduate | 4_graduate |
| | 5. PhD | 5_phd |
| | | |
| q4 | Do you practise your profession? |**q4_profession_practising_code** |
| | Yes | 1_practising |
| | No | 2_not_practising |
| | | |
| q5 | Military service | **q5_conscription_code** |
| | 1. Yes | 1_yes |
| | 2. No | 2_no |
| | 3. Ineligible for military duty | 3_not_subject |
| | | |
| q6 | Occupation | **q6_job_code** |
| | &nbsp; 1. Information technology | `1_it` |
| | &nbsp; 2. Accounting and marketing | `4_white_collar` |
| | &nbsp; 3. Top management | `2_top_management` |
| | &nbsp; 4. Mass media | `2_massmedia` |
| | &nbsp; 5. Non-profit organisations | `99_nonprofit` |
| | &nbsp; 6. Science | `3_science` |
| | &nbsp; 7. Education | `7_education` |
| | &nbsp; 8. Medicine | `8_medicine` |
| | &nbsp; 9. Civil service | `99_civil_service` |
| | &nbsp; 10. Sport | `99_sport` |
| | &nbsp; 11. Art | `5_art` |
| | &nbsp; 12. Banks and investments | `6_capital` |
| | &nbsp; 13. Construction | `5_construction` |
| | &nbsp; 14. Manufacturing | `4_manufacturing` |
| | &nbsp; 15. Freelance | `9_freelance` |
| | &nbsp; Empty | `0_unemployed` |
| | | |
| q7 | What is your income (in thousands of rubles)? | **q7_wealth_code** |
| | &nbsp; ...-5 | `1_below_5` |
| | &nbsp; 5-15 | `2_below_15` |
| | &nbsp; 15-30 | `3_below_30` |
| | &nbsp; 30-50 | `4_below_50` |
| | &nbsp; 50-80 | `5_below_80` |
| | &nbsp; 80-110 | `6_below_110` |
| | &nbsp; 110-… | `7_over_110` |
| | | |
| q8 | Do you work overtime? | **q8_overwork_code** |
| | &nbsp; 1. I work hard and often work long hours | `1_workaholic` |
| | &nbsp; 2. Sometimes I have to work overtime. | `2_busy_bee` |
| | &nbsp; 3. I have a 40-hour week. | `3_40hours` |
| | &nbsp; 4. I am able to leave work early or do not work the whole week. | `4_flexible` |
| | &nbsp; 5. I am a freelancer. | `5_freelancer` |
| | &nbsp; 6. I do not work. | `6_doesnt_work` |
| | | |
| q9 | How often do you participate in political activity? | **q9_protester_career_code** |
| | &nbsp; 1. For the first time. | `1_newcomer` |
| | &nbsp; 2. I was on Bolotnaya Square and/or Academician Sakharov Avenue. | `2_bolotnaya_debutant` |
| | &nbsp; 3. I participated in the rallies of 1991. | `3_1991_debutant` |
| | &nbsp; 4. I have participated in some other activities before. | `4_experienced` |
| | &nbsp; 5. I am a political activist and often participate in such activities. | `5_activist` |
| | | |
| | Additional column: Some respondents wanted to emphasize their participation in the 90s strikes. | **q9_3flag_src** |
| | | |
| q10 | Which problems in contemporary Russia do you consider the most significant (strictly up to 4): | **q10_Rfproblems_src** |
| | &nbsp; Boolean: 1. Corruption in the highest government levels | `q10_1` |
| | &nbsp; Boolean: 2. Corruption in ‘field office’ | `q10_2` |
| | &nbsp; Boolean: 3. Destructive reforms in the field of health and education | `q10_3` |
| | &nbsp; Boolean: 4. Lack of developed manufacturing (the problem of commodity-dependent economy) | `q10_4` |
| | &nbsp; Boolean: 5. Degradation of the population (alcohol abuse, drug addiction, juvenile delinquency) | `q10_5` |
| | &nbsp; Boolean: 6. Constraints to the political elite renewal (stagnation) | `q10_6` |
| | &nbsp; Boolean: 7. Clannishness (ongoing links between the state apparatus and business) | `q10_7` |
| | &nbsp; Boolean: 8. The considerable loss of the Russian Federation global prestige. | `q10_8` |
| | | |
| | Additional column: Check column. Rsps had to pick strictly up to 4 answers | **q10_sum** |
| | | |
| | Additional column: q10_1 &q10_2 &q10_6 &q10_7 | **q10_public_code** |
| | | |
| | Additional column: q10_3 &q10_4 &q10_5 | **q10_private_code** |
| | | |
| q11 | What do you think about Putin? | **q11_putin_src** |
| | &nbsp; Boolean: 1. I am quite loyal to V.V. Putin, the problem does not refer to him. | `q11_1_loyal` |
| | &nbsp; Boolean: 2. I admit that many people appreciate his charisma, but I do not like him. | `q11_2_calm` |
| | &nbsp; Boolean: 3. I suppose that he is not a leader for most citizens. | `q11_3_suspicious` |
| | &nbsp; Boolean: 4. I believe that all the guilt is his. | `q11_4_accusing` |
| | &nbsp; Boolean: 5. I am not interested in him, he is not the problem. | `q11_5_indifferent` |
| | | |
| | Additional column: Sum column. | **q11_sum** |
