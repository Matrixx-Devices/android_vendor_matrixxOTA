# 17-February-2025
====================
     02-17-2025
====================

   * device/google/tangorpro
d988162 tangorpro: Disabled Artifact Path Requirements
15b00d7 tangorpro: Nuke HBM
cc82dc8 tangorpro: device supports face unlock
03826f1 tangorpro: Included Specific Build Flags
28eb5e1 tangorpro: Initialize Matrixx

   * packages/apps/Twelve
b503c04 Twelve: Make player/mediaLibrarySession lateinit
5d265a0 Twelve: Reformat code

   * vendor/MatrixxOTA
fe10b8e Merge pull request #276 from Lowxorx/15.0
06a32c4 mondrian: 10.2.0 release

   * vendor/google/tangorpro
69104eb tangorpro: Removed DeviceIntelligenceNetworkPrebuilt
24a9da8 tangorpro: Nuke HBM

====================
     02-16-2025
====================

   * device/qcom/sepolicy-legacy-um
ff381799 sepolicy: Add default permission for aidl hal_bootctl

   * packages/apps/Aperture
59013c8 Aperture: Update kotlin to 1.9.23
759f8d0 Aperture: Update gradle{,w} to 8.12
0e49f58 Aperture: Update ZXing-C++ to 2.3.0
62bc27b Aperture: Update CameraX to 1.5.0-alpha05
39a00a1 Aperture: Ensure secure URIs are inserted in order
4fc2193 Aperture: Update kotlin to 1.9.10

   * packages/apps/DeskClock
296e428c0 DeskClock: Convert ListPreferences to SimpleMenuPreferences
5ddac9586 DeskClock: Remove the summaries for AM/PM and bold text
f0f776a74 DeskClock: Hide or disable some screensaver settings
713a91649 DeskClock: Fix formatting in ScreensaverSettingsActivity

   * packages/apps/Glimpse
a0ad138 Glimpse: Split ACTION_REVIEW from ACTION_REVIEW_SECURE

   * packages/apps/Jelly
1f5f1bc Jelly: Save user agreement about protected media

   * packages/apps/Twelve
1120101 Twelve: Handle empty resumption playlist
2a9b749 Twelve: Readd round icon attribute
1e4626b Twelve: Set wake mode to network
7c4ac24 Twelve: Tie CoilBitmapLoader to service scope

   * vendor/MatrixxOTA
35240f0 Merge pull request #275 from ZorEl212/15.0
1c50ebe ginkgo: 11.2.0 release
7c5a798 Matrixx: Update new IDs and push OTA [BOT]
0dfa7be Merge pull request #273 from alanpdk/15.0
dae2bf8 sky: v11.2.0 release

====================
     02-15-2025
====================

   * android
1089944 manifest Track more repos from our org - android_packages_modules_Bluetooth - android_packages_services_Telecomm - fix path for fwbase tracking

   * art
a44294a580 Update boot image and system server profiles [M80C35P56S0PP]

   * hardware/interfaces
7d7ac396db Merge 'lineage-22.1' into 15.0
6d4d419194 cec: Don't spam "Machine is not on the network"

   * hardware/lineage/interfaces
ed17ff3 libperfmgr: Only throw DisplayIdle errors if we support it

   * packages/apps/Aperture
066ea34 Automatic translation import

   * packages/apps/AudioFX
02916e7 Automatic translation import

   * packages/apps/Camelot
23242a1 Automatic translation import

   * packages/apps/Catapult
c114091 Automatic translation import

   * packages/apps/Contacts
77afb19ff Automatic translation import

   * packages/apps/DeskClock
3db9ea707 Automatic translation import

   * packages/apps/Etar
578b82a5 Automatic translation import

   * packages/apps/FMRadio
7f5188d Automatic translation import

   * packages/apps/FlipFlap
fe2abce Automatic translation import

   * packages/apps/Glimpse
d47de86 Automatic translation import

   * packages/apps/Jelly
3f4c549 Jelly: Include assets
525b66c Automatic translation import

   * packages/apps/Profiles
7455e65 Automatic translation import

   * packages/apps/Recorder
8f65896 Automatic translation import

   * packages/apps/Twelve
38aff6a Automatic translation import
4edf7e3 Twelve: LocalDataSource: Stop pretending we can have artist thumbnails
69f3c76 Twelve: BaseMediaItemView: Simplify thumbnail handling
53ccfe0 Twelve: Navigate safely!
254cec7 Twelve: Ensure all media items have fallback titles

   * packages/providers/DownloadProvider
be8b0fb7 Automatic translation import

   * packages/resources/devicesettings
8624d14 Automatic translation import

   * vendor/MatrixxOTA
ff9dfbd Matrixx: Update new IDs and push OTA [BOT]
bba2601 Merge pull request #272 from CuriousNom/15.0
df10a7a pipa: Update v11.2.0
f10101e Matrixx: Update new IDs and push OTA [BOT]
5a2fa8c Merge pull request #271 from tanvirr007/15.0
bceda16 spes: Update to v11.2.0 [15/02/2025]

   * vendor/crowdin
fef707d Automatic translation import

   * vendor/qcom/opensource/commonsys/fm
b38a391 Automatic translation import

====================
     02-14-2025
====================

   * bootable/recovery
9459e699 Revert "minui: Import graphics_drm fix from QSSI 13"

   * device/qcom/sepolicy_vndr/legacy-um
87be962ff sepolicy: NFC: Add support for snxxx AIDL service

   * device/qcom/sepolicy_vndr/sm8450
54ee7c8f8 sepolicy: NFC: Add support for snxxx AIDL service

   * lineage/scripts
38d1654 reuse_helper: Handle kotlin files

   * packages/apps/Jelly
68e9e9f Jelly: Handle MediaSession For BackgroundShortcut
0d0d674 Jelly: Background Shortcuts

   * packages/apps/TvSettings
d6b23f1f2 TvSettings: Support two button mute

   * packages/apps/Twelve
8e70bf3 Twelve: LocalDataSource: `/audio/albumart/<album_id>` exists too
1cd5d90 Twelve: LocalDataSource: Use hidden album art database
62db55b Twelve: Switch back to vendored material
33444d7 Twelve: Use a custom BitmapLoader for our service
472b00e Twelve: SubsonicDataSource: Use media item builders
8690156 Twelve: Simplify media item to data source and media type querying
f010219 Twelve: Use `ProviderIdentifier` for all fragment arguments
59cea6d Twelve: Hide trailing view for local provider

====================
     02-13-2025
====================

   * art
7aabdb7f04 Improve cleanup robustness after adb push failures.
035d8f4b6a Potential buffer overflow in environment local storage

   * device/google/atv
66aed86 Revert "atv: sepolicy: public: Pull in hal_client_domain rule"

   * frameworks/native
75d0546f48 Update otapreopt_script to support Async Pre-reboot Dexopt.

   * packages/apps/Twelve
a7af174 Twelve: Media item builders!
32ff491 Twelve: Use Album thumbnail as Audio thumbnail
b5597d7 Twelve: Lowercase cursor column names
1a2d65a Twelve: Fix double .px in MAX_THUMBNAIL_SIZE

   * vendor/MatrixxOTA
f0b583f fix salaa instruction
f3239e6 Matrixx: Update new IDs and push OTA [BOT]
8efaafd Merge pull request #269 from Mayuresh2543/15.0
0770a32 stone: v11.2.0 release
87c7ef1 Matrixx: Update new IDs and push OTA [BOT]
9796c92 Merge pull request #268 from EvilAnsh/15.0
30f2572 salaa: v11.2.0 release
f5d798a Matrixx: Update new IDs and push OTA [BOT]
7d7faab Merge pull request #267 from tanvirr007/15.0
0ac1e28 spes: Update to v11.2.0 [13/02/2025]
d791667 Matrixx: Update new IDs and push OTA [BOT]
9bc0853 Merge pull request #265 from Arijit78/15.0
4bc75bd whyred: 13/02/2025 Update

====================
     02-12-2025
====================

   * build/blueprint
e29c960 Use pool for mutatorContext and transition contexts
633ab9e Optimize proptools.CalculateHash allocations

   * device/google/atv
7beb6ac atv: sepolicy: public: Pull in hal_client_domain rule

   * packages/apps/Launcher3
