# mediawiki_ui

**mediawiki_ui** is a Pythonista module for a nicer iOS user interface for MediaWiki wikis. You can use it with Wikipedia, Gamepedia, and any other wikis using MediaWiki (Wikia wikis currently don't work).

Put this folder in `site-packages`.

## Use
Creating an instance of the `wiki.Wiki` class will open the main interface.  
You must have an argument for the wiki URL.  
Example: `w = wiki.Wiki('https://wikipedia.org/wiki/')`  
This URL MUST be the full URL for the wiki (`https://wikipedia.org/wiki`, not `https://wikipedia.org`). Since the end of wiki URLs can vary, the script won't crash but not using the full URL can cause weird bugs. 

## TODO:

- [ ] Use more than just WebView.load_url for viewing pages (like Safari's Reader view)
- [ ] Add Wikia support
- [ ] Create documentation
- [ ] Create an interface for switching between wikis
