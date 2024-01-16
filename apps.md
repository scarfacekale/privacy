# Privacy Apps
- A little foreword before I start the list. This list is meant for Android, and Android only. If you manage to find some of these apps in the App Store on your iPhone, well done. But this list is meant for Android. If you want to upgrade your privacy and security, the first step is making sure you have a secure device, without a secure device to operate on, the apps you run are next to useless. I strongly recommend you buy a Google Pixel and install GrapheneOS or CalyxOS on it preferably, if this is outside of your budget, please try to buy a cheaper Xiaomi phone that supports official LineageOS. LineageOS is the next best privacy operating system next to GrahpeneOS and CalyxOS. It's not as secure but it will be perfectly fine for most privacy enthusiasts. If you would really want to you could download it on a Samsung, or OnePlus, Motorola, with or without custom ROM. But it would still dramatically decrease your privacy and security compared to the other options I listed above. On that note, let me continue to another topic. Any app you find here that is available in the Google Play Store, I would not recommend downloading. Don't get me wrong, don't avoid downloading the entire app. But avoid downloading it from the Google Play Store. You have no idea if they injected it with hidden telemetry or spyware. Of course you can check it using Exodus but then it might already be too late. I always recommend trying to get it from F-Droid or the APK from the official website first. Not a third party APK mirror or the Google Play Store.

## Package managers
- These apps are alternatives to the Google Play Store, which is privacy invasive, bad reputation for keeping apps malware free, is slow and sluggish, and a massive privacy and security concern on your mobile device.

### [F-Droid](https://fdroid.org)
- This is a fully opensource and maintained package manager that only allows opensource applications on their platform, the codebase of the apps on it are verified by the maintainers, and if there is any non-opensource code present in the code, such as the backend it uses. Then the maintainers will give you a headsup before downloading the app.

### [Droid-ify](https://github.com/Droid-ify/client)
- If you care about looks a lot and you think F-Droid is too old looking. Since F-Droid is opensource there is many alternative apps to use for the same repositories. You can use Droid-Ify to also browse, download, and install applications from F-Droid with a much more modern look.

### [Aurora Store](https://auroraoss.com)
- If you are still not convinced to use F-Droid, Aurora Store can also be downloaded which directly forwards apps from Google Play Store, so yes, you can still download any apps from here. It forwards them anonymously over their own network so you never interact with the real Google Play Store using an anonymous account.

## Browsers
- These are all privacy and security hardened browsers, some based on Firefox, some based on Chromium. Pick whichever suits you better

### [Tor Browser](https://www.torproject.org)
- What would this list be without the Tor Browser? Yes this is the absolute best browser you can use for privacy and security. It's a Firefox fork with many adjustments such as routing all your traffic over the mostly secure TOR network. If you want maximum privacy and security. I recommend using this browser. Naturally the performance here is the biggest downside. Websites can load pretty slow at times, but if you don't mind this downside. There's no better browser.

### [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos)
- This is probably the most hardened Firefox fork for Android out there. It comes with many tweaks and many adjustments to make you safer while browsing, however naturally this also comes with performance downsides.

### [Fennec Firefox](https://f-droid.org/packages/org.mozilla.fennec_fdroid)
- This is a very good Firefox fork, with a great balance of privacy security and performance, if Mull feels too slow for you, I suggest you give this a try.

### [Bromite](https://www.bromite.org)
- This is the only Chromium based browser I will list, it's a very good chromium fork with great privacy features, such as a built in ad-blocker. If you like Chrome over Firefox, give this a try. You probably wonder where Brave is on this list. I personally do not consider Brave to be a very good or secure browser, it probably gets the job done but theres many way better alternatives out there.

## Password Manager
- Everyone should use a Password Manager, and I mean literally everyone. The world would be a better place.

### [Bitwarden](https://bitwarden.com)
- A very good and secure opensource password manager hosted in the cloud. Completely free, with a paid option. Easy to use, fast, compatible, and well maintained.

