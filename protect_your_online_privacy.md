# Protect Your Online Privacy

Government mass surveillance exposed by Edward Snowden in 2013 and recent big tech collecting and selling off our personal data, from Facebook selling your data to Whatsapp's invasive new privacy policy, have awakened many people's concern about their online privacy.

But what are our personal data? There are laws to protect our privacy. EU has GDPR (General Data Protection Regulation) to protect the data privacy of its citizen while California has CCPA (California Consumer Privacy Act). Here is how personal data defines in the law,

1. GDPR - personal data -- Personal data is any information that relates to an individual who can be directly or indirectly identified. Name and email addresses are obviously personal data. Location information, ethnicity, gender, biometric data, religious beliefs, web cookies, and political opinions can also be personal data. Pseudonymous data can also fall under the definition if it's relatively easy to ID someone from it.
2. CCPA - PI (Personal Information) -- "Personal Information" means information that identifies, relates to, describes, is capable of being associated with, or could reasonably be linked, directly or indirectly, with particular consumer or household.

Both have a very broad definition to include any data related to a person and in CCPA's case, a household too.

Then the laws define our rights to our personal data, for CCPA,
1.	The right to know about the personal information being collected, used, and shared.
2.	The right to delete personal information collected.
3.	The right to opt-out of the sale of their personal information.

GDPR has similar clauses,
1.	The right to be informed
2.	The right of access
3.	The right to rectification
4.	The right to erasure
5.	The right to restrict processing
6.	The right to data portability
7.	The right to object
8.	Rights in relation to automated decision making and profiling.

Note that those laws only protect their citizens, i.e. you can't claim your right to erasure defined in GDPR if you are not an EU citizen, nor can you claim your right to opt-out if you are not a Californian. But even for people living in the EU or California, is the privacy law enough to protect their privacy? Unfortunately, the answer is no. The laws protect us by requiring the service provider to ask for consent to start collecting personal data which they have to state why the personal data is collected and cannot use the data for other reasons. But that requirement just translated into a long jargon of privacy policy and a checkbox at the end. Most users will simply click our privacy away especially the other option is not able to use the service. Whatsapp's controversial privacy policy update is the first that sufficient users moved away from the service because of the privacy policy. 

# Who Is Collecting Our Personal Data

Companies collecting our information for targeted advertisement, so they can reduce their customer acquisition cost. Facebook is selling targeted ads with the data user provides them, your activities off Facebook, information advertisers may already have and third-party data brokers. Off-Facebook activities are collected when other businesses share the interaction with Facebook through their business tools, e.g. Facebook Login and Facebook Pixel, i.e. Facebook are collecting information about you when you go to some other website and log in via Facebook. Spencer Rascoff, the former CEO of Zillow, said it well in an interview about Robinhood and the short squeeze of Gamestop on CNBC, "If you are not paying for the product, you are the product." They use the data you've given them and make a profit so they can provide the "free" service. For its user, it's time to think about how much your personal data worth.

The data brokers are a large part of the privacy problem. They collect information from various sources, most of them can easily list out all your past addresses and phone numbers, your relatives and friends. Unlike the consumer websites which you know who they are and could exercise your right to be forgotten, most people don't even know they exist and where to find them.

Not just companies, our elected officials are also interested in our personal data. Havard has a report on political campaigns and big data in 2013 which the first two lines in the abstract states this:

"Modern campaigns develop databases of detailed information about citizens to inform electoral strategy and to guide tactical efforts. Despite sensational reports about the value of individual consumer data, the most valuable information campaigns acquire comes from the behaviors and direct responses provided by citizens themselves."

Edward Snowden said in a recent interview with John Stossel that a private company that collected my personal data can sell you a pair of shoes but they can't jail you or bomb you, but a government can and for a lot of people, does. And the data they collected is finite, even though they are large they still wouldn't have your full profile. 

# Not All Laws Are On Our Side

One important law that we should pay attention to is the USA Patriot Act signed into law by President Bush in 2001. It expands the law enforcement power to surveillance with reduced check and balance. Combine with FISA (Foreign Intelligence Surveillance Act) signed into law by President Carter in 1978, and renewed a few times which allows law enforcement to request data from private companies and set up surveillance themselves to spy upon private citizens. The concerns to these laws are similar to that of the Cybersecurity Law of the People's Republic of China, where the US government has a minimum oversight to how it can collect personal information from its citizen, and China has none. But the good news is when the Democrats put up a USA Freedom Authorization Act in 2020 to renew FISA, and tried to rush through Congress by having unanimous votes, it got stopped by Sen Mike Lee and Rand Paul and it never made it to President Trump's desk.  Also, each country has its laws around government surveillance and data privacy, it is important to understand them as best as we can when choosing services. 

# The Threat To Our Privacy

It is unarguable that government mass surveillance brings a bigger threat to our privacy but we still shouldn't underestimate the harm to our privacy from private companies, esp when our personal data becomes a commodity; big tech collecting information of its users, through their otherwise free services, purchase from data brokers or companies, repackage/analysis and sell them.

Last but not least, even for reputable companies, excessive personal data collected is still a threat to our privacy. The company could be hacked and our data being stolen. There are abundant incidents where a vast amount of personal data were stolen from companies and up for sale. Also, companies considered reputable today might not be reputable in the future. It could be caused by senior management change, or we are simply being fooled in the first place. Think of Google's "Don't be evil" corporate code of conduct (which got dropped in 2018 and it also dropped, "providing our users unbiased access to information" with it), think of Facebook when we are all happily posting personal pictures and stories to our friends, are they still trustworthy? 

# Protecting Our Privacy Starts From Us

The best way to protect your privacy is to limit the amount of information a company can collect about you. Below is a list of steps I do and the rationale behind why I believe that is important.

I've divided everything into two areas. Networking, from your computer to the website, and, on-line services, like websites, on-line storages, or instant messaging applications. 

