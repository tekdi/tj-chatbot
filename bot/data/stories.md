## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
* subscription
  - utter_subscription
* subscription_expire
  - utter_subscription_expire
* more_than_one_site
  - utter_more_than_one_site
* support_time
  - utter_support_time
* not_supporting_yet
  - utter_not_supporting_yet
* doing_timepass
  - utter_doing_timepass

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
