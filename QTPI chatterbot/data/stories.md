## general path               <!-- name of the story - just for debugging -->
* greet              
  - utter_greet
* about{"about_name":"college name"}               <!-- user utterance, in format intent[entities] -->
  - utter_name_college
* about{"about_dean":"dean"} 
  - utter_dean_name
* about{"about_chancellor":"chancellor"} 
  - utter_chancellor_name
  
## ask college name path
* greet
  - utter_greet
* about{"about_name":"college name"}
  - utter_name_college

## ask dean name path
* greet              
  - utter_greet
* about{"about_dean":"dean"} 
  - utter_dean_name

## ask chancellor name path
* greet              
  - utter_greet
* about{"about_chancellor":"chancellor"} 
  - utter_chancellor_name
  
## greet path
* greet
  - utter_greet

## ask location
* greet
  - utter_greet
* location
  - utter_location

## ask_courses
* greet
  - utter_greet
* courses
 - utter_courses
* courses{"cse":"cse"}
 - utter_cse

## ask_courses
* greet
  - utter_greet
* courses
 - utter_courses
* courses{"ece":"ece"}
 - utter_ece
 
 
## ask_courses
* greet
  - utter_greet
* courses
 - utter_courses
* courses{"mech":"mech"}
 - utter_mech

## ask_courses
* greet
  - utter_greet
* courses{"cse":"cse"}
 - utter_cse

## ask_courses
* greet
  - utter_greet
* courses{"ece":"ece"}
 - utter_ece

## ask_courses
* greet
  - utter_greet
* courses{"mech":"mech"}
 - utter_mech

## ask_placement
* greet
 - utter_greet
* placement
 - utter_placement

 
## fallback story
* out_of_scope
  - utter_unclear