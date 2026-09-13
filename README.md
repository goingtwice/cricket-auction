# Cricket Auction

Ball-by-ball IPL auction game. Bid against friends in a live shared room,
or solo against AI managers, then play a full season.

Two files. Nothing to configure.

  wrangler.toml  - Cloudflare config (one Durable Object binding)
  src/worker.js  - the game page and the auction room server

Deploy: connect this repo to Cloudflare Workers. It reads wrangler.toml
and sets everything up itself. Runs on the free tier. No card, no keys.

Ball-by-ball data derived from Cricsheet (cricsheet.org), ODC-BY 1.0.
Not affiliated with, endorsed by or licensed by the BCCI, the IPL, or any player.
