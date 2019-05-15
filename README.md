# reddit-scripts

Various reddit scripts.

Launch a script with the `-h` flag to view how to use it.

- **download_comments_post.py** : Download the comments of one or several posts.
- **download_comments_user.py** : Download the 1000 most recents comments of one or several users.
- **download_posts_user.py** : Download the posts of one or several users.
- **fetch_posts_subreddit.py** : Download the posts of a subreddit with the help of the Pushshift api.

Needs a praw.ini under the form :

```
[bot]
client_id=id
client_secret=secret
password=password
username=username
```

## Installation of the virtualenv

```
pipenv install
```

## Usage

```
pipenv run python fetch_posts_subreddit.py -h
```
