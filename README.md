# 630
this is for my 630 paper
import twitter
import json
import matplotlib.pyplot as plt

CONSUMER_KEY = 'Hr5M7BYAzxBzZuOCREz3oveNV'
CONSUMER_SECRET = 'FbOZXzejM3EvVUnU6I2YwYRzpdRWwk6B3SuzrbS9ao6Uxx9z4k'
OAUTH_TOKEN = '861563111978934272-I7D2m12fd76jKE4BjAge9rOlTdiIBPF'
OAUTH_TOKEN_SECRET = 'xuxX9STvq4NLuLsZg1jjMANqacNy9ThlQ2XUSrmbDxm78'

auth = twitter.oauth.OAuth(OAUTH_TOKEN, OAUTH_TOKEN_SECRET,
                           CONSUMER_KEY, CONSUMER_SECRET)

twitter_api = twitter.Twitter(auth=auth)