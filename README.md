slack-emojis
============

This repository stores images used for custom emojis on https://dornerworks.slack.com.

### How to download your emojis

Slack access token is required to download emojis by running `get_emojis.py`. You can get a token from [Slack Web API](https://api.slack.com/web?sudo=1).

![](https://www.evernote.com/l/AAV7WW98sZ9I15AlgDAtscMME5-UcJLvS_sB/image.png)

You can download emojis from your Slack using the token issued:

```bash
python3 get_emojis.py -o images/dornerworks dornerworks token-for-dornerworks
```
