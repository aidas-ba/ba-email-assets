# Baltic Assist email assets

Public images used in Baltic Assist IT emails. Templates live in `EMAIL_DESIGN_MAIN\EMAIL_TEMPLATES`.

**Don't rename, move or delete files here.** Emails that were already sent link to them and would show broken images.
To change an image, add it under a new name (or bump `ASSET_VERSION` in the template build) and update the templates.

## Using an image in a template

Link directly to the raw file, with the version marker:

```
https://raw.githubusercontent.com/aidas-ba/ba-email-assets/main/tiles/<icon>-<tone>.png?v=4
```

In a template, use the `__TILES__/` placeholder and the build fills in the address:

```html
<img src="__TILES__/laptop-lavender.png" width="48" height="48" alt="" style="display:block; width:48px; height:48px; border:0;">
```

Tiles are 240×240 transparent PNGs. Show them at **48×48** in cards (as in the Monitor / Due card), or 36–72 elsewhere.

**Tones:**
- **lavender:** default, the main subject of a card
- **slate:** a second item next to lavender, or a more serious topic
- **lilac:** a third item, or a softer accent
- **pink:** attention only (due dates, warnings, things to fix), matching the red/pink "attention" rule in the templates

## Logos

| File | Used for |
|---|---|
| `logo/ba-logo-navy.png` | **Current email logo**: brand navy for both words, red tick (shown at 140px) |
| `logo/ba-logo-dark.png` | Dark-mode logo, all white (Apple Mail / iPhone dark mode) |
| `logo/ba-logo-blue.png` | Earlier email logo (lighter blue); kept for emails already sent |
| `logo/ba-logo-halo.png` | Earlier email logo with white halo; kept for emails already sent |

## Tiles in use by the live templates

| File | Used for |
|---|---|
| `tiles/art-pastel-monitor.png` | Monitor card icon (same design as `monitor-lavender`) |
| `tiles/art-pastel-calendar.png` | Due-date card icon (same design as `calendar-pink`) |

## Tile library

41 icons × 4 tones. File name: `tiles/<icon>-<tone>.png`.
Regenerate or add icons with `art\render-tiles.ps1` (icons are defined in `art\art.html`); add new ones under new names.

### Devices

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `monitor` | <img src="tiles/monitor-lavender.png" width="56" alt="monitor lavender"> | <img src="tiles/monitor-slate.png" width="56" alt="monitor slate"> | <img src="tiles/monitor-pink.png" width="56" alt="monitor pink"> | <img src="tiles/monitor-lilac.png" width="56" alt="monitor lilac"> |
| `laptop` | <img src="tiles/laptop-lavender.png" width="56" alt="laptop lavender"> | <img src="tiles/laptop-slate.png" width="56" alt="laptop slate"> | <img src="tiles/laptop-pink.png" width="56" alt="laptop pink"> | <img src="tiles/laptop-lilac.png" width="56" alt="laptop lilac"> |
| `phone` | <img src="tiles/phone-lavender.png" width="56" alt="phone lavender"> | <img src="tiles/phone-slate.png" width="56" alt="phone slate"> | <img src="tiles/phone-pink.png" width="56" alt="phone pink"> | <img src="tiles/phone-lilac.png" width="56" alt="phone lilac"> |
| `printer` | <img src="tiles/printer-lavender.png" width="56" alt="printer lavender"> | <img src="tiles/printer-slate.png" width="56" alt="printer slate"> | <img src="tiles/printer-pink.png" width="56" alt="printer pink"> | <img src="tiles/printer-lilac.png" width="56" alt="printer lilac"> |
| `server` | <img src="tiles/server-lavender.png" width="56" alt="server lavender"> | <img src="tiles/server-slate.png" width="56" alt="server slate"> | <img src="tiles/server-pink.png" width="56" alt="server pink"> | <img src="tiles/server-lilac.png" width="56" alt="server lilac"> |
| `headset` | <img src="tiles/headset-lavender.png" width="56" alt="headset lavender"> | <img src="tiles/headset-slate.png" width="56" alt="headset slate"> | <img src="tiles/headset-pink.png" width="56" alt="headset pink"> | <img src="tiles/headset-lilac.png" width="56" alt="headset lilac"> |
| `wifi` | <img src="tiles/wifi-lavender.png" width="56" alt="wifi lavender"> | <img src="tiles/wifi-slate.png" width="56" alt="wifi slate"> | <img src="tiles/wifi-pink.png" width="56" alt="wifi pink"> | <img src="tiles/wifi-lilac.png" width="56" alt="wifi lilac"> |
| `camera` | <img src="tiles/camera-lavender.png" width="56" alt="camera lavender"> | <img src="tiles/camera-slate.png" width="56" alt="camera slate"> | <img src="tiles/camera-pink.png" width="56" alt="camera pink"> | <img src="tiles/camera-lilac.png" width="56" alt="camera lilac"> |

