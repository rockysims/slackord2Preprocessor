
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

---

#### Usage:
- Download index.html file.
- Open index.html in a browser.
- Choose your input .zip file.
- Click download link.
- Unzip downloaded zip file.
- Use slackord2 to import .json file(s).
