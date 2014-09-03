#How to Protect Your Nudes

The web has been awash for the past few days with news and reports on stolen celebrity photos. Commentators, talking heads, bloggers, and tech "experts" have been finger pointing, blaming all parties, guilting, lambasting, analyzing, and profiting off these hacks with a mess of hasty, poorly reported information. This article is not about that.

The purpose of this piece is not to analyze what Jennifer Lawrence and other celebrities did wrong nor analyze the privacy implications. Instead, we'll look at various attack vectors and how you can avoid them.

#General Security

Though no conclusive investigations have been completed, it seems more likely that this hack is actually a leak from many hacks utilizing many methods over a long period of time.

[Here](https://www.nikcub.com/posts/notes-on-the-celebrity-data-theft/) is an excellent piece analyzing these underground nude trading rings and how they operate.

Because of the varied attack vectors (some of which have only recently been [patched](http://thenextweb.com/apple/2014/09/01/this-could-be-the-apple-icloud-flaw-that-led-to-celebrity-photos-being-leaked/)) there is no silver bullet you can use to secure your data.

There is a strong possibility that some of these hacks originated not from the subject's phone but rather from someone else that the photos were shared with. This point is the biggest "gotcha" in sharing personal photos. You are ultimately at the mercy of his or her or their security as well - not even taking into account the trust that he/she/they will not willingly share your nudes. 

###Your Passwords Suck

Odds are your passwords are _terrible_. Odds are that you reuse the same password on tons of sites. Odds are that what you think you know about passwords is wrong. 

There is evidence that at least some of these hacks occurred because of weak passwords.

It's okay, there's a lot of bad information out there. Covering all aspects of passwords is well beyond the scope of this article, but lets touch on a few issues.

####Make it Random

The single best thing you can do for your password is to make it random. Unfortunately us humans are awful at making random passwords. Even when we follow the basic rules: 
* Avoid dictionary words - they take minutes to hack.
* Avoid Wikipedia article names - they take minutes to hack. 
* Avoid "[leet](https://en.wikipedia.org/wiki/Leet)" speak (7h4+ 1$ C0mM0n l3773r @nD $ym8ol RepLaC3m3n7) - crackers have dictionaries that sub for that too.
* Include numbers and symbols - they've got tools that anticipate this as well.
* Avoid acronyms - think you've got them beat by turning quotes and phrases into acronyms with symbols and numbers? You guessed it, they've got those in wordlists too.

So what can you do? The answer is simple: let software generate a truly random password for you.

Every major password manager (which we'll _briefly_ discuss) and even some browsers (Safari) have functionality built in to help you generate secure, random passwords. There are even [websites](http://passwordsgenerator.net/) entirely devoted to helping you generate strong passwords. 

Problem is these random passwords are hard to remember and when they're long enough to be safe, hard to type. Password managers help in both respects, but lots of people don't want to go to through the effort of installing and saving their passwords.

If you can't be bothered to install a manager and can't remember long random strings, then at the very least make your password a passphrase. Pick four or more words and type them out with spaces: "people suck with passwords." It's simple to remember at vastly more secure than the poor quality, short password you're probably using. Bonus points for mixing in symbols, numbers, and caps.

####Use Different Passwords

The single best thing you can do to buff up your security across the board is to _use different passwords_. Ideally, every site should have a unique password. This way, if any single site is compromised then the rest of your accounts should stay safe. As it stands, repeated passwords are the greatest single attack vector used to access accounts.

With the dozens if not hundreds of accounts the average user has, password managers are invaluable to help keep track of accounts.

If the idea of separate passwords is still too daunting, at the very least make sure your "core" accounts (email, apple, financial, and social media) utilize different passwords - particularly your email. If a website is compromised and your password exposed, this way you should be able to retain control of your most important accounts.

####Start Using a Password Manager

I can't say it enough. Password managers will help you generate random, secure passwords, make lots of them, make it easy to remember and login, and keep you much safer online. It doesn't particularly matter which of the major products you choose, just pick one - it's worth the couple of bucks a year:

* [1Password](https://agilebits.com/onepassword) - The best user experience in a password manager.
* [Lastpass](https://lastpass.com/) - The most popular password manager service.
* [Keepass](http://keepass.info/) - The free, locally hosted, open source option. See [KeepassX](https://www.keepassx.org/) for Linux support.

Pick one. Install it on your computer, your web browser, and your phone. Secure passwords are now easy and seamless.

###Stop Using Security Questions

Many of these hacks seem to have occurred by guessing security questions. The most notable hack of this type was probably against [Sarah Palin](https://en.wikipedia.org/wiki/Sarah_Palin_email_hack). There was a time when security questions made sense, when it was hard to find someone's mother's maiden name and what school they went to. Now it's not. Thanks to Facebook and our social web, finding answers for security questions is easy - especially if you're a celebrity.

While it may seem silly to suggest flat out lying on security questions, that's currently the best option. Hopefully site designers will purge these from their security designs, but until then make your answers up so no one can guess them.

###Enable Two Factor Authentication

Two Factor Authentication (2FA) is a second verification for logins that means that even if someone gets your password, they need access to additional piece of information to be able to login. Typically this extra info is a code generated by an app or an SMS sent to your phone. Enabling two-factor protection _greatly_ enhances the security of your accounts.

The catch with 2FA is that if you lose your phone, you might be out of luck. Most websites give you backup codes when you enable 2FA - SAVE THEM (inside your password manager is a great place). 2FA apps like [Authy](https://www.authy.com/consumers) give you an option to save your generators and access them on multiple devices.

It should be noted, Apple's iCloud _is not_ protected by 2FA - even if you enable it for your apple account so it would have not prevented any unauthorized access.

###Be Aware of Your Backups

At least some of these hacks were made possible because a mobile device automatically backed images up to the cloud. 

As an aside, if you're one of those people that isn't entirely sure what "the cloud" means and you giggled at the trailer for [Sex Tape Movie](https://www.youtube.com/watch?v=eJTct8eHKYE) then just mentally replace "the cloud" with "somebody else's server."

Automatic backups to iCloud or Google+ on Android are great for protecting your memories if your phone should be lost or destroyed. However, the automatic nature of the service may end up backing up files you don't want to share - in some cases even enabling you to accidentally make them public.

A better option is to disable automatic backup to these cloud services. Instead, use an app like [Boxcryptor](https://www.boxcryptor.com/) ([iOS](https://itunes.apple.com/us/app/boxcryptor/id649940870?mt=8) & [Android](https://play.google.com/store/apps/details?id=com.boxcryptor2.android&hl=en)) to manually backup _and encrypt_ specific images. This ensures that only the files you want to protect get backed up and offers extra protection from would be hackers, state actors, cloud owners (Dropbox, etc), and accidental sharing.

The catch is you need to remember to make those backups!

###Protect Your Images on Your Device

Encrypted cloud storage is a great option for backups, but you want probably want to encrypt and hide your images locally as well. No one wants Grandma to accidentally swipe across some private images while she looks at your vacation photos. Fortunately there are a number of image vaults for both [Android](http://techtrix.hubpages.com/hub/6-Best-Apps-to-Hide-Pictures-and-Videos-on-Your-Android-Device) and [iOS](http://hubpages.com/hub/Best-Apps-to-Hide-Pictures-on-iPhone).

For those that want the best security, look for open source encryption software such as [TrueCrypt 7.1](https://github.com/AuditProject/truecrypt-verified-mirror) (avoid 7.2) and the accompanying mobile apps that can open these encrypted containers.


#An Overview of Sharing

Now that you've bolstered your security and ensured that the potential recipient(s) of your photos has done the same, it's time to look at just how you share your most precious photos.

##The Abstinence Method

The only foolproof method when it comes to prevent leaks of your nude and racy photos is simply not to take them. Of course, this happening is as likely as abstinence only education working.

The problem with this method (though it is foolproof) is that it's ultimately the digital equivalent of "that outfit was just asking for it." Swapping sexual images is common in many relationships and should not be stigmatized, nor should those who have had their photos stolen be blamed for taking them.

When credit cards numbers are stolen we don't respond with "Why don't you just use cash?"

##Snapchat

[Snapchat](https://www.snapchat.com/) is a company with a multi-billion dollar valuation built off millions of sexual and nude photos. The app took off on the concept of self-destructing messages that users seized for sending dirty photos quickly and easily without worries of the other party saving incriminating images.

Problem is that while Snapchat repeatedly insists they don't save images, they've been forced to [admit users can](http://blog.snapchat.com/post/88578064510/our-agreement-with-the-maryland-attorney-general). While there is the snapshot notification that the recipient has saved your image, there exist a number of tools and techniques for saving photos without notifying the other user.

In short, Snapchat does not guarantee the safety of your nudes. At best, you're limited to the trust you have in the other party. At worst, Snapchat stores data, is breached, and your entire history of nudes is shared with the world. 