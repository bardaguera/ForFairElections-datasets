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
| | Lower secondary | `secondary_school` |
| | Secondary | `secondary_school` |
| | Technical school | `vocational_school` |
| | Undergraduate | `graduate` |
| | Graduate | `graduate` |
| | PhD | `phd` |
| | | |
| q4 | How do you rate the current well-being of your family? | **q4_wealth_src** |
| | We have a stable and high income. |  |
| | I am generally satisfied with the income of my family |  |
| | I fear that the well-being of my family may deteriorate. |  |
| | I find my family’s income insufficient. |  |
| | | |
| q5 | Your political views: | **q5_politics_code** |
| | Left | `communist` |
| | Nationalist (ultra-right) | `nationalist` |
| | Liberal | `liberal` |
| | Radically liberal | `liberal` |
| | Supporter of the current state of affairs | `loyal` |
| | I do not have clear political preferences | `undecided` |
| | | |
| q6 | Do you consider yourself as a member of any political organisation? | **q6_party_code** |
| | Yes | `party` |
| | No | `non_party` |
| | | |
| q7 | How often do you take part in political activity? | **q7_protester_career_code** |
| | I have never participated in any until today. | `newcomer` |
| | For the first time I was on Bolotnaya on December 10 (or on some of the rallies of those days). | `bolotnaya_debutant` |
| | I have participated in political activity before the elections. | `veteran` |
| |  |  |
| q8| Have you participated in community initiatives: volunteering, blue buckets, Khimki forest, fire fighting, observing elections ... (underline as appropriate, open-ended question) | **q8_activities_code** |
| |  | boolean |
| |  |  |
| q9 | What demands put forward on the rallies do you support (up to three)? | **q9_claims_[1..6]**, **q9_claims_cnt_answers**,	**q9_claims_cnt_polar_answers**, **q9_claims_cnt_moderate_answers**  |
| | Ensuring fair elections from now on, but recognising the outcome of the past elections | `q9_claims_1` |
| | Re-election | `q9_claims_2` |
| | Changing the election law: expanding the number of parties | `q9_claims_3` |
| | The resignation of Putin and Medvedev | `q9_claims_4` |
| | A thorough investigation of violations, punishment of violators | `q9_claims_5` |
| | “Putin to jail!” (28 This slogan was not part of the demands, but we introduced it to fix the declared radicalism of the respondents) | `q9_claims_6` |
| | | |
| q10| Which of the following statements do you agree with: | **q10_thoughts_[1..7]**, **q10_thoughts_cnt_answers**, **q10_thoughts_cnt_angry_answers**, **q10_thoughts_cnt_neutral_answers** |
| | I support the stage orators. | `q10_thoughts_1` |
| | Representatives of my interests should gain access to power. | `q10_thoughts_2` |
| | I don’t think any political spectrum expresses my interests. | `q10_thoughts_3` |
| | I don’t want any changes in the political system, but I consider violation of the law in the elections unacceptable. | `q10_thoughts_4` |
| | I am angry with the authorities’ reaction to the previous rallies. | `q10_thoughts_5` |
| | I’m sure that the rallies can affect the situation in the country. | `q10_thoughts_6` 
| | I have no particular demands, I came to support my friends. | `q10_thoughts_7` |
| | | |
| q11 | What do you think about Navalny? | **q11_navalny_code** |
| | I consider him a bright politician and leader who has outstanding charisma | `worshiper` |
| | He is an interesting person and does the right thing | `generous` |
| | I am interested in his activities, but I do not find him competent | `not_interested` |
| | I find him a tiresome talker | `anti_worshiper` |
| | I am not interested in him and/or do not know who it is. | `not_interested` |
| |  |  |
| q12 | Your attitude to the demonstrative participation in the rallies of Ksenia Sobchak, Bozhena Rynski, Tina Kandelaki and others: | **q12_celebs_code** |
| | I appreciate the participation of famous people as they attract public attention. | `approval` |
| | I think they fulfil their civic duty and are no different from other protesters. | `recognizes` |
| | I’m displeased with the fact that they are promoting themselves at the cost of the rally. | `discomfort` |
| | It annoys me that these figures turn the rally into a farce. | `discomfort` |
| | I’m not interested in these people and/or do not know who they are. Were they present? | `not_interested` |
