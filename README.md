<img class="rounded" src="https://raw.githubusercontent.com/NativeScript/artwork/main/logo/export/NativeScript_Logo_Wide_White_Blue_Rounded_Blue.png" width="250" alt="NaeLike"> 
# NativeScript_preview
NativeScript_preview, $ ns. preview / Native power without native overhead Install NativeScript Preview and start developing mobile apps with only one additional dependency. A browser.

# Nativescript 
:+1: Web Note.JS:  <https://nodejs.org/en> ..! 
<br>
:+1: Web Nativescript:  <https://nativescript.org/> ..! 
<br>
:+1: Web Nativescript Plugins:  <https://market.nativescript.org/?tab=templates&category=all_templates> ..! 
<br>
:+1: Web Nativescript Preview:  <https://preview.nativescript.org/> ..!

# Install the NativeScript CLI
Open your terminal or command prompt and execute the following command to install the NativeScript CLI from npm, which is the Node.js package manager:
```
npm install -g nativescript
```

# Create a new NativeScript Vue application
Interactively creates a new NativeScript app based on a predefined template.
<br>
```
# TEMPLATE	SYNOPSIS

# JavaScript based
$ ns create [<App Name>] [--js] [--path <Directory>] [--appid <App ID>]

# TypeScript based
$ ns create [<App Name>] --ts [--path <Directory>] [--appid <App ID>]

# Angular based
$ ns create [<App Name>] --ng [--path <Directory>] [--appid <App ID>]

# Vue.js based
$ ns create [<App Name>] --vue [--path <Directory>] [--appid <App ID>]

# Custom template
$ ns create [<App Name>] [--path <Directory>] [--appid <App ID>] --template <Template>
```

<br>
<img class="rounded" src="https://art.nativescript-vue.org/NativeScript-Vue-Green-White.svg" width="250" alt="NaeLike"> 
To create a new NativeScript Vue application, run the CLI command ns create with the name of the application followed by --vue and --ts.

```
# Create
$ ns create example-app --vue --ts

# Run the application cd example-app
$ ns run ios
$ ns run android
```

# NS Preview 
Run in your local environment / Already have a local node development environment you are familiar with?
:+1: Web Nativescript Vue:  <https://nativescript-vue.org/> ..!
<img class="rounded" src="https://preview.nativescript.org/assets/vscode_screenshot-7827d88c.png" width="100%" alt="NaeLike"> 
```
# 1. Install the NativeScript CLI
$ npm install -g nativescript

# 2. (Optional) Create a new project or use an existing one
$ ns create

# 3. Preview away!
$ ns preview
```

