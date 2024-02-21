# iOS/WatchOS Shortcuts

I have recently got into creating Shortcuts for iOS and WatchOS, especially those I can use with the Action Button. I have put the base Shortcuts at the top so you can create them first, and then create the menus below (if you wish).

# Base Shortcuts

## 🔗 Share Sheet

These are shortcuts you can use from the Share Sheet. They are just useful to have on hand. I did have more but I haven't got round to updating them...

| Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Cleanup URL` | Removes trackers from your links | [u/sharp-guru on Reddit](https://www.reddit.com/r/shortcuts/comments/loph8j/a_simple_shortcut_to_remove_tracking_tokens_from/) [My link](https://www.icloud.com/shortcuts/1de00d4cf4e94460818a0c0f75940060) |
| `Share SongWhip Link` | Use iOS's Share Sheet to share a universal URL | [u/jswelch01 on Reddit](https://www.reddit.com/r/shortcuts/comments/l6spo9/songwhip_share_sheet_shortcut_that_checks_url/) [My link](https://www.icloud.com/shortcuts/7d9a248bf707474c901e0c826f41fb28) |


## 🎵 Music

I am an Apple Music user, and sometimes have trouble sharing with others, so use the two SongWhip functions below. I also have the shortcut `Choose Replay List` to quickly add the auto-generated Apple Music Replay lists to my up next. I also create a playlist per month (starting in May 2019), so have the function `Monthly Playlists` function that allows me to quickly get my last 6 playlists and add them to my up next. Check the bottom notes for more details.

And of course `Shazam & Save` is especially great on an Apple Watch!

| Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Share SongWhip Link` | Use iOS's Share Sheet to share a universal URL | [u/jswelch01 on Reddit](https://www.reddit.com/r/shortcuts/comments/l6spo9/songwhip_share_sheet_shortcut_that_checks_url/) [My link](https://www.icloud.com/shortcuts/7d9a248bf707474c901e0c826f41fb28) |
| `Song.link Shortcut` | Get the currently playing song, get a universal URL and copy it to the clipboard| [Michael Moore on ShortcutsGallery](https://shortcutsgallery.com/shortcuts/song-link-apple-music-share/) [My link](https://www.icloud.com/shortcuts/e826d56e2d9c4b749799a50b88e32e34) |
| `Smart Play Music` | Checks whether you're playing anything before asking whether you want to start playback (and shuffled or not) | [Me!](https://www.icloud.com/shortcuts/d7751d810f754f1ea52a568c48acf97e)
| `Choose Replay List` | Automatically makes a list of all your Apple Music Replays and lets you choose one to add to your up next | [Me!](https://www.icloud.com/shortcuts/161d2dfaab5746708f884d12114af18c) |
| `This Year's Replay` | Automatically gets the current year's Apple Music Replay and plays it next | [Me!](https://www.icloud.com/shortcuts/d55b3ef2df0c43258a796fc73ea43e96) |
| `Monthly Playlists` | Automatically finds my monthly playlists and queues them (see notes below) | [Me!](https://www.icloud.com/shortcuts/81b6648f76a549d1a2c5cd10a22c9536) |
| `Shazam & Save` | Shazams a song and adds it to your music library | [Me!](https://www.icloud.com/shortcuts/4c54f4860e874224860b92c045d3e54d) |

Notes on `Monthly Playlists`:
- These are playlists I have been making for a while - I just make one for each month and add any songs I like to them
- If you would like to see the playlists you can view them on my profile [here](https://music.apple.com/profile/jamesjingyi)
- The formatting of the title is in the format `Playlist #x - Month YYYY`, I made this up before I made the shortcut and worked backwards
- If you are customising this yourself, you will want to change the start date from 1 May 2019 to whatever your first date is - if you would like help constructing syntax lemme know!

## 🔋 Batteries

Requires [AllMyBatteries](https://apps.apple.com/gb/app/allmybatteries-track-battery/id1621263412)

For this section, everything is designed to be set up as automations:
- AirPods Shortcuts are designed to be set up as automations on disconnect
- Watch Shortcuts are designed to be set up as automations that run at a set time each day
- The Logging Shortcut is designed to be an automation that runs at set times in the day (I used it to check whether I was having battery issues with my Watch)

Have a play with the result - I have an alert for AirPods and a Reminder for the Watch, but you can customise these!

| Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `AirPods Battery Reminder - Alert` | Shows an alert if your AirPods are less than 30% | [Me!](https://www.icloud.com/shortcuts/b3db0ae4b8be4e858dd27e1b0ceaa12d) |
| `Watch Battery Reminder - Reminder` | Adds a reminder to charge your Watch if it's less than 40% | [Me!](https://www.icloud.com/shortcuts/9fdc5e3c97914f288cfb45ecb77ff716) |
| `Watch Battery Log` | Logs your Watch's Battery and adds it to a Note | [Me!](https://www.icloud.com/shortcuts/59d2400956fe4faeaf9d37a5aded6378) |

## 🗓️ Calendar

u/bamfhacker made a great shortcut in [this thread](https://www.reddit.com/r/shortcuts/comments/a291m0/show_tomorrows_events/) which checks tomorrow's scheule, and I have adjusted it into four:

 Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Remaining Today` | Shows an alert that shows what events are remaining in the day | [Me!](https://www.icloud.com/shortcuts/ce71bd4d70c04a7ea6917e7b3081fd98) |
| `Today's Schedule` | Shows an alert that shows the events for that day (including previous ones) | [Me!](https://www.icloud.com/shortcuts/16b86fa680e64bacb9ac6912f77e7d5f) |
| `Tomorrow's Schedule` | Shows an alert that shows the events for tomorrow (including Birthdays) | [Me!](https://www.icloud.com/shortcuts/1032b6bf22c9423bae172d61cb709229) |
| `Tomorrow's Schedule With All Day` | Shows an alert that shows the events for tomorrow and all day events (including Birthdays) | [Me!](https://www.icloud.com/shortcuts/cfd9ce396452450eaf81a2397f3e4ca4) |

## 🧭 Navigation

I find it insufferable that you can't search for contacts within the Maps app, so I created this Shortcut so that you can search for a contact and get their address quickly:

 Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Open Directions` | Select a contact and get directions to them | [Me!](https://www.icloud.com/shortcuts/5553af311f6e4870b223d12c2069adab) |
| `Directions To —` | Designate a location and get instant directions to it | [Me!](https://www.icloud.com/shortcuts/05655ad44420407e8f973c7fa9501726) |
 
# 📋 Menus

## 📱 iPhone Menus

I use a combination of Focus Modes, device orientation and lock status (via [Actions](https://apps.apple.com/gb/app/actions/id1586435171)), and an Action Button + volume tap (thanks [Snazzy Labs!](https://www.youtube.com/watch?v=0bvHUvWI4TI)). They are then mapped through multiple Shortcuts to make the Action Button do the following:
- If the device is locked, launch the camera app
- If the device is landscape, launch the camera app
- If the Action Button is pressed and then within 500ms, a volume button is pressed, launch the camera app
- If the device is unlocked and portrait, launch a menu based on the Focus state

### Focus States

My Focus States automatically trigger throughout the day based on location, time, and other things like when I am connected to my car. I can then have customised menus based on the functions I might want to have in these. As I made functions I realised that the menus were becoming quite long, so I consolidated some of them into smaller menus. 

These are the current Focus States I have, and their respective actions:
- Work - Work Menu
- Sleep - Sleep Menu
- Music - Music Menu
- Cinema - Toggle Torch
- Driving - Driving Menu
- Presenting - Work Menu
- Home - Home Menu
- None - General Menu
To toggle between these, I use the `Action Button` shortcut.

### Device Orientation and Lock Status

To enable this further detail, in Settings, I set my Action Button to use the `Action Volume` shortcut (which is based off [Snazzy Labs's version](https://www.youtube.com/watch?v=0bvHUvWI4TI)), which uses `if` statements to first check for device orientation, then checks whether the volume button was pressed (to launch the camera), otherwise runs `Action Button` to show the relevant menu. 

### Menu Formatting and Emojis

As someone who likes to just quickly glance and see the main functions, I wanted to make it very easy to quickly find the function from a list. I use a combination of emojis and fomatting to text to achieve this. To achieve this difference, I had to use Unicode Sans Serif rather than Apple's built in font so that I can bold the text that I want. I use [YayText's website](https://yaytext.com/sans-serif/) to create these.

The format of each of my functions is:
`📱  —  𝗙𝘂𝗻𝗰𝘁𝗶𝗼𝗻 𝗌𝗎𝗉𝗉𝗈𝗋𝗍𝗂𝗇𝗀 𝗌𝗍𝗋𝗂𝗇𝗀` - Which is an emoji, two spaces, an em-dash, and then the function and the supporting string (formatted correctly)

I also hate how the curvature of the modals cuts into the bottom of menus on devices like the 15 Pro Max, so I use the following edited text for the bottom of each menu: ` ⁻ ᴰᴼᴺᴱ ⁻ `. This is not linked to any action so it just dismisses the menu.

### Menu Content

As I started creating lots of the menus, I realised that some of the funcitons were both repeated and also not commonly used, but I still wanted access to them. I therefore created a `Utility Menu` shortcut that can be run from any of the menus. It just presents another menu.

I also linked to other menus when it felt appropriate (e.g. my Home Menu allows you to bring up the Music Menu).

As a general rule, I create more shortcuts if a function gets too complex. This just allows me to diagnose problems easier, and repeat functions across multiple menus in an easier way (I'm not sure whether this is best practice or not).

Below are my shortcuts, but I'm not sure whether they actually are useful as they might break when you import them, but hopefully the syntax helps:

| Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Action Volume` | Runs a different shortcut if you press a volume button after you press the action button (also includes device orientation and lock status in mine) | [OG - Snazzy Labs](https://www.youtube.com/watch?v=0bvHUvWI4TI) [Mine](https://www.icloud.com/shortcuts/fb67beca554d41059dd6fd44ccddbdb7) |
| `Action Button` | Runs a Shortcut based on the current Focus Mode | [OG - u/kylewhirl](https://www.reddit.com/r/shortcuts/comments/16gyf0m/created_a_shortcut_that_changes_the_action_button/) [Mine](https://www.icloud.com/shortcuts/1a9d01d8cb3d443fbb965d9acc4740d0) |
| `Utility Menu` | My Utility Menu | [Me!]](https://www.icloud.com/shortcuts/34ceb5bec2424660a5de9ffed80c0c27) |
| `Work Menu` | My Work Menu | [Me!](https://www.icloud.com/shortcuts/70033107306646e9b86953e8138ef761) |
| `Sleep Menu` | My Sleep Menu | [Me!](https://www.icloud.com/shortcuts/c2c0ca39cede47b48f7e0fc172cd8423) |
| `Home Menu` | My Home Menu | [Me!](https://www.icloud.com/shortcuts/1723e01456d84bf5b1c208b546146e2a) |
| `General Menu` | My General Menu | [Me!](https://www.icloud.com/shortcuts/a356fdd9e3d64b099b0981189ed92e47) |
| `Music Menu` | My Music Menu | [Me!](https://www.icloud.com/shortcuts/42d736ddc4aa487486a43a5c9ee75bbc) |
| `Driving Menu` | My Driving Menu | [Me!](https://www.icloud.com/shortcuts/2b2f7aa148804b4aa3bdd6d25a0d89d3) |

## ⌚️ Watch Menus

I wanted to emulate the same menus for my Watch, but since there is less space and the functions are a bit more limited, I created different menus.

### Shortcut Sync

I have had some issues with synchronising shortcuts to my Watch, especially if I have just made them. I have the following assumptions:
- Of course you have to have selected 'Show on Watch', but this doesn't immediately sync it
- You can run shortcuts that are not ticked as 'Show on Watch' using other shortcuts
- I think all syncing actually happens through iCloud rather than directly from the iPhone to the Watch (not sure though)
- The created or edited shortcut needs time to sync with iCloud first, then it can go to the Watch
- This sync seems to not happen as quickly (or at all) on cellular connections - Wifi is much better
- When selecting the shortcut to use for the Action Button, even if you see it in the Shortcuts app on the Watch, it doesn't immediately appear in the Settings to select (both on your Watch and iPhone) - you just have to wait a while! 

### Shortcuts

I have a similar `Action Button AW` function to my phone, but I have less menus on the Watch so lots of them point to the same places. This shortcut is based on the [iPhone `Action Button` shortcut from u/kylewhirl](https://www.reddit.com/r/shortcuts/comments/16gyf0m/created_a_shortcut_that_changes_the_action_button/).

Any menus have been adapted with shorter titles, and with the relevant Watch functions (e.g. the Flashlight has to be remapped). I also added a 'Back' option that goes back to the previous menu since it's harder to use without one on the Watch compared to the phone. 

Note: I would love to be able to start a voice recording from a shortcut, but you can't start it from the Watch, you can only open the Voice Memos app, and then you have to tap the 'Record' button yourself... 

| Shortcut name | Description | Link/Source |
| :----------- | :----------- | :----------- |
| `Action Button AW` | Runs a Shortcut based on the current Focus Mode | [Mine](https://www.icloud.com/shortcuts/0312af3fd38542ca89fc6da1f5e383f7) |
| `Utility Menu Watch` | My Watch Utility Menu | [Me!](https://www.icloud.com/shortcuts/5e57a40f92a64c6bbfa25e9070af256a) |
| `Music Menu Watch` | My Watch Music Menu | [Me!](https://www.icloud.com/shortcuts/4c3c15b490ef470294d5518e73f4af7c) |
| `Home Control Watch` | My Watch Home Control Menu | [Me!](https://www.icloud.com/shortcuts/0437193c4a8842cda6751cf4a69187fe) |
| `Always On AWU` | Toggle the Always On Display (tested on Ultra 2) | [My link*](https://www.icloud.com/shortcuts/fcdd5f1c79e6443792a28482efe1308e) |

\* I found this somewhere but I can't find it again, sorry. I have made my own link for now.





