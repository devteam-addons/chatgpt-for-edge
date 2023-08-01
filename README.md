# ChatGPT for Edge

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/wong2/chatgpt-google-extension/pre-release-build.yml)
[![Twitter Follow](https://img.shields.io/twitter/follow/chatgpt4google?style=social)](https://twitter.com/chatgpt4google)
![License](https://img.shields.io/github/license/wong2/chatgpt-google-extension)

A browser extension to display ChatGPT response alongside Google (and other search engines) results

[Install from Edge Add-on Store]([#](https://microsoftedge.microsoft.com/addons/detail/chatgpt-for-edge-all-po/fkjiikdgpjeaocggailpihiklianahgp))

[Install from Mozilla Add-on Store](#)

## Supported Search Engines

Google, Baidu, Bing, DuckDuckGo, Brave, Yahoo, Naver, Yandex, Kagi, Searx

## Screenshot

![Screenshot](screenshots/extension.png?raw=true)

## Features

- Supports all popular search engines
- Supports the official OpenAI API
- Supports ChatGPT Plus
- Markdown rendering
- Code highlights
- Dark mode
- Provide feedback to improve ChatGPT
- Copy to clipboard
- Custom trigger mode
- Switch languages

## Troubleshooting

### How to make it work in Brave

![Screenshot](screenshots/brave.png?raw=true)

Disable "Prevent sites from fingerprinting me based on my language preferences" in `brave://settings/shields`

### How to make it work in Opera

![Screenshot](screenshots/opera.png?raw=true)

Enable "Allow access to search page results" in the extension management page

## Build from source

1. Clone the repo
2. Install dependencies with `npm`
3. `npm run build`
4. Load `build/chromium/` or `build/firefox/` directory to your browser