### Access & security

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `key` | <img src="tiles/key-lavender.png" width="56" alt="key lavender"> | <img src="tiles/key-slate.png" width="56" alt="key slate"> | <img src="tiles/key-pink.png" width="56" alt="key pink"> | <img src="tiles/key-lilac.png" width="56" alt="key lilac"> |
| `lock` | <img src="tiles/lock-lavender.png" width="56" alt="lock lavender"> | <img src="tiles/lock-slate.png" width="56" alt="lock slate"> | <img src="tiles/lock-pink.png" width="56" alt="lock pink"> | <img src="tiles/lock-lilac.png" width="56" alt="lock lilac"> |
| `shield` | <img src="tiles/shield-lavender.png" width="56" alt="shield lavender"> | <img src="tiles/shield-slate.png" width="56" alt="shield slate"> | <img src="tiles/shield-pink.png" width="56" alt="shield pink"> | <img src="tiles/shield-lilac.png" width="56" alt="shield lilac"> |
| `user` | <img src="tiles/user-lavender.png" width="56" alt="user lavender"> | <img src="tiles/user-slate.png" width="56" alt="user slate"> | <img src="tiles/user-pink.png" width="56" alt="user pink"> | <img src="tiles/user-lilac.png" width="56" alt="user lilac"> |
| `people` | <img src="tiles/people-lavender.png" width="56" alt="people lavender"> | <img src="tiles/people-slate.png" width="56" alt="people slate"> | <img src="tiles/people-pink.png" width="56" alt="people pink"> | <img src="tiles/people-lilac.png" width="56" alt="people lilac"> |

### Communication

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `mail` | <img src="tiles/mail-lavender.png" width="56" alt="mail lavender"> | <img src="tiles/mail-slate.png" width="56" alt="mail slate"> | <img src="tiles/mail-pink.png" width="56" alt="mail pink"> | <img src="tiles/mail-lilac.png" width="56" alt="mail lilac"> |
| `send` | <img src="tiles/send-lavender.png" width="56" alt="send lavender"> | <img src="tiles/send-slate.png" width="56" alt="send slate"> | <img src="tiles/send-pink.png" width="56" alt="send pink"> | <img src="tiles/send-lilac.png" width="56" alt="send lilac"> |
| `bell` | <img src="tiles/bell-lavender.png" width="56" alt="bell lavender"> | <img src="tiles/bell-slate.png" width="56" alt="bell slate"> | <img src="tiles/bell-pink.png" width="56" alt="bell pink"> | <img src="tiles/bell-lilac.png" width="56" alt="bell lilac"> |
| `link` | <img src="tiles/link-lavender.png" width="56" alt="link lavender"> | <img src="tiles/link-slate.png" width="56" alt="link slate"> | <img src="tiles/link-pink.png" width="56" alt="link pink"> | <img src="tiles/link-lilac.png" width="56" alt="link lilac"> |

