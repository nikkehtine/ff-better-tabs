# FF-Better-Tabs
Small userChrome.css file to make the tab close button work better in Firefox

This is a very minimal file with only a few rules, so it should be compatible with all Firefox versions that use Proton UI (>= 89.0) and is unlikely to get broken by updates.

## Tweaks

- The tab close button is hidden by default
- It shows up when you hover over a tab
- You can enable always showing the close button on active tabs

## Screenshots

![firefox_MvnNYSwFZL](https://github.com/nikkehtine/FF-Better-Tabs/assets/27138416/b662ca9f-2271-4e01-bd9a-cefb3ad1980c)

If you want to always have a close button visible on the active tab, you can uncomment the last rule:

![firefox_aI2YRzyPF7](https://github.com/nikkehtine/FF-Better-Tabs/assets/27138416/3a37cae9-89e5-4fd8-8675-75950f143eac)

## Installing

1. Download this repository
2. Go to `about:config`
3. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
4. Go to `about:support`
5. Open the **profile folder**
6. Copy the `chrome` folder from this repository to the profile folder you just opened
7. Close all open windows and open Firefox again
