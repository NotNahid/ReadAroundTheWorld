How it works:
There are two key data structures at the top of the <script> section:

books — this is where your progress lives. Each entry is a country name mapped to the book you're reading/read from that country.
countries — the full list of 195 countries with their flag emojis. You don't need to touch this.

A country entry in books can have 3 states:

Done (finished) — just has title and author
WIP / currently reading — has wip: true
Has a playlist — has a playlist URL, which shows a "listen →" link
