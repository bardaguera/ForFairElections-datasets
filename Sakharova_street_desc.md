| QNo  | Question | ColName / Code |
| ------------- | ------------- |------------- |
| q1 | Age, gender | **q1_age_src**, **q1_sex_src** |
| | | |
| q2 | Area of employment (indicate your profession, if possible) | **q2_job_code** |
| | &nbsp; Student | `4_student` |
| | &nbsp; University student | `4_student` |
| | &nbsp; Public sector employee | `2_public_sector` |
| | &nbsp; Commercial organisation employee | `1_private_sector` |
| | &nbsp; Freelance | `3_freelance` |
| | &nbsp; Not working (including housekeepers) |  `5_unemployed` |
| | &nbsp; Retiree | `5_retired` |
| | | |
| q3 | Education | **q3_education_code** |
| | &nbsp; Lower secondary | `1_secondary_school` |
| | &nbsp; Secondary | `1_secondary_school` |
| | &nbsp; Technical school | `2_vocational_school` |
| | &nbsp; Undergraduate | `3_graduate` |
| | &nbsp; Graduate | `3_graduate` |
| | &nbsp; PhD | `4_phd` |
| | | |
| q4 | How do you rate the current well-being of your family? | **q4_wealth_src** |
| | &nbsp; We have a stable and high income. |  |
| | &nbsp; I am generally satisfied with the income of my family |  |
| | &nbsp; I fear that the well-being of my family may deteriorate. |  |
| | &nbsp; I find my family’s income insufficient. |  |
| | | |
| q5 | Your political views: | **q5_politics_code** |
| | &nbsp; Left | `1_communist` |
| | &nbsp; Nationalist (ultra-right) | `2_nationalist` |
| | &nbsp; Liberal | `3_liberal` |
| | &nbsp; Radically liberal | `3_liberal` |
| | &nbsp; Supporter of the current state of affairs | `4_loyal` |
| | &nbsp; I do not have clear political preferences | `5_undecided` |
| | | |
| q6 | Do you consider yourself as a member of any political organisation? | **q6_party_code** |
| | &nbsp; Yes | `party` |
| | &nbsp; No | `non_party` |
| | | |
| q7 | How often do you take part in political activity? | **q7_protester_career_code** |
| | &nbsp; I have never participated in any until today. | `1_newcomer` |
| | &nbsp; For the first time I was on Bolotnaya on December 10 (or on some of the rallies of those days). | `2_bolotnaya_debutant` |
| | &nbsp; I have participated in political activity before the elections. | `3_veteran` |
| |  |  |
| q8| Have you participated in community initiatives: volunteering, blue buckets, Khimki forest, fire fighting, observing elections ... (underline as appropriate, open-ended question) | **q8_activities_code** |
| |  | boolean |
| |  |  |
| q9 | What demands put forward on the rallies do you support (up to three)? | **q9_claims_[1..6]**, **q9_claims_cnt_answers**,	**q9_claims_cnt_polar_answers**, **q9_claims_cnt_moderate_answers**  |
| | &nbsp; Ensuring fair elections from now on, but recognising the outcome of the past elections | `q9_claims_1` |
| | &nbsp; Re-election | `q9_claims_2` |
| | &nbsp; Changing the election law: expanding the number of parties | `q9_claims_3` |
| | &nbsp; The resignation of Putin and Medvedev | `q9_claims_4` |
| | &nbsp; A thorough investigation of violations, punishment of violators | `q9_claims_5` |
| | &nbsp; “Putin to jail!” (28 This slogan was not part of the demands, but we introduced it to fix the declared radicalism of the respondents) | `q9_claims_6` |
| | | |
| q10| Which of the following statements do you agree with: | **q10_thoughts_[1..7]**, **q10_thoughts_cnt_answers**, **q10_thoughts_cnt_angry_answers**, **q10_thoughts_cnt_neutral_answers** |
| | &nbsp; I support the stage orators. | `q10_thoughts_1` |
| | &nbsp; Representatives of my interests should gain access to power. | `q10_thoughts_2` |
| | &nbsp; I don’t think any political spectrum expresses my interests. | `q10_thoughts_3` |
| | &nbsp; I don’t want any changes in the political system, but I consider violation of the law in the elections unacceptable. | `q10_thoughts_4` |
| | &nbsp; I am angry with the authorities’ reaction to the previous rallies. | `q10_thoughts_5` |
| | &nbsp; I’m sure that the rallies can affect the situation in the country. | `q10_thoughts_6` 
| | &nbsp; I have no particular demands, I came to support my friends. | `q10_thoughts_7` |
| | | |
| q11 | What do you think about Navalny? | **q11_navalny_code** |
| | &nbsp; I consider him a bright politician and leader who has outstanding charisma | `1_worshiper` |
| | &nbsp; He is an interesting person and does the right thing | `2_generous` |
| | &nbsp; I am interested in his activities, but I do not find him competent | `3_indifferent` |
| | &nbsp; I find him a tiresome talker | `4_anti_worshiper` |
| | &nbsp; I am not interested in him and/or do not know who it is. | `3_indifferent` |
| |  |  |
| q12 | Your attitude to the demonstrative participation in the rallies of Ksenia Sobchak, Bozhena Rynski, Tina Kandelaki and others: | **q12_celebs_code** |
| | &nbsp; I appreciate the participation of famous people as they attract public attention. | `1_approval` |
| | &nbsp; I think they fulfil their civic duty and are no different from other protesters. | `2_recognizes` |
| | &nbsp; I’m displeased with the fact that they are promoting themselves at the cost of the rally. | `3_discomfort` |
| | &nbsp; It annoys me that these figures turn the rally into a farce. | `3_discomfort` |
| | &nbsp; I’m not interested in these people and/or do not know who they are. Were they present? | `4_indifferent` |