### [KeepassXC](https://keepassxc.org)
- For the more die hards out there that do not want their passwords stored in a cloud. You can use KeepassXC which stores all your passwords locally on your device, you can get it to sync using syncthing or other services, it's a bit of a hassle to setup. But it's worth it if you want local passwords.

## Authenticator
- Ideally, you want to setup 2 factor authentication on as much apps as you can that are of value. But most people use Google Authenticator for this, which kind of defeats the purpose.

### [Aegis](https://getaegis.app)
- A feature rich, clean 2 factor authenticator app with backups.

### [FreeOTP](https://freeotp.github.io)
- Same deal as Aegis, but older and smaller.

## Keyboard
- This is most likely overlooked by many people. But it's very important, if you don't have a secure keyboard to type on, then does it really matter which app you use to type it on?

### [Open Board](https://f-droid.org/packages/org.dslul.openboard.inputmethod.latin)
- A perfect GBoard alternative that has every feature you could want with a low footprint.

### [Android Keyboard AOSP](https://www.apkmirror.com/apk/lineageos/android-keyboard-aosp-2)
- Preinstalled on custom ROMs such as LineageOS. My personal favorite, simple to use, clean UI. Material You support, and no clutter or useless things on the display after editing.

## VPN
- A VPN app can help you stay anonymous in the internet if you know how to use it, this means no contamination with your personal accounts, so turn the VPN off for things like Whatsapp or GMail if you use that. But it can greatly increase your anonymity if you use a secure one.

### [Mullvad](https://mullvad.net)
- A very secure and open source VPN service that accepts every payment including even cash! They store the data in RAM instead of disk which makes it very hard to extract any sort of meaningful information from it. They recently got raided by police and they had no data on their customers. They are a cheap top notch VPN provider you should definitely consider.

### [Crypto Storm](https://cryptostorm.is)
- If you are a bit more paranoid and you prefer a smaller more underground solution, you can try this service! They go in great detail how they secure their servers and they offer a wide range of secure encryption and hashing algorithms for communication.

### [Self host](https://github.com/angristan/openvpn-install)
- Whether you use OpenVPN or Wireguard, it's easy to set your own VPS up with an OpenVPN server or Wireguard server to protect your identity. This way you know for sure that nobody is spying on you. However it also comes with downsides in my opinion. You are the only one using the server so you don't blend in like with other VPN services like Mullvad where multiple people use the same server. Tor also makes great use of this approach by making every user look the exact identical same so it's very hard to track you.

## Firewall
- A firewall app can help you exactly choose which apps get internet permission, which don't and which websites or telemetry endpoints get blocked.

### [Rethink DNS Firewall](https://rethinkdns.com)
- This app is a DNS, Firewall, and VPN client all in one, I strongly suggest you try it, its easy to use, flexible, modern, fast, simple to understand. You can manually choose blocklists in the settings for all kinds of goals, such as blocking malware or ads, or tracking.

### [AFWall+](https://play.google.com/store/apps/details?id=dev.ukanth.ufirewall)
- An honerable mention, it's also a very good firewall, but it requires root permission. This makes it very powerful but also less easy to install. It's very good like Rethink DNS Firewall, but my preference goes out to Rethink.

## Camera
- Everyone needs a camera app on their phone, whether you have a custom ROM or not.

### [OpenCamera](https://f-droid.org/en/packages/net.sourceforge.opencamera)
- This camera application usually does the job, the quality isn't very good but it works and is fully opensource

### [GCam](https://www.celsoazevedo.com/files/android/google-camera)
- Yes it is quite surprising to find it on this list isn't it? I will give you my personal take on the matter. If you use a firewall and block the internet access of gcam, then you can probably, most likely, safely use it. You won't have to sacrifice any convenience for this one

### Preinstalled camera app
- Much like GCam, you can simply block the internet access of the camera app and use it for your daily needs.

