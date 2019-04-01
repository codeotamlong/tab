# mnml-startpage
This is an MINIMAL startpage without any relation with the fashion brand MNML. I just remove all vowels from the word "minimal". Based on cadejscroggins's project, which is named "tilde", I modified it to meet my requirements and habit, including:
* Bookmarks
* Groups
* Shortcut-keys
* Re-draw brand logo with CSS background element (yes, i know it's crazy but funny!)
and (may be?) something which I forgot

# To-do lists:
Not sure, but may be:
* Search Engines and Suggestions?
* Multi-level of Bookmarks?
* New Commands?
I will update when I need!

# Installation (Firefox)
- Download (or "git clone")
- Homepage: Firefox support set a local html file as homepage
- New tab page:
    - Option 1: https://addons.mozilla.org/vi/firefox/addon/new-tab-override/
    - Option 2: Using user-chrome on firefox. Credit: https://luke-baker.github.io/
- (Optional) Online: https://ducminh3112.gitlab.io/mnml-startpage/


# Usage: If I have'nt mentioned before as my personal mod, it's same as the original of cadejscroggins (Credit: https://github.com/cadejscroggins/tilde). In short:
> - Enter `?` for full list of keyword
> - Enter `keyword` for website, e.g enter `git` for "https://gitlab.com/"
> - Enter `keyword:searchterm` for searching, e.g: enter `git:hello world` for https://gitlab.com/search?search=hello+world
> - Enter `keyword/subpage` for sub webpage, e.g: enter `git/ducminh3112` for https://gitlab.com/ducminh3112
> - Enter `search-term` for Googling, e.g: enter `cats` for [Google for cats](https://encrypted.google.com/search?q=cats).
> - Enter `url` for webpage, e.g: enter `google.com` for https://www.google.com/

# luke-baker 's user-chrome guide (Credit: https://luke-baker.github.io/):
**Initial setup**
>1. Enter about:support into Firefox's location bar.
>2. Click the Open Folder button. This launches a file manager window with your Firefox profile folder.
>3. Open Firefox_chrome.zip. If you extract it into your Firefox profile folder, it will create the chrome folder, and inside it, userContent.css, userChrome.css, and userChrome.xml. If you already have your own CSS files set up, only extract userChrome.xml, then copy the code from the ZIP's userChrome.css into your own.
>4. A restart is required for the change to take effect, though the files won't affect anything until you add some styles or scripts.

**Adding user scripts**
>1. Option 1: Simply save the *.uc.js files into the chrome folder.
>2. Option 2: You could paste every script in a single file named userChrome.js in the chrome folder, but that's not very manageable. 

# cadejscroggins 's usage guide (Credit: https://github.com/cadejscroggins/tilde):

To go to a site, enter the corresponding key. To view the available sites and
their keys, press `?`. If your input doesn't match any of the commands, a
generic Google search will be triggered. For example:

- Entering `r` would redirect you to [www.reddit.com](https://www.reddit.com).
- Entering `t` would redirect you to [twitch.tv](https://www.twitch.tv).
- Entering `cats` would search
  [Google for cats](https://encrypted.google.com/search?q=cats).

On mobile, you can click the clock to focus the search input.

#### Searching

You can search any of the sites by typing a colon after the site's key, followed
by your search query. For example:

- Entering `g:tilde` would search
  [GitHub for tilde](https://github.com/search?q=tilde).
- Entering `s:radiohead` would search
  [SoundCloud for radiohead](https://soundcloud.com/search?q=radiohead).

#### Specific Locations

You can go to a specific location on a site by typing a forward slash after the
site's key, followed by the location on the site you'd like to be redirected to.
For example:

- Entering `r/r/startpages` would redirect you to
  [www.reddit.com/r/startpages](https://www.reddit.com/r/startpages)
- Entering `h/popular` would redirect you to
  [hypem.com/popular](http://hypem.com/popular).

#### URL Redirects

If you enter in a full domain or URL, you will be redirected to said domain or
URL. For example:

- Entering `stallman.org` would redirect you to
  [stallman.org](https://stallman.org/).
- Entering `https://smile.amazon.com` would redirect you to
  [smile.amazon.com](https://smile.amazon.com/).

#### Query Paramater

Additionally, you can pass any query via the `q` query param. For example:

- Going to `file:///path/to/tilde/index.html?q=cats` would search
  [Google for cats](https://encrypted.google.com/search?q=cats).

This allows you to invoke Tilde with your native browser search bar.

### Configuration

The above is just the beginning. Open up the [index.html](index.html) file and
read through the `CONFIG`!