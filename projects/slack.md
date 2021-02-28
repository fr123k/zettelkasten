# Slack

https://slack.com/

# Projects

## Confluence Search Bot

Prototype [confluence-slackbot](https://github.com/fr123k/confluence-slackbot)

Analyse slack message and use the nouns to perform confluence searches and post the 
results back to the triggered slack message.

## Send Later Bot 

Its inspired by the following slack app [later](https://senditlater.app/)

*Major Disadvantages*
* the messages are stored on a 3rdparty storage
* its a stateful app

### Idea

* using the slack reminder feature to setup reminders send to an bot or an dedicated channel
* the bot just pick up the reminder from slack and send it as normal message to the target

*Advantages*
* the message are not stored outside of slack itself
* stateless application


## Timekeeper Game

[timekeeper](https://github.com/papsicle/timekeeper)

Service that use slack for keeping a highscore about being later or on time in meetings.
