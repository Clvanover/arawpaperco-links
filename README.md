# arawpaperco.com short links (GitHub Pages)

Until the Shopify site launches, arawpaperco.com is served from this repo.
Each folder is one short link: `/<name>/index.html` redirects to the target.

| Address | Goes to |
|---|---|
| arawpaperco.com | Etsy shop |
| arawpaperco.com/calendar | Free 2027 calendar sign-up page (MailerLite) |
| arawpaperco.com/honeydo | Honey Do Cards sign-up page (MailerLite) |
| arawpaperco.com/main | Main sign-up page (free Tally Card + planning pages, Araw list) |

Any capitalization works (/Main, /HoneyDo): 404.html lowercases the path and redirects; add new links to its list too.

Add a link: copy a folder, change the URL in it (3 places), commit and push.
When Shopify takes over the domain, recreate these as Shopify URL redirects
(Online Store > Navigation > URL Redirects) BEFORE switching DNS.
