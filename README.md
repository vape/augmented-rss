### Augmented RSS Feeds

Some RSS Feeds don't include actual content, forcing you to click on the link and go to the site (which defeats the purpose of RSS in my opinion).

This is a Flask app which contains proxy feeds which augment the original feed with actual content.

So far, these are the augmenters I've added. Feel free to add your own and send pull requests.

- [Toothpaste for Dinner](http://www.toothpastefordinner.com/) - [Augmented Feed](http://augmented-rss.herokuapp.com/feed/tpfd)
- [Dilbert](http://www.dilbert.com/) - [Augmented Feed](http://augmented-rss.herokuapp.com/feed/dilbert)
- [Saturday Morning Breakfast Cereal](http://www.smbc-comics.com/) - [Augmented Feed](http://augmented-rss.herokuapp.com/feed/smbc)
- [Hover States](http://hoverstat.es/) - [Augmented Feed](http://augmented-rss.herokuapp.com/feed/hover-states)
- [Awwwards](http://www.awwwards.com/) - [Awwwards Feed](http://augmented-rss.herokuapp.com/feed/awwwards)


The app is hosted on Heroku ([http://augmented-rss.herokuapp.com](http://augmented-rss.herokuapp.com)).

You can send pull requests and I can update my Heroku app, or you can create your own app on Heroku (or wherever) and do your own thing.
