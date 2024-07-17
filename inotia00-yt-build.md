# v4.10.2
YouTube
- feat(GmsCore support): add patch options `GmsCoreVendorGroupId`: com.mgoogle, `CheckGmsCore`: https://github.com/inotia00/VancedMicroG/releases/Latest
- feat(YouTube): separate the `Bypass image region restrictions` patch from the `Alternative thumbnails` patch
- feat(YouTube/Player components): `Hide player popup panels` setting now hides the products panel
- feat(YouTube/Swipe controls): add `Enable save and restore brightness` setting
- fix(YouTube): restart dialog that appears when the user first installs the app restarts the app too quickly, so the new layout is not fetched (add a restart delay to resolve issues)
- fix(YouTube/Alternative thumbnails): handle more thumbnails
- fix(YouTube/Hide feed components): `Hide carousel shelf` setting sometimes hides the Watch history in the You tab
- fix(YouTube/Hide feed components): do not hide flyout menu
- fix(YouTube/Overlay buttons): change default value
- revert(YouTube/Hide feed components): `Hide expandable chip under videos` setting does not work (as support version has been rolled back to YouTube `19.16.39`)
- feat(YouTube/Translations for YouTube): update translation
