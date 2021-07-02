# DistributedSystem-Project-PastaBot
Distributed System Project for Bachelor Course of Software Engineering at Politecnico di Bari.
The aim of this project is producing a multimodal Pasta recommendation system (Pasta MMCIS).

After an intense research process (which led to the production of a research article for a probable pubblication), a Telegram bot has been developed using Telegram Chatbot python library.

SCENARIO: A multimodal recommendation systems allows the user to communicate with a chatbot which uses both text and images. After the communication process, the chatbot has tot provide a pasta dish recommendation based on user preferences.


Two possibile interactions:
- Ingredients-oriented recommendation: provide a set of dishes by filtering the menu with respect of dishes ingredients
- Image-oriented recommendation: provide pasta dishes with a certain level of mutual similarity 


INGREDIENTS-ORIENTED RECOMMENDATION STEPS:
1) User emotion acquisition (ask for user actial mood: Happy 😁, Neutral 😐, Sad ☹️, Angry 😡)
2) User preferences acquisition (which ingredients the user likes, dislikes or is allergic to). This step is personalized according to the acquired mood
3) Recommendation based on preferences: identification and selection of pasta dishes of the menu which respect the provided conditions. Share with the user the name and image of the selected dish but also the ingredients and a friendly human-like recommendation.

IMAGE-ORIENTED RECOMMENDATION STEPS:
1) User emotion acquisition (ask for user actial mood: Happy 😁, Neutral 😐, Sad ☹️, Angry 😡)
2) Direct recommendation of a random dish of the menu. The user can accept it or ask for a similar dish or for a different one.
3) If the user ask for a new dish, a similarity algorithm identify the most similar or most different dish based on the dish images
4) Recommendation includes the name and image of the selected dish but also the ingredients and a friendly human-like recommendation.


How to run
- Create a bot directory and enter it
- Run command -> pipenv install python-telegram-bot
- Run command -> pipenv run python pastaBot.py (or botImaheSimilarity.py)
- Search for the bot into Telegram app and start the conversation
