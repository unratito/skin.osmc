**Changes**

_New_
- add option to adjust dim factor of unfocused art 
- add option for additional text highlight
- add channel icon to PVR info dialog
- add new widget options (through skin.helper.widgets script)
- add AURO media flags (based on file naming)
- add new cover art highlighting (size change depending on focused state)
- add new movie collection indicator

_Improved_
- add more weather information to weather window
- refine music icons
- remove watched status for music items (in views and widgets)
- adjust representation of object based audio codec tags
- refine positioning and scaling of media tag icons
- adjust viewtype 55 for music and add-ons to match viewtype 53 for movies and TV shows
- improve highlight color of selected text
- change appearance of all progress icons to round shape
- add no dimming of cover art
- dim watched and collection indicator depending on cover dimming setting
- update watched overlay icon to match appearance of new movie collection indicator
- add current control ID to debug overlay
- change overlay color setting to match appearance of background color setting

_Fixed_
- fix scrollbar in music navigation
- fix item widths in various windows
- fix weather window
- fix focused items in addon list view (e.g. YouTube)
- fix PVR views to add scrolling and adapt season/episode representation
- fix widget details label for PVR items (when using skinshortcuts script)
- fix scrollbar in file browser

**Changelog v17.0.5**

AddonBrowser.xml:
- add underline highlight to focusedlayout

Custom_Overlay_Debug.xml:
- add current control ID to debug overlay

Defaults.xml:
- add focus textures with colordiffuse variable

DialogAudioDSPManager:
- add underline highlight to focusedlayout

DialogButtonMenu.xml:
- add underline highlight to focusedlayout

DialogContextMenu.xml:
- add focus texture with colordiffuse variable

DialogFavourites:
- add underline highlight to focusedlayout

DialogFullScreenInfo.xml:
- override button highlight to never show

DialogMediaSource.xml:
- add underline highlight to focusedlayout

DialogVideoInfo.xml:
- change label of ratings to "rating"

DialogPVRChannelGuide:
- add underline highlight to focusedlayout

DialogPVRChannelManager:
- add underline highlight to focusedlayout

DialogPVRChannelsOSD:
- add underline highlight to focusedlayout

DialogPVRGroupManager:
- add underline highlight to focusedlayout

DialogPVRInfo.xml:
- add channel icon to PVR info dialog
- fix alligning
- fix missing colons

DialogSelect:
- add underline highlight to focusedlayout

DialogSubtitles:
- add underline highlight to focusedlayout

DialogVideoInfo.xml:
- add underline highlight to focusedlayout of cast list

FileBrowser:
- add underline highlight to focusedlayout
- fix scrollbar (onright, pagecontrol)

FileManager:
- add underline highlight to focusedlayout

Font.xml:
- add new Font73 with bold style

Home.xml:
- add onload to set NFDimOpac skin string to 100

Include_Home_OSMC.xml:
- add underline highlight to focusedlayout

Includes_Widgets.xml:
- adjust positioning and size of focused and non-focused widget images for new cover art highlighting

Includes.xml:
- change formatting and position of media tag icons

LoginScreen.xml:
- add underline highlight to focusedlayout

MusicOSD.xml:
- make visualization settings buttons conditionally visible

MusicVisualisation.xml:
- fix width of next playing fadelabels

MyMusicNav.xml:
- fix conditional visibility of scrollbar
- adjust wall scrollbar for adjusted viewtype55

MyMusicPlaylistEditor.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

MyPrograms.xml:
- adjust wall scrollbar for adjusted viewtype55

MyPVRChannels.xml:
- add underline highlight to focusedlayout

MyPVRGuide.xml:
- use variable "SEListView", if season and episode are needed
- add scrolling to long PVR titles

MyPVRRecordings.xml:
- add underline highlight to focusedlayout

MyPVRSearch.xml
- add underline highlight to focusedlayout

MyPVRTimers.xml
- add underline highlight to focusedlayout

MyVideoNav.xml:
- adjust wall scrollbar for adjusted viewtype53

MyWeather.xml:
- fix day labels
- match forcast to correct day
- replace localize for "now" with translatable one
- add more weather information (humidity/precepitation, sunrise/sunset)

script-skinshortcuts-static.xml:
- replace DiffusePosterNF with variable
- adjust positioning and size of focused and non-focused widget images for new cover art highlighting
- update watched overlay icon
- replace OverlayColorNF by DiffusePosterNF variable

script-skinshortcuts.xml:
- add underline highlight to focusedlayout

Settings.xml:
- change togglebutton layout (increase button hight, reduce item gap)

SettingsCategory.xml:
- add focus textures with colordiffuse variable to buttons

SettingsProfile.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

SettingsSystemInfo.xml:
- fix button width
- add focus textures with colordiffuse variable to buttons

SkinSettings.xml:
- rewrite window to accomodate highlighting and immitate behaviour of other settings windows
- add addon install command for script.skin.helper.service and script.skin.helper.widgets for new widget option when customizing main menu through script.skinshortcuts
- add "0" state of "Adjust non-focus dim opacity" skin setting
- change overlay color setting to match appearance of background color setting

SmartPlaylistEditor.xml:
- add underline highlight to focusedlayout
- add focus textures with colordiffuse variable to buttons

Variables.xml:
- add DiffusePosterNF variable (used for new cover art dim option)
- add focus variables (used for new highlighting option)
- cleanup mediaImages variable
- remove now unused Day variables
- adjust StatusOverlay/StatusOverlayWide variables to hide watched status for music
- add lines breaks to PVRDescription variable
- add new addon-skinhelperwidgets variable for new recommended addon in skin settings section
- add AURO detection in file names to audio variable
- change language code formatting to capitalized in audiolanguage and subtitlelanguage variable
- change SelectedColor to new, improved color
- add "0" condition to DiffusePosterNF variable
- change OverlayColor variable to accommodate the overlay color setting change

Viewtype50.xml:
- add underline highlight to focusedlayout
- use new Font73 for focused label
- remove bold style from focused label

Viewtype51.xml:
- add underline highlight to focusedlayout
- add new collection icon
- replace OverlayColorNF by DiffusePosterNF variable

Viewtype52.xml:
- replace DiffusePosterNF with variable
- add new collection icon
- update watched overlay icon
- replace OverlayColorNF by DiffusePosterNF variable

Viewtype53.xml:
- replace DiffusePosterNF with variable
- adjust view for new cover art highlighting
- add new collection icon
- update watched overlay icon
- replace OverlayColorNF by DiffusePosterNF variable

Viewtype54.xml:
- fix width of Artist info fadelabel
- add underline highlight to focusedlayout

Viewtype55.xml:
- replace DiffusePosterNF with variable
- show title in wall view for addons/games as well
- adjust view for new cover art highlighting

defaults.xml:
- remove DiffusePosterNF color
- change SelectedColor to new, improved color

strings.po:
- add new localizes for new skin settings buttons (#31104 and #31105)
- add new localize for new recommended addon in skin settings section (#31106)

Textures.xbt:
- repack content of media folder after adding new focus textures
- repack content of media folder after adding new music icons
- repack content of media folder after adding new media tag icons
- repack content of media folder after adding new progress icons
- repack content of media folder after adding new collection icon and after changing watched status icons

overrides.xml:
- add new widget option for skin.helper.widgets script

template.xml:
- replace DiffusePosterNF with variable
- fix widget details label for PVR items
- add conditions to prevent use of PVR widget titles for recent movies widget
- adjust positioning and size of focused and non-focused widget images for new cover art highlighting
- update watched overlay icon
- replace OverlayColorNF by DiffusePosterNF variable

addon.xml:
- bump version to 17.0.5