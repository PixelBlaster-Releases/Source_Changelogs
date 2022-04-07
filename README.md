# Changelog

### 1. PixelPropsUtils: Update raven fp to april

### 2. base: Fix derp

### 3. Led lights: don't skip dialer and other ones

### 4. base: Add option to disable led after full charging [1/2]

### 5. Notifications light: Add @hide to fix build

### 6. Notification lights: use default resources for color on and off [2/2]

### 7. LEDs: fix default color

### 8. base: Allow to customize notification led light [2/2]

### 9. base: Enable notifications led light by default [1/2]

### 10. base: Battery light customization [1/2]

### 11. zygote: Disable debug

### 12. base: set scrolling friction to 0.006f

### 13. charging: Allow using vibration without sounds

### 14. SystemUI: Invoke keyguard exit animation

### 15. Add config to exempt telephony-related app from location indicators

### 16. stop enforcing camera sound for certain carriers

### 17. Add a config to state whether a device supports increased touch sensitivity. (#2)

### 18. QuickStatusBarHeader: Fix forbidden static imports.

### 19. base: SystemUI: Fix circle battery QS tinting

### 20. RecoverySystem: make the package readable before checking capex

### 21. zygote: Enable USAP by default for S.

### 22. AutoBrightness: Add support for one shot auto-brightness [1/2]

### 23. ScreenshotHelper: ignore timeout when taking partial screenshots

### 24. fw/b: Add capability to allow tethering to use VPN upstreams [1/3]

### 25. EasterEgg: Fix some warnings

### 26. StrictMode: Don't enable extra features for userdebug builds

### 27. overlays: Do not build the default cutout RROs

### 28. SystemUI: Remove excess margin from data saver icon

### 29. SystemUI: Display a toast when a screenshot is deleted

### 30. DefaultPermissionGrant: Fix google search crash

### 31. Exclude Bluetooth app from Location indicators

### 32. base: Fix location privacy indicator getting stuck

### 33. base: improve location privacy indicator toggle

### 34. base: allow toggling location privacy indicator [1/2]

### 35. QuickSettings: Add Haptic Feedback to tiles [1/2]

### 36. base: Add navbar layout inversion tuning [1/2]

### 37. overlays: Bring back icon shapes

### 38. SystemUI: Hide tuner icon in QS panel

### 39. fixup! fwb: Seperate statusbar from tuner and launch externally

### 40. TunerService: Add parseInteger failsafe method

### 41. TunerServiceImpl: Blacklist Settings.System from tuner reset

### 42. SystemUI: tuner: Allow Tuner API for System settings

### 43. Tuner: Don't clear out prefs, it's not disabled

### 44. TunerService: Prevent NPE with tunable

### 45. base: SystemUI: enable tuner and show in Settings

### 46. privapp-permissions: Grant missing TelephonyProvider perm.

### 47. SystemUI: PeopleSpaceWidgetManager: don't spam logcat

### 48. base: Speed up Orientation Listener

### 49. BatteryMeterView: Move null check to the beginning of the method.

### 50. NavigationModeController: Silence log spam

### 51. ANDROID: Fix EventLog string class problem in ViewRootImpl#enqueueInputEvent()

### 52. services: LightsService: Mute an annoying error message.

### 53. GpsNetInitiatedHandler: Disable more debugging

### 54. Disable/reduce functionality of various ad/analytics libraries

### 55. base: Introduce Adaptive Playback [1/2]

### 56. IconPackKaiAndroidOverlay: fix for carriers using 5 bars of signal

### 57. libs: hwui: Build using ThinLTO

### 58. Make Quick Unlock compatible with long PIN/Password [1/2]

### 59. Keyguard: Forward port lockscreen quick unlock [1/2]

### 60. Scramble pin: fix scrambling after 12L

### 61. Keyguard: Add option to scramble pin layout when unlocking [1/2]

### 62. KeyguardSliceProvider: Show Now playing titles only in AmbientIndication.

### 63. SystemUI: Fix NPE in AmbientIndicationContainer.

### 64. AmbientIndication: Fix music ticker being black on AOD when using light wallpaper.

### 65. Ambient music ticker: Adjust the margin to the bottom a bit.

### 66. Ambient music ticker: Moar layout fixes.

