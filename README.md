# Agent Harbor — $HARBOR

Single-file website: `index.html`. No build step. Upload to GitHub Pages / Netlify / Vercel, or just open it.

## Setup
Open `index.html`, search for `var CONFIG` and fill in what you have:

```js
buyUrl:    '',  // pump.fun coin page
chartUrl:  '',  // chart link
xUrl:      'https://x.com/AgentHarborAI',
feeWallet: '',  // public wallet receiving creator fees → adds a "verify on Solscan" link
canDo:  [...],  // the agent's rules: only list things that are true
cantDo: [...]
```

Empty links go to @AgentHarborAI on X. The site never shows a contract address.
The animated harbor, dock log and vault numbers are a simulation and are labelled as such on the page.
