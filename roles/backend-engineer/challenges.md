# getNEXT Backend Engineer Assignment

Hello and welcome, these are our assignments for the Backend Engineer role / Full-stack Engineer Role.

In order to proceed with the interview, we would like you to pick just **one** of the below options and follow the instructions.

The options are designed to be completed within a short time frame, to showcase your skills

The implementation should include at minimum these parts:

- Instructions to set up and run the application
- Explanation of all dependencies, why they are included and how they are used
- The code used should be of "production" level quality, so things like comments, readable code and abstractions should be used where appropriate

## Option 1 🏂 Slack Bot Game

## Scope

We want to build a fantastic Slack bot, that plays a simple game between a computer and a Slack user. The rules are simple:

- At the start of each game the computer will calculate a random whole number from `0` - `10`
- The user gets 3 guesses at what the number could be
- If the user guesses incorrectly the bot should respond if it's a `higher` or `lower` number than what was guessed
- After the 3 guesses are exhausted or if a correct number is correctly guessed, a winner should be declared (the user or the bot)

Additional requirements:

- Multiple users should be able to play with the bot simultaneously without it breaking (hint: identify sessions based on the user)
- If the application is restarted, the progress of the games should not be destroyed (hint: use a data store)
- We will be focusing on _your code_, your choice of infrastructure / servers / services / etc, will not be judged. We don't care if it has High Availability built in or not.

Example game:

- **User**: /botgame start
- **Bot**: Welcome to the Slack Bot Game, try and guess what number I am thinking of between 0 and 10
- **User**: 5
- **Bot**: The number I'm thinking of is `higher`
- **Bot**: 7
- **Bot**: Close guess! But the number is `higher`
- **User**: 9
- **Bot**: Congratulations! You guessed the number I was thinking of!

You can use any framework or library you like, just make sure to note why you've chosen it and what its purpose is. Any code that is not your own should be annotated from where it came from and for what purpose.

NOTE: You can sign up for a free Slack account and setup the API credentials here: https://api.slack.com. This includes all the documentation you may need to craft the perfect bot!
