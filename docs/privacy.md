# PostDeck Privacy Policy

Effective date: November 21, 2026

PostDeck is a Windows app that makes, schedules and posts short videos. Cribian makes PostDeck. This policy tells you which data PostDeck uses, where the data goes, and how you delete it.

## Summary

- PostDeck has no server and no user accounts. Cribian does not get your videos, posts, keys or account logins.
- PostDeck collects no analytics and no usage data.
- PostDeck sends data only to the services that you set up, and only for a task that you start or schedule.
- Cribian gets data from you only when you send a problem report.

## Data on your computer

| Data | Where PostDeck keeps it |
|---|---|
| Posts, drafts, the schedule, the video library and the settings | The PostDeck app storage in `%APPDATA%\PostDeck` |
| The API keys on the Studio page (Gemini, Claude, OpenAI or your own server) | The PostDeck app storage in `%APPDATA%\PostDeck` |
| Account logins for YouTube, TikTok, Facebook, Instagram and Bluesky | `%APPDATA%\PostDeck\poster-vault.bin`, encrypted with your Windows login |
| Studio, its packages, the clip jobs and the finished clips | `%LOCALAPPDATA%\PostDeck\Studio` |
| OBS recordings | The folder that OBS records to. Studio reads the files there and does not copy them. |

## Data that leaves your computer

| Service | What PostDeck sends | When |
|---|---|---|
| YouTube (Google) | The video, the title, the description and the tags, with your login. PostDeck also reads the statistics of your videos. | When a post goes out, when you upload a VOD, and on the Analytics page |
| TikTok | The video and the post text, with your login. PostDeck also reads the statistics of your videos. | When a post goes out, and on the Analytics page |
| Facebook and Instagram (Meta) | The video and the post text, with your login. PostDeck also reads the statistics of your posts. | When a post goes out, and on the Analytics page |
| Bluesky | The video and the post text, with your handle and app password | When a post goes out, and on the Analytics page |
| A posting service, for example Upload-Post | The video and the post text, with your key for that service | Only when you set a posting service in **Settings** → **Posting service** |
| Twitch and Kick | Your channel name | While the live clipper reads your public chat |
| The AI model from the Studio page: Google Gemini, Anthropic Claude, OpenAI, or your own server | The transcript of the video, the word times and the stream title. Gemini also gets still frames, short copies of clips and, for a video without speech, the video file. | When Studio makes or edits clips |
| GitHub | A request for the newest PostDeck version | When PostDeck starts, and every 10 minutes |
| GitHub, the Python Package Index, PyTorch, Hugging Face and Meta | Requests to download the programs and the AI model files | During **Set up Studio**, and the first time Studio uses an AI model file |
| Web3Forms | The text of your report, the app details if you keep them, and your email if you type it | Only when you click **Send report** |

Each service gets your IP address with each request. Each service uses the data under its own privacy policy.

With a free Gemini key, Google can use the data to improve its products, and people at Google can read it. See https://ai.google.dev/gemini-api/terms.

The setup guide in PostDeck lists each Studio step and the data that it sends to the AI model. See **Setup guide** → **Advanced**.

## YouTube and Google

- PostDeck uses the YouTube API Services. When you connect YouTube, you agree to the YouTube Terms of Service: https://www.youtube.com/t/terms
- Google uses data under the Google Privacy Policy: https://policies.google.com/privacy
- PostDeck uses the data from Google APIs in compliance with the Google API Services User Data Policy, including the Limited Use requirements: https://developers.google.com/terms/api-services-user-data-policy
- PostDeck keeps your Google login only on your computer. It does not share your Google data with Cribian or with other services.
- To remove the access of PostDeck to your Google account, open https://myaccount.google.com/permissions.

## Delete your data

1. To delete the posts, the library and the settings, open **Settings** → **Your data** and click **Delete workspace**.
2. To remove an account login, click **Disconnect** on its card in **Accounts**.
3. To remove Studio, delete the folder `%LOCALAPPDATA%\PostDeck\Studio`.
4. To remove all data, uninstall PostDeck. Then delete `%APPDATA%\PostDeck` and `%LOCALAPPDATA%\PostDeck`.
5. To remove the access of PostDeck at a network, use the app permissions in the security settings of that network.

Cribian keeps problem reports in an email inbox. To delete a report that you sent, send a report that asks for it.

## Children

PostDeck is not for children under 13.

## Changes to this policy

When this policy changes, the effective date changes. The What's new window in PostDeck tells you about the change.

## Contact

In PostDeck, open **Report a problem**.