4878c9ee72 New Crowdin updates (#480)
68c38d1e91 Launcher3: Fix up jank with navbar long press
146ead4ca0 Launcher3: Add Circle To Search [1/2]
76d9a06ecc Launcher3: Add a toggle for long press on navbar to search [2/3]
5f53ebfc7b Launcher3: Implement long press nav bar to search gesture
e3f9b4652e Revert "Launcher3: Add Circle To Search"
6b479bd9cd Launcher3: Update folder preview and background color
753d9e3abd New Crowdin updates (#477)
93c717ccd0 Launcher3: Remove all_apps_search_bar_content_overlap on tablets
802c9b3cb5 Launcher3: Update lens intent in QSB
149717a398 New Crowdin updates (#472)
4c78038bc3 fixup! Launcher3: Allow widgets to have 1 row as minimum size
361bebc0e8 fixup! Launcher3: Implement hidden & protected apps
044b7d85c5 Revert "Launcher3: Hidden & Protected Apps: Make first app fully visible"
bf72491d71 fixup! Launcher3: Allow hiding top shadow on statusbar
95a8708426 Launcher3: Keep clear-all button from being disabled
c50e0e9864 Launcher3: Fix upstream bug with dots enabled (#5167)
213d4e3229 Revert "Launcher3: Never add hotseat to visible elements for app state"
039ec8b68d Launcher3: Fix taskbar crash when disabled on fold devices
bb21e2702e Launcher3: Hide app search results of profiles in quiet mode
b43f8303c0 Launcher3: QsbContainerView: Allow configurable widgets
ae105b316d Launcher3: Do not leak preference change listener
a4d2faafae Merge pull request #5 from kde-yyds/work-blur-background-at-app-launch

   * packages/apps/crDroidSettings
5d7b3c48 matrixx: Add about Matrixx

   * vendor/MatrixxOTA
6b6c88f Matrixx: Update new IDs and push OTA [BOT]
0db948b Merge pull request #264 from drishal/15.0
5f2c88c Pong: Feb update
185c5e2 Matrixx: Update new IDs and push OTA [BOT]
12cb6f1 Merge pull request #263 from thepriyanshujangid/15.0
1c27836 Redwood: v11.2 Feb SPL update
413db22 Matrixx: Update new IDs and push OTA [BOT]
7914636 Merge pull request #262 from royweisfeld/15.0
b9d80c5 garnet: Updated to v11.2.0
96995d4 Matrixx: Update new IDs and push OTA [BOT]
93fc05d Merge pull request #261 from Arijit78/15.0
78c1a85 whyred: 11.2 release

   * vendor/certification
6b49d4f certification: update to latest Baklava beta (#4)

====================
     02-11-2025
====================

   * device/qcom/sepolicy_vndr/legacy-um
d929ad85c sepolicy_vndr: allow sensors HAL to do binder call to system_server

   * device/qcom/sepolicy_vndr/sm8450
76a576ae7 sepolicy_vndr: allow sensors HAL to do binder call to system_server

   * frameworks/native
3bbc693ae5 Fix SurfaceFlinger crash caused by layerleak

   * hardware/lineage/interfaces
8f445d1 fingerprint: aidl: Improve documentation on sensor_location
3824e1a fingerprint: aidl: Use soong to decide which arch to build
9d7e862 fingerprint: aidl: Allow setting more than one sensor location
87c6ff2 fingerprint: aidl: Initial legacy libhardware implementation
15024d6 fingerprint: aidl: Initial stub service

   * lineage-sdk
a36e8368 Automatic translation import
2f8d4562 Automatic translation import
685b69ad sdk: Support breath LED mode

   * packages/apps/Backgrounds
9b2b59a Backgrounds: Add some more walls
8888d45 Backgrounds: Bring New walls Thanks to @XelXen for this awesome walls

   * packages/apps/crDroidSettings
5dfe8674 Matrixx Settings: Revamp settings font picker
dc324a29 Matrixx Settings: update key for volume haptic feedback
494c86ef Matrixx Settings: Settings: Add toggle for contextual dashboard messages [2/2]
b444de2f Settings: Add statuslyricext support [1/2]
87fae62b Matrixx Settings: Add Landscape iOS-16 battery style from Iconify [2/2]
e9e4093f [Squash] Matrixx Settings: Add status bar lyric [2/2] also Reset props for status bar lyric [2/2]
a0fc510a  Matrixx Settings: Hide ADB and developer setting enable status [2/2]
b7a2999c Matrixx Settings: Add QS Header Clock styles [2/2]
a9a1e9a4 Matrixx Settings: Add support for hide applist [2/2]

   * vendor/MatrixxOTA
45898e2 Matrixx: Update new IDs and push OTA [BOT]
2f99fe3 Alioth 11.2.0 Feb patch update
ef5c88a peridot: Update json
1dc27e3 Matrixx: Update new IDs and push OTA [BOT]
e5555c3 Merge pull request #260 from Arijit78/15.0
7602fce peridot: Initial release
9527c99 Merge pull request #259 from Matrixx-Devices/15.0-wip
9c4804b Matrixx 11.2.0 changelogs

   * vendor/lineage
68eb9bfa Revert "vendor: Enable smart battery"
b44967ac vendor: also append time in version

====================
     02-10-2025
====================

   * build/make
29b5b71228 build_image: get squashfs partition size from image size

   * build/soong
c4e20d5d3 soong: Show Matrixx Code name on lunch

   * device/google/tangorpro-kernels/5.10
32da39f Merge remote-tracking branch 'origin/fifteen' into fifteen
1c8868b tangorpro: update kernel-and-modules prebuilt
eb1d4c1 tangorpro: add trunk_staging prebuilt kernels.
16979ba tangorpro: update kernel-and-modules prebuilt

   * frameworks/base
4d65132d2381 PPutils: Update FP for Feb release
352f8da24f9d base: Make contextual dashboard message optional [1/3]
458b110a3457 SystemUI: Add haptic feedback to volume slider [1/2]
720c666f1621 SystemUI: Hide percent view when using iOS 16 battery style
bf40d32d78f8 Battery styles: Add Landscape iOS-16 battery style from Iconify [1/2]
01e888e7a317 SystemUI: Fix qs clock color in white mode
8db7ac0d69e3 QS Clocks: Update OOS clock style
87e7df775b11 IdleManager: update packagelist
576f302b81eb IdleManager: CleanUp
09b84b309590 base: Implement background process killer [1/2]
9689ee56e73c Print original error in case of failure in uncaughtException
b8ef1ea5b46f SystemUI: LyricViewController: Partially fix white-on-white issue
c476a21f5ebc  Status bar lyrics: Fix bug where some lyric would be wrongly ignored
91edc05659da [SQUASHED] base: Add status bar lyric for Android 15
3b86d49e5323 base: Hide ADB and developer setting enable status [1/2]
c8ec212cf654 Add QS Header Clock styles
61108d0d4aaf base: Add support for hide applist [1/2]
6e5f66820316 Only spoof packages installed by Aurora Store and modify new API
33740362c565 don't leak device-wide package list to apps when work profile is present
1636feb513b1 PM: Force all packages as installed via Google Play Store
e7c220490b5f Hide hidden apps from all apps except system
cef35f9a4920 Make AOSP native freeform windows always-on-top
c56fa0a1cfbf StatusbarLogo: Add matrixx logo
52e7112937cc update default pif value to pass device integrity
8e56332dfa20 wm: Fix freeform window minimize not working
39454eeae386 Shell: Use night/light theme for buttons/caption color instead of luminance
d5efcf91ca9d wm: Ensure freeform tasks bounds gets updated when launching tasks
4daf107039ad Fix accident evict if start more than 1 task to same position
4c574e5c5bef Update the surface position when changing TransitionInfo.Root
8d75f7b1c8a1 Update InputSink on transition finish
f76bfca6d500 Fixed the occasional flickering caused by sub-windows.
c77623e145ad Ignore pip task when checking task visibility in recents transition
6c5c6b3ddb87 Make split screen only reparent non-empty task
0e4b951c2464 Internet tile: Do not update network layout when toggling hotspot
806647007332 SystemUI: Reduce screenshot dismiss delay to 3 seconds
bea24aa88ac4 SystemUI: Dismiss screenshot window on touch outside
688d281a6d9e aapt2: support freezing private resource IDs
bfcb6b316aa6 SystemUI: Fix Custom QS Header not working [1/2]
f1eedf60b229 core: Update freeze IDs of ContextualSearch for QPR1
6cde05dc4d86 aapt2: add freeze IDs for ContextualSearch
57662df69631 Update Blur value
cc9790e7ed08 Cover more cases when ignoring secure window flags
e747f7011a26 core: Add transperent notification style [EXPERIMENTAL] [1/3]
7d6cd0205428 SystemUI: Update groove color for brightness slider
7f3b0cc68b7c base: update clear sky string again
cde808c4ee12 notify HWUI when scrolling
733259eb5c46 PPUtils: update fingerprint for jan
f2cb253efde1 SystemUI: Set load up hint when expanding QuickSettings
96b005b5e7e4 SystemUI: Media player mode toggle [1/2]
a9c422ba5b8d [EXPERIMENTAL] Implement Better QS [1/3]
40c06c2b0fa1 Revert "SystemUI: Implement Split notification shade changes [SQUASH]"
374b52a0b29f Revert "SystemUI: Discard QQS rows landscape settings"
ea85dffe9ff9 build: Don't check for fingerprint mismatch
3d04220f6a36 Make Build.TYPE and Build.FINGERPRINT consistent for apps
21f90baca1bc Initial implementation of KeyboxImitationHooks
87ff8f4f7bef overlays: Add notch bar killer
9a008f956894 base: Allow locking tasks to recents [1/2]
021f80c19350 SplashscreenWindowCreator: handel nullpointer exception gracefully
d196c1823b75 PPutils: spoof playstore to recent pixel
9e2c087ec92d core: Optimize download/upload animations
6d2bfae057d0 base: Allow to always show the time in media player [1/2]
8ca988c26d14 SystemUI: Use click effect instead of duration for haptic feedback for QSTile
faa8db9a1771 QuickSettings: Add Haptic Feedback to tiles [1/2]
c381feb64756 core: Make all list dividers transparent
312c2c02b677 Display Engine: Triluminous -> Triluminous Pro
e6b3135123b5 DisplayModeDirector: Allow to enforce user selected resolution
9590716ea376 Reduce default animation duration
f27740b72b09 Reduce ContrastColorUtil logspam
aec64d3141b8 LocalImageResolver: Stop the spam
b94cde06cb8c fwb: silence handwriting error spam
ac0eaef62c83 base: Introduce Smart 5G service [1/2]
290aca58fc0e fixup! for PreferredNetworkTile according to A15
ab4a66a9cc70 SystemUI: Introduce preferred network tile
d8bab85e5595 fwb: Update weather string sunny --> clear sky
3f23c09a53d4 HACK: telephony: Conditionally force enable LTE_CA
812b49bdbce5 base: Double tap to trigger doze [1/2]
b3389efde14c Settings: Implement preference category UI changes
7c77cffda018 remove thumb circle from seekbar * looks BAD AF
7ff43deebca4 AbsSeekBar: fix 1x1 white pixel thumb we dont want
bfd857d1065a drawable: Fix seekbar when disabled
c6817c6fa1bb fwb: Add circle thumb at the end of seekbar
782a42c5a26a Redesign seekbar
b7eb24b9d606 [Squash] : Readd Swipee to ScreenShot option
44ab41c92b00 core: Introduce VibrationUtils
55bbd5cc4ab1 services: Introduce Reality Display engine [1/2]
0d6f1e8d762e base: Allow to hide screen capture status from apps [1/2]
a0929410b600 base: ignore window secure flags
4dcc1c853d6f Revert "Update Media Seekbar Thumb Shape"
05151b6175c7 Revert "Camera2: Notify fps as Session Based Parameter"
55fcd65d0524 Disable notification Header
3f382f8479be FlashlightControllerImpl: Fix crash when camera IDs list is null
f3a5fe16adc3 Add config overlay to force enable multi resolution for camera
03dab0dbff7b Camera2: Notify fps as Session Based Parameter
12ef4b2e8619 PPUtils:add option to keystore safetynet attestation blocking [1/2] *for Users who want to use custom pif and tricky box
4a5216176308 PPUtils: update fingerprint for Device attetation
dce73d2642e5 PPUtils: Spoof Pixel XL to Snapchat
cc93a4859738 core: Update configs * Expose Tensor features to Pixel Studio * Expose Tensor features to dialer (Prevent showing compat messages) * Expose 2024 experience to PixelAIPrebuilt * Update process lists
cdf83a5332c0 core: Introduce SystemRestartUtils
d719d6d0fe81 PPutils: Fixup! spoofing
6313bb243a07 update fingerprint to pixel 9 pro xl
f7f39618f71e PPU: Add more spoofing properties for gameprops -> per-app transition
4f5ad6e24010 PixelPropUtils: Handle empty gms spoofing properties
b03305f82f0a PixelPropUtils: Implement json-based game spoofing [1/2]
84510fc2ca38 PixelPropUtils: Add support for json-based (PIF) spoofing [1/2]
fddcfc860e7a PixelPropsUtils: Spoof as husky beta
57e217a02383 PixelPropsUtils: Final cleanup
a68375721eba PixelProps: Remove games and pixel5 spoofs
442f270b4b0d PixelProps: Spoof pixel launcher for circle to search feature
eea265d2156b PixelPropUtils: Do not spoof unspecified packages as barbet
cab5b658d7f0 Add shouldBypassTaskPermission for pixel launcher
74ab1db6709a Revert PixelPropUtils conflicts [SQUASH]
d85b47bc1f93 [Squash] : remove some changes from Pixelprop * inorder to bring few more features
f0921fe1812d Revert "PixelPropsUtils: Move certified props to vendor"
b16e7c28b2c3 Revert "PixelPropsUtils: Dynamically spoof props for GMS"
fa4466952e8f Revert "AttestationService: Fixes and tune up"
929548632605 Revert "Add three fingers swipe actions [2/3]"

   * hardware/lineage/interfaces
a90b7f9 light: Add `lcd-backlight-ex` to the list of backlight devices
232ba05 light: Add `panel0-backlight-ex` to the list of backlight devices

   * hardware/samsung/nfc
61bc89f nfc: Rename debug level property

   * packages/apps/Settings
8757129b840 AppUtils: Filter cloneable apps to include only launchable packages
c6d614588d5 RunningServices: Remove DeveloperOptionAwareMixin interface
1bdbd53a331 Settings: Revamp Contextual Dashboard Messages - Also fix Dashboard msg in light mode
d5ac87d2186 Settings : Make contextual dashboard message optional [1/2]

   * packages/apps/Twelve
dec2d10 Twelve: Make togglePlayPause() rewind if playback has ended
2c66e7b Twelve: Add some margin to create playlist button
11e6ecb Twelve: Don't open bottom sheet for "create playlist" item
8a0e7de Twelve: Move onPrepareView callbacks using item to onBindView
799a828 Twelve: Merge all media item views

   * vendor/addons
5dbb6e77 addons: BlackTheme: Make more container surfaces black
298f4c53 Revert "addons: BlackTheme: Make shades little more darker"
8a7c06c1 addons: Update themed icons
dbb69cb2 addons: add GeneralSans font overlay take from https://github.com/DroidX-UI/vendor_droidx/tree/15/fonts

   * vendor/lineage
4ecad06f vendor: Bringin matrixx 11.2.0 Lemma
ea3832b9 vendor: Enable compact notification HUN
384222c7 rro_overlay: Use headline font for PermissionController
8afcbebd overlay: device_config: Updates
947ddd00 overlay: device_config: Add values required for Speech Recognition
488ca819 overlay: device_config: Escape special characters
e904a837 overlay: device_config: animate navbar on long press
6c4ec6e0 soong: Add libcameraservice extension config
d3dab3d3 common: Build tensorflow lite jni
c9c688ee crdroid: Disable default frame rate limit for games
b4c0dbf4 apns: Update Lebara UK
6815ed63 vars: February 2025 Security update
f01162ea Pixel 6-9: Sync SVN manually for Feb ASB

====================
     02-09-2025
====================

   * bootable/recovery
07027975 Merge pull request #3 from CuriousNom/15.0

   * frameworks/base
3fb76d9cf6c0 SystemUI: Redraw display cutout on overlay changes
11625ce404dd LocaleTile: Fix crash on LongClick
2da998311d02 New Crowdin updates (#1190)
dedcbd491976 Update Crowdin configuration file
11fc4954c5ac QS Header: Fix memory leaks
22e88d5ed833 QS Panel Styles: Fix thinline QS style
0e55e8772ae5 base: Add a toggle for long press on navbar to search [1/3]
29a45752b6bd Fixed a fatal exception which cause IndexOutOfBoundsException.
1bb2231f8b3c The binder die callback should add the wms global lock.
4b3d47010a23 Revert "Fix the potential memory leak issue caused by setExtension."
cb7af84d0f36 SystemUI: Implement pocket lock check for faceunlock
167a8a75a3ac SystemUI: Prevent indicator text cutting off in biometric prompt
6982d7cfb78e SystemUI: Apply burn-in translations to weather view as well
975d90111655 pm: aconfig: do not error on flags missing per partition
67f9261a934c Don't enable extra StrictMode features for userdebug builds
a6515d6b5531 SystemUI: Constrain keyguard indication area burn-in offset
c46edba14532 Checking whether ComponentName with current InputMethod is not null
bc53b102be04 AudioService: Cancel old toasts when switching ringer mode
07aaf8ec7164 AudioService: do not block focus request from applications compiled with lower version sdks
25d67a853ba0 Wifi Standard: Use coroutines instead of handler
99602e595887 Status Bar Tuner: Fix preference icon tint
78e35c0b86ba SystemUI: Tuner: Move to SwitchPreferenceCompat
cd5b1ed89d1d BluetoothControllerImpl: Optimize connected battery level scanning
7890b8072413 BluetoothControllerImpl: fetch battery level from any device
6911c9fa326e BluetoothControllerImpl: Synchronize mConnectedDevices access
d22e1b318ff2 SystemUI: Fix Internet Tile showing no service
2ae5da63d3dc SystemUI: Fix slider tile layout issue on A11 QS style
5d1a454648ed AllowDelayedLocking as long as run-in-bg allowed
2f1f982edc4f FlashlightStrengthTile: Do NOT leak CameraManager TorchCallback
065f041e8b28 SystemUI: Introduce Flashlight Strength Tile
577cca35963e Flush output buffers when command is complete
ed239aca7d2f SystemUI: Fixup cast chip long press when not showing a timer
76695ecb33ee SystemUI: Allow long pressing timer chips to directly stop the action
70976bc08d6c frameworks/base: Import Xiaomi Image Tags defenitions
5674386a7abb SystemUI: tuner: Enable enableOnBackInvokedCallback
bf369892ffd5 core: Expose method to toggle recent apps through Binder
3d4a721151d2 CarrierConfigManager: Enable inflate signal strength by default
e5f5072a2b20 base: Do not reset keyguard going away state - Fixes the flicker on turning off the screen when udfps is enabled
6e3345d3f290 Fix the potential memory leak issue caused by setExtension.
40e264e19252 SystemUI: Add switch for compact HUN [1/2]
6e765d584884 SystemUI: Remove power menu shadow
d2dac0dd5824 Persist music stream volume per user for Automotive
bfd605d94066 Fix surfaceControl release exception
7c3062ba98da Ignore null action in NativeTombstoneManager.
231d5522ae99 Ignore null action in KeyChainSystemService.
60918a58126e Ignore null action in WebViewUpdateService.
b34cbcf7b9d6 Ignore null action in AudioService.
d0c49e9eef4f Ignore null action in ActivityManagerService.
064bc0066d4a Ignore null action in AppBindingService.
4e9c8b547a21 Ignore null action in BinaryTransparencyService$PackageUpdatedReceiver
07154de298eb Ignore null action in VcnManagementService$VcnBroadcastReceiver
a0bfadf1d82f Ignore null action in AppStateTrackerImpl.
6395b53a985e Ignore null action in NotificationAttentionHelper.
55f47d2375f9 Ignore null action in DeviceIdleController.
1041be8c3fe5 Ignore null action in BackgroundJobsController.
a8b96dbd0dc9 Ignore null action in AppWidgetServiceImpl.
959a06582465 Ignore null action in AlarmManagerService$UninstallReceiver.
2e86e7448d03 Ignore null action in AppRestrictionController.
1a17829a4096 Ignore null action in SliceManagerService.
55f428094105 Ignore null action in PackageManagerService.
8caa1abbb1b8 SystemUI: Allow devices to disable 5G toggle
e5db22ec1868 Ignore null action in AudioService.
9f61fa0bd597 Fix FD leaks in BootReceiver.
e916cfc6c702 Ignore null action in GpuService.
26aab304017e MobileDataStatsPuller: add rate limit before post msg to handler
d1f0f0b11c82 avoid deadLock caused by onAuthenticationPrompt()
e7d1823b56ef base: Restore system dynamic colors for QS theme
575a0a181456 SystemUI: Discard QQS rows landscape settings
f1e959536456 SystemUI: Implement Split notification shade changes [SQUASH]
aab48ebcebcd fixup! Screenshot: Append app name to filename
f448c31f96c9 SystemUI: write initial value of SHOW_QR_CODE_SCANNER_SETTING on first call
49d5d3871883 Fix crash when long pressing navbar home
dcd71155ddee SystemUI: Nuke oriented navbar handle
bd3c99cd3490 SystemUI: Whitelist SystemUI Clocks from privilege checks
59bacf847513 SystemUI: Change heads up ticker text style to match clock
31e42f0d237b SystemUI: Use privacy_chip_background for charger indicator bg
3d0ddc2c7ff1 SystemUI: Update Bluetooth battery level assets
35ae2907fb6d Catch Exception to avoid SyncCallback residue
11f6a5574ff9 Fix window token leak on multi-display targets
76dece1b32ad Fix small mistakes in dumped string
05d9d77ce6c1 Deregistering mixes before register mixes in connectMixes
50052781f34a base: Add support for application downgrade [1/2]
1fb6a1b07ac9 don't call the reparent method when the old parent of task is removed.
a464ef542306 close the opend resources when IOException happen.
18c9bc594b71 Adding nullptr check for some framework components
696d260f4a69 Crash during Task switch
0b911ac29e11 SystemUI: Add back QS animation styles
177a856c32ad SystemUI: Add tuner service for QSTileViewImpl
91e0bbfaa7f1 SystemUI: ToastUI: Fix wrong theme and no icon
99ef17781d3e remove ScrollCache when Activity destroyed
8125bd01c754 ThemedResourceCache: Remove lambda and optimize map pruning iteration
27fbec8bc4d1 ThemedResourceCache: Replace ArrayMap with HashMap for performance
2d58b6422b2b SystemUI: Add separate check for custom lockscreen weather.
5d38d40d6f61 fix missing make NonNull judgment when the old parent is null.
42795e7f7601 Fix system server crash in drag scenario with null ClipData.
0def112ce5dc Don't wait on lock in getClassLoader if already cached.
5c19350c14c8 LocationFudger: Avoid division by zero
0dd461b3f543 ensure the opend resources are eventually closed when IOException happen.
429b4b1eb868 SystemUI: Fix smartspace layout
74376b77f24d fix missing add global lock to call the anyTaskForId method.
43ff02a7fc85 Adds missing standard include <memory> for std::shared_ptr<>.
011c6b6b8c59 Transition: fix NPE problem.
6fe9f889c85c add workaround for updateWifiBatteryStats() system_server crash
52cc98981fba add workaround for SSM.newTargetUser() system_server crash
6bdd30d8eb84 base: Add option to cycle through ringer modes [1/3]
46845e56ed71 InstallPackageHelper: fiX the NPE problem.
8ffb12723b83 UidObserverController: Protect mValidateUids with mLock
5a8dd1732a40 TaskDisplayArea: fix NPE problem.
31403fd7dd91 base: Allow disabling private DNS for VPN [1/2]
7c2728f94c81 SystemUI: SmartspaceSection: Build decoupled views only when required
32b0a589d94f SystemUI: Do initialize long press QS effects when supported
877c4e357580 SystemUI: Disable longpress effect for A11 QS tile
d577e841d18a SystemUI: Disable secondary click on bluetooth tile conditionally
97c0c10ea0c5 SystemUI: Add face unlock icon to keyguard blueprint
0779ad5503e3 SystemUI: Add private DNS QS tile
825c5886afd5 VoiceInteraction: Check if default package is installed
131cd85bf018 Update pixel framework hooks and wrappers
fca873e927df Add required priv-app permissions for SystemUIGoogle
1d436cb64cae Integrate Pixel framework hooks and wrappers
3a322ef78125 wm: Skip freeform displays from forcing desktop mode
0bc9d52c5936 wm: Show rounded corners on freeform window on internal display
4ec9e3e349e3 wm: Add API to listen for secure content in display
cc5ddf8b2a66 services: Add freeform system service
3fb8a7fb1e14 base: Add support for LMOFreeform service
2a23a181cc81 PackageWatchdog: fix the double close issue.
a68c823d2bb2 PowerStatsLogger: ensure the opend stream is closed when IOException happen.
755b1b8625d7 ScreenRecordingCallbackController: fix NPE problem.
8c716d0ed269 FadeOutManager: the NPE problem due to add null value to SparseArray.
611cf782b692 RecentTasks:fix NPE problem to avoid system_server process crash.
19ece997659d JobConcurrencyManager: fix the NPE problem.
494683747d01 Fix an NPE when a user is added and then removed quickly
eeeaa6211244 core: Catch OOB when returning pooled string
88fedeea37dc Fix AudioDeviceAttributes null crash
3a2c43e63524 Fix pip enter crash in landscape split-screen pair
620cf8c09be8 SystemUI: Improve the new biometric prompt layout
031f31f0ddee fix handling of MATCH_ARCHIVED_PACKAGES flag in getPackageUidInternal()
71f31b92cfbf Add missing @Nullable to TextUtils.equals()
1d4ac6cf6077 Settings: Expose clipboard auto clear setting [1/3]
64319b209390 base: Add customization for double tap recents key [2/3]
b7bd44f84edd base: Use SingleKeyRule for app switch long press
2ba5fcc8b7dd Avoid set transition ready to false when backgroud activity launch blocked
fb538a243006 SystemUI: Introduce 5G toggle in internet connectivity dialog
585d0ba72335 SystemUI: Sync power menu and restart menu layout
eb3a5bde1f05 ScreenOffAnimation: Fix system animation disable check
7eacc40e3e7f core/res: Do not hardcode text height in shutdown dialog
3a5d25e1770d InputMethodUtils: Fix system bootloop when no IME found
95654ae23d95 correct up eventTime
3fd35ccfaabb LayoutInflater: remove less frequently used widgets
99b100ecf21b LayoutInflater: Fallback to reflection when view tryCreateViewDirect fails
4aa23639e631 LayoutInflater: Opportunistically create views directly for performance
60f707a25ed5 SystemServiceRegistry: Replace ArrayMap with HashMap for performance
f64064a8e5b0 LocalServices: Replace ArrayMap with HashMap for performance
3999a8f7c574 base: Allow showing Ambient instead of fully waking [1/2]
8e3a6ee1b35d Optimize the SplashScreenView drawing process
7e1f48af8a7f Asynchronous initialization of shader cache.
f88a7b3cde21 fix the CWE problem in Biometrics.
2296fbedbcfb BiometricScheduler: fix the NPE problem in startWatchdog method.
8eeef77d401d SurfaceControl: add more window types to consider NoVote
335894a8291a Fix equals and hash code methods for the Property class
4415db5acb81 PackageInstaller: fix NPE due to a race condition in PackageUtil
6ae94bb64c49 fix an upstream race condition in handling of system error files
ab0e5be1f8ae fix NPE system_server crash in IMMS.resetDefaultImeLocked()
ac25cbc7066a SystemUI: biometrics: Add missing calls to parent onFinishInflate
ecfc7e1dc81c UniMode: Fixe bug that caused OverrideNightMode* to not work
968c7f499248 TintController: add lock to fix NPE problem.
867920339522 SystemUI: Fix colored icons going blank
4250c29412f5 SystemUI: Do not refresh theme on battery style changes
2c2fb1131f7c fixup! Firewall: Migrate to POLICY_REJECT_ALL
2cf3246ab80f Stop domain verification delegated from UIDs blocked by network policy
107f63a10828 Synchronizing the loudness codec dispatcher
3719248febc6 Fix VcnConfig garbage collection
2eb47d6b3eeb SystemUI: Fixup applying statusbar extra padding
c182e846cb2a SystemUI: Allow tuning extra padding for statusbar layout [1/2]
db94d5486c37 FATAL EXCEPTION IN SYSTEM PROCESS: android.ui
1792bc2f3b77 Adding nullptr check in Image_getHardwareBuffer() and Image_getFormat().
4e4976be83a7 Do not preserve window when window not added
bbfb13ef862b Use MappedFile in android_database_SQLiteConnection
1fb30f73ebe5 Avoid subtracting shmem twice when calculating LOST RAM.
ef072874ed0a AndroidManifest: add missing bluetooth intents to protected-broadcast
f3a5830ac5f6 Fix process memory data during dump
b75dcf0be83b Fix the wrong light doze state check
8005fc6e1c6f SystemUI: Add ability to hide carrier name on lockscreen [1/2]
007b718d2d65 PhoneWindowManager: Add vibration when using physical camera button gesture
40f7cc82b3c2 base: Allow to customize bottom corner swipe up action [2/4]
22a0cf1c37c8 Keep a null check before accessing the BluetoothA2dpWrapper APIs.
84bbce71b4ff BrightnessUtils: Conditionally use low gamma implementation for brightness curve
25818307b77d ImageReader: Allow skipping of nativeDetachImage
a4ab42f68e2b SystemUI: Adapt "Extend kill button to notification conversation guts" to A14 QPR2
a759bccb7f32 RuntimeInit: Prevent bootloop trying to handle app crash of null service
9c1ff9f2ed66 StringBlock: Prevent SystemUI crash when inflating QS
48a7e21232ec Make empty modem activity info as valid
33ad86d2dc6a Fix incorrect text shown at PUK lock screen
22b0720246ff SystemUI: Handle the SIM_STATE_NOT_READY state
f58a07df6935 sounds: Implement new screenshot sound effect
df7b02d73cd1 Don't update OverScroller fling state if improper time passed
b98b8951ec5a OplusTypeCastingHelper: update stub
656447b39607 Add some fwb stubs from Oplus
16372237e488 AppLock: Fix service initialization
cddc6f5fcaac AppLock: Intercept locked apps launching from recents
dfaeb5c89a9b AppLock: Make kotlin libs available only within this module
0aebd42d8298 AppLock: Update for kotlin errors
1313a967f129 AppLock: Allow using face unlock for biometric authentication
922490d37f7e AppLock: Move services to new package
dcd863293ea7 AppLock: Allow locking all apps visible in launcher
0ed62ce475ea AppLock: Update API to hide unprotected apps
65a94692659f base: Introduce app lock [1/4]
32bbced82512 Fix uninstall for all users
fd4ec0ed1031 AvatarPhotoController: Fix resource leak and recycle bitmap
39a2ca93e98e NSSLC: Prevent possible memory leak
7b38e6fcfb2c libandroid_defaults: explicitly enable ThinLTO
9c99d74c2c29 Optimize AbsListView to reduce click operation latency
1e37d2ab5164 ViewConfiguration: Set scroll friction to 0.009
68985d83c0cb AbsListView: Improve scrolling cache
d53e866925b4 Speed up Orientation Listener
374ec2fbbdd3 UdfpsController: add LAUNCH boost
bc479a60a6dd services: Implement exit app animation boost
5dfd109a8564 services: Implement activity boost optimization
7c49dca276a4 services: Implement transition boosting
973e7df120d4 services: Implement scroll gesture boosting
ad61f3e2485a services: Disallow max cached processes above 128
a91d858a854f CUR_MAX_CACHED_PROCESSES is not greater than the maximum value allowed
c8ca80544ca0 DSR: Fix DSR when we have toast window
1b389b22fa18 DSR: Fix broken DSR
d519a18d0a61 ActiveServices: Add delayed service restart (DSR) due to app launch
73c03ce48ef4 CachedAppOptimizer: Fix persistent compact skipped
dc70fa3bcd38 CachedAppOptimizer: Set thread group to background
74833330a0d3 CachedAppOptimizer : Pageout File pages during system compaction
08f3b0d72916 OomAdjuster: B-service aging propagation on memory pressure
a5d12d3312d6 Restore getSimStateForSlotIndex in SubscriptionManager
8d05877f2856 SystemUI: MediaHierarchyManager: Initiate allowMediaPlayerOnLockScreen
de960fa44b34 FaceUnlock: Remove background behind indicator on lockscreen
6cad6448e441 FaceSense: Vibrate on successful authentication
a9564514e2f6 services: Force load FaceSense providers
19098c1fa803 SystemUI: Implement bouncer face unlock animation
bd65f363d4a4 Avoid device reboot caused by SecurityException.
51c7417b43ad SystemUI: biometrics: Follow user setting to confirm face unlock
61d1212f7193 SystemUI: Use proper tint for face unlock icon
50630de9aeac SystemUI: Implement face unlock recognition animation and text
a5618826c7b5 SystemUI: Disable FaceUnlock Lockouts
c5b9900a4240 FaceService: Conditionally add ParanoidSense
68f501d34a52 base: Initial SenseProvider for FaceSense service
0468404386d7 Fix memory leak on MediaProjectionPermissionActivity
f6936da28645 Wakelock: Ensure `inner` wakelock is not null before releasing it
b9806f387be2 SystemUI: Update ChatGPT quickaffordance activity
11b8acec455d SystemUI: Add affordance shorcut for AI Voice Assistant
bf469e225e87 SystemUI: screenshot: Catch RejectedExecutionException
a26b3bc89f7c SystemUI: Add default path for FPS info service
46818e2bfd84 SystemUI: Use secondary label for language QS tile
eea0292cd8de SystemUI: CastTile: Open cast settings on long click
d964e7cf24d4 SystemUI: Re-designed caffeine tile icon
e7d08392d808 SystemUI: Add Locale Tile
be92c4ba984c SystemUI: Add Screenshot tile
bbfa1cab6753 SystemUI: Add refresh rate tile
fdb85c99ed67 SystemUI: Add Weather tile based on OmniJaws client
41486034f603 SystemUI: Add Smart Pixels tile
988beb06118c SystemUI: Add tile to show volume panel
5e92ec9daa58 SystemUI: Introduce DataSwitchTile
b45fab7df20e SystemUI: Add Compass tile
911a877c71fd SystemUI: Rewrite FPSInfoService in kt from scratch
56e56671abb7 SystemUI: FPS Info Overlay & Tile
15f140bf3c81 QS: Add CPUInfo toggle tile
0a551bbbd4e1 base: add CPU info overlay
7b91a8501f3a SystemUI: QS: Add On-The-Go Tile
20c747771a37 SystemUI: Add Sound tile
1deede9af9f9 SystemUI: Fix Wakelock issue
8ba83758eb33 SystemUI: Adapt screenshot sound to ringer modes
010793f7ffc7 Pulse: Implement pulse color based album art [1/2]
88e55b8d558f Pulse: Fix crash when linking visualizer
d2ad912e2ef9 Pulse: Make view linkages more robust
6ca0d35fb87c Pulse: Prevent systemui-related crashes
9f13dec748f0 Pulse: Fix orientation checks
2f89fa9bd13b Pulse: ColorContoller: Fix getting default accent color
38b44ec98698 Pulse: Simplify checks and prevent issues
be32ba183bc5 Pulse: Detach pulse view only when attached
9be90720de2b Pulse: Solid renderer round lines [1/2]
c849e22ea71a Pulse: Set current Refresh rate as FPS animation value
bcc338b71c5b Pulse: Extend to Ambient Screen
0ccc2c09787f Pulse initial checkin for Android 13 [1/2]
c4463a759216 BiometricScheduler: Cancel operation if not idle
fc727d16fe1b wm: Follow rounded corners by split divider corner size
d03d27f979db base: Add DND & Rate settings to flash on call [1/3]
05dc63cc1964 base: Add Flashlight blink on incoming calls [1/3]
708be272c6c9 Incall vibration options [1/3]
f14f420e26fa Increase Zenmode max hour limit from 12 to 24
3d53c8a5eaaf RingtoneManager: Set an default ringtone for the SIM 2
02425c096731 base: Phone ringtone setting for Multi SIM device [1/3]
daa19cdfb449 base: Allow choosing a custom vibration pattern [1/3]
229afbb569bc base: Add vibration patterns from OOS [1/3]
138d9e1966bc base: Allow customizing volume stream steps [1/2]
d6b5b3f6625c audio: Don't play sound effects if stream is muted
85095fc938e6 SystemUI: VolumeDialog: Fix systemui NPE while casting
0b0661746f17 SystemUI: VolumeDialog: Pass touch outside of volume panel
5aad9f016a08 SystemUI: VolumeDialog: Avoid multiple animations on touch spam
8f15132470fb SystemUI: VolumeDialog: Fix volume panel on left on secondary users
5472a351d72d SystemUI: VolumeDialog: Add content observer for panel timeout
ff4ff5d9e26c SystemUI: VolumeDialog: Dismiss dialog on config change
69a8a2802d14 SystemUI: VolumeDialog: Ensure proper resource release
5a5aee205a57 SystemUI: VolumeDialog: Open volume panel on expand long click
e20c55212471 SystemUI: VolumeDialog: Properly set initial dialog gravity
36a4e526b266 SystemUI: VolumeDialog: Change bg tint for inactive rows
d1fd47442476 SystemUI: VolumeDialog: Fix per-app volume on secondary users
a20a5c08d762 SystemUI: VolumeDialog: Add app rows to volume dialog
d625202cc7d9 SystemUI: VolumeDialog: New per-app volume icon
65a5ae2e5357 base: make per-app work with multi audio focus
dbee6c11415b base: support per-app volume [2/3]
72c4623e2558 Implement DeviceConfigUtils and service
816926c971a7 base: Add minimal support for Richtap vibrations
396095065fdf SystemUI: Introduce Adaptive Playback [1/2]
ba6f1f422b4e base: Allow scheduling always on display [1/2]
9f5468d8098a Doze-on-charge: Add few improvements and fixes
2508b3c1f648 base: Add Doze-on-charge customization [1/2]
f6c7510f9416 SystemUI: Allow toggling rotation button suggestion [1/2]
6e2f37b4ecc9 Fix crash with protected content with ElectronBeam/Scale screen-off animation
a91505628139 fwb: Screen off animations [1/2]
97f843faabd7 SystemUI: Allow devices to disable Smart Pixels on UDFPS
29a57f317c65 SystemUI: Smart Pixels [1/2]
51f03fbfedce fwb: Implement cutout force full screen [1/2]
5910c406eba6 Ambient Music Ticker - Allow to pulse on new tracks [1/2]
ecd0f61e21fe SystemUI: Add edge light customizations [1/2]
89f06e03106d base: Add bool to enable/disable doze by default
f9d4f007d287 Allow tuning ambient display with sensors [1/3]
03066885cad9 Add toggle to disable charging animation [1/2]
43404b42f049 SystemUI: Add dimens to set max offset of navigation bar burn-in protection
66cbb00928b2 SystemUI: Implement burn-in protection for status/navbar
184dd99986e5 SystemUI: Integrate Google Lens into Screenshot UI
a9e6e57a23ae SystemUI: Allow disabling clipboard overlay [1/2]
f71716743db7 Add kill button to notification guts [1/2]
af7f30bdeca5 HeadsUp: add timeout option (1/2)
86c42f5847fc Allow to suppress notifications sound/vibration if screen is ON [1/2]
dbe2b92b1254 SystemUI: Default to true for HeadsUp notifications
b1c889d6ad6f SystemUI: Add less boring heads up option
f45cd43e8a53 Reload navbar icons on changing style [1/2]
88002a927256 base: Update mock LinearmotorVibratorService
c33045402712 base: Add overlay to mock oplus LinearmotorVibratorService
ade099f83c2f base: Add mock oplus LinearmotorVibratorService
f3d9271511c6 base: Ensure pocket sensor is wakeup
f46b3855c8fe base: Allow to define custom pocket sensor value
c2840b6f2383 services: Start pocket mode service only if supported
f3cdc89b4af9 core: Use blue area for pocket mode illustration
3ffee6edd652 core: Refactor pocket mode interface code
e5e35083a4f5 policy: introduce pocket lock
677ee2aa6cdb GameSpace: Improvements for detecting foreground app exit
6bdf11004eef base: Fix gamespace on secondary users
67cb7f9416fe base: Fix NPE in GameManagerService
406f843cf122 base: Fix lock gesture not working for secondary users
4606a35ec5a5 base: Rework lock gesture feature
3fec7f3b00fe Add three fingers swipe actions [2/3]
bf2b6220d1f2 GameManagerService: Prevent multiple threads from accessing settings observer onChange
3e34323fb669 GameManagerService: Set device_config property on behalf of GameSpace
233261b11f9a SystemUI: Add support for GameSpace
652900d9a1fe SystemUI: Update resources on theme change in shade header
ab9ad21adfd5 Revert^2 "SystemUI: Remove nav bar background in QS customizer"
447629733541 SystemUI: Fix navbar tint when QS expanded
1cff76c79e19 Add Alert Slider user interface [SQUASHED]
cfe4fe4cd1b7 Add config overlay for battery info update
68c707a03f68 Update battery info every second when device is charging
985bd66abd58 SystemUI: Enable power menu blur via window flags
9addd6a8b9a4 SystemUI: Also blur power sub-menus
2ec8844de399 SystemUI: Blur the power menu
acf6b01c20ec SystemUI: Add restart SystemUI in Advanced Reboot [1/2]
8125a1eb8bef SystemUI: On-The-Go Mode (1/2)
12889b56c2e3 Allow adding space below IME on disabling navigation hint [1/3]
9ee92950655c Hide navigation hint when taskbar is enabled
0d98e4727ae2 SystemUI: Allow Configuring Navbar Radius [1/2]
5cbe4dd5e76f Cancel long swipe for cancelBack in navigation gesture
0e0d6e4d47e9 Add optional haptic feedback to new back gesture affordance
cac7219f403c Optional haptic feedback on back gesture [1/2]
8b77d0e5258b Allow to hide gesture on new back gesture affordance
6f4de96c0928 Allow to hide arrow for back gesture [1/2]
e299d75d1a4a fixup! Implement edge long swipe gesture
cbc861a906a1 EdgeBackGestureHandler: Change back gesture height intervals
2a032c9963ce Allow changing back gesture height [1/2]
93bb714514df EdgeBackGestureHandler: Switch to Tuner API
31ba0621a484 Allow changing the length of gesture navbar [1/2]
015ae2fa6810 NavigationBarInflaterView: Improve applying overlays
5b7fa2c02a17 Navbar: Fix issue where pill disappears in gestural mode
d097821d3093 Add separate tunables for navbar layout customization
35278f0fd017 add the lock in toString method.
4d40d03c5273 ATMS: fix the NPE problem in case the dream activity fails to start.
c27cdc7de67e keyguard: Do not trigger a wake up when hiding lockscreen
5af8fac54007 SystemUI: fix antiquated TunerActivity bugs
a625b2b23933 Fix DnsEvent ArrayIndexOutOfBound error
35e7062c8c45 Fix the wallpaper not hiding immediately
5ac117ea4a90 SystemUI: Update groove color
f769a0fac871 SystemUI: Use groove for brightness slider
ecca8318125d Make all activities resizable
f999d0ff2e83 core: Allow vendor odm symlink in framework overlays paths
de2750840a61 SystemUI: Update QS customizer background color
e38ccf28e521 display: Handle zero auto brightness adjustment
124f07e22f60 SystemUI: Fix crash when click rotation button on keyguard
1b28ecea836c JobScheduler: Remove jobs for non-existent packages
9873fcb2fc53 Cancel backup on transport error
9e03648f024b SystemUI: Remove tracing in `NoRemeasureMotionLayout`
63e1f6166e0c SystemUI: Fix crash when resetting ShadeController views
459dd813e466 SystemUI: Fix suspicious spaces around new mobile icons
1d549e7f89dc ActivityManagerNative: Prevent possible soft-reboot
96370118bd0f SystemUI: Drop unused rounded corner padding
1b809f0b99c6 FileRotator:fix NPE due to The File.list() method may be return null.
15beabba06f5 ConfigurationController: Prevent app crash on orientation change
6fd4fa142de9 fwb: Fix navigation bar button hit testing
7555e1fb6016 development: Address NPE when removing preferences out of developer options
775290d64818 SQLiteDatabase: Catch corrupt exception during transaction
acb37b6168a9 LockPatternUtils: Decrease minimum pin length for auto confirmation
7c7fda8f096b Shell: Don't show bugreport on DocumentsUI
81311c7177a4 telephony: SmsMessage: Bring newFromCDS method back
d9801a2dae61 EnhancedEstimates: Get estimates from Device Health Services
d59df4ec49af Avoid crash when dream starts
de528b0f6f8e PhoneWindowManager: Prevent NPE with voice search action
4a53a825a35a PhoneWindowManager: Check NPE for LineageHardware
8d19ce3fb52e base: Introduce Accidental Touch
6a0ea4bca050 Switch gesture navbar to new navigation bar key event source
289fe4dc8ccf base: Introduce new navigation bar key event source
3194a7b7362f Move Swap capacitive buttons to Settings [1/3]
69a6569d8ce7 Add toggle to disable HW keys [1/2]
f3c7e0878fdf Add more device key actions
26c516b2c21a Forward port pixel navbar animation from redfin 11 [1/2]
cb5b79f8a67f Make sensor block package list configurable [1/2]
7881b4fe7d27 base: Add Accelerometer and Linear Acceleration sensors in blocking list
9d4b87a8ec43 FWB: Sensor block per-package switch (1/2)
847a136df681 SystemSensorManager: sensor block per-package
b5088f86d77e FingerprintAuthenticationClient:fix NPE problem due to getListener method return var is null.
22d1282ad43d Fingerprint authentication vibration [1/2]
d965c976ff48 SystemUI: Remove padding for system icons in status bar
605492bf8657 ThemeOverlayApplier: Exclude Launcher3 and Themepicker overlays
95b1dd80ba4d SystemUI: Fix wrong thread exception when updating QS tiles
736d6e92668a QRCodeScannerController: Check for google package availability
3c7b46a4033a QRCodeScannerController: Use Lens as fallback activity
849af7b0a4c5 SystemUI: Ignore font padding for large ls clock
1df4a634eaf2 Allow overlaying font spacing for lockscreen clock
d0d32525ae51 base: Add support for Lockscreen clock fonts
f921766a7669 Add support for Navbar styles
354c37e9a52e UdfpsAnimation: Ensure window token is null before skipping hide
c468bff54478 Add support for UDFPS icons
c8629daa6efe SystemUI: Allow chroma & luminance to affect secondary colors [1/3]
dc339dc7dadd UdfpsAnimation: Address memory leaks and improvements
033a1ee9a287 UDFPS: Make GhbmIlluminationListener interface public
c4f43743f263 SystemUI: Fix Udfps animation positioning logic
3cf195bb0a95 SystemUI: Fix up UDFPS animations for multi-user
ff55381ba4c4 UdfpsAnimation: Ensure the UDFPS animation is always hidden
28c2cec0f5e9 UdfpsAnimation: Assume that style 0 is always 'none'
503589a83afa UdfpsAnimations: Use DisplayUtils.getScaleFactor to support multiple resolutions
12f26a677cea SystemUI: Make sure the udfps animation is hidden on the bouncer
f732e75a3eb1 SystemUI: Simplify udfps animation style selection
8b213685e1a3 Bring back UDFPS animation
2ce9a71c0063 UdfpsController: make sure to continue with onAcquired even when pulsing
3e7ba9d6a8b8 base: Allow toggling screen off FOD [1/2]
49b49f4243bc udfps: Allow devices to pulse onFingerDown instead of waking the screen
22d297bb3372 udfps: Add support for udfps on aod without dedicated sensor
71d4310c925d SystemUI: Launch power menu from QS only if enabled
1b12a6342213 Hide power menu on secure lockscreen [1/2]
822afff5c7cd SystemUI: Reduce keyguard indication text padding
8f7136e5036d BatteryService: Add support for oem fast charger detection
8d6560f81bc3 base: allow disabling ripple effect on unlock [1/2]
87d739388ac5 SystemUI: Add current divider config for lockscreen charging
bd61f65aee81 LockscreenCharging: squashed (1/3)
b1d2ca30663e SystemUI: Add missing location permission
ebbb101141f0 SystemUI: Add proper toggle for smartspace [1/2]
29b5afd8ca76 SystemUI: Fix SystemUI crash when removing status area
df598cd03923 SystemUI: Fix wrong thread exception when updating smartspace views
38815b28022d KeyguardClockSwitchController: Prevent an NPE on early boot
0e54e0e948ac Remove smartspace view when OmniJaws weather is enabled
8435ee409b67 SystemUI: Add optional wind info & humidity on lockscreen [1/2]
289bced4434c Add optional weather condition text on lockscreen
bb12b56b087e SystemUI: Add pixel style lockscreen weather based OmniJaws
421e196d0f07 OmniJawsClient: Clean up unnecessary check
0982a8953826 OmnijawsClient: Fix memory leak
d264e1853c1d OmnijawsClient: Close cursor to avoid memory leak
8f64804d27c8 OmnijawsClient: Fix widget theme [1/2]
04c6eb3201a8 OmnijawsClient: Use new google icon set by default
a318dea72ab8 crdroid: Add OmniJawsClient
8c2025e52134 SystemUI: Allow to toggle BT directly with Bluetooth tile [1/2]
9f522ed90acb StatusBarIconController: Don't crash at boot
7f0a3270e1e1 SystemUI: Prevent OOB when reinflating QS panel with notifications
eea6ae162187 SystemUI: Add QS Panel Style [1/3]
b4a1f7ba0350 SystemUI: Fix side scrolling issues with vertical/A11 tile layout
485e35f9ec11 SystemUI: Do not marquee QS label text
d709375eaeaf SystemUI: Add A11 QS UI Style [1/3]
5ac5eb2c8609 SystemUI: Allow to change QS tile label text size [1/2]
fc4b2409dd25 SystemUI: Prevent systemui crash when reinflating QS
c71f501ddf20 SystemUI: Add QS tile layout settings [1/2]
95d2f7d9eecb SystemUI: FileHeaderProvider: Fix resource leaks
a56a6ba61c73 ImageHelper: Improvements for retrieving compress bitmap
ffe78fde3be0 SystemUI: Rewrite and cleanup for header provider
57c7fdac637d SystemUI: Compress custom file headers properly
45dafc7bc1ec base: import ImageHelper
8f44120e969c SystemUI: Add QS Header Image customization [1/2]
68b28603b3d5 base: change background activity start mode to allow for widget configure
5cca74cc645a SystemUI: Allow toggle dual tone QS background [1/2]
d8cd78c6a1e1 SystemUI: Align the QS carrier text to its gravity bias
9a7c0605d173 NotificationShade: Make blur crossfading more gradual
73680f33ef08 PowerUI: Mute logcat spam.
2ee150f12b58 TelephonyManager: Gracefully handle null telephony service
ccc6fca0747e Remove unnecessary HashMap instantiation
672bfc0190cb SystemUI: Align keyguard carrier text with status bar
9ff69af1ccae SystemUI: Add null check for wakelock in KeyguardViewMediator
f9f0c80fb7a4 libhwui: compile for performance
d49e2b259356 libhwui: enable O3 when compiling for perf
12c6d1012216 libhwui: remove deprecated perf flags
9683fdb32f12 SystemUI: Always allow plugins
9c4e5e6f2279 Don't show app error dialog before system booted
501789f55072 Add button to AppErrorDialog to upload crash information to pasty
6946dc3750c8 Fix NPE in BootReceiver
2ffd44889aa6 SystemUI: Fix logspam in NotificationMenuRow
dce28f41685e SystemUI: Add vibration when long pressing QS footer settings button
8a0ec894c4ac SystemUI: Adapt long press on QS settings to launch crDroid Settings
dd905e82d5ee QSFooter: Launch crDroid Settings when long clicking settings
723f664306c4 keyguard: Actually kill Fancy Colon
ff9b221d5319 Fix WifiInjector instance exception if WifiService disabled
6952c96a1b4a services: Add NPE check for updating system app from play store
d8374e950e6f SystemUI: Update track title and artist on metadata change
d9970406c552 SystemUI: Fix janks in QS Data Usage when expanding QS Panel
10b60f5b2c2d SystemUI: Rework QS data usage UI
80501f64b7c2 SystemUI: Queue data usage text request only if enabled
744d4d3b8f92 SystemUI: Disable wifi listening in QS footer when view detached
5effc58bfbba SystemUI: Set initial usage text view as invisible
d1921dfda2fa SystemUI: Debounce QS data usage updates
92dd68d7ddd1 SystemUI: Improve QS data usage info
35009fca46c2 SystemUI: Always show suffix for DataUsage
a9cd9dfc996c SystemUI: Avoid NPE in QS footer data usage
f21ad6416538 SystemUI: Allow hiding QS footer data usage [1/2]
48d7b894a7a0 SystemUI: Show daily data usage in QS footer [SQUASHED]
4a3c8c7a0927 Revert "Clean up unused methods from DataUsageController"
1f153f45d2b4 SystemUI: Apply QS transparency to footer actions background
286e5ede85b9 ScrimController: Ensure alpha is fully transparent during AOD mode
664c20448830 ScrimController: Ensure the tint is set to black during AOD mode
dcd7df5e44b2 SystemUI: Fix auth scrim turning black in white theme
137bc03b3e58 SystemUI: Remove composite alpha from additional scrim on lockscreen
a13b2f609e9a SystemUI: Fix scrim issues regarding transparency
712b6a4e9124 SystemUI: Fix multiple QS background scrim issues
ff96e241feb5 SystemUI: Use Tuner API to apply QS custom alpha
3edf95e12452 SystemUI: Transparent QS customization
1f30d6cee209 SystemUI: Use transparent background for QS footer
89f506d2dc4d SystemUI: Apply rounded corners for QS footer
95a87034c5e7 Allow disabling qs on secure lockscreen [1/2]
117521334ca7 Add toggle to enable brightness slider haptic feedback [1/2]
fb383b0f7b91 SystemUI: Add haptics to brightness slider
9c59f9573a25 BrightnessController: Use TunerService API
c9b7dbb591d1 SystemUI: BrightnessController: do not update slider from DisplayManager callback if user is changing brightness
bebda0fed3b2 SettingsLib: Fix crash when checking emergency gesture state
4404d2d2c30e SettingsLib: Make IllustrationPreference bg protection transparent
154329dfaaa5 SettingsLib: UsageProgressBarPreference: Fix multiple NPEs
86c99a100f43 SettingsLib: Animate the UsageProgressBarPreference
94d77e85d869 SettingsLib: Change collapse mode to scale
c45e6404a1f3 SettingsLib: Change collapsed header color to match background color
5c3b4adfd2a3 SystemUI: Port statusbar brightness control
90a1248a88a6 Use FORCE_SHOW_NAVBAR to actually toggle navbar
1e51080b8933 CentralSurfacesImpl: Switch back to tuner API
3aee2a6fe943 Bring back QQS brightness slider
c5e7dd35cea3 Revert "Remove QQS brightness controller"
84e74b7c40b6 SystemUI: Tune wifi standard icon margins
e04bc40dbe74 SystemUI: WifiStandard: Avoid usage of Resources#getIdentifier()
71fec442f8d4 SystemUI: Introduce wifi standard icon feature [1/2]
88f4bcc5f576 MobileSignalController: Prevent possible memory leak
7e98f467f658 SystemUI: Allow using 4G icon instead of LTE [1/2]
ead677c21933 SystemUI: Option to disable Data Disabled Indicator icon [1/2]
aafa8bec63dc NetworkTraffic: Do not request layout on visibility
4e07485f2744 NetworkTraffic: Clean up and move settings
cabc9f572b77 NetworkTraffic: Fix leak in network callback
375326a23787 NetworkTraffic: Prevent SystemUI crash on user change
f525fc73e7d0 NetworkTraffic: Consider CLAT interfaces (IPv6)
625ae9f3300c NetworkTraffic: Prevent network callback exception on theme change
0724a94a9088 Network traffic mode for status bar [2/3]
96d15f2504c8 SystemUI: Forward port 'HD & wifi calling statusbar icons'
1dd521d8a23c SystemUI: Remove existing icon group if its overriding
98b36cd8defa SystemUI: Do not duplicate SPN and PLMN in network name
c6034a621446 SystemUI: Add roaming indicator to statusbar tuner
e3acf2f7a8f8 SystemUI: Allow toggling privacy indicators [1/2]
aa0d693772e9 SystemUI: Kill old privacy indicator icons completely
98b873b7dd1d Custom statusbar logo customizations [1/2]
5bed85eebb5f SystemUI: Apply colored icons and notification count to new icon area controller
eb149de1a613 SystemUI: Add ability to toggle bluetooth battery level [1/2]
eeecbaeb5d8e SystemUI: Fix notification count not working after a reboot
16856a72efe2 SystemUI: Forward-port notification counters
b67443bf13f9 SystemUI: Use app icons for notifications in statusbar
98718192eea8 SystemUI: Separate double tap to sleep on lockscreen [1/2]
c2eb19e1fc1c NotificationPanelView: Switch to Tuner API
4d32432905aa SystemUI: Add case to quick pull down status bar anywhere
fc5fa49a8489 SystemUI: Disable quick QS pull down by default
3b6b70c91641 QuickSettingsController: Switch to Tuner API
a9721cbc9e65 Battery Styles: Never enable dual tone on landscape battery styles
2e67e552a5de Battery Styles: Apply battery style to battery status chip
8f847a23715e Battery Styles: Add customization for QS
c747c3604944 Battery Styles: Fix color on QS for circle battery styles
4d573e38cf18 Battery Styles: Add BatteryBar [1/2]
f4e83cdcbefc Battery Styles: Set white tint in darkmode
acb75b3cdec0 Battery Styles: Use single low level warning config
25f8a37e5b81 Battery Styles: Update plus color for battery
08d4b4ec017a Battery Styles: Hide plus when showing battery percentage inside icon
78f1ffd73070 Battery Styles: Allow setting percent view on left [1/2]
2e6d9ab5cca8 Battery Styles: Introduce Battery Landscape [1/2]
067338267c71 Battery Styles: Show a bolt ⚡ when charging
16cacb8901fa Battery Styles: Introduce full circle battery style
0a0a8f586bf3 Battery Styles: Readd dotted Circle to Kotlin impl
6589a0b72f40 Battery Styles: Improvements and clean up for more customizations
f4ef91849c1f base: Add crDroid utils
47c90ebeaf54 base: Add metric for crDroid Settings
1756b4763c6b crdroid: Adapt settings for A15
331660ecfc2f SystemUI: Fix up status bar start side content layout
44f875032bd0 SystemUI: Fix up status bar end side content layout
7a88c19adcad SystemUI: Switch to TunerService for CollapsedStatusBar
29830d9510b3 SystemUI: Statusbar clock background chip [1/2]
381019d0abc2 Revert "SystemUI: Network Traffic [1/3]"
8b068daf2dd2 SystemUI: Avoid NPE in ClockRegistry
1f85f1f48754 Add DeskClock to hiddenapi whitelist
963fdb6d28a6 Clock: Use executor for tuner settings
d0dcb76c4b33 SystemUI: Block few clock customizations in QS header
d04da3464e46 SystemUI: Retune clock paddings
6bd388415c30 SystemUI: Properly apply dark theming to clock
1e2328a0e2e0 Use position tunable to hide clock as well
879768abbfa0 Add option to auto hide status-bar clock
548b874b6dff Statusbar clock customizations
3323cc26cbc4 Add separate tunable for clock seconds
cf2b7dae4521 base: use a double click effect for charging if there is no amplitude control support
30b225a006c4 SystemUI: Add hotspot toggle in QS internet dialog
ca5bfa1e23e1 InternetDialog: Properly nullify wifi toggle
43e6f194dad4 InternetDialog: Add missing setOnClickListener for data toggle
eda60a9fb638 SystemUI: Fix exception when retrieving signal strength drawable
4869d1ab1bbc SystemUI: Update default tiles as per usability
7e2bfe397e6b SystemUI: Fix RecodingController NPE with GameSpace
2141af4f3f3c Screenrecord: Export RecordingService for External Usage
8814a87bc09c KeyguardIndication: Set wakelock on doze only when required
8b18ca602b08 KeyguardIndication: Fix glitchy charging info on AOD
e4cbb6946ab4 KeyguardIndication: Fix glitchy charging info on lockscreen
628e08527313 Crash occured due to null pointer exception.
0f50a5e32e62 frameworks: Fix null pointer Issue
7275c335b2ba view: add null check for dispatch touch view
697ee67e6a1c SystemUI: Add statusbar call strength icon to tuner prefs
60402c9b18bf SystemUI: Add switch data saver icon
959e2fc2007e View: Prevent NPEs when initiating surface drag
87a24da31169 wm: Fix NPE when pip onAnimationEnd
8162788d2d94 Fix SystemUI NPE when ScreenDecorations is disabled
b9e44f026c90 QSPanel: Fix NPE in updateViewPositions()
97dc86e69bc7 Calm down attention service logspam
d3c8a4e4c7b3 PowerMenu: Hide emergency affordance if not selected
6d97b6cf6464 services: Skip access check for matlog shipped with rom
297a3bb6a650 Fix the NullPointerException in Android S Version:mServicesData
f2fa56a10e3a InputWrapper: Opt out early if session == null
18d97fda0463 neko/Cat: Mark FLAG_IMMUTABLE PendingIntent with FLAG_MUTABLE
a6222ac7bc85 NetworkPolicyManagerService: turn this into just a warning
727afea0dbe4 KernelCpuUidActiveTimeReader: Do not spam log with negative active time
0310911b5383 SystemUI: Fix SystemUI Crash
ab936d5bd166 SystemUI: Dismiss screenshot window on touch outside
d2865ce8bf47 NightLight: Allow lower temperatures
e6d87778654a MountService: Prevent NPE with DropBoxManager
a7f171fb1d47 ZygoteInit: Disable debug and tracing
147ed93de275 fwb: Disable some debug/log/trace
cc3d37a76540 fwb: Only enable some features on eng build
c770a9847706 NavigationBarInflaterView: Use Tuner API
3b2376f75a43 base: Update few drawables
a0522fa8efe8 SystemUI: Add statusbar NFC icon
ae3d0d459fb8 SystemUI: Update NFC tile drawable
a0d0b265d2a5 base: Remove restrictions for system audio record [1/2]
bbc8fa080b14 Move Bluetooth timeout back to AOSP settings
d27a90f90313 Wi-Fi timeout feature
53319a2d44eb SystemUI: Follow light/dark theme in power menu
353d7db4eed0 SystemUI: Follow monet theme on privacy indicators
98d690b4af6e SystemUI: QSCustomizer: Add reset to toolbar menu
b4bf1c30600d SystemUI: Use proper Resolver background color
fcecf65ad48b SystemUI: Remove visibility check in setting QSCarrier color
00a24819d6b2 SystemUI: Calculate paged QS tiles height properly
8586f5577710 SystemUI: refresh system icons on theme change
c0b1294a32b5 SystemUI: Fix QS header clock color
5c6116c7acaf SystemUI: Always refresh power menu on UI mode change
0bceb8d69758 BrightnessController: Update icon state for auto bg icon
99cbef720931 Use brightness icon matching with slider redesign
179ca13e4636 SystemUI: Fix dark scrim on light theme on pixel devices
8aeafe6ed1b1 SystemUI: Follow Dark/Light theme for Safe Mode dialog
577389aa33bb SystemUI: Follow light/dark theme in SplitShade Header
2f022a036aa7 SystemUI: Re-inflate QS and SB when CONFIG_SCREEN_LAYOUT
ce5500930cf8 SystemUI: Add dual-tone light and dark themes for QS
9af1bcd4b739 SystemUI: Initialize QS tiles in inactive state
67b5db84dfcc SystemUI: Use themewrapper for QSCustomizer and tune colorUnavailable
3612189230ae SystemUI: Follow light/dark theme in quick settings
0ea92a6a596d SystemUI: styles: Revert QS colors back to pre A15/QPR1
e1158a7c8266 Revert "Do not re-inflate QS and SB when CONFIG_UI_MODE"
5beaff38f5b6 Revert "Make QS always use dark theme colors"
5a250d86a340 SystemUI: monet: Allow a more granular control over shades [1/2]
c3066c503da8 SystemUI: Add charging icon to the charging animation
dfef7f757193 base: Use wireless charging animation for wired charging too
dd9a740fbfdc config_progress_background_tint: Use accent color for progress bar background
2f440e14ee83 SystemUI: Use color accent for charging animation
4c7793fd8b00 CarrierConfig: Enable payphone call blocking option
d61d1438c92e CarrierConfig: Always show ICCID
1f809b4628f5 CarrierConfig: allow toggling VoWiFi while roaming by default
ed19f3ee1e06 CarrierConfig: Always show APN settings on CDMA carriers
869bb7514e1b core: Remove old app target SDK dialog
06bc0e47ddd4 CarrierConfigManager: enable LTE+ icon by default
ab3ca3f76234 base: Update some icons to MD2
8ca0200c72f7 Camera: Prevent array index out of bound exception
ca16f89bbf72 CameraManager: Fix NPE in getting cameraIds
9049211ccd2c Camera: Prevent crash when unable to find tag
a486197ed355 CameraServiceProxy: fix exception
6dbb67654aad core: camera2: StreamConfigurationMap: add constructor for MIUI camera
9074a1669939 Camera: Clearing exception for Extended Face
f6b20f73ceda Camera: Decrement image references after 'onNextImageAvailable'
17021d01dfae camera: Add backwards-compatible CaptureResultExtras constructor
5d2603c4c6f9 CameraDeviceImpl: Don't crash when checking input configuration failed
aad942f2c3b2 Select the proper request list size
a306c8ebaf3d Camera: Prevent crash with prebuilt camera metadata
342c9cd320de Camera: Ignore torch status update for aux or composite camera
67e775a6c046 CameraManager: Fixup exposing aux camera to apps
2645c1185153 Camera2: Notify fps as Session Based Parameter
8ba5bafc85d7 camera: Allow selected camera apps to skip unconfigure
1b198962fc7e Guard in short-circuit evaluations for stringSplit methods.
ce51bd615a54 Camera: Don't crash when trying to disable shutter sound
bd861378cb51 Camera: Don't throw exceptions when value pairs have spaces in them
f1e5a81ebf5d Camera: Add feature extensions
a99fd40da102 Camera: Extend face detection
cb74e2565662 Fix Photosphere/Camera FCs
9b856cad6c16 Allow sending vendor- or device-specific commands to the camera HAL.
d4da3b2e57dd Put bare minimum metadata in screenshots
e6c7cf4656b8 pm: Add seamless migration between test and release keys
b3971089d904 BatteryStatsViewer: Enable enableOnBackInvokedCallback
5e17c1979c14 BatteryStatsViewer: Fix theme
2c5b326eebda BatteryStatsViewer: Move it to Battery Section
29fd349d0dce BatteryStatsViewer: Fix initial activity after launch
3bab4ad0da98 BatteryStatsViewer: Add summary for IA preference
e11bbf7d587c BatteryStatsViewer: Remove some hardcoded strings
e42240352b9a Create IA entry for BatteryStatsViewer
2ae08411c278 Revert "Hide the Battery Stats Viewer launcher by default"
fbb494ec673b SystemUI: Fix Biometric dialog corner radius
56b489561a79 SystemUI: Link dialog radius to config_dialogCornerRadius
ee9e1b6f29fc SystemUI: use default dialogCornerRadius for qs customize title
0bb5a8ea02c7 Battery light: 100% charged level (1/3)
90962d7e3b56 SystemUI: Better QS detail clip animation
822c30451123 SystemUI: Fix QS customizer corner radius
0d9e4aa3d570 DisplayModeDirector: Make sure we apply refresh rate on startup
c4b222e6caba ThemeOverlayApplier: Apply wifi and signal icon styles last
e612acfe9922 ThemeOverlayApplier: Catch a potential NPE.
9b1d0311885e ThemeUtils: Use current user for THEME_CUSTOMIZATION_OVERLAY_PACKAGES
259b1c88e34c ThemeUtils: Make it compatible for all targets
12b49153c460 Bring back ThemeUtils for Theming
e2efd03be493 SystemUI: Fix thread safety issue when adding tunables
954dd3ed555f SystemUI: Allow using tuner API for Global settings
40e82ad4320a TunerService: Add parseInteger method
58082bd95d8a TunerService: Prevent NPE with tunable
fb73f5864002 SystemUI: Allow using tuner API for LineageSettings
fb43c7b85478 Revert "Deprecate TunerService"
524c062ab34d ColorUtils: Prevent crash if alpha component is translucent
557f6436c239 Set navbar color for device default settings theme
2b78d72cb424 Fixed a crash in settings in tts engine selection screen.
e76ad4e6f5c5 ListView: Disable dividers by default
534581181705 SystemUI: Make popup menus more rounded
66fa03c5c6d7 services: Skip access check for matlog shipped with rom
bb720a0f7327 DisplayUtils: Introduce getScaleFactor
e9267a92f188 core: Fix menu popup ripple
aad77c153a83 SystemUI: More rounded corners
774998c64856 SystemUI: Add colors to assistant animation
de13a87679c4 SystemUI: Reduce screenshot dismiss delay to 3 seconds
5cd3cf19efb3 SystemUI: Remove Android build number from QS footer
c38640c4bb5e SystemUI: screenshot: Hide action chips text labels
4e726cabfde6 TtsEngines: avoid crashes caused by null engine name
7b20345e93e7 WebView: Add check before setting default or fallback provider
375d16ae13af core: pm: Wipe package cache on upgrade
9acd6133f3b4 Allow signature spoofing on user builds
67f7042a7aaa Set FakeStore/PlayStore as Aurora Store installer package name
c7c863df7ab5 Hide hidden apps from all apps except system
7a21e0310288 Avoid Settings app NPE on broken packages
a231c624ada9 Prevent crashing with several child profiles
5a46ad67627b Show hidden apps on secondary users' app lists
141919a74ad6 NavigationBarInflater: Update navigation no hint package overlay
7ce724afbd5c SystemUI: Update black theme package overlay
c4ef796d646a SettingsLib: Migrate MainSwitchPreference to Material3
ad982ef38c89 SystemUI: Re-evaluate system theme on UI mode change
968e907cb5b6 Add deep sleep preference controller [1/2]
d5184b203b08 SettingsLib: Don't show system overlays on apps list
4ba74b9a6bd4 SettingsLib: Fix nav bar color on certain apps
6503fd8381f7 SettingsLib: Make IllustrationPreference bg protection transparent
c2de3566ff63 SettingsLib: Update 5G+ icon to Silk design
be0e0944e8f3 SettingsLib: Update 4G+ icon to Silk design as well
847f01c078ec SettingsLib: Update LTE+ icon as per new Silk design
c83657752ff6 AttestationService: Fixes and tune up
674d62da4028 PixelPropsUtils: Dynamically spoof props for GMS
ef0d7cc991bf PixelPropsUtils: Move certified props to vendor
52f36c45714a Introduce PixelPropsUtils for safety net spoof [SQUASHED]
4d5c2d564d63 SystemUI: Fix fontinterpolator unable to interpolate due to unknown default axes value
933f05cb3a28 Set alert dialog message to use system font
10ade2d5c371 fonts: Add more sans-serif aliases
8894815f678d TypeFace: Improve system font overriding method
fefc0249cec3 graphics: Override system fonts with user-selected overlays
3198e08acc8f base: styles: Use user fonts for Material UI themes
7dfd640cdb2e Fonts: Add regular / light font config
d945f48d5029 base: Use font configs instead hardcoded fonts
7ae4fd75e85c Wire up default fonts with config
e10876ddaa08 base: Export bodyFontFamily and bodyFontFamilyMedium symbols
dddac9d611ea SmoothSpinners: Makes the loading "spinner" animation smoother
bbf3f4d84bc6 base: Add rounded corners to activity open/close animation
cb407b0f2b3e base: Pause apps feature
e865c7bbb710 base: Add stub files
8f2748b40ab1 Merge tag 'android-15.0.0_r14' into staging/lineage-22.1_merge-android-15.0.0_r14

   * hardware/qcom-caf/msm8953/audio
1b5ce68f1a visualizer: do not use GNU old-style field designators
1809521b6a voice_processing: do not use GNU old-style field designators
218e835767 audio-effects: Fix out-of-bound read
c7945b3662 audio-hal: Fix kw issue
71c5e51120 audio-hal: oob read when doing the typecase
51cdec106b hal: Update 64-bit vendor HAL path
01be9192c4 soundfx: Convert to blueprint & remove unused effects
ddd4045c35 audio: Remove autoconf/automake files
23c50e9f81 audio: Remove OMX components
0f32dcd453 audio: Remove disabled HW accelerated effects
e342823606 audio: Remove unsupported QAHW
2b2841b3bc audio: Remove unused hdmi_in_test
c70ad9ca25 audio: Remove deprecated audio daemon

   * hardware/qcom-caf/msm8953/display
47e27c7418 Revert "gpu_tonemapper: Fix compilation issue."
5345254cfd gpu_tonemapper: Fix loop increment never executed
3a56441266 Convert some display libraries to blueprint
681046fd02 Remove unused libcopybit sources
6d2c56e9d5 qdutils/hwc: Remove unused code surrounding fps calculations
61890b7fff sdm: Remove USE_GRALLOC1 conditionals
12d9f2ca89 sdm: Remove use_hwc2 conditional
0bc83cf81d sdm: Remove display_config_version conditionals
bad9b7af9a Revert "hwc2: Avoid adding default color mode when display PP is unsupported"
c54d77b5ca Revert "hwc2: Remove multi-display support from wearables."
be97b92a6e sdm: Cleanup unused code, round 2
1e0788c9d3 display: Cleanup unused code
9ae410d70b display: Remove deprecated lights.$(TARGET_BOARD_PLATFORM)
a407397f40 display: Remove libmemtrack library

   * hardware/qcom-caf/msm8998/audio
970b452a3b hal: update audio effects config names
0b702d7ccc post_proc: fix mul-overflow
d6bec2c279 hal: Show cal step for volume listener
8f607d5055 visualizer: dynamically parse the sound card when opening mixer
d396d643bf post_proc: Add USB device support for bass boost
32fe461f1e visualizer: do not use GNU old-style field designators
c7b9f35c22 voice_processing: do not use GNU old-style field designators
15a96f3ad3 audio-effects: Fix out-of-bound read
927a1882cf audio-hal: Fix kw issue
fff6b47b04 audio-hal: oob read when doing the typecase
af7b3277b8 hal: Update 64-bit vendor HAL path
a310768ff9 soundfx: Convert to blueprint & remove unused effects
9164a77fbb audio: Remove autoconf/automake files

   * hardware/qcom-caf/sdm845/audio
d6b236ac74 visualizer: do not use GNU old-style field designators
5bb9c04a33 voice_processing: do not use GNU old-style field designators
0c00f920ca audio-effects: Fix out-of-bound read
a8cefba281 audio-hal: Fix kw issue
0a0ffe2aae audio-hal: oob read when doing the typecase
07a88dcd10 hal: Update 64-bit vendor HAL path
f9c22aba8e soundfx: Convert to blueprint & remove unused effects
1f6606f76e audio: Remove autoconf/automake files

   * hardware/qcom-caf/sm8150/audio
15dc2b0cbc visualizer: do not use GNU old-style field designators
c47189f8b2 voice_processing: do not use GNU old-style field designators
b61b62ecf2 audio-hal: Fix kw issue
56b6afdb40 hal: Update 64-bit vendor HAL path
566fa517c3 soundfx: Convert to blueprint & remove unused effects
1e377baf21 audio: Remove autoconf/automake files

   * hardware/qcom-caf/sm8250/audio
0547a74443 visualizer: do not use GNU old-style field designators
ce9604d4c6 voice_processing: do not use GNU old-style field designators

   * hardware/qcom-caf/sm8250/media
3bfc8ddfb mm-core: Remove no longer used codecs
c64f23926 mm-core: Convert to blueprint
a47853022 mm-core: Remove unused files & flags
d004c5f44 mm-video-v4l2: Convert to blueprint

   * hardware/qcom-caf/sm8350/audio
452725a165 audio: Drop STT meta test app
b13925e6ee visualizer: do not use GNU old-style field designators
f5b6e037a4 voice_processing: do not use GNU old-style field designators

   * packages/apps/Dialer
c13546198 Merge 'lineage-22.1' into 15.0

   * packages/apps/DocumentsUI
478d895bf Merge 'lineage-22.1' into 15.0

   * packages/apps/LineageParts
01061b3 Disable unused components
ef7afa4 Remove unused Network Traffic fragment
3730773 Use ListPreference for charging control fragment
4287c4f Update color mode preview from Android 12
6aa153c Utilities: Fix inaccess Build.DATE
f6f6ec7 Kill redundant search fun party
a820271 Make trust interface less boring
1cc06b7 Add initial crDroid stats support
7251fc7 stats: Mod version switched to crdroid version
881cb1a Ship as crDroid based on LOS

   * packages/apps/Messaging
995da78 Merge 'lineage-22.1' into 15.0

   * packages/apps/Settings
85a817b0676 Settings: Revamp Contextual Dashboard Messages
2f96ac6f2f8 Settings: Introduce contextual dashboard messages
d9a96b8eebd Use default letter spacing for category titles
721b6d9be30 Settings: Improve udfps enroll introduction layout
d07faed19fd Settings: Use internal display brightness in overlay displays
4a095ef1484 Settings: Fixup fingerprint enroll finish layout
5f420bf0a9e Settings: Retain udfps overlay shown state on restoring activity
05b79eafaa5 Settings: Pull navigation mode settings out
de48c688407 UsbDefaultFragment: Remove DeveloperOptionAwareMixin
0635b6f90b3 Settings: Make google's battery widget work
98fcfdef200 Settings: Better check for GSA package
e00ca35ed97 Settings: Add Circle To Search [2/2]
6016c741f9c Settings: Add a toggle for long press on navbar to search [3/3]
d6a982a33f7 Settings: Expose radio info (*#*#4636#*#*)
07c91f7fcf8 Settings: Battery: Implement background process killer [2/2]

   * packages/apps/Twelve
c95473a Twelve: Reformat code
0836d86 Twelve: Fix/improve intent handling navigation

   * packages/apps/Updater
35d7963 New translations (#84)
0560741 Update Crowdin configuration file
2c14d1e Catch exceptions when enabling performance mode
0f9e696 Revert "Updater: layout: activity_updates: add spacing.."
c0f32d5 Updater: Update parsed info whenever data is refreshed
13bc9bf Updater: Add support links and some more info
07a0657 Updater: Use headline font for activity header
238d244 Updater: Nuke Lineage's website on installation blocked dialog
91aa830 Updater: Initial adaption for crdroid
fb990ca Updater: Change package name to avoid conflict
835f24a Ship as crDroid based on LOS

   * packages/services/OmniJaws
4e8be72 OmniJaws: fix error handling and clear cached weather data
302687b OmniJaws: Broadcast disabled error code intent when the service is disabled via toggle.
ab09177 Revert "OmniJaws: Use OWM keys for crdroid devices only"
9fb041c OmniJaws: fix weather activity layout
b709548 OmniJaws: migrate OWM provider to One Call API 3.0
982739b Revert "OmniJaws: OpenWeatherMapProvider: Use onecall v3 API"

   * vendor/addons
04c8cc71 extra: Prebuilt StatusBarLyricExt

====================
     02-08-2025
====================

   * android
c27b056 manifest: February 2025 Security Update

   * bootable/recovery
2e3bf15b minui: Import graphics_drm fix from QSSI 13

   * build/make
32860bb502 Merge tag 'android-15.0.0_r14' into 15.0

   * build/release
c4c4459d Disable flexiglass changes
fe1506a9 Merge tag 'android-15.0.0_r14' into 15.0

   * device/qcom/sepolicy_vndr/sm8550
bbbbed900 sepolicy: NFC: Add support for snxxx AIDL service

   * frameworks/av
cf46443fe2 fixup! av: support per-app volume [1/3]
bf86502482 CameraProviderExtension: add enabled bool and always set torch
141af36164 CameraProviderExtension: Use weak linkage for default implementations
6f5c4bd69a CameraProviderExtension: Inject strength in fixupTorchStrengthTags
9de9d04af7 CameraProviderExtension: Reset strength level on torch off
3582f2da99 CameraProviderExtension: Update mTorchStrengthLevel with new level
1ed85e884a CameraProviderExtension: Return BAD_VALUE for invalid strength level
4b9fb31101 camera: Add extension to control torch light strength
98e510df13 Fix Integer Overflow in MPEG4Writer
d5d22172b2 Audiopolicy : skipDelays in registerPolicyMixes
8a026400e5 Extends "Camera: Skip stream size check for whitelisted apps"
39aaf389cb Merge tag 'android-15.0.0_r14' into 15.0

   * packages/apps/FMRadio
f3eb07a FMRadio: Rework custom jni support

   * packages/apps/Jelly
649eef6 Jelly: set MainActivity launchMode to singleTask

   * packages/apps/Settings
5911b9f7eab Settings: Move applock to apps section
97161c51ff2 Merge tag 'android-15.0.0_r14' into 15.0

   * packages/apps/Twelve
2a492f1 Twelve: Fix-up provider preference store

   * packages/apps/crDroidSettings
d48603d8 Matrixx Settings: Init Matrixx

   * packages/modules/Bluetooth
223db2e848 Merge tag 'android-15.0.0_r14' into 15.0

   * packages/services/Telecomm
255a3a97b Merge tag 'android-15.0.0_r14' into 15.0

   * system/core
08b6b547e Merge tag 'android-15.0.0_r14' into 15.0

   * toolchain/pgo-profiles
ef159ad Refreshed afdo profiles drop from ZP1A.250124.003.A1

   * vendor/MatrixxOTA
90918de Matrixx: Update new IDs and push OTA [BOT]
6c32da6 Merge pull request #257 from royweisfeld/15.0
3df43d4 garnet: Rebase trees and add vanilla
b86d848 Matrixx: Update new IDs and push OTA [BOT]
73168e9 Merge pull request #258 from alanpdk/15.0
09bb9d2 sky: Initial A15 Official release

   * vendor/lineage
01ef2c17 base: Reset props for status bar lyric [1/3]

   * vendor/qcom/opensource/libfmjni
c5ace14 libfmjni: Convert it to filegroup and header lib

