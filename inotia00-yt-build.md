# v4.9.1
YouTube
- feat(YouTube): add support versions `19.21.40`

- feat(YouTube): add `Enable OPUS codec` patch

- feat(YouTube): add `Miniplayer` patch (Replaces `Enable tablet mini player` patch)

- feat(YouTube): change patch name `Enable minimized playback` to `Remove background playback restrictions`

- feat(YouTube): merge patch from RVX/anddea:
- feat(YouTube): Add `Custom Shorts action buttons` patch (Replaces `Shorts outline icon` patch)
- feat(YouTube): Add `Visual preferences icons` patch
- feat(Translations): Add patch options to remove languages and provide own translation / strings.xml
- feat(YouTube/Settings): Add search bar in settings

- feat(YouTube): proper nouns and clarity of in-app strings

- feat(YouTube): split `Custom header` for YouTube patch from the `Custom branding icon` for YouTube patch

- feat(YouTube/Hide action buttons): add `Disable Like and Dislike button glow` setting

- feat(YouTube/Hide ads): add Close fullscreen ads settings

- feat(YouTube/Hide feed components): separate the `Hide low views video` settings from `Hide recommended videos` settings 

- feat(YouTube/Hide player flyout menu): add `Hide quality menu header` 

- feat(YouTube/Settings for YouTube): unify toast key format

- feat(YouTube/Shorts components): add `Hide Super Thanks button` settings 

- feat(YouTube/Shorts components): remove `Hide disabled comments button` setting

- feat(YouTube/Swipe controls) add Enable swipe to change video setting (YouTube 19.19.39+)

- fix(YouTube/Hide ads): toasts are shown multiple times 

- fix(YouTube/Hide feed components): `Hide Visit store button` setting does not work 

- fix(YouTube/Litho filter): do not obfuscate ConversionContext

- fix(YouTube/Return YouTube Channel Name): correctly handle exception 

- fix(YouTube/Return YouTube Dislike): no longer hides glow animation 

- fix(YouTube/Spoof client): add missing side effects 

- fix(YouTube/Spoof client): first video is always spoofed as a client of Shorts, Clips

- fix(YouTube/Spoof client): restore playback speed menu when spoofing to an iOS, Android TV, Android Testsuite client
- feat(YouTube/Translations for YouTube): update translation
