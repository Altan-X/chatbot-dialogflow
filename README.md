# chatbot-dialogflow
Building a chatbot using DialogFlow as part of KadaKareer's Virtual Apprenticeship 2022

## What is DialogFlow

## DialogFlow Terminologies

1. `Agent` - actual chatbot
2. `Utterance` - *triggers* the interaction to begin; from the user
3. `Intent` - why/what from the user

  + `Training Phrases` 
  + `Actions & Parameters`  
     - configure this to respond to user intent and give approriate response  
     - define variables to collect and store  
  + `Response`  
    - action

5. `Invocation` - what the user says
6. `Invocation name` - found within the  `invocation`
7. `Entities` - input variables from `Utterance`; critical information
8. `Context` - the method to store & access variables and to exchange information from intent to another
9. `Fulfillment` - found in the backend, for dynamic responses

## Process
1. User Utterance - what the user says that will *activate* the chatbot
2. Intent Matching 

  + information from User Utterance
  + process of mapping among series of training phrases to match the user `Intent` 

3. Response - static or dynamic action; the Intent acted on for the user

## Steps
1. Create `Agent`
2. Under Settings, switch on Beta access to API and save
3. Knowledge Tab > feed the document (under construction) 
