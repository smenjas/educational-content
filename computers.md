# How to Use Computers Safely

- [Security](#security)
  - [Passwords](#passwords)
  - [Domain Names & Certificates](#domain-names--certificates)
  - [Personal Data](#personal-data)
- [Types of Computers](#types-of-computers)
  - [Servers](#servers)
  - [Desktops & Laptops](#desktops--laptops)
  - [Smartphones](#smartphones)
  - [Tablets](#tablets)
  - [Voice Assistants](#voice-assistants)
  - [Embedded Computers](#embedded-computers)
- [Consuming Data](#consuming-data)
- [Programming](#programming)

## Security
Imagine that when you open the front door of your home, you might find yourself
on any street in the world.  That's how a computer works.  Poor security can
give away the keys to your life.

### Passwords
A password's strength can be measured in bits of entropy.  A short password
with only letters and numbers doesn't have many bits: it's weak.  A longer
password with more variation has more bits: it's stronger.

It's very hard for us to remember strong passwords.  If it's easy to remember,
it's easy to crack.  Password cracking is where people use computers to figure
out your password.  If you can remember your password (for example, it's your
pet's name and the year someone you love was born), then it's quite likely
someone will write a computer program that can figure it out, based on your
social media, or your friends' social media.

#### Password Managers
If you want to prevent people breaking in to your accounts, you need to use
strong, unique passwords for every site, especially your email accounts.

Password managers generate strong, unique passwords for every site, and
remember them for you.  You should use one.  There are several:
- [LastPass](https://www.lastpass.com/)
- [1Password](https://1password.com/)
- [Dashlane](https://www.dashlane.com/)
- [iCloud Keychain](https://support.apple.com/guide/mac-help/use-keychains-to-store-passwords-mchlf375f392/mac)
- [Google Password Manager](https://support.google.com/accounts/answer/6208650?hl=en)
- [Mozilla Firefox](https://support.mozilla.org/en-US/kb/password-manager-remember-delete-edit-logins)

You will still need to remember the password to your password manager, but now
you can forget the rest.

#### Choosing a Strong Password You Can Remember
A strong password has several bits of entropy, the more the merrier.  Think of
four or more words that have nothing to do with each other except in your
brain.  Silently repeat them to yourself, many times.  Don't use existing song
lyrics, or lines from a poem or a book or a blog.  Those can be guessed.

For example: [**correct horse battery staple**](https://xkcd.com/936/ "xkcd: Password Strength")

Choose your own!

### Domain Names & Certificates
The only way to know who controls a web site is by the domain name.

A domain name is part of a URL, which you can find in the address bar of your
browser, or by copying a link and pasting it somewhere.

If a web site is not encrypted, then people can see everything you see, and
everything you send to the site.  Therefore you should always pay attention to
whether the sites you visit are encrypted.  If the URL begins with http instead
of https, then it's not encrypted.  Even if it does begin with https, it's only
encrypted if the sites certificate is valid and up to date.  You will often see
a padlock icon to indicate whether a web site is encrypted.  You can click on
the padlock icon to see information about the web site's domain name and
certificate.  If a certificate is no longer valid, some browsers will show an
icon to indicate that.

Even if the web site's domain belongs to the organization you think it does,
and they have encrypted the web site, you should only interact with web sites
that belong to organization you trust to engage n business with you honestly.
If you do not trust someone, then a web site certificate should not override
that.

You definitely should not enter any passwords or personal information on sites
that are not encrypted.  If you do, you are broadcasting that information for
the world to see.

### Personal Data
Personal data include names, phone numbers, email addresses, physical
addresses, passwords, usernames, government ID numbers, student ID numbers, and
many other things you might not think about, like GPS coordinates that are
included in most of the photos people take.

You should be very careful with personal information.  Once you post it
publicly you cannot prevent anyone from copying it.  Even if you think you did
not share it publicly, you may have done so accidentally.  If you share a photo
that shows some mail with your address on it, or you enter your address into an
online store that's not encrypted, you have broadcast your address to the
world.

Try to avoid sharing any personal information, except when you are required to.
Even then, you should feel free to pause, and think about whether you want to
interact with someone.  Do not ever feel pressured to provide information to
someone over the Internet or on the phone with personal information
immediately.  You're allowed to take time to think about it, and call them back
later if you decide to.

#### Work vs. Personal
You should separate your work and personal data as much as possible, to avoid
legal complications and providing an example of professionalism.

If you can, have separate devices for work and personal use, and use each
exclusively for their intended purpose.

If your devices belong to your employer, you should still avoid using your
work email for personal communication.  Instead, use a personal email.

## Types of Computers
There are many different kinds of computers that affect your every day life,
some of which you will never see.

### Servers
A server is just a computer that communicates with other computers, and may not
have a screen or a keyboard or pointing device attached at all.  Whenever you
use a computer, it is probably communicating with many servers.

A datacenter is just a bunch of servers in a room or a building, designed to
hold a bunch of servers.

The cloud is just a bunch of datacenters.

### Desktops & Laptops
Desktop and laptop computers (sometimes called workstations) are designed for a
person to use directly.  They almost alwasy include a keyboard and a pointing
device.  Sometimes they have touchscreens, but not always.  They use a
graphical user interface (GUI) called WIMP: Windows, Icons, Mouse, Pointer.
They also have command line interfaces (CLIs), which are very useful for
programming and interacting with servers.

### Smartphones
Smartphones generally have touchscreens, and not many buttons.  They use
graphical user interfaces (GUIs), and rarely include command line interfaces
(CLIs).  They are generally much simpler to use that desktop and laptop
computers, but in some ways they are less powerful.

### Tablets
Tablets are basically giant smartphones.

### Voice Assistants
Voice assistants are included in most smartphones, and some desktops and
laptops.  There are also standalone devices designed to be use mostly with
voice input, some of which don't have screens.  Alexa, the Google Assistant,
and Siri are the most popular.

Alexa and the Google Assistant record what they hear, and use those recordings
to target advertising to you.  Siri does not.

### Embedded Computers
Embedded computers are all over the place: in your car, fridge, stove, toaster,
maybe even your lightbulbs.  Security is just as important for these devices as
it is for every other computer.  Pay attention to which manufacturers you
trust.

## Consuming Data
A computer lets you read, or listen, or watch all kinds of content.  When you
go to school, your teachers tell you what to read.  At the library, you choose.
TV used to have only a few channels, and the broadcaster decided the schedule.
Online video often lets you choose what to watch and when.

When we choose to read or watch something, we often do so because we were
influenced by advertising or social media.

It's tempting to let others choose what we read and watch, but there are
options to exercise control.

Many sites publish their content using an RSS or Atom feed.  You can create
your own news feed using a feed reader like [Feedly](https://feedly.com/).
It's free.  Create an account and add some sites you enjoy.

There are also many sites that allow you to discover the wealth of knowledge
in the world:
- [Internet Archive](https://archive.org/)
- [Librivox](https://librivox.org/): free, public domain audiobooks
- [Open Culture](http://www.openculture.com/)
- [Project Gutenberg](https://www.gutenberg.org/)
- [Wikipedia](https://en.wikipedia.org/): free-content encyclopedia
- [YouTube](https://www.youtube.com/)

Don't let yourself sit in rut.  Explore, learn, create, and share.

## Programming
If you want to know more about how computers work, check out [Free Code
Camp](https://www.freecodecamp.org/).
