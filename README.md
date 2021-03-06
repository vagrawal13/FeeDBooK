FeeDBooK 1.0
============


## Introduction

FeeDBooK is an RSS Reader desktop application based on Swing framework in
Java for reading feeds from your favorite websites without the need to visit the
website regularly for latest content. The reader is still in its early stages and
supports only basic functionalities such as Add/Remove Subscription, set specific
proxy settings to download the feed etc. The interface is clean and is developed in
mind keeping the usability and aesthetics of the application in just the right
blend.

The software is Open Source and developed as a part of a college project so you
can go ahead and modify/improve upon the functionalities and features of the
application as you like.


## Technical Specifications

The application makes use of the widely popular library ROME for parsing ATOM
feeds. Apart from this various swing components have been programmed in a
BORDER layout fashion to develop the GUI.

## ROME Java Library

ROME is an open source tool to parse, generate and publish RSS and Atom feeds.
Using Rome you can parse the available RSS and Atom feeds. Without bothering
about format and version of RSS feed. The core library depends on the JDOM XML
parser.

Atom is on the similar lines of RSS is another kind of feed. But it�s different in
some aspects as protocol, payloads.
RSS is a method to share and publish contents. The contents may be any things
from news to any little information. The main component is xml. Using xml you
can share your contents on web. At the same time you are free to get what you
like from others.


## Dependency

* J2SE 1.4+, JDOM 1.0
* Jar files (rome-0.8.jar, purl-org-content-0.3.jar, jdom.jar)
* Using Rome to read a Syndication Feed

## Read Feeds

ROME represents syndication feeds (RSS and Atom) as instances of the
com.sun.syndication.synd.SyndFeed interface.
ROME includes parsers to process syndication feeds into SyndFeed instances. The
SyndFeedInput class handles the parsers using the correct one based on the
syndication feed being processed. The developer does not need to worry about
selecting the right parser for a syndication feed, the SyndFeedInput will take care
of it by peeking at the syndication feed structure. All it takes to read a syndication
feed using ROME are the following 2 lines of code:
SyndFeedInput input = new SyndFeedInput();
SyndFeed feed = input.build (new XmlReader (feedUrl));


## Requirements


Latest Java Development Kit and Java Runtime Environment package are the only
requirements as ths software is developed entirely in Java.
OS: Windows/Ubuntu/Macintosh.


## Get Started


The software is really very simple to use. You have to manually specify the
website rss feed link in the Add Subscription menu option. You can also remove
subscriptions which you no more want to read feeds from.
Select subscriptions from the dropdown populates the feeds with list of titles
displayed in the left pane, choosing from which shows its description, title and
other details. There is also an option to open the feed link in the default browser
of your OS.