### Files & forms

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `document` | <img src="tiles/document-lavender.png" width="56" alt="document lavender"> | <img src="tiles/document-slate.png" width="56" alt="document slate"> | <img src="tiles/document-pink.png" width="56" alt="document pink"> | <img src="tiles/document-lilac.png" width="56" alt="document lilac"> |
| `clipboard` | <img src="tiles/clipboard-lavender.png" width="56" alt="clipboard lavender"> | <img src="tiles/clipboard-slate.png" width="56" alt="clipboard slate"> | <img src="tiles/clipboard-pink.png" width="56" alt="clipboard pink"> | <img src="tiles/clipboard-lilac.png" width="56" alt="clipboard lilac"> |
| `download` | <img src="tiles/download-lavender.png" width="56" alt="download lavender"> | <img src="tiles/download-slate.png" width="56" alt="download slate"> | <img src="tiles/download-pink.png" width="56" alt="download pink"> | <img src="tiles/download-lilac.png" width="56" alt="download lilac"> |
| `upload` | <img src="tiles/upload-lavender.png" width="56" alt="upload lavender"> | <img src="tiles/upload-slate.png" width="56" alt="upload slate"> | <img src="tiles/upload-pink.png" width="56" alt="upload pink"> | <img src="tiles/upload-lilac.png" width="56" alt="upload lilac"> |
| `trash` | <img src="tiles/trash-lavender.png" width="56" alt="trash lavender"> | <img src="tiles/trash-slate.png" width="56" alt="trash slate"> | <img src="tiles/trash-pink.png" width="56" alt="trash pink"> | <img src="tiles/trash-lilac.png" width="56" alt="trash lilac"> |

### Status

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `tick` | <img src="tiles/tick-lavender.png" width="56" alt="tick lavender"> | <img src="tiles/tick-slate.png" width="56" alt="tick slate"> | <img src="tiles/tick-pink.png" width="56" alt="tick pink"> | <img src="tiles/tick-lilac.png" width="56" alt="tick lilac"> |
| `alert` | <img src="tiles/alert-lavender.png" width="56" alt="alert lavender"> | <img src="tiles/alert-slate.png" width="56" alt="alert slate"> | <img src="tiles/alert-pink.png" width="56" alt="alert pink"> | <img src="tiles/alert-lilac.png" width="56" alt="alert lilac"> |
| `info` | <img src="tiles/info-lavender.png" width="56" alt="info lavender"> | <img src="tiles/info-slate.png" width="56" alt="info slate"> | <img src="tiles/info-pink.png" width="56" alt="info pink"> | <img src="tiles/info-lilac.png" width="56" alt="info lilac"> |
| `question` | <img src="tiles/question-lavender.png" width="56" alt="question lavender"> | <img src="tiles/question-slate.png" width="56" alt="question slate"> | <img src="tiles/question-pink.png" width="56" alt="question pink"> | <img src="tiles/question-lilac.png" width="56" alt="question lilac"> |
| `cross` | <img src="tiles/cross-lavender.png" width="56" alt="cross lavender"> | <img src="tiles/cross-slate.png" width="56" alt="cross slate"> | <img src="tiles/cross-pink.png" width="56" alt="cross pink"> | <img src="tiles/cross-lilac.png" width="56" alt="cross lilac"> |
| `plus` | <img src="tiles/plus-lavender.png" width="56" alt="plus lavender"> | <img src="tiles/plus-slate.png" width="56" alt="plus slate"> | <img src="tiles/plus-pink.png" width="56" alt="plus pink"> | <img src="tiles/plus-lilac.png" width="56" alt="plus lilac"> |
| `clock` | <img src="tiles/clock-lavender.png" width="56" alt="clock lavender"> | <img src="tiles/clock-slate.png" width="56" alt="clock slate"> | <img src="tiles/clock-pink.png" width="56" alt="clock pink"> | <img src="tiles/clock-lilac.png" width="56" alt="clock lilac"> |
| `calendar` | <img src="tiles/calendar-lavender.png" width="56" alt="calendar lavender"> | <img src="tiles/calendar-slate.png" width="56" alt="calendar slate"> | <img src="tiles/calendar-pink.png" width="56" alt="calendar pink"> | <img src="tiles/calendar-lilac.png" width="56" alt="calendar lilac"> |
| `hourglass` | <img src="tiles/hourglass-lavender.png" width="56" alt="hourglass lavender"> | <img src="tiles/hourglass-slate.png" width="56" alt="hourglass slate"> | <img src="tiles/hourglass-pink.png" width="56" alt="hourglass pink"> | <img src="tiles/hourglass-lilac.png" width="56" alt="hourglass lilac"> |
| `refresh` | <img src="tiles/refresh-lavender.png" width="56" alt="refresh lavender"> | <img src="tiles/refresh-slate.png" width="56" alt="refresh slate"> | <img src="tiles/refresh-pink.png" width="56" alt="refresh pink"> | <img src="tiles/refresh-lilac.png" width="56" alt="refresh lilac"> |

