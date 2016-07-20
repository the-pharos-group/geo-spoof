# GEO SPOOF
> Spoof your iOS device GPS location for any app on your phone that uses GPS
>

![Example](./example.gif)

## Features

* Jump to places with [Algolia Places](https://community.algolia.com/places/) search :rocket:
* Switch between different speed presets
* Total distance counter 
* Current speed counter
* Autopilot walk / subway & teleport

## Requirements

* Xcode installed
* An iOS device connected to your Mac via USB

## How-to run

1. Connect to your Mac via USB
2. Start the `pokemongo-webspoof` app, it will start also Xcode
3. Rename the Bundle Indentifer to something unique and different
4. Build & run Xcode project on your connected iPhone
5. Check the `Auto update Xcode location` in the app when everything is running
6. Go back to Xcode, click into menu Debug -> Simulate Location -> pokemonLocation ( see hint at [#5:comment](https://github.com/iam4x/pokemongo-webspoof/issues/5#issuecomment-233739078) )
7. And voilà, you can move with the arrows key and see your character move

**NOTE:** You can also use your keyboard arrows to move on the map 👍

## How-to Update

1. Remove `pokemongo-webspoof.app` from authorized app to Accessibility
  * (System Preferences -> Security & Privacy -> Privacy Tab -> Accessibility)
2. Delete `pokemongo-webspoof.app` from your computer
3. Download latest release
4. Add back new `pokemongo-webspoof.app` to authorized app to Accessibility
  * (System Preferences -> Security & Privacy -> Privacy Tab -> Accessibility)

## Develop

* Download nodejs^6 (https://nodejs.org/en/)
* `$ git clone git@github.com:iam4x/pokemongo-webspoof.git`
* `$ cd pokemongo-webspoof && npm install`
* `$ npm run dev`

Happy hacking 👍

## Credits

* [Pokemon-Go-Controller](https://github.com/kahopoon/Pokemon-Go-Controller) for first proof of concept
* @Kampfgnom for [his applescript](https://github.com/kahopoon/Pokemon-Go-Controller/issues/29#issue-165194926)
