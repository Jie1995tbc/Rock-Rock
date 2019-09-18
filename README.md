# Rock-Rock
import tweepy
auth = tweepy.OAuthHandler('BePXBQnnodwym2KOVSVaDGMJt', 'vj4G9SYGRzHWZLwHoHtsUjqeBNgQQY7q4FFPnxs3SkTDGfaQ7E')
auth.set_access_token('1171640747352842244-eg2gQVsNhlbL1FV6SPsPD72vfLzMiZ', 'XAT4XUzyXr7UAyTunUGScRYQZGutuBIhWHmErHqpWO28p', 'https://twitter.com')
api = tweepy.API(auth)

#download my home timeline tweets and print
# public_tweets = api.home_timeline()
# for tweet in public_tweets:
#   print(tweet.text)

# user = api.get_user('Jie')
# print(user.screen_name)
# print(user.followers_count)
# for friend in user.friends():
#   print(friend.screen_name)

#session to store a request token
#session.set('request_token', auth.request_token['oauth_token'])

#redict the url from twitter(request_token)
redirect_url = auth.get_authorization_url()
#authorize code(shouquanma) from twitter: (web app)
verifier = request.GET.get('oauth_verifier')



#user timeline tweets: count = 10
# name = 'CNN'
# tweet_count = 10

# for tweet in api.user_timeline(id = name, count = tweet_count):
#   print(tweet.text)

# query = 'Trump'
# language = 'en'

# for tweet in api.search(q = query, lang = language):
#   print(tweet.user.screen_name,"Tweeted: ", tweet.text)
