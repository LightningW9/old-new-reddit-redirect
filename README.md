# Obsolete August 2024

Reddit has announced that it is discontinuing the old new.reddit.com platform.

https://www.reddit.com/r/help/comments/1ehmgmr/next_steps_for_newredditcom/

This addon now only works if you create a reddit community (you don't want to manage it, make it private). It is likely that this workaround will stop working once reddit has migrated mod tools to the new platform.

# Old-New Reddit Redirect

This addon is for users that are forced to beta test reddits "new-new" design that ignores settings etc. It will redirect links to the "old-new" design (new.reddit.com).

The code is forked from Tom Watson's "Old Reddit Redirect".

Tested with Firefox. It should also work with Chrome however I am not planning to test or publish this.

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

Development of this addon has ended. You are welcome to fork/re-release it yourself.

## License

Code released under [the MIT license](LICENSE.txt).
