RSS feed reader. When I read an item in a feed, azusa compares that to the last
time the feed went from no new items to some new items (in number of times the
program's been opened) to determine a rough estimate of how bored I had to be to
read it. As it learns tastes more and more, I can start just reading the home
screen of the program, which has things I'm more likely to be interested in at
the top.

Like Google Reader, azusa can assign a feed to multiple folders. Unlike Google
Reader, azusa can nest folders arbitrarily deep (so that, for instance, anything
put in the "Python" folder is automatically included in "Programming").
Selecting a folder will show all feeds in that tag, ordered once again by
"interesting" value.

Web app.

First, we probably would start off with the various tags viewable.

![tags](http://github.com/xiongchiamiov/azusa/raw/master/mockups/tags.png)

Some have child tags, some don't. Clicking on a tag will display all feeds
matching it in the right pane. Moving tags around will probably be accomplished
with simple drag-n-drop.

Double-clicking the middle divider brings us to a list of the feeds that match
the selected tag.

![feeds](http://github.com/xiongchiamiov/azusa/raw/master/mockups/feeds.png)

This list is flat. Selecting a feed will display only items from that feed in
the right pane.

Double-clicking the right divider gives a list of the different items in the
selected feed.

![items](http://github.com/xiongchiamiov/azusa/raw/master/mockups/items.png)

Selecting an item will show only that item in the right pane. Previously-read
items may still be shown in this list, greyed-out.

Double-clicking the left divider brings us back to the tag overview. To view
multiple panes at once, drag a slider out. Dragging a slider in will collapse it
again, allowing you to view the feeds alone.

Name unrelated: [Nakano Azusa] is a character from K-On!.

[Nakano Azusa]: http://anidb.net/ch7124
