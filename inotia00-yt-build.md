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
