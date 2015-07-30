```javascript
javascript:(function(a){window.trelloAppKey="optional";window.trelloIdList="optional";var b=a.createElement("script");b.src="https://sarenji.github.io/trello-bookmarklet/trello_bookmarklet.js";a.getElementsByTagName("head")[0].appendChild(b)})(document);
```

This is a <a href="http://en.wikipedia.org/wiki/Bookmarklet">bookmarklet</a> you can use to create a card in <a href="https://trello.com">Trello</a> from Kickstarter projects.

The first time you run it on a site, it will walk you through a simple setup:

 1. Input your API Key (which you can get at https://trello.com/1/appKey/generate)
 2. Authorize the site to interact with Trello
 3. Select the list that you'd like the bookmarklet to add cards too

You'll only need to go through those steps once per domain; from then on, you should be able to send your
issues/cases/whatever directly to Trello in a single click.

**Note:** This is a fork of https://github.com/danlec/Trello-Bookmarklet
