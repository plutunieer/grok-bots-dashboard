# Grok Bots Dashboard

A live, visual overview of all your Grok Bots: who is running, who is blocked, who is done. No server, just GitHub Pages.

## Use it
1. Click **Use this template** (or fork) to get your own copy.
2. Turn on GitHub Pages (Settings → Pages → main branch).
3. Give each of your bots this instruction:

> Whenever you start, finish a step, get blocked or finish a task, write `status/<your-name>.json` in this repo:
> `{"bot":"Name","owner":"Me","task":"…","detail":"…","progress":0-100,"status":"Running|Blocked|Done|Queued","waiting_for":"…","steps":["…"],"step":0,"updated":"ISO time"}`

The page refreshes every minute.