# Networking Level Privacy Protection

Let's start with networking. When we visit a website or use a mobile application, an over-simplified view is the application or browser will go through the operating system, query the DNS server from your ISP/carrier, and then connects to the web services. 

## Operating System
This is the most fundamental element to guard our privacy, however, it's also the most difficult to implement. Linux, like Fedora or Ubuntu, provides a much better privacy option. They are open-sourced, the chance to have spyware hidden is lower as changes (pull requests) are open and other users can check them. However, not all software runs on Linux, for me, not able to use Adobe Photoshop, Lightroom and InDesign is a deal-breaker, for my wife, it is AutoCad. There are ways you can run Windows applications on Linux, like [using WINE](https://linuxhint.com/install_adobe_photoshop_linux/) or [using Virtual Machine](https://all3dp.com/2/autocad-for-linux-ubuntu-how-to-install-it/). Unfortunately, both require quite a bit of technical knowledge to get them working, and often, with lower performance and stability. 

Windows 10 is arguably the worst among all operating systems, your OneDrive data, Cortana searches, and MS browse history could be sold to third-party according to Microsoft's privacy policy. But if you couldn't bite the bullet and switch to Linux yet, you could run [WindowsSpyBlocker](https://github.com/crazy-max/WindowsSpyBlocker/releases) to remove some data collection points from Windows 10. To run this,

1. download WindowsSpyBlocker.exe from the Github page. Note, if you have a virus scanner, it will be marked as infected.
2. run the program, it will open up a text-based window.
3. choose 1 for Telemetry
4. then 1 for Firewall
5. then 2 to Add spy rules
6. then 3 to Add update rules
7. then enter "back" to go back to the Telemetry menu
8. then 2 for NCSI
9. then 2 to apply Debian NCSI
10. at last, enter exit to quit the program

This will add firewall rules to Windows to block traffics to known Windows telemetry endpoints. And NCSI stands for Network Connectivity Status Indicator. It works by performing a DNS lookup of a Microsoft hostname and download a file from it. This is providing Microsoft our IP address and time, although TechNet says the server's log is not used to identify users. WindowsSpyBlocker provides an easy way for you to use Debian (a Linux distribution) instead, this is shifting the trust from Microsoft to Debian developed by a community-supported Debian Project.

Windows 10 has a few privacy settings to play around with, go to Settings -> Privacy -> General, you can turn off advertising ID and other tracking options. Settings -> Privacy -> Location Privacy Settings, you can turn off the location service altogether or not allow (selected or all) apps to access your location. Settings -> Privacy -> Contacts Privacy to not allows apps to access your contact list. Settings -> Privacy -> Speech to turn off speech recognization (and won't be to speak to Cortana). There are tons of other features you either can turn off or limit access to only certain apps. Last but not least, Settings -> Cortana Permission, remove all permissions for this device, and unlink all services from Cortana. 

[PrivacyTools.io](https://www.privacytools.io/operating-systems/) recommended a software name "W10Privacy" which allows you to have an easy interface to configure all those settings. I haven't tried it personally as I believe it is enough to go through the privacy settings and turning everything off. 

## Mobile Operating System

Nowadays, we are likely to spend more time on our mobile phones than our desktop/laptop computers. The privacy of our phones is thus, very important. Unfortunately, just like the operating systems for desktop/laptop computers, it's something very difficult to accomplish.

For Android users, installing Google service would compromise your privacy on your phone. To avoid installing Google service, you'll need to install a custom ROM. These custom ROM are built from Android Open Source Project (AOSP) and will not contain any Google services as Google only open-sourced the Android phone but none of the Google services. [Lineage OS](https://www.lineageos.org/) (previously CyanogenMod) is one of the best available. However, it only supports a limited list of devices and the process to flash a custom ROM onto a 600+ phone is, indeed, scary. It's worth mentioning here is that I have flashed my phone many times and have never bricked (e.g. a boot loop, thus unable to access the menu required to flash the phone) my phone. Also, some of the applications, like Uber or Lyft, would not work without Google services as it's leveraging some Google API to get network location or payment. [MicroG](https://microg.org/) reimplemented the proprietary Google Play Services with Free/Libre and Open Source Software (FLOSS) replacement. To embark on this journey, you'd have to start with a phone compatible with Lineage OS. 

[F-droid](https://f-droid.org/) is a Free and Open Source Software (FOSS) replacement for Google Play Store. Please be aware that even though F-droid itself is free and open-source, and it's not tracking you, but the application you downloaded from it might not. 

A lot of Android phones are loaded with bloatware from the carrier and Google. To disable them, go to Settings -> Apps -> (application) -> Disable. While we are browsing the list of applications installed, go through each of the application's permissions (Settings -> Apps -> (application) -> App permissions) and make sure every single one of them has a good reason for it, pay special attention to permission for the microphone, camera, contact, and location. Some bloatware can't be disabled, but some permissions can be denied. Unfortunately, some apps can't be disabled nor any of their permission can be denied, e.g on my LG phone, there is an LG IMS app which I don't know what it is and can't be disabled and none of its permission can be denied. To find a list of applications permitted to use the location service, go to Settings -> Locations. Most apps don't need continuous location service, choose "Allow only while using the app" to avoid accessing your location in the background. At last, those locked down bloatware could be uninstalled with a pro version of Titanium Backup if you have rooted your phone. 
Here is a list of software that I've disabled, Chrome, Duo, Google, Google Pay, YouTube, and a few from my phone's manufacturer and carrier.

### A note on rooting and installing custom ROM.

To root your phone, go to [Root Master](http://www.rootmaster.co) and download the APK. But note that some apps detect if the phone is rooted, e.g. Pokemon Go. You can unroot your phone by downloading SuperSU from Google Play and run full unroot. Also, note that Samsung phones have a KNOX system which will be tripped if you root or flash a custom recovery/ROM. It will void your warranty and won't receive over-the-air (OTA) updates in the future. 

## Router

At home, your computer and your phone are likely connected to the Internet (your ISP) using WIFI. Your computer/phone connects to your WIFI access point which connects to your router to your ISP through a modem (cable modem or DSL modem depends on your service provider). If you are renting a router from your ISP, it has a WIFI access point, router, and modem all in one piece of hardware. 

I am not aware of any incidents that router manufacture is found to leak or collect user's information, but it is possible. After all, all your Internet traffic AND local traffic goes through the router. However, if you'd like to be absolutely safe, you can install an open-source firmware, like OpenWrt to replace the factory one. As with flashing custom ROM for Android devices, you'll have to start with OpenWrt and choose a device that works with it. But the good news is, installing OpenWrt is quite easy, you just have to follow your router's upgrade firmware instruction (however, flashing it back to factory settings is another story). There is a lot of configuration available with OpenWrt, and unlike your manufacture firmware, most of them require a lot of expertise to install and configure. If you are not tech-savvy enough, it would be a bumpy ride filled with frustration and sadness.

## VPN/DNS/Internet Service Provider/Wireless Carrier

When you enter a URL on your browser, your computer will first contact a DNS (Domain Name Service) server to resolve the hostname into an IP address. The IP address is the real address the network finds a route to the destination server. The usual setup is your computer query your router as a DNS, which will forward to the DNS that your ISP assigns you. The ISP's DNS doesn't resolve the hostname for you but will kick off a chain of communication to find the DNS server that does have the information. Since DNS query is plain text, your ISP might not know the exact page you're visiting, but it will know at what time which website you have visited. And of course, it has your real personal information and can link the traffic directly to you. Your ISP can also combine with the actual traffic, to determine the type of traffic it is especially if the traffic is not encrypted (i.e. HTTPS). Nowadays most websites have HTTPS (on your browser, the little lock icon on your address bar indicates it's using HTTPS). It's a big red flag if you see a disabled sign overlaying the lock, most browsers will first warn you before letting you browse that page. That would indicate the website is not using a valid certificate, the name for the certificate doesn't match the website you're visiting or it's expired. An HTTPS (or rather TLS, Transport Layer Security) certificate is a digital envelope containing the website's public key. A simplified way to demonstrate how it works is the website will present its public key to the browser (thus the lock icon), the browser will then generate an encryption key, encrypt it with the server's public key and send it to the server. Since the server is the only one with the private key, only that server can read the encryption key the browser generated. Now all traffic forward is encrypted with the encryption key. Note that when the browser first receives the public key, it'll also verify if it's signed by a trusted party, known as Certificate Authorities (CA). The browser is preloaded with those CA's public keys, so it can use it to verify if the website's public key is signed by one of the trusted authorities. It will also warn users if the website is using an outdated encryption algorithm and key sizes, i.e. it can be a brute force within a reasonable time frame. The list of good algorithms and key sizes would change as hardware or algorithm improves, it is one of the reasons why it is important to update your browser. With HTTPS, your ISP couldn't see the content of your traffic, but it can still know where you are connecting to. 

To block your ISP from getting that info, you can use a Proxy or a VPN service. A proxy allows you to connect through another server that connects to the destination website on your behalf. It won't add additional encryption to your traffic, not helps with ISP collecting your traffic through their DNS. A VPN service, on the other hand, can provide a lot more services to protect your privacy and security as it's creating a virtual network making your computer appears to be on their network. I've tried two VPN services, ExpressVPN and ProtonVPN. Both are excellent. ExpressVPN has an advantage over other VPN providers is they provide firmware to your router. Thus, without any settings, every piece of equipment in your house connecting to the Internet will enjoy privacy protection. Unfortunately, the firmware has a speed limit that will slow down your Internet access. 

One of the services a VPN provider provides is DNS-over-HTTPS. Your devices already support it, however, not your ISP/carrier. Google provides a free DNS-over-HTTPS service and if you are using a Proxy server and somehow you trust Google's privacy protection, that would also protect you from your ISP's prying eye. 

Some VPN services, like ProtonVPN, also provides malware, tracking, and ad-block, connection to known offending sites are blocked on the network level. And after you've installed the VPN software, go to [ipleak.net](https://ipleak.net) to make sure no DNS or IP is leaked.  Another benefit for using the DNS server with a VPN is, like ProtonMail, the DNS server is within the VPN, i.e. the traffic won't go over any other provider unencrypted.

One of the annoyances of using a VPN is that it's a constant war between the VPN provider and some websites, like Netflix which limit its user's location. Some have legitimate usage, like Netflix where some videos are available only to certain regions, a user with a VPN hides their origin, thus, allowing the user to see contents that shouldn't be allowed in their region. Other websites block VPN traffics as other than security and privacy concerning users, hackers and other illegal activities also want to hide their identity and origin. Firewall and admins will block a whole block of IP addresses to stop illegitimate traffics from coming to their site. Thus, we sometimes have to disconnect and reconnect to a different server, thus getting a new IP address to access some websites. In this regard, ProtonVPN seems to be doing pretty well. 

Other than VPN, there's, in fact, another option, Tor. It is a browser aiming to protect our privacy and against censorship. It also has a [hardware router solution](https://torrouters.com/). Tor works by using a random algorithm to find different routes over its vast network of machines, each link encrypted and leave no traces. Although it's secure, it doesn't provide DNS-over-HTTPS and it's significantly slower, I gave up within a week. 

## Browser

A very detailed study by Douglas J. Leith, School of Computer Science & Statistics, Trinity College Dublin, Ireland in 2020 shows that among Brave, Chrome, Firefox, Safari, Edge, and Yandex, Brave is the only browser with default settings not sending any trackable information back to their backend servers. Edge and Yandex both send persistent identifiers and cannot be disabled by users. Brave is the best choice here, but I have troubles with their user experience and some feature on some site doesn't seem to work, I have decided to use Firefox. Firefox's default settings have several telemetries turned on and some convenient features, like the type-a-head suggestion in the address bar, or spell-check in text input fields, turned on. Fortunately, it can be easily disabled with the help of [Firefox profilemaker](https://ffprofile.com). All you have to do is to visit the webpage, a few options to choose from, and download the profile as a zip file. It's an open-sourced project and has an active community making it more trustworthy to use. Here are the steps to create a new private browsing profile.
1. Go to [Filefox profilemaker](https://ffprofile.com) and on the "Annoyances" page, 
    1. set "Content to new tab page" to "Empty"
    2. optionally disable autoplay
2. on the "Browser Features" page, 
    1. by default, it disables all Google stuff 
    2. DNS-over-HTTPS is also disabled by default, that's because it's using Cloudflare which is owned by Microsoft. Also, if you are on a VPN with DNS-over-HTTPS support, this is not necessary.
    3. so, nothing needs to change on this page.
3.	on the "Privacy" page, 
    1. the default settings here are fine.
    2. Optionally, you can change the user agent (it's a text string browsers sent out so websites can respond with a page specific for the browser.) However, it can also be used to identify you if you're using an uncommon browser. 
    3. Disable search suggestion
    4. Disable search keywords
4. on the "Website tracking" page, 
    1. enable "resistFingerprinting" but it would likely make recapture more difficult. You're likely to get more images to pick before it determines you're a human.
5. on the "Security" page, 
    1.  Optionally, you can uncheck "Disable automatic updates". If you're going to update your browser when a new version is available, you might as well just let the browser update itself.
	on the "Addon" page, 
    1.	install "Decentraleyes" extension
	on the "Enterprise Policies" page, 
    1.	leave everything as default
	Finally, download profile.zip on the "Finish" page. 
    1.	open a Command Prompt (click on the Windows button, and type command prompt)
    2.	type the following, "C:\Program Files (x86)\Mozilla Firefox\firefox" -no-remote -ProfileManager
    1.	it will open a "Firefox - Choose User Profile" window
    2.	Click "Create Profile" and give it a name.
    3.	Click "Start Firefox", a new Firefox using the new profile will be opened.
3. On the new Firefox, enter "about:support" in the address bar  
    1.	Click "Open Folder" on the "Profile Folder" row. You should see a File Explorer window opened, that's all the files for the newly created profile. We are going to delete everything and replace it with the one from Firefox Profilemaker.
    2.	Close the new Firefox window as it will prevent you from deleting the profile files.
    3.	On the File Explorer window, delete everything in the folder but not the folder itself.
    4.	Open the profile.zip file, it'll launch another File Explorer window. Copy everything to the profile directory.
4.	From the "Firefox - Choose User Profile" window, click "Start Firefox" again. 
    1.	Firefox with the new profile will be launched.
    2.	on the "CanvasBlocker presets", choose one of the options. I've chosen "Stealth settings".
8. You can go to, [EFF Cover Your Tracks](https://coveryourtracks.eff.org/) to test your browser's privacy protection. 
    1.	Unfortunately, at this point even though we have strong protection against web tracking, but our fingerprint is still unique.
    2.	The page has a lot of details about how websites are tracking our identity. The user-agent our browser is sending and can collect a surprisingly large amount of information about my computer, like screen size, timezone, system front, canvas fingerprint (we have Canvas Blocker to spoof that), WebGL fingerprint, the graphic card, and driver, audiocontext fingerprint (depends on the audio card).
    3.	With that, we'll first spoof our user-agent.
9.	Go to "about:addons", 
    1.	Search for and install "User-Agent Switcher and Manager". The most common user-agent is probably the latest version of Chrome on Windows 10, which should be a good choice.
    2.	A more advanced option is to cycle between two or more user-agent, 
    3.	Click on the addon's icon
    4.	Click options
    5.	Click Custom mode and enter this,
    ```json
    { 
    "*": [ 
	    "Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.7113.93 Safari/537.36", 
	    "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:86.0) Gecko/20100101 Firefox/86.0" 
	    ]
	}
    ```
    7.	You can test the settings by going to [whatmyuseragent.com](https://whatmyuseragent.com/) and refresh the page. You should see the user-agent changes between refreshes.
    8.	This helps reduce cross-site tracking so when I logged onto one website, an Ad fingerprinted me, then I open another webpage with the same Ad provider, it would fingerprint me again only to get a different user-agent which can help skew their logic to uniquely identify me. (Note that user-agent is just a small part of fingerprinting, but it helps when we create variances to make it more difficult to track.)
    9.	Install "Facebook Container" to put Facebook in jail. Facebook Pixel can collect data when you visited websites using its service (usually pages that have a Facebook like-button), even if you haven't press that button.
10.	Go to "about:preferences#privacy" 
    1.	set "send websites DO NOT TRACK signal" to always
    2.	uncheck everything under "logins and passwords"
    3.	set "HTTPS-Only mode" to all windows
11. Go to https://qwant.com and click "Add Qwant to Firefox" 
    1.	Go to "about:preferences#search" and make sure the default search engine is Qwant.
    2.	Remove Google, Amazon, Bing, eBay, DuckDuckGo, and Wikipedia from "Search Shortcuts" by clicking the name and click the "Remove" button.
    3.	Note, it's probably because search suggestion is disabled, searching on the address bar now by default treated as a URL. But all you have to do is click on the Qwant icon under "This time, search with" in the pulldown and hit Enter.

### Privacy, Like Security, Comes With A Price

Now we have a setting with much better privacy protection. However, that comes with a price. Searching on the address bar is less convenient and you won't have suggestions. Some websites won't work at all, like the Firefox Profilemaker site has a link to a page showing your current user-agent setting and how common it is. [That page](https://techblog.willshouse.com/2012/01/03/most-common-user-agents/) is protected by Cloudflare against DDOS attack, but the way it works is by getting the fingerprint our browser, Canvas Blocker, uBlock, User-agent Switcher and Manager and the browser settings we choose earlier works together so Cloudflare couldn't fingerprint the browser, thus, Cloudflare blocked us from accessing that webpage. I've tried disabling uBlock, Canvas Blocker, and User-agent Switcher for that page but it's still not getting past Cloudflare. If it's a website that you absolutely trusted, you can bring up the "Firefox Choose User Profile" window and start the old Firefox profile (make sure you uncheck the "User the selected profile without asking at startup" checkbox or install another browser knowing whatever you do there is completely unsafe and would give out your identity.

For most websites, you can disable privacy protection for that site or page so that it will work, but I would recommend looking for alternatives. This is a signal we are sending to the companies to respect our privacy. To enable/disable uBlock, you just have to click on the big power button on the addon's popup. User-agent Switcher and Manager, you can right-click on the addon's icon and choose "Manage Extension", then click on the meatballs menu and choose options. You can add a comma-separated list of websites' domain names to the black-list mode. The same steps can get you to Canvas Blocker's option page. On block mode, the setting should be "fake". Click on the arrow behind it, a list of site-specific values is shown and you can add a site to the list, click the "+" button and choose the block mode for that site.

(todo: sync settings between devices)

### Cautions On Using Addons

We've praised a few add-ons, they do great things to protect our privacy. However, they can also do great harm. At the beginning of 2021, my company's IT remove a Chrome extension named the great suspender from all our browsers (and Google removed it eventually). Turns out the maintainer sold the software to another person and he then made a few releases but the source code is not on GitHub and possibly a trojan is introduced to the new release. My company did the safe thing and remove it from all of our browsers. This incidence is not an isolated case. There are reports in which malicious person purchases well-loved popular add-ons only to put tracking or other ill-intended tools in it. Those add-ons usually have extended permission so they can capture the traffic, modify webpages to deter websites trying to fingerprint us. Great caution and continuous monitoring are needed to make sure we stay on top of the security and reliability of our software. A few things we can do, follow sites such as [Hacker News](https://news.ycombinator.com/), follow security/privacy-focused news feed (I'm still looking for a good one), and even follow the Github project if it's open-sourced on Github (in the great suspender case, the earliest warning showed up on Github but the feed usually cluttered with code changes and other discussions. It is difficult for non-developer to follow).

### Search Engine

I have been using DuckDuckGo ever since I ditched Google Search. Needless to say, Google collects your search and pages you interacted with and sells it. I didn't miss it one day after removing it from all my personal computers. But I recently stumble upon an article, 7 Best Private Search Engine from restoreprivacy.com. 

"The founder of DDG, Gabriel Weinberg, was also behind a social network called Names Database, which collected the real names and addresses of its users. He then sold Names Database (and all the user data) to Classmates.com for "approximately $10 million in cash" in March 2006.
DuckDuckGo was launched a few years later, in 2008, and was branded as a privacy search engine."

Doesn't seem the founder has a stellar record in respecting others privacy and the server is located in the US, it's not a red flag and there is no major incidence (there is one case that it somehow load the favicon from their server instead of the website you're visiting if you are using the DuckDuckGo browser, and they have quickly corrected it.) But if you are uncomfortable about using DuckDuckGo, Qwant is a good choice. Other than privacy, censorship is also another important factor in choosing a search engine. A good test is to search some controversial terms and compare the results between different search engine.  That should give you a clue if the search engine has algorithm favoring any political views.  Also, note that some of the private search engines are using Bing as the backend. They protect our privacy by proxying our search request and strip out all identifiable information. However, since the backend is Bing, it is subjected to censorship if Microsoft decided to censor certain webpages.

## Web Service Layer Privacy Protection

Now that we have a fairly good base, we will look into various web services. A general rule-of-thumb is,

1.	Communication is encrypted,
2.	Better still, End-to-End encryption is used, 
3.	Open-sourced,
4.	Self-hosted or allow users to pick storage,
5.	Supports MFA (multifactor authentication) either with TOTP (time-based one-time password) or hardware keyfob (such as YubiKey)
In this section, I'd like to go over some of the services that I use and why I picked them.  Also, since the focus is privacy here, I am not going to talk about the cost, and most of them are paid services.  I did shop around and compare prices without compromising on security and privacy.

### Email

I'm using ProtonMail as my email provider. 

1.	It is hosted in Switzerland, outside of the US and EU jurisdiction.
2.	It supports MFA using hardware keyfob
3.	It provides End-to-End Encryption (E2EE) where the encryption happens at your client and only the recipient has the decryption key, so all hops from your ISP to the Internet to ProtonMail back to the recipient's ISP can only see the encrypted message and it's mathematically infeasible to decrypt in a realistic time and cost. 

There is controversy about ProtonMail's claim to be E2EE,

1.	It has a web client, where JavaScript on a browser is considered insecure. Encryption keys are more vulnerable to be stolen or hijacked.
2.	Subject lines are not encrypted (for PGP compatibility).
ProtonMail has an official response and even have representative engaged with users on Reddit. 

To me, the biggest concern is their web client, but it is not necessary to use their web client, I use their mobile application and ProtonBridge which allowing downloading my emails to my desktop using Outlook. Of course, if someone filed a FISA application against me and have it approved, I'd have to surrender my emails even though ProtonMail is stored on a server outside of US jurisdiction as I have a local copy. But that's not my concern here, the chance of the government targeting only me is pretty small, the main threat is mass surveillance, not targeted. And that the mobile downloaded them to my phone too. But storing on my local hard disk allows searching. My wife had contacted customer support requesting a search feature and the response is that they can't look at our email so they can't implement search on their web client as the search needs to happen on the server. (One of their pending features is encrypted search, not sure how that can be done. It'd be interesting when they release more details.)

To configure your ProtonMail mobile app, go to Account Settings -> Privacy and make sure Auto-load remote content is off (and I have Auto-load embedded iamges turned on).  The reason to have auto-load remote content turned off is to protect against spy pixel; since the image is retrieved from the sender's server, it can see your IP address or more.

### Calendar

ProtonMail has a new feature ProtonCalendar. It's just like a normal Calendar app, just that it's encrypted like ProtonMail. It is a relatively new service and the major drawback is the application doesn't support reading in other public calendars. 

### Instance Messaging

Both Telegram and Signal are the two most common privacy-oriented instance messaging applications. Signal has a presentation detailing the open whisper system later become Signal and it’s impressive.  The algorithm is very complicated but to summarize, it aimed to achieve perfect forward secrecy (PFS) and a way to establish an encryption key between the two parties without a 3rd party.  Traditional encryption (like RSA) generates a private key and a public key.  Data encrypted with the public key can only be decrypted with the private key and that it is mathematically impossible to calculate the private key given the public key, thus the public key is shared with the other party so it will use it to encrypt any messages coming from that party.  Since the public key is shared in a possible insecure channel, a 3rd party is introduced to certify its validity.  For the TLS certificate (HTTPS) it’s Certificate Authority (CA).  To get rid of that, Diffie-Hellman (DH) is used to establish an encryption key by exchanging public information between the two parties and mathematically with each party’s private key calculated the same encryption key.  Anyone intercepting the communications would only have the public information and would not be able to derive the encryption key.  Note, Signal uses 3XDH (triple Diffe-Hellman) to agree on an encryption key and Double Ratchet Algorithm to keep generating a new key for each message.  Because a new key is generated for each message and you cannot derive the new key with an old one that is compromised, hackers spending days compromising an encryption key would not be able to use that to decrypt any newer messages.  Telegram, on the other hands, by default use server-client encryption, i.e. Telegram server will decrypt your message and re-encrypt it for the recipients.  Only secret chats use E2EE.  

To make sure your privacy is safe with both applications, you will need to change a few default settings.

On the Telegram app, go to Settings -> Privacy and Security

1.	Change Phone Number, Last Seen & Online, and Forwarded Messages to Nobody
2.	And Profile Photos, Calls, and Groups to My Contacts
If you are joining public groups in Telegram, it’s very important to no let other group members see your phone number.  A weak link in a member of the group could leak out your phone number and thus your identity.

And since we are setting profile photos, receiving calls, and allowing others to add you to groups to the people in our contact lists, it’s vital to make sure we have a well-managed trusted contact list.  If that’s not you, it’s better to set them also to nobody and add exceptions to a few friends if needed.

On the Signal app, there is not much we need to change.  Go to Settings -> Privacy, turn on screen lock and incognito keyboard.  You should turn on Always relay calls if you are not on a VPN.  And if you are in, or expected to be in, a more extreme situation where your phone could be physically acquired by a malicious entity, turn on screen lock inactivity timeout (and set it to quickly expires) and turn on screen security (in that case, you shouldn’t turn on any biometric phone unlock and instead requires a PIN).

Signal is clearly more privacy-friendly.  I'd encourage switching over to Signal instead of Telegram.

About Whatsapp’s new privacy policy, it drove away a lot of subscribers to move to Signal and/or Telegram.  The concern is that Whatsapp is sharing personal data collected at Whatsapp to Facebook.  Whatsapp recently posted a clarification and misleadingly citing the use of E2EE so the company cannot read the subscriber's messages.  While it is true, the concern is Whatsapp is collecting our phone number, contacts, and other information sharing to Facebook and not that it is reading our message contents.  With that information even user doesn’t have a Facebook account or friends only connected through Whatsapp but not Facebook, Facebook can finally get that missing link.  So, even Whatsapp is using the same E2EE algorithm as Signal, the privacy protection still differs.

### Online Photo Album

I have switched from Google Photos to SmugMug.  SmugMug has unlimited full resolution storage for photos and videos (not even Google Photos provies that).  But it's hosted in California, i.e. under the juridiction of the USA.  The privacy policy shows it's collecting more information that I'd like but states that it never sold any personal data.  I picked SmugMug solely because of the storage it provides.

Google Photos has a lot of fun and convenient features like face recognition, location detection, similar image detection, panoramic detection, auto-generate video, rotation suggestion, and document archive suggestion.  There might be more and they are probably building more.  However, exactly because of those features, it’s showing you that what Google can collect about you with your photos other than the EXIF (Exchangeable Image Format) which your camera adds metadata like location, time, camera/lens brand to your picture.  Moving to SmugMug would mean we have to give up all those features and go through a rather annoying process to delete everything from Google.

SmugMug has an app to transfer photos from Google Photos directly.  However I haven't use it so I couldn't say to its usability.  Another option is to use Picbackman.  It's a paid application but it could move your photo album around.  I haven't move photos from Google Photos as I have them in my local hard disk, full resolution, I'd rather upload the full resolution file to Smugmug then the scaled down version from Google Photos.  
 
Google Photos does not have an easy way to delete all photos (just as Facebook doesn’t have a way to do that either).  You will have to select a few pictures and delete them.  Luckily, Rishab automated the process.  Head on to [his Github page](https://github.com/mrishab/google-photos-delete-tool), and follow the instruction there.   In addition to disabling loading pictures, I have also zoom out to about 50%, so it can select more pictures every delete.  I have also deleted the following section of the code

```
    if (checkboxes.length <= 0) {
        console.log("[INFO] No more images to delete.");
        clearInterval(deleteTask);
        console.log("[SUCCESS] Tool exited.");
        return;
    }
 ```

which make the deletion more stable (but it won't know when to stop, you'll have to manually close the browser when there is nothing to delete).

There is also a few things to setup in SmugMug.

 1. After logged in, click on your avatar and select Edit My Profile.
 2. Make sure to go over all fields on About Me and Social.
 3. Next go to Account Settings -> Privacy and you can add a password to your site access or only the person you choose (they will need to create an account on Smugmug).  
 4. Turn off Social Sharing Link in Discovery -> Sharing
 5. Turn off searching in Discovery -> Search -> Site Visibility.  Set Google Search Visibility to No and SmugMug Search Visibility to No - Total Lockdown.

Sharing pictures in SmugMug is a lot more complicated than Google Photos.  To share photos with family and friends, you'll have to add them Account Settings -> Contacts.  Then, create an Album for sharing and invite them to the album.  Afterall, SmugMug is for photographers to build a website to show their works.  

I'm not very satisfied with SmugMug as a Family and Friends sharing app.  However, it's the only one I found which can hold the amount of photos I have.

Another solution could be using [PhotoPrism](https://github.com/photoprism/photoprism).  It's a privately hosted app for browsing, organizing, and sharing your photo collection.  [NextCloud](https://nextcloud.com/) is not a photo app but a self-hosted platform for collaboration, file management/sharing, and even calendar.  It also has a photo app in it.  Since it's self-hosted and open-sourced, we have better control of the security of our data.  However, if the security of the cloud hosting is not done correctly, it could expose your data into bigger danger.  

### Notes and Webpages bookmarks

[Joplin](https://joplinapp.org/) is an open-sourced and note-taking application.  It's like Microsoft OneNote but it doesn't have a centralized storage.  It has a desktop application and mobile application.  You can configure the backend storage so we have control on where the data is stored and we always own the data.  It also supports E2EE so any document stored are encrypted.  The default uses DropBox, but since everything is encrypted that data stored is safed.  The backend storage providers (in the case, DropBox) could still track our IP addresses (but with VPN, you should be fine) but they couldn't do any other tracking or identification as the Joplin app is calling their API rather than using the web pages.

### Video

If you are using YouTube, at least log out from Google. If you are using Android, you can download [NewPipe](https://newpipe.net/) either from their site directly or F-droid.  It is an open-sourced, privacy-friendly app proxing to YouTube.  You can watch any YouTube videos without Google tracking you and no ads too.  And added benefit, you can download video too.  All data are stored locally on your device and it's not using Google API so it won't leak out our identity to Google.

### Password Management

Most browser will offer to store your password, credit card and addresses for you.  Those are very important privacy data and I wouldn't trust storing them in a browser and sync them across all browsers.  e.g. Google stored the Chrome data on their server.  [BitWarden](https://bitwarden.com/) is a open-sourced, third-party audited (security), E2EE, cross-platform password manager and have an option to self-host.  If you're storing your password on Google Chrome or Firefox, you can easily export them and import to BitWarden.

1. Export from Chrome
    1. go to chrome://settings/passwords
    2. select the kebab menu button (the vertical 3 dots) and select Export passwords
    3. select comma-separate values as format
2. Export from Firefox
    1. go to about:logins
    2. select the meatballs menu button (the horizontal 3 dots) and select Export logins
    3. save the file
3. Import into BitWarden
    1. Logon to bitwarden
    2. select Tools -> Import Data 
    3. select Chrome (csv) or Firefox (csv)
    4. select Import Data
4. Delete all passwords from Chrome
    1. on the same password settings page
    2. turn off Offer to save password
    3. go to https://chrome.google.com/sync
    4. click Clear Data, you will see that there is no saved data on Google servers
    5. go to chrome:/seetings
    6. turn off Chrome sync and click Clear browsing data under Privacy and Security
    7. go to the Advanced tab and select everything and All time, then click Clear data
5. Delete all passwords from Firefox
    1. go to about:logins
    2. click on the top right meatballs menu button and select Remove All Logins
    3. go to about:preferences#privacy
    4. uncheck Ask to save logins and passwords for websites
    5. also uncheck Autofill addresses and Autofill credit cards and remove any saved addresses and credit cards

### A note on OATH2

A lot of websites allows us to register to their services using Facebook or Google login, the protocol used is called OAuth2.  It's a security protocol designed to authenticate a user with a trusted third-party (in this case, Facebook or Google) so the user credential never leaves the trusted party.  The websites then recieves security tokens knowing the user has been authenticated by Facebook and Google.  The website can also reqest some data from the trusted third-party which usually will show up as permission checkboxes on the login popup.  But when Facebook and Google no longer are the trusted-party?  The other websites likely still trust them (that the user is authenticated) but we are providing our connection to the site to Facebook/Google.  I'd recommend using emails and register to the website directly.

### A note on MFA

The best MFA (Multi Factor Authentication) are those support hardware keyfob, like Yubikey.  When you authenticates to those service, you'll have to either plugin the keyfob to a USB port or touch your phone using NFC (Near Field Communication).  i.e even if your password has been hacked/stolen, without the physical key, they hacker still couldn't access your account. TOTP (Time-based One-Time password) is also good.  When you authenticates with TOTP, you'll need to open an authenticator app and it will present a code which will expire in about a minute.  However, if you are using Google Authenticator on your phone and storing your password on your phone, getting access to your phone would acquire both.  A more secure approach is to use Yubikey as the TOTP authenticator storage (Yubico Authenticator).  Since TOTP data are not stored on the phone, acquiring your phone will only get half of the secret.  The worse is the phone-based OTP.  Phone-based OTP tends to be valid for hours instead of seconds in TOTP.  Even Microsoft urges to stop using phone-based OTP.  SMS and voice call are transmitted unencrypted, determined hacker can intercept calls or trick telephone network into sending the MFA to a malicious SIM card known as SIM swapping.

### Social Media

All major social media make a profit by collecting and selling your personal data.  It's time we find others way to connect with your friends and family.

### DeleteMe

A lot of our personal data are already out there and owned by data brokers.  [DeleteMe](https://joindeleteme.com/) provides a services to go through all those brokers and request deletion on your behalf.  

### A note on Web Camera and Microphone

We have covered that we can control which apps have access your camera and/or mic.  On a desktop computer, the easiest way is to connect them to an external USB hub with power button, and turn them on only when needed.  As for laptop, use a webcam cover to cover them.

## References and Good Reads:

1.	[California Consumer Privacy Act](https://www.oag.ca.gov/privacy/ccpa)
2.	[What you need to know about the 2020 California Privacy Law](https://laws101.com/2020-california-privacy-law/)
3.	[What is GDPR, the EU's new data protection law?](https://gdpr.eu/what-is-gdpr/)
4.	[GDPR isn't enough to protect us in an age of smart algorithm](https://theconversation.com/gdpr-isnt-enough-to-protect-us-in-an-age-of-smart-algorithms-97389)
5. [PrivacyTools.io](	https://www.privacytools.io/)
6.	[Facebook and IG are spying on you, and they are not hiding it](https://medium.com/digital-diplomacy/facebook-ig-are-spying-on-you-and-theyre-not-even-hiding-it-41828ac52e1b)
7.	[Facebook knows what you eat: discover the entire data Facebook collects about you, step by step](https://medium.com/digital-diplomacy/facebook-knows-what-you-eat-how-to-visualize-all-the-data-facebook-knows-about-us-c89fe3cb4f89)
8.	[Facebook's targeted Ads are more complex than it lets on](https://www.wired.com/story/facebooks-targeted-ads-are-more-complex-than-it-lets-on/)
9.	[How Target figured out a teen girl was pregnant before her father did](https://www.forbes.com/sites/kashmirhill/2012/02/16/how-target-figured-out-a-teen-girl-was-pregnant-before-her-father-did/?sh=2596d3596668)
10.	[Big data is revolutionizing political campaigning](https://www.talend.com/blog/2016/09/14/big-data-is-revolutionizing-political-campaigning/)
11.	[About End-To-End Encryption (E2EE)](https://joplinapp.org/e2ee/)
12.	[Political campaigns and big data](https://scholar.harvard.edu/files/todd_rogers/files/political_campaigns_and_big_data_0.pdf)
13.	[Firefox privacy - The complete how-to guide](https://restoreprivacy.com/firefox-privacy/)
14.	[7 Best Android Root Software (with or without computer)](https://joyofandroid.com/android-root-software/)
15.	[Knox Enterprise Firmware Over-the-Air](https://www.samsung.com/us/business/solutions/services/mobility-software/e-fota/)
16.	[List of Free/Libre and Open Source apps for Android](https://forum.xda-developers.com/t/index-floss-list-of-free-libre-and-open-source-apps-for-android.3482219/)
17.	[ProtonMail Android Privacy](https://protonmail.com/blog/android-privacy/)
18.	[Off-Facebook activities](https://www.facebook.com/help/2207256696182627?helpref=faq_content)
19.	[How Facebook tracks you, even when you are not on Facebook](https://www.consumerreports.org/privacy/how-facebook-tracks-you-even-when-youre-not-on-facebook/)
20.	[What do Microsoft and NCSI have in common](https://www.techrepublic.com/blog/data-center/what-do-microsoft-and-ncsi-have-in-common/)
21.	[What is SSL/TLS certificate and how does it work](https://protonmail.com/blog/tls-ssl-certificate/)
22.	[Tor overview](https://2019.www.torproject.org/about/overview.html.en#thesolution)
23.	[Web Browsers Privacy: What do browser says when they phone home?](https://www.scss.tcd.ie/Doug.Leith/pubs/browser_privacy.pdf)
24.	[Google removes "Don't be evil" clause from its code of conduct](https://gizmodo.com/google-removes-nearly-all-mentions-of-dont-be-evil-from-1826153393)
25.	[Urgent: Security: New maintainer is probably malicious](https://github.com/greatsuspender/thegreatsuspender/issues/1263)
26.	[EFF Analysis of the provisions of the USA Patriot Act](https://www.eff.org/deeplinks/2003/10/eff-analysis-provisions-usa-patriot-act)
27.	[This is what End-to-End Encryption should look like](https://jitsi.org/blog/e2ee/)
28.	[Is ProtonMail really secure?](https://www.techspot.com/news/82776-protonmail-review-secure-email-really-secure.html)
29.	[Response to analysis of ProtonMail's cryptographic architecture](https://protonmail.com/blog/cryptographic-architecture-response/)
30.	[Make my website completely private (SmugMug)](https://help.smugmug.com/make-my-website-completely-private-BJsgPkNrM)
31.	[SmugMug Privacy Policy](https://www.smugmug.com/about/privacy/)
32.	[What is perfect forward secrecy? A guide for 2021](https://www.cloudwards.net/perfect-forward-secrecy/)
33.	[Demystifying the Signal Protocol for End-to-End Encryption (E2EE)](https://medium.com/@justinomora/demystifying-the-signal-protocol-for-end-to-end-encryption-e2ee-ad6a567e6cb4)
34.	[Here's why ProtonMail is better for your privacy than Gmail](https://medium.com/swlh/heres-why-protonmail-is-better-for-your-privacy-than-gmail-a760fe8c89d6)
35.	[Using Zoom?  Here are the privacy issues you need to be aware of](https://protonmail.com/blog/zoom-privacy-issues/)
36.	[How to Bulk Delete Saved Passwords from Google Chrome](https://windowsloop.com/delete-saved-passwords-google-chrome/)
37. [Microsoft urges users to stop using call & SMS-based multi-factor authentication](https://www.zdnet.com/article/microsoft-urges-users-to-stop-using-phone-based-multi-factor-authentication/)