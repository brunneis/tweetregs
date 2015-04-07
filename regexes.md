Topical
--------------
- (?i)(yellen|fomc|fed|draghi)
- (?i)(champagne|new year|ball drop|time square)
- (?i)(wealth inequality|piketty)
- (?i)april fool'?s?
- (?i)(black|cyber) (monday|friday)

Annoying tech metaphors & similes
--------------
- (?i)(uber|netflix|pinterest|craigslist|ebay|google) of

Over-sharers
--------------
- (?i)wheels (up|down)

Clichés
--------------
- ^(?=.*\bgo\b)(?=.*\bhome\b)(?=.*\bdrunk\b).*$
- (?i)(said no one ever)

Events
-----------------------------------
- (?i)(\s|#)(ces)
- (?i)(\s|#)(sxsw)
- (?i)(\s|#)(crunchies)
- (?i)(#?\bted(\d{4})?\b|vancouver)
- (?i)#?oscars?|award|nomination|speech|best picture|actor|actress

People re-tweeting things you ignored last time
-------------
- (?i)((in.*case|if).*you.*missed.*it|ICYMI)

Plaintive requests for follows
-------------
- (?i)please.*(\bwatch\b|\bfollow\b)|(\bwatch\b|\bfollow\b).*(me|please|back)

Tweets mentioning four or more other people
-------------
- @[^@]+@[^@]+@[^@]+@

Giant hashtags
-------------
- #[^ ]{15}

Four or more hashtags in single tweet
-------------
- #[^#]+#[^#]+#

Tweets to you containing only a link
--------------
- ^@pkedrosky *https?://[^ ]+$

Tweets containing over-repeated characters
-------------
- ([a-z])/1{4}

Retweet cascades
-------------
- RT[^RT]+RT

Public conversations that have nothing to do with you
-------------
- ^\.@\w+\s+[A-Z]

Tech geekery
-------------
- [Ss]ocial\s?[Gg]raph 
- [Bb]ig\s?[Dd]ata

Not so humble brags
---------------
- (?i)(swag|yolo)

Sports silliness
-------------
- (?i)(super ?bowls?|49ers|ravens|foot ?ball|half ?times?|kick ?off|touch ?downs?|field ?goals?|NFL|(first|second|third|fourth) quarters?|over ?times?|final scores)
- (?i)(NBA|NFL|NRA|MLB|NCAA)
- (?i)(march madness|sweet (sixteen|16)|bracket|ncaa|notre dame|kentucky|duke|north carolina|tar heels|xavier|west virginia|final (four|4))
