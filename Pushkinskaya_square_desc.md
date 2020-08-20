| QNo  | Question | ColName / Code |
| ------------- | ------------- |------------- |
| q1 | Age | **q1_age_code** |
| | &nbsp;  | `1_under_18` |
| | &nbsp;  | `2_under_25` |
| | &nbsp;  | `3_under_35` |
| | &nbsp;  | `4_under_45` |
| | &nbsp;  | `5_under_57` |
| | | |
| q2 | Gender | **q2_gender_code** |
| | | |
| q3 | Education | **q3_education_code** |
| | &nbsp;1. Secondary  | `1_secondary_school` |
| | &nbsp;2. Technical school  | `2_vocational_school` |
| | &nbsp;3. Undergraduate  | `3_student` |
| | &nbsp;4. Graduate  | `4_graduate` |
| | &nbsp;5. PhD  | `5_phd` |
| | | |
| q4 | Military service | **q4_conscription_code** |
| | 1. Yes | 1_yes |
| | 2. No | 2_no |
| | 3. Ineligible for military duty | 3_not_subject |
| | | |
| q5 | Occupation | **q5_job_src** |
| | Open question with additional codes: 1. Entrepreneur 2. Freelance 3. Top management| |
| | | |
| q6 | What is your income | **q6_wealth_code** |
| | &nbsp; ...-5 | `1_below_5` |
| | &nbsp; 5-15 | `2_below_15` |
| | &nbsp; 15-30 | `3_below_30` |
| | &nbsp; 30-50 | `4_below_50` |
| | &nbsp; 50-80 | `5_below_80` |
| | &nbsp; 80-110 | `6_below_110` |
| | &nbsp; 110-… | `7_over_110` |
| | | |
| q7 | Open question: Do you participate in community initiatives: (volunteering, blue buckets, Khimki forest, observing elections). Code is boolean. | **q7_activism_src**, **q7_activism_code** |
| | | |
| q8 | How often do you participate in political activity? | **q8_protester_career_code** |
| | &nbsp; 1. For the first time. | `1_newcomer` |
| | &nbsp; 2. I was on Bolotnaya Square and/or Academician Sakharov Avenue. | `2_bolotnaya_debutant` |
| | &nbsp; 3. I participated in the rallies of 1991. | `3_1991_debutant` |
| | &nbsp; 4. I have participated in some other activities before. | `4_veteran` |
| | &nbsp; 5. I am a political activist and often participate in such activities. | `5_activist` |
| | | |
| q9 | Mark on the scale the appropriate balance between the free market and state control in Russia? | **q9_market_code** |
| | 0: Center of the scale  -5: Rapid business development with absence of social security  5: High level of state regulation and social security | |
| | | |
| q10 | Evaluate the influence degree of these factors on the Russian political life («1» — minimum impact till «5» — decisive impact) | **q10_[1..9]\_src** |
| | &nbsp; Political clans | `q10_1_clans_src` |
| | &nbsp; Putin’s clan in particular | `q10_2_family_src` |
| | &nbsp; Putin in particular | `q10_3_putin_src` |
| | &nbsp; Oligarchy | `q10_4_oligarchy_src` |
| | &nbsp; The irremovability of power | `q10_5_rotation_src` |
| | &nbsp; Bureaucracy of «United Russia» political party | `q10_6_united_russia_src` |
| | &nbsp; The Office of the president | `q10_7_cabinet_src` |
| | &nbsp; Low civic activity | `q10_8_passivness_src` |
| | &nbsp; Antichrist | `q10_9_antichrist_src` |
| | | |
| q11 | What does it take to arrange satisfactory federal elections? | **q11_[1..9]\_src** |
| | &nbsp; 1. No media censorship | `q11_1_censorship_src` |
| | &nbsp; 2. Churov's resignation | `q11_2_churov_src` |
| | &nbsp; 3. Returning the option “against all” | `q11_3_bulletin_src` |
| | &nbsp; 4. Establishment of minimum voter turnout required | `q11_4_turnout_src` |
| | &nbsp; 5. Setting electronic ballot boxes | `q11_5_digital_src` |
| | &nbsp; 6. Free registration of candidates | `q11_6_candidates_src` |
| | Other: open answer| **q11_7_other_src** |
| | | |
| q12 | Where do you get information from: the media/social networks. Specify your answer. | |
| | Open answers | **q12_1_newspaper_src**, **q12_2_radio_src**, **q12_3_tv_src**, **q12_4_social_src** |