## Communication
- These are apps I consider safe to use to send any type of message or image on. Note that all of these apps are fully opensource, and will stay opensource

### [Signal](https://signal.org)
- This is the best Whatsapp alternative. This can be used to chat with people that use Whatsapp, they'll most likely use it if you really want them to, its fast, good UI. and good features, but requires phone number, also end to end encrypted with a very strong protocol spec

### [Wire](https://wire.com)
- This is also a Whatsapp alternative, it's not as good as Signal I would personally say. But it's still very good and easy to use. It's mostly used for businesses, and it's crerated by a Swiss organization.

### [Element](https://element.io)
- This is a matrix client. Matrix is an opensource decentralized chat application with strong end to end encryption, note that the downsides are that usernames are still used. This can be safely used to chat with strangers or online friends

### [Simplex](https://simplex.chat)
- This is what I consider the most paranoid out of all of them, it uses a seperate encrypted chain for sending and receiving messages, these chains are formed over tor, using a fully decentralized network ran by volunteers all across the world, this network also eliminates the concern of being tracked based on a username, since this app uses no usernames.

### [Session](https://getsession.org)
- I also consider this to be highly paranoid. It uses the lokinet network instead of the tor network, it's written by the Oxen foundation and is of course opensource and end to end encrypted and is identified by nothing more than an ID.

### [Jitsi](https://meet.jit.si)
- Opensource voice chatting network. You shouldn't use their official instance since they require you to log in using Google or Github. They were required to do this by police because their network was being used by criminals, but you can still use another instance like Riot's instance. Or self host it.

## Social Media
- Most people still want to use some sort of social media to socialize or lurk on, so I will give some alternatives to Instagram or Snapchat or Facebook here.

### [Mastodon](https://joinmastodon.org)
- A decentralized fediverse network to share all your interests, there's tons of instances out there for any topic you can think of, give it a tr.y.

### [Lemmy](https://lemmy.ml)
- Opensource decentralized Reddit alternative

## Media
- These will be apps to replace things like Youtube

### [NewPipe](https://newpipe.net)
- This is a youtube alternative without tracking, ads, or telemetry. Note that IP is still forwarded to google.

### [Libre Tube](https://libretube.dev)
- This is a Youtube alternative without tracking, ads, or telemetry aswell. Not that your IP will NOT be forwarded to google and instead use a pipe instance. This app is for the more die-hard privacy fanatics, it is still in beta, less stable and sometimes buggy.

### [Odysee](https://odysee.com)
- Fully opensource alternative Youtube network, that allows you to create a channel and upload, or consume content without being tracked, and without censorship.

### [Seal](https://f-droid.org/packages/com.junkfood.seal)
- Youtube video or audio downloader, free and opensource with the highest quality.

## Music
- These are opensource apps to use to listen to music, forget Spotify. this is all you will need (no really I mean it)

### [Metro](https://f-droid.org/packages/io.github.muntashirakon.Music)
- This app is an offline music player, you can download the music from Youtube using Seal, it will save them locally on your device and you will always be able to play them even if you have no internet. App can be found in the F-Droid package manager. 

### [Vi Music](https://f-droid.org/packages/it.vfsfitvnm.vimusic)
- If you find Metro a big hassle to use, you can also use Vi Music. This app directly gets music videos from youtube music with a modern and clean UI. Very fast, you can save music, make playlist, shuffle, repeat. All the functions that Spotify also has without any payment needed and without tracking.

## Email
- These apps are alternatives to the big brother mess that is GMail, Outlook, Yandex, you name it.

### [K9 Mail](https://k9mail.app)
- This app allows you to login to any of your email accounts with any service such as protonmail, disroot, tutanota, GMail, Outlook. So if you MUST use Outlook or GMail for whatever reason, use this app because you won't get tracked from the app, only from the network. Combining this with something like disroot or your own self hosted email is probably the best approach. App can be find in F-Droid