### Places & things

| Icon | lavender | slate | pink | lilac |
|---|:---:|:---:|:---:|:---:|
| `pin` | <img src="tiles/pin-lavender.png" width="56" alt="pin lavender"> | <img src="tiles/pin-slate.png" width="56" alt="pin slate"> | <img src="tiles/pin-pink.png" width="56" alt="pin pink"> | <img src="tiles/pin-lilac.png" width="56" alt="pin lilac"> |
| `globe` | <img src="tiles/globe-lavender.png" width="56" alt="globe lavender"> | <img src="tiles/globe-slate.png" width="56" alt="globe slate"> | <img src="tiles/globe-pink.png" width="56" alt="globe pink"> | <img src="tiles/globe-lilac.png" width="56" alt="globe lilac"> |
| `cloud` | <img src="tiles/cloud-lavender.png" width="56" alt="cloud lavender"> | <img src="tiles/cloud-slate.png" width="56" alt="cloud slate"> | <img src="tiles/cloud-pink.png" width="56" alt="cloud pink"> | <img src="tiles/cloud-lilac.png" width="56" alt="cloud lilac"> |
| `box` | <img src="tiles/box-lavender.png" width="56" alt="box lavender"> | <img src="tiles/box-slate.png" width="56" alt="box slate"> | <img src="tiles/box-pink.png" width="56" alt="box pink"> | <img src="tiles/box-lilac.png" width="56" alt="box lilac"> |
| `settings` | <img src="tiles/settings-lavender.png" width="56" alt="settings lavender"> | <img src="tiles/settings-slate.png" width="56" alt="settings slate"> | <img src="tiles/settings-pink.png" width="56" alt="settings pink"> | <img src="tiles/settings-lilac.png" width="56" alt="settings lilac"> |
| `star` | <img src="tiles/star-lavender.png" width="56" alt="star lavender"> | <img src="tiles/star-slate.png" width="56" alt="star slate"> | <img src="tiles/star-pink.png" width="56" alt="star pink"> | <img src="tiles/star-lilac.png" width="56" alt="star lilac"> |
| `training` | <img src="tiles/training-lavender.png" width="56" alt="training lavender"> | <img src="tiles/training-slate.png" width="56" alt="training slate"> | <img src="tiles/training-pink.png" width="56" alt="training pink"> | <img src="tiles/training-lilac.png" width="56" alt="training lilac"> |
| `chart` | <img src="tiles/chart-lavender.png" width="56" alt="chart lavender"> | <img src="tiles/chart-slate.png" width="56" alt="chart slate"> | <img src="tiles/chart-pink.png" width="56" alt="chart pink"> | <img src="tiles/chart-lilac.png" width="56" alt="chart lilac"> |
| `bolt` | <img src="tiles/bolt-lavender.png" width="56" alt="bolt lavender"> | <img src="tiles/bolt-slate.png" width="56" alt="bolt slate"> | <img src="tiles/bolt-pink.png" width="56" alt="bolt pink"> | <img src="tiles/bolt-lilac.png" width="56" alt="bolt lilac"> |
