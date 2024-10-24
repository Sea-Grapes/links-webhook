# Webhook Generator

A simple tool to easily generate a bookmarklet for fetching discord webhooks. Useful for saving urls to a discord channel (If you want to do this for some reason). I have no clue why I made this into a "SaaS" tool lmao, could have literally been a cmd line thing but noooo. Also people keep figuring out my webhook url (probably via bots generating links) so I need a quick way to update them.

![Screenshot of the webpage](/img/img1.png "Generator example")
<sub>Don't worry the webhook url is fake :)</sub>


## Features
- Input a webhook url
- customize bookmarklet name
- easy installation

## Dependencies
- Currently using tailwindcss play cdn (I'm too lazy to build the css lmao, also I aint using a whole framework for this tiny project)
- Using [nue-glow](https://www.npmjs.com/package/nue-glow) from NueJS for code highlighting. Go check them out, nue-glow is way faster and better than shiki/prism.