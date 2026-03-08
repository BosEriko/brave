# Instructions
Setup a few things with Brave.

## Update your settings
- [x] Use wide address bar
- [x] Use vertical tabs
  - [x] Hide completely when minimized
- [x] Set as default browser
- [ ] Close window when closing last tab

## Startup Pages
Set your startup pages by going to `brave://settings/getStarted` → `On startup` → `Open a specific page or set of pages`:
- https://habitica.com/
- https://todoist.com/
- https://mail.proton.me/u/3/all-mail#filter=unread&sort=date

## Extensions
- [Proton Pass](https://chromewebstore.google.com/detail/proton-pass-free-password/ghmbeldphafepmbegfdlkpapadhbakde)
- [Vimium](https://chromewebstore.google.com/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)
- [Custom Style Script](https://chromewebstore.google.com/detail/custom-style-script/ecjfaoeopefafjpdgnfcjnhinpbldjij)

## Vimium
### Excluded URLs and keys
- `https?://jstris.jezevec10.com/*` — `All`
### Custom key mappings
```
map <C-;> createTab https://jstris.jezevec10.com/play/sprint/40
```

## Custom Style Script
### Jstris
URL: `https://jstris.jezevec10.com/`
```css
#lrem {
  color: white !important;
  margin-top: -380px !important;
  margin-left: -255px !important;
  z-index: 999999 !important;
  position: absolute !important;
  width: 241px !important;
  display: flex !important;
  justify-content: center !important;
  font-size: 100px;
  text-shadow:
    1px 1px 0 rgba(0,0,0,0.5),
    -1px 1px 0 rgba(0,0,0,0.5),
    1px -1px 0 rgba(0,0,0,0.5),
    -1px -1px 0 rgba(0,0,0,0.5),
    1px 0 0 rgba(0,0,0,0.5),
    -1px 0 0 rgba(0,0,0,0.5),
    0 1px 0 rgba(0,0,0,0.5),
    0 -1px 0 rgba(0,0,0,0.5);
}
#sprintText {
  display: none !important;
}
```
