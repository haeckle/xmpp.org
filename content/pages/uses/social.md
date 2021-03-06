---
Title: Social
Url: uses/social
Save_as: uses/social.html
Parent_id: uses
Top_menu_show: false
Top_Menu_order: -1
Dropdown_menu_show: false
Footer_show: false
Sidebar_menu_show: true
Sidebar_menu_size: 4
Sidebar_menu_title: Uses of XMPP
Sidebar_menu_elem_name_1: Instant Messaging
Sidebar_menu_elem_url_1: uses/instant-messaging
Sidebar_menu_elem_name_2: Internet of Things
Sidebar_menu_elem_url_2: uses/internet-of-things
Sidebar_menu_elem_name_3: Social
Sidebar_menu_elem_url_3: uses/social
Sidebar_menu_elem_name_4: WebRTC
Sidebar_menu_elem_url_4: uses/webrtc
Content_layout: multiple-columns
---

## Realtime Social

XMPP's core messaging can be extended to create group sharing and social networking apps (for example ATOM-formatted feeds).

Three features make XMPP a great choice for powering social projects:

Firstly, because each user connects with their username (in XMPP-speak, their `JID`), a social service can always be sure that only the right user is getting the right information. This baked-in security means XMPP is particularly a great fit for building secure group sharing applications.  

Secondly, XMPP's realtime nature means users of a social service will receive immediate updates when another user does somethign that involves them (for example: `you were @mentioned in tybalts-party@capulet.lit`).

Finally XMPP's publish-subscribe constructs make a great foundation for building activity-feed type applications. Users can post to their feed, and XMPP will take care of propogating the updates to that user's subscribers in a secure way.

## Projects using XMPP Social

There are many people pairing WebRTC with XMPP. 

The [Buddycloud Core](http://buddycloud.com/core) messaging stack is a set of social services that include help developers build a complete social application and includes user-onboarding, content recommendation and media sharing features.

[Jappix](https://jappix.org) a Javascript XMPP client with social features.

[Movim](https://movim.eu/) is a PHP based distributed social networking platform.

[Salut à Toi](http://salut-a-toi.org) a Python based multi-frontends XMPP client featuring (micro)blogging, file sharing, games, etc. [Libervia](https://libervia.org) is its web frontend.
