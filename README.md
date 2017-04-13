# Personal Security Tips

In the age of mass surveillance, your personal information is much more easily accessed by 3rd parties whom you may not necessarily wish to permit accesss. But increased security usually comes at a cost of some convenience. It is up to you to decide how far down the rabbit hole of paranoia you want to fall, but doing nothing only makes you a sucker. Defend yourself.


## If you don't do anything else, do these things

- accept that it *will* happen to you; you're not special
- never use the same password more than once
- use strong passwords (e.g., use `n_*8DkeX@nR0g3=@sAwP!0k` not `12345` nor `p4ssw0rd`)
- use a password manager
- use a passphrase instead of a PIN to unlock your phone
- only bring what you need across the border
- use encryption whenever you can 
- backup everything, often
- be careful what you click and beware of scams; if you don't understand someone, don't do what they say
- use less software, and regularly update what you use


## General

- use less software and regularly update what you do use; if you don't need it, don't use it; the less software you're using in the first place, the lower the risk of an attacker cracking your system; if there's stuff on your devices you're no longer using, delete it
- never ever ever use the same password more than once! each service you use should have a unique password
- use "strong" passwords (e.g., >20 random digits pulling from all the symbols on your keyboard)
- use a password manager to store all your individually unique, and super-strong passwords, so you don't need to remember them and can, thus, make them even stronger (e.g., I use 50-digit random sequences if the service allows it)
- never use a real answer to so-called "security questions" because that information is usually publicly obtainable by potential attackers (e.g., "what's your birthday?"); instead, treat these fields as passwords themselves and generate new, strong passwords using your password manager so that no one could possibly guess them (these "security questions" are usually the most vulnerable, and INsecure, parts of an authentication system)
- use "2 factor authentication" for anything that matters to you (e.g., Google, Facebook, Github, etc.); a strong password is a great first step, but for services that are important, add an additional requirement for authentication (e.g., an app that generates special codes on your phone, a special biometric key like Yubikey, etc.)
- do NOT use SMS as your second factor (plain text messages can be intercepted by attackers and even spoofed so you unwittingly grant access to the attacker)
- use encryption whenever possible; if there's an ecnrypted option and a non-encrypted option, always choose the encrypted option (e.g., when accessing a website, use "https" so that your connection is secure; and question why a website doesn't offer a secure option for connecting with it)
- encrypt your emails by using a secure email service (e.g., Protonmail); Gmail, Hotmail, Yahoo mail can all read your emails, analyze them, and sell the data to others
- use a VPN for browsing; your ISP (and others, like the government) can see everything you're doing on the internet; using a VPN encrypts all your signals between you and the VPN provider (which, obviously, places your trust with the VPN provider now) which at least minimizes the surface area for other 3rd parties to be able to access your online activity (but tunneling through a VPN network can add latency and may not be usable for all tasks; things like gaming, video streaming, and file sharing may become unusable at peak times
- stop putting all your stuff in the cloud, at least if it's not encrypted; anything you put on someone else's server that someone can access/see/read/analyze; if you're going to do it, at least lock it up so only you can access it
- backup all the things! do this as often as you're comfortable with; go buy a big external harddrive (they're cheap these days) and make a copy of all your junk onto it; then, ideally, store that harddrive in a different physical location so that if there's a disaster (like a fire or tornado or something) your data will still be safe (the chances of a disaster happening in two places simultaneously are a lot less likely)
- use full disk encryption on your computing devices; this protects your data from anyone who might gain physical access to your device (like through physical theft)
- do NOT enter your personal information into contests, mailing lists, or websites unless you fully understand why they need your information and what they're going to do with it
- IoT? no thanks. The "internet of things" aims to connect all manner of previously "dumb" devices to the internet so that you can control them remotely. But my toaster makes toast just fine without being connected to the internet; why would I expose myself, needlessly, to an increased surface area for potential attack on my privacy and information security?
- type it yourself; "auto fill" does exactly what it says it does. if someone other than you has your phone, do you really want all your password and credit card fields being automatically filled in?
- disable auto suggest/spelling services; these features take what you're typing, send it over the internet to a cloud server which analyzes what you typed in order to make a set of suggestions and then sends those suggestions back to your computer/device; all of this gets logged on that server, identifies you, and compromises the privacy of what you were typing


## Mobile Devices

- stop using a 4-digit PIN for your password! (use a passphrase)
- use secure communications software; stop using the built-in SMS (texting) app that came with your phone! instead, use an "end-to-end encrypted" app (e.g., Signal, by Open Whisper Systems) which does exactly the same thing but is only readable by you and the person you're texting
- disable fingerprint access (someone could force you to open your phone, could take your fingerprint without your permission, or could just [fake it](http://www.telegraph.co.uk/technology/2017/04/11/smartphone-fingerprint-scanners-could-easily-fooled-fake-prints/); passwords require reading your mind, which is a lot harder)
- only download apps from trusted sources (e.g., Google Play, Apple App Store)
- when you're done browsing, close all the tabs you opened
- when you're done using an app, shut it down
- when you're not using an app anymore, delete it
- keep your OS up to date (updates contain security improvements and bug fixes crucial to staying ahead of the surveillance game)
- when you're not using your phone, turn on airplane mode so it's disconnected from the network
- don't bring your mobile devices across the border (especially the american one) unless you absolutely need them (consider how you feel about granting the border agents access to all the data on your phone and possibly your online social media accounts; if you aren't comfortable with that don't put yourself in a position where it will be possible for them to get access in the first place... if you don't want to hand everything over to them they could confiscate your devices, detain you physically, you might miss your flight and be required to answer questions to the authorities)
- never do anything that requires security over free wifi (the person running the wifi can see everything you're doing); just like ISP snooping, using a VPN can protect your information from prying eyes
- tweak your privacy settings (disable access to all apps/features unless you need them; e.g., does Facebook really need access to my physical location all the time? does Candy Crush really need access to my contact list?)
- turn off notifications (e.g., potentially private information could be displayed on your lock screen, wich an advesary could see, even if they don't have access to the device itself)
- disable Siri/Google Assistant/Alexa/Cortana (you are essentially wire-tapping yourself: these services, by definition, are always listening to your microphone and sending data to remote servers)


## Hardcore

- don't connect your password manager to the cloud (not strictly necessary, and you lose a *lot* of convenience, but some piece of mind that the only possible way for an attacker to get at your passwords is by pwning your one personal computer; not dozens of web servers)
- while you're in transit, put your phone in a faraday cage (or otherwise disable it) to prevent tracking and signal interception (e.g., from imsi-catchers)
- tighten up your "opsec" (operational security; that is, how you operate in the physical world) like, for example, consciously decide when and where you want your purchases to be recorded (e.g., every time you use your payment cards a computer is recording and tracking what you're doing with your money); maybe pay for cash sometimes for things you don't want tracked ;)
- annonomize your online activities by using the Tor protocol; this adds significant overhead (it's slow as fuck), however, and may not be useful for all you online activities; but for sensitive information (e.g., blowing the whistle on an organization and sending information to the press) you can keep your tracks more annonymous to prevent identifying yourself to anyone listening to the signals flowing through the network
- run your own VPN so that you personally control who has access to your online activity and can eliminate the primary security issue of using a VPN provider (but this does increase the risk of your web server host having some access)
- build a mesh network and surf the internet without an ISP at all
- use a network monitor/filter/firewall to control what comes in and what goes out from your computer (e.g., Little Snitch)
- activate self-destruct on your mobile devices (after a certain number of failed login attempts, the device will erase all data on it to prevent the data from falling into an advesary's hands)