### 67. Ambient music ticker: Show the now playing container on Ambient screen as well

### 68. Ambient music ticker: Fix layout on Android 12

### 69. Ambient music ticker: show Now Playing info on lockscreen

### 70. Port ambient Now Playing container from Pixel [stripped down version]

### 71. Ambient music: pulse on new music tracks and Now Playing info [1/2]

### 72. IconPackRounded: Use correct icon for notification and ring volume

### 73. overlays: Add unlinked ringtone and notification volume icons

### 74. BugFix: HWASAN: Fix stack-buffer-overflow

### 75. Handle BLE ON corner use cases with BLE APP concurrency

### 76. ColorUtils: Prevent crash if alpha component is translucent

### 77. base: Hide power menu on secure lockscreen [1/2]

### 78. SystemUI: allow disabling qs on secure lockscreen [1/2]

### 79. SystemUI: LocationTile: Be affected by the secure tiles toggle

### 80. SystemUI: InternetTile: We should be secure as well

### 81. base: Add a toggle for secure tiles on keyguard [1/2]

### 82. base: set alert dialog message to use system font

### 83. base: fix list style alert dialog to use system font

### 84. Dont throw exception if admin is null

### 85. InputMethodUtils: Fix system bootloop when no IME found

### 86. VolumeDialogControllerImpl: Stop log spam with no caption service

### 87. BatteryMeterView: Fix NPE that occurs when onDensityOrFontScaleChanged() is called.

### 88. VolumeDialog: notifyVisible after the volume panel is fully hidden

### 89. SettingsProvider: Set device name to marketname if available

### 90. base: Rearrange bluetooth icon on statusbar

### 91. hwui: JankTracer: Silence Davey logs for now

### 92. services: WindowOrientationListener: bail out if rotation resolver service instance is null

### 93. graphics: Override system fonts with user-selected overlays

### 94. SystemUI: Make sure notification icons are sticked to the left

### 95. SystemUI: Add MAINLINE_NETWORK_STACK permission

### 96. base: Fix QS clock being white on light theme

### 97. base: Fix net traffic view being white on QQS Header

### 98. SystemUI: Reduce statusbar network speed margins

### 99. SystemUI: NetworkTraffic: Minor refinements

### 100. SystemUI: Fix NetworkTraffic UI on expanded QS

### 101. SystemUI: Move NetworkTraffic in QS header

### 102. NetworkTrafficSB: Better workaround for RequestLayout() spam

### 103. NetworkTraffic: Remove screen on/off triggers

### 104. StatubarIconList: Fix Network traffic visibility on overlayChange()

### 105. NetworkTraffic: Fix speed format for 10*KB

### 106. StatusBarIconController: Avoid cast exceptions

### 107. base: Avoid casting network traffic to StatusBarIconView to prevent crash

### 108. Network Traffic: Allow to choose display mode [1/2]

### 109. Network Traffic: Customize refresh interval [1/2]

### 110. SystemUI: Improve Network Traffic

### 111. Network Traffic: remove statusbar animation

### 112. Traffic indicators: Prevent logspam caused by improperly calling requestLayout()

### 113. Traffic indicators: don't show two instances in expanded statusbar

### 114. Traffic indicators: hide in the keyguard

### 115. Traffic indicators: add properly to statusbar icons

### 116. Traffic indicators: use smaller and bold fonts in expanded statusbar

### 117. Traffic indicators: code cleanup and improvements

### 118. Network Traffic: Adjust size/text style for extended statusbar

### 119. Network Traffic: Refactor text formatting

### 120. Network Traffic: OOS style network traffic indicator

### 121. Network Traffic: Move network indicator to the right

### 122. Network Traffic: Bring back traffic indicator for all

### 123. Network traffic: fix indicator not hiding on lost connection

### 124. Net monitor: fix text color on light theme

### 125. base: Move net monitor to expanded statusbar header

### 126. Statusbar net monitor: stop the handler if screen is off

### 127. base: Network Traffic [1/2]

### 128. Fix build warning of Supported source version being RELEASE_8

### 129. SoundPool: Update queue only if streamID matches

### 130. InternetDialogController: Fix mismatch in argument list after merge of r18.

### 131. PowerManagerService: Send broadcast when going to sleep

### 132. base: Bluetooth timeout feature (1/2)

