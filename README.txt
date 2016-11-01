This simple content aggregator for twitter searches for twitter posts with the keywords you are interested in and saves them in the mongodb.

To use any of the Twitter APIs one needs access tokens as described here:
https://dev.twitter.com/oauth/overview/application-owner-access-tokens

Access tokens in a separate file (.env) and the following package is used to load them.
https://www.npmjs.com/package/dotenv

You need the following keys configured in the .env file
TWITTER_CONSUMER_KEY
TWITTER_CONSUMER_SECRET
TWITTER_ACCESS_TOKEN_KEY
TWITTER_ACCESS_TOKEN_SECRET

TODO: 
- approval frontend to pull the new content from twitter to only approve and save interesting content
- create a news digest to the content saved
- app-follow-users.js follows the specified users and tracks their posts in a similar way