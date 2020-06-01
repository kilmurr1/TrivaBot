# Welcome to TrivaBot 1.0

This is a bot I programmed as a fun project and a way for me to learn about Discord.py. It's main function is a trivia game that keeps a scoreboard of users who answer questions correctly. Currently there are around 1600 questions in the bot.

## How do I get this bot?
Just click this [link](https://discord.com/api/oauth2/authorize?client_id=708795230404739145&permissions=8&scope=bot) and follow the steps on the official discord page.

## Commands/Instructions
All commands must be proceeded by a '$' symbol in order for the bot to recognize it. Here is a list of the current commands.

**$quizme**: This is sends a random question and awaits the requesters response, if you get the question correct you will get 10 points on the scoreboard. 

**$score**: This will display the current scoreboard

**$addpoints**: This will automatically give the user 10 points. Sometimes the formatting of questions can be weird, so this should be used for when a user does actually get a question correct.

**$randomMember**: This will pick a random member from the server

**$randomMemberRole "role"**: this will pick a random member who has the specified role, i.e "$randomMemberRole "cool dude" " will pick a random user who has the "cool dude" role.

**$spam 999 "message"**: Admin only command that allows a message to be "spammed" up to 999 times. Messages must be formatted as '$spam 000 "message"' The number must be in a 3 digit format

**$whoami**: This command will tell you if you have admin rights on your current server

**$test**: This will reply with a message that says "test" if the bot is running correctly

### Other information
This bot collects usernames/id in order for the score system to work. No other personal data is collected or saved.

Thanks,

Mikey
