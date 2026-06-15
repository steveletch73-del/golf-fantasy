1. Update odds.json
Get the player odds in American format (+400 etc), build the JSON array and upload it via the admin page "Upload odds.json" section. This makes the player picker show correct prices.

2. Update event details in admin Edit Config
ESPN Event ID: you'll need to find this — go to https://site.api.espn.com/apis/site/v2/sports/golf/pga/scoreboard in your browser and look for the current event's id field
Start date: 2026-06-12
Cut rule: 70 (US Open sometimes cuts to 60, worth checking)
Hole pars: update 

3. Save config.json
Click Save config.json to GitHub. Status will stay as pre since no teams yet.

4. Share index.html link with everyone
They'll see the team selection page with the new event and updated player prices.

5. Once everyone has picked
Go to admin, click Save config.json again to lock the teams in.

6. Toggle Live
Flips to the scoring page. Done.