### 133. base: Wi-Fi timeout feature (1/2)

### 134. AppErrors: Respect appsNotReportingCrashes for ANRs

### 135. SystemUI: Use geometric 6 and 9 glyphs in PIN entry keypad

### 136. neko/Cat: Mark FLAG_IMMUTABLE PendingIntent with FLAG_MUTABLE

### 137. libs: PipTaskOrganizer: do not start fade out animation for pip if surfacecontrol leash is null

### 138. GlobalActionsDialogLite: Dismiss the dialog when restarting SystemUI

### 139. SystemUI: Limit keyguard charging stats updates

### 140. Update battery info every second when device is charging

### 141. LockscreenCharging: Calculate power from voltage and current

### 142. SystemUI: Fix current formatting on lockscreen

### 143. BatteryService: Add SuperDart charging support

### 144. base: Fix dash charge not showing battery level

### 145. BatteryService: Add VOOC charging support

### 146. BatteryService: Add Warp charging support

### 147. BatteryService: Add dash charging support

### 148. KeyguardIndication: fix fc on lockscreen charging info

### 149. Lockscreen charging info: show decimal in battery temperature

### 150. SystemUI: keyguard show charging watt

### 151. SystemUI: Keyguard: Check for a null errString

### 152. LockscreenCharging: squashed (1/3)

### 153. base: Keep recent tasks for more time in memory

### 154. base: Relax requirement for visible flag to sdcards

### 155. Notifications: Make USB-Debugging notification less important

### 156. ParcelFileDescriptor: Stop the panic

### 157. SystemUI: Add statusbar NFC icon

### 158. fixup! base: HeadsUp notification time out

### 159. fixup! base: HeadsUp blacklists/stoplists

### 160. HeadsUp: Fix crash while formatting string

### 161. HeadsUpManager: Switch to SysUIToast for showing toasts

### 162. base: HeadsUp snooze function [1/2]

### 163. HeadsUp: add timeout option (1/2)

### 164. SystemUI: HeadsUp blacklists [1/2]

### 165. base: Lockscreen no blur option: fix SysUI FC

### 166. base: Lockscreen art blur: smaller seekbar range and allow no blur

### 167. base: Lockscreen blur level: code fixes

### 168. base: configure lock screen media artwork blur level [1/2]

### 169. NotificationMediaManager: Fixup lockscreen media art toggle

### 170. Fix lockscreen wallpaper not being set if different from the Home one

### 171. SystemUI: Hide lockscreen media art if nothing is playing

### 172. base: Bring back lockscreen media art [1/2]

### 173. NotificationPanelViewController: set FLAG_IMMUTABLE for edge lightning

### 174. TwilightService: Save and use last fetched location

### 175. TwilightService: Use temporary TwilightState when location is not available

### 176. SystemUI: Ambient Edge Pulse layout [1/2]

### 177. base: Fix edge lights when sensitive notification content is hidden on keyguard

### 178. base: Only allow edge lights on AOD when AOD is enabled [1/2]

### 179. base: Ensure edge lightning is off when we are done with repeats

### 180. base: Allow using wallpaper color for notification pulse

### 181. base: Add animation duration & repeat count for notification pulse

### 182. base: Reorginize light pulse color options in one setting

### 183. SystemUI: fix notification light pulse for repeating notifications

### 184. SystemUI: fix possible case where aod stays on after notification pulse

### 185. base: Support using notification color for pulse light

### 186. SystemUI: day 0 notification light pulse fixes

### 187. base: Add custom color to ambient pulse notification lights

### 188. base: Add timeout for ambient notification pulse

### 189. SystemUI: Add Ambient Lights always on hide aod content option

### 190. base: Cleanup notification pulse values

### 191. SystemUI: replace pulse light drawable with our own vector

### 192. SystemUI: kill any leftover notification pulse on new pulse start

### 193. base: Pulse light accent color option

### 194. base: Trigger pulse light only for notifications

### 195. base: add Pulse and Ambient notification bars

### 196. base: add option to enable AOD on charging only [1/2]

### 197. base: Option to Display Data Disabled Indicator Icon [1/2]

### 198. ActivityThread: Remove Failed to find provider info logspam

### 199. base: Reduce NotificationHistoryDatabase logspam

