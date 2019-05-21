# tj-tweets
Old deprecated code of tweets bot

## Usage

Set 'TWITTER_CONSUMER_KEY', 'TWITTER_CONSUMER_SECRET', 'TWITTER_USER_TOKEN', 'TWITTER_SECRET_KEY' first. Something like this for each param:

`export TWITTER_CONSUMER_KEY=bmV2ZXJnb25uYWdpdmV5b3V1cA==`

Start with twitterUsersDaemon.php:

`php twitterUsersDaemon.php start`

## Notes

Sometimes it starting to use 99% CPU and you need to manually `kill -9` it and start again. 

It's probably impossible to run this on macOS due to problems with permissions.
