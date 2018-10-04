"# slack_skype_msteams_bot" 

"Instructions to run Slack bot" :

1. Run command 'npm install' on terminal of the application directory to install dependencies.
2. In 'package.json' file , change the scripts to '"start": "node index.js"'.
3. Create workspace on slack.
4. Visit website 'https://api.slack.com/apps' and click 'Create New App' button.
5. Fill App Name and slack workspace fields and Create App.
6. Select 'Bots' on the page and Add a Bot user and fill in Display name and Default username field.
7. From left panel select 'OAuth & Permissions' and install bot to workspace and Authorize it.
8. Copy 'Bot User OAuth Access Token' from the same tab and paste it in 'index.js' file ,search for 'token' and paste it inside quotes. Also fill the 'name' of the bot inside quotes. Run the application with command 'npm start' in application terminal.
9. Check 'general' channel of slack with welcome messages from bot. Type @botname chucknorris to recieve jokes from bot. Also try @botname with 'yomama', 'random' and 'help'. 

Instructions to run Skype and Ms Teams bot:

1. Run command 'npm install' on terminal of the application directory to install dependencies.
2. In 'package.json' file , change the scripts to '"start": "node app.js"'.
3. Install ngrok and run command 'ngrok http 3000' on cmd. Copy the https link.
3. Visit 'https://dev.botframework.com/bots/new' and filll in bot details and paste ngrok link in the field 'Messaging endpoint'. Also add '/api/messages' at the end of the ngrok link.
4. Now click 'Create Microsoft App ID and password'.Copy App ID and password and search for 'appId' and 'appPassword' in 'app.js' file and paste ID and password repectively. Then click 'Finish and go back to Bot Framework' button. Run the application with command 'npm start' in application terminal.
5. Fill in the details, tick the checkbox and Register the Bot.
6. Now add featured channels like skype and MS Teams from the .
7. If selected Skype, go to publish tab and fill in details and save it.
8. Skype is added to 'Connect to channels' list, click on Skype and add Bot to contacts. Bot will be added to your skype account and you can start the chat.
9. If selected MS Teams, it gets configured after ticking the checkbox for terms and conditions.
10.MS Teams is added to 'Connect to channels' list, click on MS Teams and add Bot is added to contacts.
