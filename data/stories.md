## survey yes
* greet
  - utter_mood
  - utter_survey
* affirm
  - utter_gender
* gender
  - utter_employment
* self_employment
  - utter_history_mental_illness
* history_mental_illness
  - utter_work_interference
* work_interference
  - utter_company_no_employees
* company_no_employees
  - utter_tech_company
* tech_company
  - utter_health_benefits
* health_benefits
  - utter_health_resources
* health_resources
  - utter_treatment_anonymity
* treatment_anonymity
  - utter_medical_leave
* medical_leave
  - utter_discussing_mental_health
* discussing_mental_health
  - utter_willing_to_discuss_collegaue
* willing_to_discuss_collegaue
  - utter_willing_to_discuss_employer
* willing_to_discuss_employer
  - utter_serious_mental_health
* serious_mental_health
  - utter_negative_consequences_mental_coworker
* negative_consequences_mental_coworker
  - utter_welcome

## survey no
* greet
  - utter_mood
* mood_great
  - utter_survey
  - utter_mood_great
* deny
  - utter_iamabot
  - utter_goodbye

## sad path 1
* greet
  - utter_mood
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy
  - utter_welcome

## sad path 2
* greet
  - utter_mood
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_cheer_up_two
  - utter_did_that_help
* affirm
  - utter_welcome
  - utter_goodbye
  
## say goodbye
* goodbye
  - utter_goodbye