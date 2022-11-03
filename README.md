
## Translates slack data structure for [Slackord2](https://github.com/thomasloupe/Slackord2).

#### Input zip structure:
	channelName1/*.json
	channelName2/*.json
	...
	users.json

#### Output zip structure:
	channelName1.json
	channelName2.json
	...

---

#### Features:
- Solves an issue where messages without an associated file are skipped by slackord2.
- Merges multiple .json files per channel into one .json file per channel.
- Filters out channel join messages (to avoid spamming).
- Changes instances of "<@USERID>" in message text to "@USERNAME".

---

#### Usage:
1. Download index.html file.
2. Open index.html in a browser.
3. Choose your input .zip file.
4. Click download link.
5. Unzip downloaded zip file.
6. Use slackord2 to import .json file(s).