### [Addy](https://addy.io)
- Opensource email aliasing.

### [Disroot](https://disroot.org)
- This is more of a smaller community, completely non profiting. That hosts various privacy related services for free for people to use including E-Mail. If you decide you want to use this since I consider it the best, you will have to manually get verified after signing up by a moderator. They do this to prevent bot users.

### [Proton Mail](https://proton.me)
- If you find K9 Mail too hard to use, or it doesn't appeal you. You can consider using Proton Mail, in my opinion it functions the exact same as GMail or Outlook but with a more privacy focused approach in mind. It also has some neat features like automatically verifying the authenticity of the sender of emails, to prevent fraud or spam mails.

### [Tutanota](https://tutanota.com)
- Same as Proton Mail but a different approach, check out both and see what you prefer.

### [Start Mail](https://startmail.com)
- A paid alternative to the ones above, paid email is often not spied on because you aren't the product, you pay for the product. Something to keep in mind.

## Phone number service
- 

## Cloud
- A lot of people want to use a Cloud service to back their important things up, most people use Google Drive for this. But of course Google Drive is not opensource and they aren't trustworthy of your personal files. There have been cases of Google losing your personal files of thousands or millions of people already.

### [Proton Drive](https://proton.me)
- This is probably the easiest solution to use, much like Google Drive, it's easy to use, sign up for and pay for. But with privacy and security built in. Unlike Google Drive.

### [Next Cloud](https://nextcloud.com)
- If you do not trust someone else to host your files on their computer, (like Google Drive or Proton Drive). You can selfhost your Cloud on your own server at home or somewhere else. Next Cloud is more secure than Proton Drive if you set it up correctly and make use of their end to end encryption feature. I highly recommend you give it a try. It can not only be cheaper than Google Drive or Proton Drive. But also be more secure.

## Navigation
- Everyone needs some kind of navigation in this day and age. The most used ones are Google Maps, or Apple Maps. It's very important to have open-source alternatives to these otherwise intrusive applications. Your location information is very sensitive and can lead to many problematic events.

### [Organic Maps](https://organicmaps.app)
- Probably my favorite opensource app for navigation. It works much like Google Maps, only it is offline and not online. You have to download the region where you live or want to go before hand, incase you lose your internet connection you can still navigate around. It has never failed me and I can always find my way, sometimes even better than with Google Maps.

### [OpenStreetMap](https://www.openstreetmap.org)
- You can use this as an alternative to searching casually when finding a location, it works great and it has a wonderful community.

## Translation
- People often also need a translation app to translate things from various languages for fun or work.

### [Lentil Translate](https://f-droid.org/packages/dev.atajan.lingva_android)
- This app uses an opensource translate backend hosted by project segfault. It works well, the app looks modern and it's very easy to use.

### [Simply Translate Mobile](https://f-droid.org/packages/com.simplytranslate_mobile)
- If any translations are inaccurate, try using this app, it uses Google Translate as backend, but proxies over the data so you don't have to interact with the website or app.

## News
- An opensource way to read news from various media outlets without exposing yourself to their analytics on their websites.

### [Read You](https://f-droid.org/packages/me.ash.reader)
- RSS Feeder for news from for example https://nu.nl. RSS is a text protocol that will allow you to fetch media in plain text from various websites, such as news outlets. The app will simply fetch it from the outlet, and display it in the app in a clean way. You will be able to carefully choose which news you want and don't want and from which outlets you want it.

## Gallery, SMS, Calculator, Voice Recorder, File Manager, Dialer, Clock, Contacts 
- Most people use google apps for these things, however obviously as the rest of the google apps, its invasive, bloated, and should be replaced. There's no real downside of changing it anyway, it's just for a basic task.

### [Simple Mobile Tools](https://simplemobiletools.com)
- This collection of applications covers everything you would need to replace the rest of your google apps on your phone.

