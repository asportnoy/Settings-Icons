<kbd>[<img title="English" alt="English" src="https://crearts-community.github.io/Assets/languages/english.png" width="40">](readme.md)</kbd>
<kbd>[<img title="German" alt="German" src="https://crearts-community.github.io/Assets/languages/german.png" width="40">](.github/docs/translations/variables/german.md)</kbd>
<kbd>[<img title="French" alt="French" src="https://crearts-community.github.io/Assets/languages/french.png" width="40">](.github/docs/translations/variables/french.md)</kbd>
<kbd>[<img title="Italian" alt="Italian" src="https://crearts-community.github.io/Assets/languages/italian.png" width="40">](.github/docs/translations/variables/italian.md)</kbd>
<kbd>[<img title="Swedish" alt="Swedish" src="https://crearts-community.github.io/Assets/languages/swedish.png" width="40">](.github/docs/translations/variables/swedish.md)</kbd>
<kbd>[<img title="Dutch" alt="Dutch" src="https://crearts-community.github.io/Assets/languages/dutch.png" width="40">](.github/docs/translations/variables/dutch.md)</kbd>
<kbd>[<img title="Spanish" alt="Spanish" src="https://crearts-community.github.io/Assets/languages/spanish.png" width="40">](.github/docs/translations/variables/spanish.md)</kbd>
<kbd>[<img title="Finnish" alt="Finnish" src="https://crearts-community.github.io/Assets/languages/finnish.png" width="40">](.github/docs/translations/variables/finnish.md)</kbd>
<kbd>[<img title="Polish" alt="Polish" src="https://crearts-community.github.io/Assets/languages/polish.png" width="40">](.github/docs/translations/variables/polish.md)</kbd>
<kbd>[<img title="Danish" alt="Danish" src="https://crearts-community.github.io/Assets/languages/danish.png" width="40">](.github/docs/translations/variables/danish.md)</kbd>
<kbd>[<img title="Portuguese" alt="Portuguese" src="https://crearts-community.github.io/Assets/languages/portuguese.png" width="40">](.github/docs/translations/variables/portuguese.md)</kbd>
<kbd>[<img title="Greek" alt="Greek" src="https://crearts-community.github.io/Assets/languages/greek.png" width="40">](.github/docs/translations/variables/greek.md)</kbd>

<kbd>[<img title="Japanese" alt="Japanese" src="https://crearts-community.github.io/Assets/languages/japanese.png" width="40">](.github/docs/translations/variables/japanese.md)</kbd>
<kbd>[<img title="Lithuanian" alt="Lithuanian" src="https://crearts-community.github.io/Assets/languages/lithuanian.png" width="40">](.github/docs/translations/variables/lithuanian.md)</kbd>
<kbd>[<img title="Estonian" alt="Estonian" src="https://crearts-community.github.io/Assets/languages/estonian.png" width="40">](.github/docs/translations/variables/estonian.md)</kbd>
<kbd>[<img title="Latvian" alt="Latvian" src="https://crearts-community.github.io/Assets/languages/latvian.png" width="40">](.github/docs/translations/variables/latvian.md)</kbd>
<kbd>[<img title="Czech" alt="Czech" src="https://crearts-community.github.io/Assets/languages/czech.png" width="40">](.github/docs/translations/variables/czech.md)</kbd>
<kbd>[<img title="Romanian" alt="Romanian" src="https://crearts-community.github.io/Assets/languages/romanian.png" width="40">](.github/docs/translations/variables/romanian.md)</kbd>
<kbd>[<img title="Slovenian" alt="Slovenian" src="https://crearts-community.github.io/Assets/languages/slovenian.png" width="40">](.github/docs/translations/variables/slovenian.md)</kbd>
<kbd>[<img title="Bulgarian" alt="Bulgarian" src="https://crearts-community.github.io/Assets/languages/bulgarian.png" width="40">](.github/docs/translations/variables/bulgarian.md)</kbd>
<kbd>[<img title="Slovak" alt="Slovak" src="https://crearts-community.github.io/Assets/languages/slovak.png" width="40">](.github/docs/translations/variables/slovak.md)</kbd>
<kbd>[<img title="Hungarian" alt="Hungarian" src="https://crearts-community.github.io/Assets/languages/hungarian.png" width="40">](.github/docs/translations/variables/hungarian.md)</kbd>
<kbd>[<img title="Russian" alt="Russian" src="https://crearts-community.github.io/Assets/languages/russian.png" width="40">](.github/docs/translations/variables/russian.md)</kbd>
<kbd>[<img title="Chinese" alt="Chinese" src="https://crearts-community.github.io/Assets/languages/chinese.png" width="40">](.github/docs/translations/variables/chinese.md)</kbd>

