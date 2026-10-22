# trellis-guide

A daily TV guide (XMLTV) for TrellisTV, built with the [iptv-org/epg](https://github.com/iptv-org/epg) grabber.

- **Channels:** `trellis.channels.xml` (the DirecTV national lineup, TV Passport for the rest and Honolulu locals, plus a few channels from TV Insider, Zap2it and Pluto).
- **Schedule:** every day at 00:17 Honolulu time (`.github/workflows/guide.yml`); **Actions › Build guide › Run workflow** for a manual refresh.
- **Guide link for Trellis:** `https://github.com/mikiebowen808-prog/trellis-guide/releases/download/latest/guide.xml.gz`

No keys or logins live here: just the channel list and public TV listings.
