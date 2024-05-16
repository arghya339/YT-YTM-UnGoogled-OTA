# v4.7.1
YouTube
- feat(YouTube): add support versions 19.03.36 ~ 19.16.39
- feat(YouTube): add Change shorts repeat state patch
- feat(YouTube): add Disable auto audio tracks patch
- feat(YouTube): change patch name Ambient mode switch to Ambient mode control
- feat(YouTube): change patch name Change player flyout panel toggles to Change player flyout menu toggles
- feat(YouTube): change patch name Disable shorts on startup to Disable resuming shorts on startup
- feat(YouTube): change patch name Hide description components to Description components
- feat(YouTube): change patch name Hide navigation bar components to Navigation bar components
- feat(YouTube): change patch name Hide shorts components to Shorts components
- feat(YouTube): change patch name Hide suggested video overlay to Fix suggested video end screen
- feat(YouTube): change patch name MicroG support to GmsCore support
- feat(YouTube): integration of Hide suggestions shelf patch into Hide feed components patch
- feat(YouTube): remove support versions 18.25.40, 18.27.36
- feat(YouTube): remove Add splash animation, Enable song search, Enable language switch, Force opus codec, Force video codec, Hide animated button background, Spoof player parameters patch
- feat(YouTube): Append time stamps information, Custom seekbar color, Enable seekbar tapping, Enable new thumbnail preview, Hide seekbar, Hide time stamp patches have been integrated into Seekbar components patch
- feat(YouTube): Custom playback speed, Disable HDR video, Default video quality, Default playback speed, Enable old quality layout, Spoof device dimensions patches has been integrated into Video playback patch
- feat(YouTube): Custom player overlay opacity, Disable speed overlay, Hide auto player popup panels, Hide channel watermark, Hide crowdfunding box, Hide end screen cards, Hide filmstrip overlay, Hide info cards, Hide seek message, Hide suggested actions, Hide suggested video overlay patches has been integrated into Player components patch
- feat(YouTube): Disable pip notification, Disable update screen, Hide account menu, Hide cast button, Hide floating microphone, Hide handle, Hide snack bar, Hide tooltip content patches has been integrated into Hide layout components patch
- feat(YouTube): Enable bottom player gestures patch has been integrated into Swipe controls patch
- feat(YouTube): Enable compact controls overlay, Force fullscreen, Hide autoplay preview, Hide end screen overlay, Hide fullscreen panels, Landscape mode, Quick actions components patches has been integrated into Fullscreen components patch
- feat(YouTube): Enable tablet navigation bar, Hide navigation label, Hide navigation buttons patches have been integrated into Hide navigation bar component patch
- feat(YouTube): Hide autoplay button, Hide captions button, Hide collapse button, Hide music button, Hide previous next button patches has been integrated into Hide player buttons patch
- feat(YouTube): Hide general ads, Hide video ads have been integrated into Hide ads patch
- feat(YouTube): Hide search term thumbnail, Hide toolbar button, Hide trending searches, Hide voice search button, Premium heading patches has been integrated into Toolbar components patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add Always expand panel and Disable description interaction settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add Disable rolling number animations settings
- feat(YouTube/Description components): Hide game sections, Hide music sections, Hide place sections settings have been integrated into Hide suggestions sections settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add Enable modern mini player settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add Hide fullscreen ads settings
- feat(YouTube/Hide ads): remove Close interstitial ads settings
- feat(YouTube/Hide feed components): add Channel tab filter settings
- feat(YouTube/Hide feed components): add Hide feed captions button settings
- feat(YouTube/Hide feed components): add Hide playables settings
- feat(YouTube/Hide feed components): remove Hide gray description settings
- feat(YouTube/Hide feed components): remove Hide store tab settings
- feat(YouTube/Hide feed components): remove Select method to hide shelves settings in Hide carousel shelf settings
- feat(YouTube/Hide feed components): Hide carousel shelf setting no longer checks navigation index
- feat(YouTube/Hide feed components): Hide suggestions shelf setting has been renamed to the Hide carousel shelf setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): Hide YouTube settings menu settings
- feat(YouTube/Hide player flyout menu): add Hide picture-in-picture menu settings
- feat(YouTube/Overlay buttons): add Hide fullscreen button settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore Tap and hold to toggle pause after repeat states features
- feat(YouTube/Player components): add Skip autoplay countdown settings
- feat(YouTube/Player components): add Speed overlay value settings
- feat(YouTube/Seekbar components): add Hide seekbar chapters settings
- feat(YouTube/Seekbar components): add Replace time stamp action settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove Double back timeout settings
- feat(YouTube/Shorts components): add Return shorts channel name settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version 17.33.42
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add Enable wide search bar with header settings
- feat(YouTube/Toolbar components): add Replace create button settings
- feat(YouTube/Video playback): add Replace software AV1 codec and Reject software AV1 codec response settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on YouTube v18.29.38
- fix(YouTube/Description components): Hide shopping links settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): Hide channel profile links settings not worked due to A/B tests
- fix(YouTube/Hide comments component): Hide thanks button setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): Hide subscriptions channel section setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): Hide captions button setting does not require set layout params
- fix(YouTube/Hide player buttons): Hide collapse button setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the suggested video end screen, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): Hide comment button settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in Patch Information is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens Import/Export settings, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): Restore old quality layout settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation

# v4.8.0-dev.2
YouTube
- fix(YouTube/Hide feed components): Hide carousel shelf setting sometimes hides the library shelf
- fix(YouTube/Hide layout components): Hide YouTube settings menu setting does not hide some settings
- fix(YouTube/Return shorts channel name): add fallback for Fetch from rss feed

# 4.8.0-dev.4
YouTube
- fix(YouTube/Hide layout components): add method to hide settings with whitelist
- fix(YouTube/Hide suggested video end screen): change the summary of settings to be clearer
- fix(YouTube/Return YouTube Dislike): wrong video id is used in shorts
- fix(YouTube/SponsorBlock): pressing the fine adjustment buttons skips to the end of the video while creating a new SponsorBlock segment
- fix(YouTube/Video playback): default video quality applies even when video is playing

# 4.8.0-dev.5
YouTube
- feat(YouTube/Spoof format stream data): improve hook method, fetch to ANDROID_TESTSUITE client
- fix(YouTube): Ambient mode control patch does not work correctly on certain versions
- rollback(YouTube/Hide layout components): remove method to hide settings with whitelist

# v4.8.0-dev.6
YouTube
- feat(YouTube): clarify in-app strings
- feat(YouTube/Hide feed components): add Hide videos by duration and Hide videos by views count greater than specified value setting
- fix(YouTube/Description components): crash occurs when the title of the engagement panel is null
- fix(YouTube/Hide action buttons): some action buttons are not hidden properly
- fix(YouTube/Hide feed components): Hide mix playlists setting hides components in channel profile
- fix(YouTube/Return YouTube Dislike): dislike count sometimes not shown in Shorts
- fix(YouTube/Spoof format stream data): some Uris are not hooked
- fix(YouTube/Spoof test client): spoofing does not work correctly when the Spoof app version setting is turned on
- fix(YouTube/Video playback): default video quality does not apply to shorts
