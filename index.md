# The Omegawytch Chronicles

Welcome to the preserved archival of 56Warrior's legendary 2002 RuneScape blog, most recently hosted on *RuneScape Inn (rsinn.com)* in 2004 where they were shared by Moridin.

> **Archival Note:** These logs have been salvaged from the Wayback Machine, stripped of dead forum BBCode, and formatted into Markdown for preservation. If you would like to see the originals, they can be found [here](https://web.archive.org/web/20040904172350/http://www.rsinn.com/forum/showthread.php?t=2375).

## Table of Contents

{% assign chapters = site.chapters | sort: "path" %}
{% for chapter in chapters %}
- [{{ chapter.title }}]({{ chapter.url | relative_url }}){% if chapter.original_date %} — {{ chapter.original_date }}{% endif %}
  {% endfor %}