A curated Pi-hole blocklist focused on advanced ad tech and tracking networks such as Equativ (Smart AdServer), Flashtalking (Mediaocean), Snigel, and AdChoices-related domains.
This list helps remove modern programmatic ads, dynamic banners, and tracking pixels that bypass default Pi-hole filters.

Includes regex rules for:

- Equativ / Smart AdServer
- Flashtalking (Mediaocean)
- Snigel (Snigelweb)
- AdChoices networks (Google Ads, Criteo, OpenX, Rubicon, etc.)

Perfect for users looking to enhance privacy, reduce advertising requests, and block DSP/SSP tracking on smart TVs, browsers, and mobile devices.

To use, add the RAW URL of this Gist under "Group Management → Adlists" in your Pi-hole admin panel, then run `pihole -g` to update.