# Nativescript App Preview
Produces a QR code which can be used to preview the app on a device without the need to install various SDKs and tools or configure your environment for local iOS or Android development.
To scan the QR code and deploy your app on a device, you need to have the NativeScript Playground app:
<br>
<div class="ml-28 mt-4 flex items-center space-x-4"><a href="https://preview.nativescript.org/ios" target="_blank" aria-label="Download the Preview app from the AppStore" class="v-popper--has-tooltip"><svg role="presentation" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 40" class="h-10 md:h-12"><path d="M110.135 0H9.535c-.367 0-.73 0-1.095.002-.306.002-.61.008-.919.013A13.215 13.215 0 0 0 5.517.19a6.665 6.665 0 0 0-1.9.627 6.438 6.438 0 0 0-1.62 1.18A6.258 6.258 0 0 0 .82 3.617 6.601 6.601 0 0 0 .195 5.52a12.993 12.993 0 0 0-.179 2.002c-.01.307-.01.615-.015.921V31.56c.005.31.006.61.015.921a12.992 12.992 0 0 0 .18 2.002 6.588 6.588 0 0 0 .624 1.905A6.208 6.208 0 0 0 1.998 38a6.274 6.274 0 0 0 1.618 1.179 6.7 6.7 0 0 0 1.901.63 13.455 13.455 0 0 0 2.004.177c.31.007.613.011.919.011.366.002.728.002 1.095.002h100.6c.36 0 .724 0 1.084-.002.304 0 .617-.004.922-.01a13.279 13.279 0 0 0 2-.178 6.804 6.804 0 0 0 1.908-.63A6.277 6.277 0 0 0 117.666 38a6.395 6.395 0 0 0 1.182-1.614 6.604 6.604 0 0 0 .619-1.905 13.506 13.506 0 0 0 .185-2.002c.004-.31.004-.61.004-.921.008-.364.008-.725.008-1.094V9.536c0-.366 0-.73-.008-1.092 0-.306 0-.614-.004-.92a13.507 13.507 0 0 0-.185-2.003 6.618 6.618 0 0 0-.62-1.903 6.466 6.466 0 0 0-2.798-2.8 6.768 6.768 0 0 0-1.908-.627 13.044 13.044 0 0 0-2-.176c-.305-.005-.618-.011-.922-.013-.36-.002-.725-.002-1.084-.002Z" style="fill: rgb(166, 166, 166);"></path><path d="M8.445 39.125c-.305 0-.602-.004-.904-.01a12.687 12.687 0 0 1-1.87-.164 5.884 5.884 0 0 1-1.656-.548 5.406 5.406 0 0 1-1.397-1.016 5.32 5.32 0 0 1-1.02-1.397 5.722 5.722 0 0 1-.544-1.657 12.414 12.414 0 0 1-.166-1.875c-.007-.21-.015-.913-.015-.913v-23.1s.009-.692.015-.895a12.37 12.37 0 0 1 .165-1.872 5.755 5.755 0 0 1 .544-1.662 5.373 5.373 0 0 1 1.015-1.398 5.565 5.565 0 0 1 1.402-1.023 5.823 5.823 0 0 1 1.653-.544A12.586 12.586 0 0 1 7.543.887l.902-.012h102.769l.913.013a12.385 12.385 0 0 1 1.858.162 5.938 5.938 0 0 1 1.671.548 5.594 5.594 0 0 1 2.415 2.42 5.763 5.763 0 0 1 .535 1.649 12.995 12.995 0 0 1 .174 1.887c.003.283.003.588.003.89.008.375.008.732.008 1.092v20.929c0 .363 0 .718-.008 1.075 0 .325 0 .623-.004.93a12.731 12.731 0 0 1-.17 1.853 5.739 5.739 0 0 1-.54 1.67 5.48 5.48 0 0 1-1.016 1.386 5.413 5.413 0 0 1-1.4 1.022 5.862 5.862 0 0 1-1.668.55 12.542 12.542 0 0 1-1.869.163c-.293.007-.6.011-.897.011l-1.084.002Z"></path><path d="M24.769 20.3a4.949 4.949 0 0 1 2.356-4.151 5.066 5.066 0 0 0-3.99-2.158c-1.68-.176-3.308 1.005-4.164 1.005-.872 0-2.19-.988-3.608-.958a5.315 5.315 0 0 0-4.473 2.728c-1.934 3.348-.491 8.269 1.361 10.976.927 1.325 2.01 2.805 3.428 2.753 1.387-.058 1.905-.885 3.58-.885 1.658 0 2.144.885 3.59.852 1.489-.025 2.426-1.332 3.32-2.67a10.962 10.962 0 0 0 1.52-3.092 4.782 4.782 0 0 1-2.92-4.4Zm-2.732-8.09a4.872 4.872 0 0 0 1.115-3.49 4.957 4.957 0 0 0-3.208 1.66 4.636 4.636 0 0 0-1.144 3.36 4.1 4.1 0 0 0 3.237-1.53Z" style="fill: rgb(255, 255, 255);"></path><path d="M42.302 27.14H37.57l-1.137 3.356h-2.005l4.484-12.418h2.083l4.483 12.418h-2.039Zm-4.243-1.55h3.752l-1.85-5.446h-.051Zm17.101.38c0 2.813-1.506 4.62-3.779 4.62a3.07 3.07 0 0 1-2.848-1.583h-.043v4.484h-1.86V21.442h1.8v1.506h.033a3.212 3.212 0 0 1 2.883-1.6c2.298 0 3.813 1.816 3.813 4.622Zm-1.91 0c0-1.833-.948-3.038-2.393-3.038-1.42 0-2.375 1.23-2.375 3.038 0 1.824.955 3.046 2.375 3.046 1.445 0 2.393-1.197 2.393-3.046Zm11.875 0c0 2.813-1.506 4.62-3.779 4.62a3.07 3.07 0 0 1-2.848-1.583h-.043v4.484h-1.859V21.442h1.799v1.506h.034a3.212 3.212 0 0 1 2.883-1.6c2.298 0 3.813 1.816 3.813 4.622Zm-1.91 0c0-1.833-.948-3.038-2.393-3.038-1.42 0-2.375 1.23-2.375 3.038 0 1.824.955 3.046 2.375 3.046 1.445 0 2.392-1.197 2.392-3.046Zm8.495 1.066c.138 1.232 1.334 2.04 2.97 2.04 1.566 0 2.693-.808 2.693-1.919 0-.964-.68-1.54-2.29-1.936l-1.609-.388c-2.28-.55-3.339-1.617-3.339-3.348 0-2.142 1.867-3.614 4.519-3.614 2.624 0 4.423 1.472 4.483 3.614h-1.876c-.112-1.239-1.136-1.987-2.634-1.987s-2.521.757-2.521 1.858c0 .878.654 1.395 2.255 1.79l1.368.336c2.548.603 3.606 1.626 3.606 3.443 0 2.323-1.85 3.778-4.793 3.778-2.754 0-4.614-1.42-4.734-3.667ZM83.346 19.3v2.142h1.722v1.472h-1.722v4.991c0 .776.345 1.137 1.102 1.137a5.808 5.808 0 0 0 .611-.043v1.463a5.104 5.104 0 0 1-1.032.086c-1.833 0-2.548-.689-2.548-2.445v-5.189h-1.316v-1.472h1.316V19.3Zm2.719 6.67c0-2.849 1.678-4.639 4.294-4.639 2.625 0 4.295 1.79 4.295 4.639 0 2.856-1.661 4.638-4.295 4.638-2.633 0-4.294-1.782-4.294-4.638Zm6.695 0c0-1.954-.895-3.108-2.401-3.108s-2.4 1.162-2.4 3.108c0 1.962.894 3.106 2.4 3.106s2.401-1.144 2.401-3.106Zm3.426-4.528h1.773v1.541h.043a2.16 2.16 0 0 1 2.177-1.635 2.866 2.866 0 0 1 .637.069v1.738a2.598 2.598 0 0 0-.835-.112 1.873 1.873 0 0 0-1.937 2.083v5.37h-1.858Zm13.198 6.395c-.25 1.643-1.85 2.771-3.898 2.771-2.634 0-4.269-1.764-4.269-4.595 0-2.84 1.644-4.682 4.19-4.682 2.506 0 4.08 1.72 4.08 4.466v.637h-6.394v.112a2.358 2.358 0 0 0 2.436 2.564 2.048 2.048 0 0 0 2.09-1.273Zm-6.282-2.702h4.526a2.177 2.177 0 0 0-2.22-2.298 2.292 2.292 0 0 0-2.306 2.298ZM37.826 8.731a2.64 2.64 0 0 1 2.808 2.965c0 1.906-1.03 3.002-2.808 3.002h-2.155V8.73Zm-1.228 5.123h1.125a1.876 1.876 0 0 0 1.967-2.146 1.881 1.881 0 0 0-1.967-2.134h-1.125Zm5.082-1.41a2.133 2.133 0 1 1 4.248 0 2.134 2.134 0 1 1-4.247 0Zm3.334 0c0-.976-.439-1.547-1.208-1.547-.773 0-1.207.571-1.207 1.547 0 .984.434 1.55 1.207 1.55.77 0 1.208-.57 1.208-1.55Zm6.559 2.254h-.922l-.93-3.317h-.07l-.927 3.317h-.913l-1.242-4.503h.902l.806 3.436h.067l.926-3.436h.852l.926 3.436h.07l.803-3.436h.889Zm2.281-4.503h.855v.715h.066a1.348 1.348 0 0 1 1.344-.802 1.465 1.465 0 0 1 1.559 1.675v2.915h-.889v-2.692c0-.724-.314-1.084-.972-1.084a1.033 1.033 0 0 0-1.075 1.141v2.635h-.888Zm5.24-1.758h.888v6.26h-.888Zm2.124 4.007a2.133 2.133 0 1 1 4.247 0 2.134 2.134 0 1 1-4.247 0Zm3.333 0c0-.976-.439-1.547-1.208-1.547-.773 0-1.207.571-1.207 1.547 0 .984.434 1.55 1.207 1.55.77 0 1.208-.57 1.208-1.55Zm1.849.98c0-.81.604-1.278 1.676-1.344l1.22-.07v-.389c0-.475-.315-.744-.922-.744-.497 0-.84.182-.939.5h-.86c.09-.773.818-1.27 1.84-1.27 1.128 0 1.765.563 1.765 1.514v3.077h-.855v-.633h-.07a1.515 1.515 0 0 1-1.353.707 1.36 1.36 0 0 1-1.501-1.348Zm2.895-.384v-.377l-1.1.07c-.62.042-.9.253-.9.65 0 .405.351.64.834.64a1.062 1.062 0 0 0 1.166-.983Zm2.053-.596c0-1.423.732-2.324 1.87-2.324a1.484 1.484 0 0 1 1.38.79h.067V8.437h.888v6.26h-.851v-.71h-.07a1.563 1.563 0 0 1-1.415.785c-1.145 0-1.869-.901-1.869-2.328Zm.918 0c0 .955.45 1.53 1.203 1.53.75 0 1.212-.583 1.212-1.526 0-.938-.468-1.53-1.212-1.53-.748 0-1.203.58-1.203 1.526Zm6.964 0a2.133 2.133 0 1 1 4.247 0 2.134 2.134 0 1 1-4.247 0Zm3.333 0c0-.976-.438-1.547-1.208-1.547-.772 0-1.207.571-1.207 1.547 0 .984.435 1.55 1.207 1.55.77 0 1.208-.57 1.208-1.55Zm2.107-2.249h.855v.715h.066a1.348 1.348 0 0 1 1.344-.802 1.465 1.465 0 0 1 1.559 1.675v2.915h-.889v-2.692c0-.724-.314-1.084-.972-1.084a1.033 1.033 0 0 0-1.075 1.141v2.635h-.889Zm8.845-1.121v1.141h.976v.749h-.976v2.315c0 .472.194.679.637.679a2.967 2.967 0 0 0 .339-.021v.74a2.916 2.916 0 0 1-.484.046c-.988 0-1.381-.348-1.381-1.216v-2.543h-.715v-.749h.715V9.074Zm2.19-.637h.88v2.481h.07a1.386 1.386 0 0 1 1.374-.806 1.483 1.483 0 0 1 1.55 1.679v2.907h-.889V12.01c0-.72-.335-1.084-.963-1.084a1.052 1.052 0 0 0-1.134 1.142v2.63h-.888Zm9.056 5.045a1.828 1.828 0 0 1-1.95 1.303 2.045 2.045 0 0 1-2.081-2.325 2.077 2.077 0 0 1 2.076-2.352c1.253 0 2.009.856 2.009 2.27v.31h-3.18v.05a1.19 1.19 0 0 0 1.2 1.29 1.08 1.08 0 0 0 1.07-.546Zm-3.126-1.451h2.275a1.086 1.086 0 0 0-1.109-1.167 1.152 1.152 0 0 0-1.166 1.167Z" style="fill: rgb(255, 255, 255);"></path></svg></a><a href="https://preview.nativescript.org/android" target="_blank" aria-label="Download the Preview app from Google Play" class="v-popper--has-tooltip"><svg role="presentation" viewBox="0 0 180 54" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" class="h-10 md:h-12" style="fill-rule: evenodd; clip-rule: evenodd; stroke-linejoin: round; stroke-miterlimit: 2;"><path d="M1400 100H150c-27.5 0-50 22.5-50 50v300c0 27.5 22.5 50 50 50h1250c27.5 0 50-22.5 50-50V150c0-27.5-22.5-50-50-50" style="fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M1400 500H150c-27.5 0-50-22.5-50-50V150c0-27.5 22.5-50 50-50h1250c27.5 0 50 22.5 50 50v300c0 27.5-22.5 50-50 50m0-8c23.16 0 42-18.844 42-42V150c0-23.16-18.84-42.004-42-42.004H150c-23.156 0-42 18.844-42 42.004v300c0 23.156 18.844 42 42 42h1250" style="fill:#a6a6a6;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M574.184 397.566c0-8.378-2.481-15.05-7.45-20.027-5.644-5.918-13-8.879-22.043-8.879-8.66 0-16.023 3-22.078 9.008-6.066 6.004-9.093 13.449-9.093 22.332 0 8.887 3.027 16.328 9.093 22.336 6.055 6.004 13.418 9.008 22.078 9.008 4.297 0 8.411-.84 12.317-2.516 3.906-1.68 7.039-3.91 9.383-6.703l-5.274-5.277c-3.972 4.746-9.441 7.117-16.426 7.117-6.316 0-11.777-2.219-16.386-6.66-4.61-4.446-6.914-10.211-6.914-17.305 0-7.094 2.304-12.859 6.914-17.305 4.609-4.441 10.07-6.66 16.386-6.66 6.7 0 12.286 2.231 16.758 6.699 2.903 2.911 4.582 6.957 5.031 12.153h-21.789v7.207h29.075c.281-1.567.418-3.071.418-4.528" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M574.184 397.566h-1c-.008-8.187-2.399-14.546-7.157-19.32l-.011-.008-.004-.008c-5.465-5.714-12.489-8.558-21.321-8.57-8.429.012-15.484 2.887-21.375 8.715-5.878 5.84-8.785 12.969-8.796 21.625.011 8.66 2.918 15.785 8.796 21.621 5.891 5.832 12.946 8.711 21.375 8.723 4.168 0 8.137-.813 11.922-2.434 3.789-1.633 6.782-3.773 9.012-6.43l.766.645-.707.707-5.274-5.281.707-.703.77.64c-4.157 4.981-9.992 7.492-17.196 7.477-6.55.008-12.312-2.332-17.078-6.942-4.812-4.625-7.23-10.714-7.222-18.023-.008-7.309 2.41-13.398 7.222-18.023 4.766-4.61 10.528-6.95 17.078-6.942 6.922-.012 12.821 2.336 17.465 6.992 3.102 3.11 4.86 7.418 5.321 12.774l.093 1.086h-21.879v5.207h28.075v1l-.985-.176c.274-1.516.403-2.957.403-4.352h2c0 1.52-.141 3.082-.434 4.707l-.148.821h-30.911v-9.207h22.789v1l-.996.086c-.441-5.032-2.043-8.821-4.742-11.532-4.297-4.281-9.57-6.394-16.051-6.406-6.082.008-11.242 2.102-15.691 6.379-4.406 4.262-6.598 9.703-6.609 16.586.011 6.883 2.203 12.324 6.609 16.586 4.449 4.277 9.609 6.371 15.691 6.379 6.762-.016 11.868-2.25 15.661-6.762l.703-.836 6.043 6.051.648.648-.59.7c-2.457 2.929-5.73 5.254-9.754 6.98-4.031 1.731-8.285 2.598-12.711 2.598-8.89.008-16.562-3.117-22.785-9.301-6.246-6.172-9.394-13.93-9.386-23.043-.008-9.109 3.14-16.871 9.39-23.047 6.219-6.18 13.891-9.301 22.781-9.293 9.258-.008 16.938 3.067 22.766 9.188l-.723.691.707-.707c5.18 5.176 7.75 12.168 7.743 20.734h-1m46.093 25.063h-27.324v-19.024h24.641v-7.21h-24.641v-19.024h27.324V370H585.25v60h35.027v-7.371" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M620.277 422.629v1h-28.324v-21.024h24.641v-5.207l-24.641-.003v-21.024h27.324V371H586.25v58h33.027v-6.371h1v1-1h1V431H584.25v-62h37.027v9.371h-27.324v17.024h24.641v9.21h-24.641v17.024h27.324v1h-1M652.789 370h-7.715v52.629h-16.758V430h41.231v-7.371h-16.758V370" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M652.789 370v1h-6.715v52.629h-16.758V429h39.231v-5.371h-16.758V370h1v1-1h1v51.629h16.758V431h-43.231v-9.371h16.758V369h9.715v1h-1m46.59 0v60h7.707v-60h-7.707" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M699.379 370h1v59h5.707v-58h-6.707v-1h1-1v-1h8.707v62h-9.707v-62h1v1m41.906 0h-7.715v52.629h-16.757V430h41.23v-7.371h-16.758V370" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M741.285 370v1h-6.715v52.629h-16.757V429h39.23v-5.371h-16.758V370h1v1-1h1v51.629h16.758V431h-43.23v-9.371h16.757V369h9.715v1h-1m56.508 12.777c4.441-4.496 9.875-6.742 16.301-6.742 6.426 0 11.863 2.246 16.297 6.742 4.445 4.496 6.672 10.243 6.672 17.223 0 6.98-2.227 12.727-6.672 17.223-4.434 4.496-9.871 6.742-16.297 6.742s-11.86-2.246-16.301-6.742c-4.434-4.496-6.66-10.243-6.66-17.223 0-6.98 2.226-12.727 6.66-17.223Zm38.301-5.023c-5.899-6.066-13.235-9.094-22-9.094-8.774 0-16.106 3.028-21.992 9.094-5.903 6.059-8.84 13.476-8.84 22.246 0 8.77 2.937 16.188 8.84 22.246 5.886 6.067 13.218 9.098 21.992 9.098 8.719 0 16.035-3.047 21.961-9.137 5.918-6.09 8.879-13.492 8.879-22.207 0-8.77-2.954-16.187-8.84-22.246" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m798.504 383.48-1.422-1.406c4.606-4.676 10.352-7.051 17.012-7.039 6.656-.012 12.41 2.363 17.008 7.039 4.636 4.68 6.968 10.735 6.961 17.926.007 7.191-2.325 13.246-6.961 17.926-4.598 4.676-10.352 7.051-17.008 7.039-6.66.012-12.406-2.363-17.012-7.039-4.625-4.68-6.961-10.735-6.949-17.926-.012-7.191 2.324-13.246 6.949-17.926l1.422 1.406c-4.242 4.317-6.363 9.747-6.371 16.52.008 6.773 2.129 12.203 6.371 16.52 4.281 4.316 9.394 6.433 15.59 6.445 6.191-.012 11.316-2.129 15.586-6.445 4.25-4.317 6.371-9.747 6.379-16.52-.008-6.773-2.129-12.203-6.379-16.52-4.27-4.316-9.395-6.433-15.586-6.445-6.196.012-11.309 2.129-15.59 6.445Zm37.59-5.726-.715.695c-5.734-5.875-12.746-8.777-21.285-8.789-8.543.012-15.555 2.914-21.278 8.789l-.027.031.027-.031c-5.722 5.895-8.546 13.004-8.554 21.551.008 8.547 2.832 15.656 8.554 21.551 5.723 5.875 12.735 8.781 21.278 8.793 8.484-.012 15.48-2.93 21.246-8.836 5.742-5.922 8.582-13.02 8.594-21.508-.012-8.547-2.844-15.656-8.555-21.551l.715-.695.719-.695c6.062 6.226 9.128 13.949 9.121 22.941.007 8.941-3.071 16.648-9.161 22.902-6.093 6.278-13.726 9.453-22.679 9.442-9 .011-16.656-3.149-22.711-9.403v.004c-6.074-6.23-9.129-13.953-9.121-22.945-.008-8.992 3.047-16.715 9.121-22.945l.027-.028-.027.032c6.055-6.254 13.711-9.407 22.711-9.399 8.996-.008 16.652 3.145 22.719 9.399l-.719.695m19.66-7.754v60h9.383l29.16-46.676h.332l-.332 11.563V430h7.715v-60h-8.047l-30.508 48.938h-.332l.332-11.567V370h-7.703" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M855.754 370h1v59h7.828l29.16-46.676h1.914l-.359 12.578V429h5.715v-58h-6.492l-30.508 48.938h-1.914l.359-12.583V371h-6.703v-1h1-1v-1h8.703v38.387l-.332 11.578-1-.027v-1h.332v1l-.848-.532L893.41 369h9.602v62h-9.715v-36.125l.332-11.578 1 .027v1h-.332v-1l.848.531L865.691 431h-10.937v-62h1v1m313.606-170h18.66v125.012h-18.66V200Zm168.07 79.98-21.39-54.199h-.64l-22.2 54.199h-20.1l33.29-75.753-18.98-42.137h19.47l51.3 117.89h-20.75Zm-105.82-65.781c-6.12 0-14.64 3.055-14.64 10.617 0 9.649 10.62 13.348 19.78 13.348 8.21 0 12.06-1.769 17.05-4.184-1.45-11.578-11.42-19.781-22.19-19.781Zm2.25 68.516c-13.51 0-27.5-5.953-33.29-19.141l16.56-6.914c3.54 6.914 10.13 9.168 17.05 9.168 9.65 0 19.46-5.793 19.62-16.086v-1.285c-3.38 1.93-10.61 4.824-19.46 4.824-17.85 0-36.03-9.808-36.03-28.144 0-16.727 14.64-27.504 31.04-27.504 12.55 0 19.46 5.629 23.81 12.222h.64v-9.648h18.01v47.93c0 22.191-16.56 34.578-37.95 34.578Zm-115.32-17.953H1092v42.851h26.54c13.95 0 21.87-11.55 21.87-21.425 0-9.688-7.92-21.426-21.87-21.426Zm-.48 60.25h-44.71V200H1092v47.363h26.06c20.68 0 41.01 14.973 41.01 38.825 0 23.851-20.33 38.824-41.01 38.824ZM874.25 214.176c-12.891 0-23.684 10.793-23.684 25.617 0 14.98 10.793 25.937 23.684 25.937 12.727 0 22.715-10.957 22.715-25.937 0-14.824-9.988-25.617-22.715-25.617Zm21.426 58.804h-.645c-4.187 4.993-12.246 9.504-22.394 9.504-21.266 0-40.758-18.687-40.758-42.691 0-23.844 19.492-42.371 40.758-42.371 10.148 0 18.207 4.512 22.394 9.664h.645v-6.121c0-16.274-8.699-24.973-22.715-24.973-11.438 0-18.527 8.219-21.43 15.145l-16.269-6.766c4.672-11.277 17.078-25.133 37.699-25.133 21.91 0 40.437 12.891 40.437 44.305v76.363h-17.722v-6.926ZM926.285 200h18.688v125.016h-18.688V200Zm46.238 41.242c-.484 16.434 12.727 24.809 22.231 24.809 7.416 0 13.696-3.703 15.786-9.024l-38.017-15.785Zm57.997 14.176c-3.54 9.508-14.34 27.066-36.411 27.066-21.91 0-40.113-17.238-40.113-42.531 0-23.844 18.043-42.531 42.207-42.531 19.497 0 30.777 11.922 35.447 18.848l-14.5 9.668c-4.83-7.09-11.44-11.762-20.947-11.762-9.504 0-16.269 4.351-20.621 12.887l56.868 23.523-1.93 4.832Zm-453.082 14.016v-18.043h43.175c-1.289-10.149-4.672-17.559-9.828-22.715-6.281-6.285-16.109-13.211-33.347-13.211-26.583 0-47.364 21.426-47.364 48.008 0 26.582 20.781 48.011 47.364 48.011 14.339 0 24.808-5.64 32.542-12.89l12.727 12.726c-10.793 10.313-25.133 18.207-45.269 18.207-36.411 0-67.02-29.644-67.02-66.054 0-36.41 30.609-66.051 67.02-66.051 19.656 0 34.476 6.441 46.074 18.527 11.922 11.922 15.629 28.676 15.629 42.207 0 4.192-.321 8.055-.969 11.278h-60.734Zm110.789-55.258c-12.891 0-24.008 10.633-24.008 25.777 0 15.305 11.117 25.777 24.008 25.777 12.886 0 24.003-10.472 24.003-25.777 0-15.144-11.117-25.777-24.003-25.777Zm0 68.308c-23.524 0-42.696-17.882-42.696-42.531 0-24.488 19.172-42.531 42.696-42.531 23.519 0 42.691 18.043 42.691 42.531 0 24.649-19.172 42.531-42.691 42.531Zm93.132-68.308c-12.886 0-24.004 10.633-24.004 25.777 0 15.305 11.118 25.777 24.004 25.777 12.887 0 24.004-10.472 24.004-25.777 0-15.144-11.117-25.777-24.004-25.777Zm0 68.308c-23.523 0-42.691-17.882-42.691-42.531 0-24.488 19.168-42.531 42.691-42.531 23.52 0 42.692 18.043 42.692 42.531 0 24.649-19.172 42.531-42.692 42.531" style="fill:#fff;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m205.098 176.105-.743.711c-2.91 3.079-4.628 7.86-4.628 14.051v-1.457 221.211-1.516c0 6.704 2.003 11.754 5.359 14.782l123.898-123.895-123.886-123.887M199.77 412.27c0 .007 0 .015.003.023-.003-.008-.003-.016-.003-.023m.003.07v.012-.012" style="fill:url(#a__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m370.277 257.215.942.535 48.929 27.801c4.665 2.652 7.774 5.867 9.325 9.269-1.547-3.402-4.657-6.621-9.325-9.273l-48.929-27.801-.942-.531m.012 1.465-41.305 41.312 41.301 41.305 49.863-28.328c6.332-3.598 9.887-8.235 10.481-12.973v-.019c-.594-4.727-4.149-9.368-10.481-12.965l-49.859-28.332" style="fill:url(#b__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M213.93 171.387c-3.461 0-6.481 1.125-8.836 3.25l.004.004c2.355-2.125 5.379-3.254 8.84-3.254h-.008m.004 1.465c-3.461-.004-6.481 1.125-8.836 3.25v.003l123.886 123.887 41.305-41.312-145.152-82.473c-4.016-2.277-7.821-3.355-11.203-3.355m-8.871 1.812c-.219.199-.434.41-.645.629l.645-.629" style="fill:url(#c__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M328.984 299.992 205.086 423.887c2.355 2.121 5.371 3.246 8.828 3.246 3.391 0 7.199-1.082 11.223-3.363l145.148-82.473-41.301-41.305m42.235 42.238-146.082 83c-4.024 2.282-7.832 3.364-11.223 3.364h-.043.059c3.383 0 7.187-1.078 11.207-3.36l146.082-83.004" style="fill:url(#d__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M214.852 171.41c3.144.18 6.625 1.262 10.285 3.336l145.14 82.469-145.14-82.469c-3.657-2.078-7.141-3.156-10.285-3.336m-9.758 3.227-.031.027a.26.26 0 0 0 .031-.027m-.676.656-.063.062v.004c.024-.023.043-.046.063-.066" style="fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m370.277 257.215.942.535-.942-.535" style="fill:url(#e__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M213.938 171.387c-3.461 0-6.485 1.129-8.84 3.254l-.004-.004a.26.26 0 0 1-.031.027l-.645.629c-.02.02-.039.043-.063.066l.743.743c2.355-2.125 5.375-3.254 8.836-3.25 3.382 0 7.187 1.078 11.203 3.355l145.152 82.473.93-.93-.942-.535-145.14-82.469c-3.66-2.074-7.141-3.156-10.285-3.336a18.554 18.554 0 0 0-.914-.023" style="fill:url(#f__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M204.355 175.355c-2.91 3.079-4.628 7.86-4.628 14.051v.004c0-6.195 1.718-10.972 4.628-14.051v-.004" style="fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M204.355 175.359c-2.91 3.079-4.628 7.856-4.628 14.051v1.457c0-6.191 1.718-10.972 4.628-14.051l.743-.711-.743-.746" style="fill:url(#g__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m204.355 175.359.743.746v-.003l-.743-.743" style="fill:url(#h__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M429.473 294.82c.769 1.688 1.156 3.422 1.156 5.157v.007c0-1.738-.387-3.472-1.156-5.164" style="fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="m371.219 257.75-.93.93 49.859 28.332c6.332 3.597 9.887 8.238 10.481 12.965 0-1.735-.387-3.469-1.156-5.157-1.551-3.402-4.66-6.617-9.325-9.269l-48.929-27.801" style="fill:url(#i__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M430.629 299.992v.004c-.004 5.231-3.5 10.461-10.481 14.43l-48.929 27.801h-.004l.004.003 48.929-27.8c6.989-3.969 10.489-9.207 10.481-14.438" style="fill:#404040;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M430.629 299.996c-.594 4.738-4.149 9.375-10.481 12.973l-49.863 28.328.93.93h.004l48.929-27.801c6.981-3.969 10.477-9.199 10.481-14.43" style="fill:url(#j__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M199.727 410.621v.012-.012m.043 1.625v.024-.024m.003.047v.047-.047m0 .059c.579 10.273 6.165 16.207 14.067 16.242-3.426-.02-6.41-1.145-8.746-3.25v.004l-.028-.028c-.246-.222-.48-.457-.711-.699-2.625-2.777-4.281-6.937-4.582-12.269" style="fill:#404040;fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M199.727 409.105v1.528c0 .551.015 1.09.043 1.613v.024c0 .007 0 .015.003.023v.059c.301 5.332 1.957 9.492 4.582 12.269l.731-.734c-3.356-3.028-5.359-8.078-5.359-14.782m5.339 16.215.028.028c-.008-.012-.02-.02-.028-.028" style="fill:url(#k__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><path d="M370.285 341.297 225.137 423.77c-4.024 2.281-7.832 3.363-11.223 3.363-3.457 0-6.473-1.125-8.828-3.246l-.731.734c.231.242.465.477.711.699l.028.024c2.336 2.105 5.32 3.23 8.746 3.25h.074c3.391 0 7.199-1.082 11.223-3.364l146.082-83-.004-.003-.93-.93" style="fill:url(#l__playstore);fill-rule:nonzero;" transform="matrix(.13333 0 0 -.13333 -13.33 66.67)"></path><defs><linearGradient id="a__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="scale(-237.34) rotate(45 1.43 -2.487)"><stop offset="0" style="stop-color:#00a0ff;stop-opacity:1;"></stop><stop offset=".01" style="stop-color:#00a1ff;stop-opacity:1;"></stop><stop offset=".26" style="stop-color:#00beff;stop-opacity:1;"></stop><stop offset=".51" style="stop-color:#00d2ff;stop-opacity:1;"></stop><stop offset=".76" style="stop-color:#00dfff;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#00e3ff;stop-opacity:1;"></stop></linearGradient><linearGradient id="b__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-180 219.172 149.993) scale(241.97)"><stop offset="0" style="stop-color:#ffe000;stop-opacity:1;"></stop><stop offset=".41" style="stop-color:#ffbd00;stop-opacity:1;"></stop><stop offset=".78" style="stop-color:orange;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#ff9c00;stop-opacity:1;"></stop></linearGradient><linearGradient id="c__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-135 231.512 66.39) scale(321.851)"><stop offset="0" style="stop-color:#ff3a44;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#c31162;stop-opacity:1;"></stop></linearGradient><linearGradient id="d__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="scale(143.72) rotate(-45 4.786 .28)"><stop offset="0" style="stop-color:#32a071;stop-opacity:1;"></stop><stop offset=".07" style="stop-color:#2da771;stop-opacity:1;"></stop><stop offset=".48" style="stop-color:#15cf74;stop-opacity:1;"></stop><stop offset=".8" style="stop-color:#06e775;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#00f076;stop-opacity:1;"></stop></linearGradient><linearGradient id="e__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-180 219.172 149.993) scale(241.97)"><stop offset="0" style="stop-color:#ccb300;stop-opacity:1;"></stop><stop offset=".41" style="stop-color:#cc9700;stop-opacity:1;"></stop><stop offset=".78" style="stop-color:#cc8400;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#cc7d00;stop-opacity:1;"></stop></linearGradient><linearGradient id="f__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-135 231.512 66.39) scale(321.851)"><stop offset="0" style="stop-color:#cc2e36;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#9c0e4e;stop-opacity:1;"></stop></linearGradient><linearGradient id="g__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="scale(-237.34) rotate(45 1.43 -2.487)"><stop offset="0" style="stop-color:#008de0;stop-opacity:1;"></stop><stop offset=".01" style="stop-color:#008de0;stop-opacity:1;"></stop><stop offset=".26" style="stop-color:#00a7e0;stop-opacity:1;"></stop><stop offset=".51" style="stop-color:#00b8e0;stop-opacity:1;"></stop><stop offset=".76" style="stop-color:#00c4e0;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#00c7e0;stop-opacity:1;"></stop></linearGradient><linearGradient id="h__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-135 231.512 66.39) scale(321.851)"><stop offset="0" style="stop-color:#e0333c;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#ab0f56;stop-opacity:1;"></stop></linearGradient><linearGradient id="i__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-180 219.172 149.993) scale(241.97)"><stop offset="0" style="stop-color:#e0c500;stop-opacity:1;"></stop><stop offset=".41" style="stop-color:#e0a600;stop-opacity:1;"></stop><stop offset=".78" style="stop-color:#e09100;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#e08900;stop-opacity:1;"></stop></linearGradient><linearGradient id="j__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="rotate(-180 219.172 149.993) scale(241.97)"><stop offset="0" style="stop-color:#ffe840;stop-opacity:1;"></stop><stop offset=".41" style="stop-color:#ffce40;stop-opacity:1;"></stop><stop offset=".78" style="stop-color:#ffbc40;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#ffb540;stop-opacity:1;"></stop></linearGradient><linearGradient id="k__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="scale(-237.34) rotate(45 1.43 -2.487)"><stop offset="0" style="stop-color:#40b8ff;stop-opacity:1;"></stop><stop offset=".01" style="stop-color:#40b9ff;stop-opacity:1;"></stop><stop offset=".26" style="stop-color:#40ceff;stop-opacity:1;"></stop><stop offset=".51" style="stop-color:#40ddff;stop-opacity:1;"></stop><stop offset=".76" style="stop-color:#40e7ff;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#40eaff;stop-opacity:1;"></stop></linearGradient><linearGradient id="l__playstore" x1="0" y1="0" x2="1" y2="0" gradientUnits="userSpaceOnUse" gradientTransform="scale(143.72) rotate(-45 4.786 .28)"><stop offset="0" style="stop-color:#65b895;stop-opacity:1;"></stop><stop offset=".07" style="stop-color:#62bd95;stop-opacity:1;"></stop><stop offset=".48" style="stop-color:#50db97;stop-opacity:1;"></stop><stop offset=".8" style="stop-color:#44ed98;stop-opacity:1;"></stop><stop offset="1" style="stop-color:#40f498;stop-opacity:1;"></stop></linearGradient></defs></svg></a></div>
<br>
:+1: App Store (iOS):  <https://itunes.apple.com/us/app/nativescript-playground/id1263543946?mt=8&ls=1> ..!
<br>
:+1: Google Play (Android):  <https://play.google.com/store/apps/details?id=org.nativescript.play> ..!

# Developer : NaeLike เนไลก์

<img class="rounded" src="https://naelike.com/assets/upload/page/home/naelike.png" width="220" alt="NaeLike"> 
<img class="rounded" src="https://www.naelike.com/assets/upload/logo/logo-text-3.png" width="220" alt="NaeLike"> 

> Naelike เนไลก์

@เว็บไซต์ :+1: Web :  <https://naelike.com> ..! :shipit:
<br>
@ติดตาม :+1: Web :  <https://naelike.com/addmee> ..! :shipit:

TikTok :  <https://www.tiktok.com/@naelike6564>
<br>
Facebook :  <https://web.facebook.com/NaeLikePage>
<br>
Instagram :  <https://www.instagram.com/naelike_ig>
<br>

<a href="https://link.ckpzmc.xyz/dispnae"> 
   <img class="rounded" src="https://i.pinimg.com/originals/1a/9a/f1/1a9af177bdcd0bd93568e59bb7600cbe.png" width="120" alt="NaeLike"> 
   </br>
   <b class="fs-12">Discord คลิก..!</b> 
</a>

