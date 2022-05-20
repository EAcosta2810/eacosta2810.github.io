# Configuration Guide

Services:

- [x] Google Analytics
- [ ] GTM

## External

Depends on external resource.

Load from **./static/*** folder's

module|fetch
|-|-|
services|list of services `[..., {title, description} ]`
team|list of team members `[..., {name, role, link, picture} ]`

## Embedded

or non-modifiable

**Constants**

state|developing|production
|-|-|-|
Tag ID|`G-Z0H6BT1EG0`|
FormHttp|`https://formspree.io/f/xwkybzpn`|`https://formspree.io/f/moqrnzyq`

**Google Analytics - Development**

module|category|send on
|-|-|-|
App|`general`|connect
Contact|`contact`|successful
Contact|`contact`|custom error
Contact|`contact`|deactivated
Contact|`contact`|name error
Contact|`contact`|mail error
Contact|`contact`|message error
Contact|`contact`|open linkedin
Contact|`contact`|open facebook
Contact|`contact`|open instagram
Contact|`contact`|open mailito
Team|`team`|open linkedin