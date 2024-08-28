# Obsolete August 2024

Please note this addon no longer works due to reddit removing the option to force the older layout with new.reddit.com
https://www.reddit.com/r/help/comments/1ehmgmr/next_steps_for_newredditcom/

# Old-New Reddit Redirect

This addon is for users that are forced to beta test reddits "new-new" design that ignores settings etc. It will redirect links to the "old-new" design (new.reddit.com).

The code is forked from Tom Watson's "Old Reddit Redirect".

Tested with Firefox. It should also work with Chrome however I am not planning to test or publish this.

This can be installed from the Firefox add-ons site.

[Firefox Add-on](https://addons.mozilla.org/en-GB/firefox/addon/old-new-reddit-redirect/)

#### Redirected domains

- `reddit.com`
- `www.reddit.com`
- `np.reddit.com`
- `amp.reddit.com`
- `i.reddit.com`

#### Whitelisted domains

- `old.reddit.com`
- `sh.reddit.com`

## Development

In Firefox, head to `about:debugging#/runtime/this-firefox`

Load temporary add-on and select `manifest.json`

Where possible, I will aim to keep this in sync with the source code until it is no longer needed.

## License

Code released under [the MIT license](LICENSE.txt).
