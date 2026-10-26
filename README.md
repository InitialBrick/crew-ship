# Crew Ship
Static PWA. To log activity: add an object to the TOP of activity.json:
{"time":"2026-10-27T09:00:00+09:00","bot":"Venture","text":"Posted episode 2","room":"studio"}
bot = Pip|Venture|Relay|Pixel; room (optional) = bridge|studio|comms|design|common.
Add "type":"accomplishment" to show it on the Common Room bulletin board.
Profits: edit numbers in profits.json "sources" and set "updated" (YYYY-MM-DD). Real numbers only. "mission" sets the HUD goal bar (name + goal in USD).
Then: git commit -am "log" && git push  (Render auto-deploys in ~1 min).
