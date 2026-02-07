# AI Bounty Hunter Readiness Quiz

An interactive quiz that helps new users understand if AI bounty hunting on the [AI Bounty Board](https://bounty.owockibot.xyz) is right for them.

## Features

- **10 targeted questions** covering skills, tools, payment setup, and bounty process knowledge
- **Personalized scoring** with results from 0-10
- **Tailored recommendations** based on your score tier
- **Responsive design** that works on desktop and mobile
- **Single HTML file** - no build tools or dependencies required

## Topics Covered

| Topic | Questions |
|-------|-----------|
| Wallet Setup | Crypto wallet readiness, Base network familiarity |
| Payments | USDC on Base, earning expectations |
| Bounty Lifecycle | Submission process, autograde system |
| Required Tools | Git/GitHub, code editors, CLI tools |
| Submission Tips | Strategy, documentation, requirements coverage |
| Time Commitment | Availability and realistic planning |

## Score Tiers

| Score | Level | Description |
|-------|-------|-------------|
| 8-10 | Ready to Hunt | Jump in and start earning |
| 5.5-7.9 | Almost There | A few areas to brush up on |
| 3-5.4 | Getting Started | Follow the learning path |
| 0-2.9 | Start From Basics | Build foundational knowledge first |

## Deploy to GitHub Pages

1. Fork or clone this repository
2. Go to **Settings** > **Pages** in your GitHub repo
3. Under **Source**, select **Deploy from a branch**
4. Choose `main` branch and `/ (root)` folder
5. Click **Save**
6. Your quiz will be live at `https://<username>.github.io/bounty-onboarding-quiz/`

## Local Development

Simply open `index.html` in your browser:

```bash
open index.html
# or
python3 -m http.server 8000
```

## Project Structure

```
bounty-onboarding-quiz/
  index.html    # Complete quiz (HTML + CSS + JS)
  README.md     # This file
```

## License

MIT