# Variablen

Hier finden Sie eine Liste der verwendeten Variablen des Settings icon Theme Addon.

## Info

Diese Variablen werden nicht so sehr für die Anpassung verwendet, sondern geben den Themes die Möglichkeit, die Version anzuzeigen und zu prüfen, ob ein Theme geladen wurde.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-info-version``` | ```"v1.1.0"``` |
| ```--SeIc-info-loaded``` | ```"✅"``` |

## Width

Mit dieser Variable können Sie die Seitenleiste der Einstellungen um den eingegebenen Wert erweitern.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-width-serverlist``` | ```38px``` |

## Text Style

Mit diesen Variablen können Sie den Stil der Überschrift oder des Textes ändern, Sie können ``uppercase``, ``lowercase`` oder ``capitalize`` nutzen.

| Variable | Default Value
| ------------- | ------------- |
| ```--SeIc-style-header``` | ```uppercase``` |
| ```--SeIc-style-text``` | ```capitalize``` |

## Color (Header)

Mit diesen Variablen können Sie die Farben der Kopfzeile in der Einstellungsseitenleiste ändern.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-color-header-normal``` | ```var(--channels-default)``` |

## Color (Icon)

Mit diesen Variablen können Sie die Farben der Icons in der Einstellungsseitenleiste ändern.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-color-icon-normal``` | ```var(--interactive-normal)``` |
| ```--SeIc-color-icon-hover``` | ```var(--interactive-hover)``` |
| ```--SeIc-color-icon-active``` | ```var(--interactive-active)``` |
| ```--SeIc-color-icon-logout-normal``` | ```var(--text-danger)``` |
| ```--SeIc-color-icon-logout-hover``` | ```var(--info-danger-text)``` |
| ```--SeIc-color-icon-nitro-normal``` | ```hsla(302,calc(var(--saturation-factor, 1)*100%),72.5%, 1.0)``` |
| ```--SeIc-color-icon-nitro-hover``` | ```var(--interactive-hover)``` |
| ```--SeIc-color-icon-nitro-active``` | ```var(--interactive-active)``` |

## Color (Text)

Mit diesen Variablen können Sie die Farben des Textes in der Einstellungsseitenleiste ändern.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-color-text-normal``` | ```var(--interactive-normal)``` |
| ```--SeIc-color-text-hover``` | ```var(--interactive-hover)``` |
| ```--SeIc-color-text-active``` | ```var(--interactive-active)``` |
| ```--SeIc-color-text-logout-normal``` | ```var(--text-danger)``` |
| ```--SeIc-color-text-logout-hover``` | ```var(--info-danger-text)``` |
| ```--SeIc-color-text-nitro-normal``` | ```hsla(302,calc(var(--saturation-factor, 1)*100%),72.5%, 1.0)``` |
| ```--SeIc-color-text-nitro-hover``` | ```var(--interactive-hover)``` |
| ```--SeIc-color-text-nitro-active``` | ```var(--interactive-active)``` |

## Color (Background)

Mit diesen Variablen können Sie die Farbe des Hintergrunds in der Seitenleiste Einstellungen anpassen.

| Variable | Default Value |
| ------------- | ------------- |
| ```--SeIc-color-background-normal``` | ```transparent``` |
| ```--SeIc-color-background-hover``` | ```var(--background-modifier-hover)``` |
| ```--SeIc-color-background-active``` | ```var(--background-modifier-selected)``` |
| ```--SeIc-color-background-logout-normal``` | ```transparent``` |
| ```--SeIc-color-background-logout-hover``` | ```var(--button-danger-background)``` |
| ```--SeIc-color-background-nitro-normal``` | ```transparent``` |
| ```--SeIc-color-background-nitro-hover``` | ```hsla(302,calc(var(--saturation-factor, 1)*100%),72.5%, 0.2)``` |
| ```--SeIc-color-background-nitro-active``` | ```hsla(302,calc(var(--saturation-factor, 1)*100%),72.5%, 1.0)``` |