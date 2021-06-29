# DistributedSystem-Project-PastaBot
Distributed System Project for Bachelor Course of Software Engineering at Politecnico di Bari.
The aim of this project is producing a multimodal Pasta recommendation system.

After an intense research process (which led to the production of a research article for a pubblication), a Telegram bot has been developed using Telegram Chatbot python library.

SCENARIO & STEPS:
Multimodal recommendation systems: the user communicates with a chatbot which uses both text and images. 


Two possibile interactions:
- Recommendation ingredients-oriented: provide a set of dishes by filtering a menu with respect of dishes ingredients
- Recommendation image-oriented: provide pasta dishes with a certain level of similarity 

INGREDIENTS-ORIENTED RECOMMENDATION STEPS:
1) User emotion acquisition (ask for user actial mood: Happy 😁, Neutral 😐, Sad ☹️, Angry 😡)
2) User preferences acquisition (which ingredients the user likes, dislikes or is allergic to). This step is personalized according to the mood
3) Recommendation based on preferences: identification and selection of pasta dishes of a menu which respect the provided conditions

