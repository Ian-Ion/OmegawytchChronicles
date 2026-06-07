# The Omegawytch Chronicles

Welcome to the preserved archival of 56Warrior's legendary 2002 RuneScape blog, most recently hosted on *RuneScape Inn (rsinn.com)* in 2004 where they were shared by Moridin.

> **Archival Note:** These logs have been salvaged from the Wayback Machine, stripped of dead forum BBCode, and formatted into Markdown for preservation. If you would like to see the originals, they can be found [here](https://web.archive.org/web/20040904172350/http://www.rsinn.com/forum/showthread.php?t=2375).

These stories hold a special nostalgic place for me personally; I have fond memories of reading them as a young player and have always been fascinated by the depth of imagination and storytelling that went into them. In my opinion, Omegawytch is a very early example of what would these days be considered a "snowflake" account, and these chronicles seeded my interest in the wonderful world of unique account builds.

## Original Introduction by Moridin

> _Among the thousands of visitors that have passed through the Runescape forums of Scapeboard, some of these people are remembered for their posts which hold an amazing quality of intelligence and foresight. Chief among those still remembered is 56Warrior, a man whose posts showed the true depth of mind with an amazing ability to grasp the reader with his simple story of a new character – Omegawytch. He takes us from her birth, through to her defence training which allowed her to wield the rare Dragon Helmet and quest fulfilment at a time where such things were left for Legends. Omegawytch defied her time and completed the most difficult of abilities at the lowest of levels._
>
> _Starting in November of 2002 and continuing on for five months, he posted sixteen instalments to the Omegawytch Chronicles detailing the feats of the character that many would disdain as a younger player. Yet, as with all good things, they must end. The final chapter was written on the 17th of March in 2003. By now, Omegawytch had a true voice and he had plumbed the depths of her mind. But the pen remained silent; the stories had ground to a halt._
>
> _Over time, the stories gradually faded from sight. Passing down and moving deeper and deeper as new stories and writings took their place. Soon the Chronicles were but a distant memory, a thing that as soon was thought fled back into the dark recessed of one’s subconscious. As when a forest fire sweeps through the land leaving nothing but blackened stumps, the world of Scapeboard was too wiped from existence. But as with any fire, seedlings take growth as soon as the flames die. And so the memories of Omegawytch resurface once more into the collective conscious._
>
> _I had played for over a year by the time 56Warrior made his first post though I never did read it. Nor did I read his second, nor his third, nor fourth. I was a casual visitor of Scapeboard, I did not discover this wealth of imagination until the tenth episode. I was enthralled by his grasp for the character. And so I began to re-read the older ones. And within a month, they had stopped. It was then that I decided to copy them and keep the knowledge that was written._
>
> _And so I will now share with you the extraordinary tale that took five months to create in one of the most unique minds of Runescape – 56Warrior’s “The Omegawytch Chronicles.” Each day, I will post a new episode and each day you will learn just a little bit more of this timeless character. I hope you will enjoy._

## Table of Contents

{% assign chapters = site.chapters | sort: "path" %}
{% for chapter in chapters %}
- [{{ chapter.title }}]({{ chapter.url | relative_url }}){% if chapter.original_date %} — {{ chapter.original_date }}{% endif %}
  {% endfor %}