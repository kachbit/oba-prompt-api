# oba prompt api
Simple http request to retrieve the latest prompt for oba
## Retrieving:
The url below retrieves the latest oba prompt for spanish
```http
GET https://kachbit.github.io/oba-prompt-api/oba-v1p6-es.txt
```
## Bots
**luka** - beginner. speaks english and teaches the spanish basics<br>
**oba** - intermediate/adv. conversations in spanish<br>
**koko** - advanced. speaks only spanish and talks about any subject the user wants

## Prompt analysis:
analyzing the AI's responses. strengths and weaknesses provided by chatgpt.
| version | tokens | strengths | weaknesses | rating | tested ``temp``,``topP`` |
|---|---|---|---|---|---|
| oba-v1-es | ``422`` |  simple and concise | slow minded (dumb)  | alright | n\a |
|  oba-v1.5-es | ``218``  | uses repetition to reinforce learning and improve retention, provides immediate feedback and corrections  | responses might feel slightly repetitive or rigid, lacking flexibility in adjusting to the user's pace or style of learning, could offer more varied prompts or exercises to engage the user  |  alright | n/a |
|  oba-v1.6-es (cicero update) | ``293``  | very good at coming up with unique debatable topics. this update I transitioned from a teaching based assistant to a conversation based assistant.  | not good at correcting the user's mistakes. | yeah it's alright | ``1.91``,``0.97`` |
|   |   |   |   |   |   |
