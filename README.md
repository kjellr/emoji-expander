# Emoji Expander

You know how in Slack, you can type `:face_with_rolling_eyes:`, and it will give you 🙄? 

This is a Chrome extension that basically does the opposite of that on the webpages you visit. When the extension finds an emoji, it replaces the emoji with the text-based equivilent. 

For example: 

- ❤️ becomes `:heart:`
- 🙀 becomes `:scream_cat:`
- 🫠 becomes `:melting_face:`
- ✨ becomes `:sparkles:`
- 🕴️becomes `:man_in_business_suit_levitating:`

Et cetera, you get the picture. Or well... you don't. You get some text instead of the picture. That's the whole point.

## Installation

`:warning:` I haven't submitted this to the Chrome Web Store — it was just a fun weekend hack!

1. Download this repo.
2. Open `chrome://extensions/`
3. Activate "Developer mode" in the top right.
4. Click "Load unpacked"
5. Select the "Source" folder you downloaded.
6. Have fun! `:tada:`

## Screenshots

![Extension](https://user-images.githubusercontent.com/1202812/200149799-e324e98a-c471-45bf-acf5-998a00d99a18.png)

Before|After
---|---
![Google's suggested questions about emoji, with emoji](https://user-images.githubusercontent.com/1202812/200150493-d1f8a6be-9efa-4985-a99b-295cc2f84dca.png)|![Google's suggested questions about emoji, with no images](https://user-images.githubusercontent.com/1202812/200150494-abeb61be-f8b1-4cf6-a63a-20a5d371c85d.png)

Before|After
---|---
![Emoji summary with emoji](https://user-images.githubusercontent.com/1202812/200149328-cafb9d11-12b3-407a-a952-91da9b9bce6c.png)|![Emoji summary with no images](https://user-images.githubusercontent.com/1202812/200149333-e6785ddb-7e1d-4e0a-abcf-aa69cfeeb130.png)

## FAQ

_So wait, why did you make this?_

`:shrug:`

_Will this slow down my web experience?_

Yes, probably. Especially if you visit an emoji-heavy page like [this one](https://unicode.org/emoji/charts/full-emoji-list.html). 

_Does this really replace every single emoji?_

Probably not? It's likely I missed something. Feel free to open an issue if you notice something wrong.

_How do I uninstall it?_

Just select "Remove from Chrome..." like you would for any other extension. 

## Acknowledgements

- I forked this from [Eric Bailey](https://github.com/ericwbailey)'s classic [Millennials to Snake People](https://github.com/ericwbailey/millennials-to-snake-people) repo.
- The emoji list and short names were sourced from [Emoji Data](https://github.com/iamcal/emoji-data). 