### [AOSP Preinstalled Applications](https://android.googlesource.com/platform/packages/apps)
- Custom ROMs like LineageOS ship with the default AOSP apps, you can safely use these instead of Simple Mobile Tools. Otherwise if you don't have a custom ROM. Yes you want to switch them out

## Calendar
- Most people will want a calendar app to write down birthdays and such. Who uses paper these days anyway? Old news.

### [Etar](https://f-droid.org/packages/ws.xsoh.etar)
- An opensource feature rich calendar app with material design.

### [Simple Calendar](https://simplemobiletools.com)
- I put calendar in its own tab because I really like Etar, you can choose which one you prefer.

## Notes
- Most people want a quick notes app aswell, to write quick things down to remember for later. Do you really want Google to know all these things?

### [QuillPad](https://f-droid.org/packages/io.github.quillpad)
- A feature rich note app to replace Google Notes, not much to say about this one.

### [Another Notes App](https://f-droid.org/en/packages/com.maltaisn.notes.sync)
- A Material You, simple, clean, functioning notes app if you find QuillPad a bit too overwhelming.

## Text Editor
- Some of you folks like to code on your phone, well you don't want your coding habits to be patternized so they can later be used to identify you! Here are some opensource alternatives to use for your daily coding routines

### [ACode](https://acode.app)
- A full fledged, feature rich, modern looking, fast, text editor for your phone. You won't need anything else.

## Syncing
- Some people like to sync files, passwords, text documents, you name it locally on devices without a cloud in the mix, such as with using KeePassXC

### [Syncything](https://syncthing.net)
- Completely opensource file sharing application supported on every operating system to sync your personal files between devices with ease.

## PDF Reader
- Most people use Adobe reader, or some other proprietary app to read pdfs. You can easily replace this with an opensource alternative.

### [Librera Reader](https://librera.mobi)
- Nothing much to say, just a pdf reader.

### [Collabora Office](https://www.collaboraoffice.com)
- Nothing much to say here either, just another pdf reader.

### [Pdf Viewer](https://github.com/GrapheneOS/PdfViewer)
- A secure PDF Viewer made by the GrapheneOS developers. It's the simplest out of these all and does the job well.

## Weather
- Well if you're one of these people that needs an app for weather, then you are in luck

### [Geometric Weather](https://f-droid.org/en/packages/wangdaye.com.geometricweather)
- Real time temperatures, daily forecasts with upto 15 days, dark theme, material design.

## Meditate
- Some people like to meditate before going to bed, but its often hard to find an opensource app to do this for you.

### [Noise](https://f-droid.org/packages/com.github.ashutoshgngwr.noice)
- Allows you to play natural noises or artificial noises with a strength, repeat delay, mix and so on.

### [Inner Breeze](https://f-droid.org/en/packages/io.naox.inbe)
- Uses the Wim Hof Breathing Method to help you calm down and relax.

## Fitness
- Many of you opensource enthusiasts are also gym rats, or fitness fanatics. I will of course include apps for you aswell.

### [Paseo](https://f-droid.org/packages/ca.chancehorizon.paseo)
- A simple to use step counter using your device's built-in step sensor.

### [Gym Routines](https://f-droid.org/en/packages/com.noahjutz.gymroutines)
- A simple yet powerful gym app to track your workouts, and your progress.

## Health
- A lot of girls like to check up on their sexual health to make sure they are not missing periods or having delayed periods, or to check when they will get a period. These apps can also help identify whether or not you can potentially be pregnant. It's very useful for especially insecure teenage girls that just started doing things downstairs.

### [Drip](https://f-droid.org/packages/com.drip)
- A fully opensource menstrual cycle and fertility tracker.

### [Euki](https://eukiapp.com)
- Not opensource, but has a good track record of privacy which leads me to believe this is probably your best bet if you want an app to check up on your sexual health. Clean modern looking app that goes straight to the point.
