1. Bump version in `src/manifest.json`
2. npm run build:ff && cp ./build_firefox/notion_boost_firefox.zip ~/Desktop
3. Go to https://addons.mozilla.org/en-US/developers/addon/unlisted-twolfson-notion-boost/versions/submit/
4. Upload file, no minifiers
5. Wait 45s to 1 min
6. Receive email
7. Open link -> Open corresponding version
8. Click `.xpi` under "Files" at the top -> Firefox will prompt to install :tada:

-------

Need to self sign:
- Can do this locally via `web-ext sign` but that was taking a while
- Choosing to distribute via https://addons.mozilla.org/en-US/developers/addon/submit/upload-unlisted
  - as per https://blog.mozilla.org/addons/2017/01/26/mixing-listed-and-unlisted-on-amo/
  - It does take a minute for it to all go through (receive email when done) but it works =D
    - https://addons.mozilla.org/en-US/developers/addon/unlisted-twolfson-notion-boost/edit
    - Use link from version page (Files -> notion_boost...xpi) to install :tada:

![Notion Boost](./src/images/readme/header.jpg)

# Notion Boost browser extension

> Browser extension to add 20+ features to Notion.so like sticky outline (table of contents), small text & full width by default,scroll to top button, hide slash command menu, hide help button, bolder text and more.

## 🏠 [Homepage](https://gourav.io/notion-boost)

### ⬇ Downloads

- [Chrome extension](https://chrome.google.com/webstore/detail/notion-boost/eciepnnimnjaojlkcpdpcgbfkpcagahd)
- [Firefox addon](https://addons.mozilla.org/en-US/firefox/addon/notion-boost/)

### ⭐ Full List of Features 👉 https://gourav.io/notion-boost#-currently-added-features

Missing some feature? [suggest it](https://github.com/GorvGoyl/Notion-Boost-browser-extension/issues/new)

See what's new in latest update: https://gourav.io/notion-boost/whats-new

---

#### 👍 Liked this extension? express your love by rating [★★★★★](https://chrome.google.com/webstore/detail/notion-boost/eciepnnimnjaojlkcpdpcgbfkpcagahd) on Chrome/Firefox store.

#### ✨ Follow [@NotionBoost](https://twitter.com/intent/follow?user_id=1312809481240154112) on Twitter for many amazing Notion tips & tricks.

#### 👨‍💻 Follow the maker [@GorvGoyl](https://twitter.com/intent/follow?user_id=325435736) behind this extension.
