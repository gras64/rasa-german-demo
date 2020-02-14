## feedback1
    - utter_ask_feedback
* out_of_scope
    - utter_thumbsup
    - utter_anything_else

## feedback2
    - utter_ask_feedback
* enter_data
    - utter_thumbsup
    - utter_anything_else

## feedback3
    - utter_ask_feedback
* affirm
    - utter_great
    - utter_anything_else

## feedback deny
    - utter_ask_feedback
* deny
    - utter_thumbsup
    - utter_anything_else

## feedback thank
    - utter_ask_feedback
* thank
    - utter_noworries
    - utter_anything_else

## feedback thumbsup
    - utter_ask_feedback
* feedback{"feedback_value": "negative"}
    - slot{"feedback_value": "negative"}
    - utter_thumbsup
    - utter_anything_else

## feedback thumbsup
    - utter_ask_feedback
* feedback{"feedback_value": "positive"}
    - slot{"feedback_value": "positive"}
    - utter_great
    - utter_anything_else

## New Story

* greet
    - utter_greet_noname

## New Story

* how_are_you
    - action_default_ask_affirmation
* how_are_you
    - action_revert_fallback_events
* how_are_you
    - action_default_fallback
* ask_howdoing
    - utter_ask_howdoing

## New Story

* are_you_there
    - utter_are_you_there

## New Story

* how_are_you{"language":"deutsch"}
    - slot{"language":"deutsch"}
    - utter_mycroft_german

## New Story

* mycroft_german{"language":"deutsch"}
    - slot{"language":"deutsch"}
    - utter_mycroft_german

## New Story

* are_you_there
    - utter_are_you_there

## New Story

* know-mycroft
    - utter_know_mycroft