### 200. PowerUI: Mute logcat spam.

### 201. SystemUI: Optional haptic feedback on back gesture [1/2]

### 202. ViewConfiguration: Misc improvements (rev 2)

### 203. base: allow to swap volume buttons rotation based [1/2]

### 204. SystemUI: Correctly update brightness slider settings

### 205. base: QS brightness slider settings: tunables -> Settings

### 206. SystemUI: QSAnimator: Properly animate bottom brightness slider

### 207. BrightnessMirrorController: Don't show auto brightness icon when it's disabled

### 208. [SQUASH] SystemUI: Port brightness slider changes

### 209. base: Supress telephony crashing platform

### 210. core: PinSet: fixup and improve code

### 211. overlays: Fix inactive state Wifi Icon in Circular,Filled Kai Icon Pack

### 212. Restore cache clean up code in PackageManagerService

### 213. SystemUI: Add AOD QS tile

### 214. base: Legacy WFD output video mode settings [1/3]

### 215. base: Disable debug

### 216. base: IS_DEBUGGABLE -> IS_ENG

### 217. fwb: drop some debug

### 218. NfcTile: Don't create an error when editing tiles

### 219. fwb: silence statx boot spam

### 220. base: Double tap to trigger doze [1/2]

### 221. SystemUI: Fix signal bar icon overlay issue

### 222. base: Properly regenerate the share drawable.

### 223. base: Make center clock follow paddingTop

### 224. base: Allow additional padding for center clock

### 225. PowerManager: Add proximity check on wake

### 226. base: Add Touch HIDL support

### 227. BatteryService: Add support for OEM fast charger detection

### 228. overlays: let's have consistent indentation

### 229. IconPack{Kai,Victor}: Fix clock icon

### 230. overlays: fixup themepicker package name for IconPacks

### 231. overlays: fixup launcher package name for P20 icons

### 232. SystemUI: Fix size of icon of vibrate ringer mode for additional icon packs

### 233. overlays: Unify icon packs category name

### 234. overlays: bring back icon packs

### 235. SystemUI: allow changing the length of gesture navbar [1/2]

### 236. base: allow hiding navbar [1/3]

### 237. SystemUI: allow to limit the max framerate of built-in screen recorder

### 238. overlays: Remove Noto Serif + Source Sans Pro font style

### 239. base: TtsEngines: fix yet another NPE

### 240. TtsEngines: avoid crashes caused by null engine name

### 241. base: Volume Rocker Wake [1/2]

### 242. KeyStore: Add getApplicationContext method required for Asus Devices

### 243. SystemUI: Allow toggling combined signal icons [1/2]

### 244. styles: Use user fonts for Material UI themes

### 245. SystemUI: Don't confuse rotation with orientation

### 246. base: Less boring heads up option: always show alarm clock headsup

### 247. base: Less boring heads up option [1/2]

### 248. base: Allow to suppress notifications sound/vibration if screen is ON [1/2]

### 249. base: Add colors to assistant animation

### 250. base: Allow Launcher3 to use android.permission.FORCE_STOP_PACKAGES

### 251. BatteryMeterView: Allow disabling QS battery estimates [1/2]

### 252. QuickStatusBarHeader: don't disable estimate mode for centered notch devices

### 253. EnhancedEstimates: Rewrite estimates in kotlin

### 254. EnhancedEstimates: Get estimates from Device Health Services

### 255. base: Remove aosp's 'show battery percentage' setting

### 256. SystemUI: tuner: Hide battery options

### 257. Battery icon: fix requestLayout() calls spam when in lockscreen

### 258. Battery icon: fix signal icon padding when using Hidden style

### 259. Battery options cleanup [1/2]

### 260. Battery Styles: Remove unneeded function parameter in BatteryMeterView

### 261. Battery Styles: Introduce full circle battery style

### 262. Battery Styles: Hide plus when showing battery percentage inside icon

### 263. Battery Styles: Readd dotted Circle to Kotlin impl

### 264. Battery Styles: Show a bolt ⚡ when charging

### 265. Battery Styles: Bring back good ol' circle battery style

### 266. Revert "SystemUI: Implement hide gestural navigation hint bar [1/3]"

### 267. Merge tag 'android-12.1.0_r4' into 12.1

