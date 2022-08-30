# slackbot-tutorial

Code/tutorial updated to reflect Slack API v1 -> v2 changes. [Updated tutorial is available on Medium](https://medium.freecodecamp.org/how-to-build-a-basic-slackbot-a-beginners-guide-6b40507db5c5) as I cannot edit the content on freeCodeCamp's website.

Used in conjunction with this [tutorial](https://medium.freecodecamp.org/how-to-build-a-basic-slackbot-a-beginners-guide-6b40507db5c5)

Feel free to [tweet me @vishifishy](https://twitter.com/vishifishy) if you have any trouble, feedback, or wanna say thanks!

<!-- 
xoxb-3768540680197-3816174709574-BOQbt3yuOk6me2uOvXlUmTUz
ef07563c6f1e92fb26468bd0aeca0376

curl -X POST \
     -H 'Authorization: Bearer xoxb-3768540680197-3816174709574-BOQbt3yuOk6me2uOvXlUmTUz' \
     -H 'Content-type: application/json;charset=utf-8' \
    --data '{"channel":"#test","text":"Hello, Slack!"}' \
https://slack.com/api/chat.postMessage

export SLACK_BOT_TOKEN="xoxb-3768540680197-3816174709574-BOQbt3yuOk6me2uOvXlUmTUz" 
 

test
python3 scheduled.py 
-->