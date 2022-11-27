# roblox-group-scraper
Tool for finding ownerless Roblox groups.

---

# Config
- `threadCount`: amount of threads to be used for scanning
- `displayErrors`: show errors related to scanning
- `isLooped`: scanning will restart from min once it reaches max range
- `webhookUrl`: found groups will be sent to the specified webhook url via an embed
- `minMemberCount`: groups with member counts below this amount won't be shown
- `range`: group ids will count from `min`, up until `max`

---

# Output
Matched groups will be logged into the file `found.csv` with the following fields:
- Id
- Member count
- Url
- Name

---

# Usage
- Set up config.json and example.env to your preferences
- Rename example.env to .env
- Add your HTTP/HTTPS proxies to proxies.txt
- Press Run

---

Credit: https://github.com/h0nde/roblox-group-scraper

---