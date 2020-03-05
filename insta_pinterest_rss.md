# Instagram RSS via Pinterest

Curious reader [@plasticmind](https://github.com/plasticmind) [asked this question on the Twitter](https://twitter.com/plasticmind/status/1235589410789285889):

    Dear lazyweb: does anyone know of a way to pull the Instagram feed for a particular user into a site automatically without needing to pay a monthly subscription for a service? Happy to entertain dev-related options.

The answer is, as always, "it depends." If it's your account, you can do this with Pinterest, and along the way make sure that any time one of your Instagram posts winds up on Pinterest it will have correct attribution.

## To get a feed of Instagram posts onto a Web site:

- Sign in to Pinterest and visit [the Claim page under Settings](https://www.pinterest.com/settings/claim).
- Under "Claim Other Accounts" find Instagram and click Claim
- Authorize your Instagram account
- Tell Pinterest you'd like it to save all of your Instagram posts to a board. You can make a new one right there, and import all your previous Instagram posts if you like. (Recommended for people who always want their Instagram posts to have correct attribution on Pinterest!)
- Open your new Instagram board in a fresh tab.
- Copy the URL. (If you are importing your previous posts they might not all be there yet; they will be along shortly.)
- Be sure this is a public board or the next step won't work!
- Visit the [Pinterest Widget Builder](https://developers.pinterest.com/tools/widget-builder/?type=board)
- Paste in your board URL wehre it says Pinterest Board URL.  You should see a preview immediately.
- Copy the embed code and script link; follow instructions to paste into your site.
- Board and profile widgets will render up to the last 50 posts.

## If all you really wanted was RSS

- Follow the instructions above until you're looking at your Instagram board in a fresh tab.
- In your browser's URL bar, remove the trailing slash and add `.rss`.  Here's mine:  https://www.pinterest.com/kentbrew/my-instagram.rss
- RSS feeds will render up to the last 20 posts.
- If you like you can also ask for an RSS feed for a profile, by adding `feed.rss` to the URL. Mine's at https://www.pinterest.com/kentbrew/my-instagram.rss