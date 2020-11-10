# Primary_Associates_On_Twitter
This script is intended to find the primary contacts/friendships of a Twitter account based on frequency of public tweets to or about another account and avoids listing celebrities followed by the original Twitter account.

You will need to get the Twitter API keys to use this script.
The script works best with Twitter accounts that have hundreds, not thousands, of "friends" and "following" accounts.
Input the screenname (not display name) of the account you a researching as a string at this spot in the script:
          # choose username to search
          usernames = [""]

The script requires that you have the following libraries to import
import requests
import csv
import sys
import pandas as pd
import tweepy #https://github.com/tweepy/tweepy
import time
import numpy
import cv2
