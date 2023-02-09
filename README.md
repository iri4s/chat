# easychat
A simple, easy way to make a chat room. All you need is scaledrone, and a fork of this repo. Do whatever with it, and if you find ways to optimize the code, make a pull request.

# How to set up
In order to set up your own easychat chatroom, you need to have a scaledrone account. 
# Step 1: Create a Channel
Go to https://dashboard.scaledrone.com/channels and create a channel. Name it whatever you like. Make sure to turn on message history.
# Step 2: Copy the Channel ID
Copy the channel ID of the channel you've made.
# Step 3: Change CLIENT_ID
Go into script.js and replace the string of zeros with the channel ID you copied.
# Step 4: Publish to Github Pages
Publish to github pages via actions, with the "deploy static content to pages" action.

# That's It! You're done.
Feel free to make any changes to the code as you see fit.
