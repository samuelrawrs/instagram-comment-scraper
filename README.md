# instagram-comment-scraper
Attempting to obtain comments from an instagram post and visualizing the data.

edit: 24/3/2023 - I've not implemented the bot checking on the users who have commented but might do it next time. It'll probably be something simple like filtering users as valid or not based on their number of followers/following. Would be great if I had access to their account creation date.

more details are in the [python notebook]([url](https://github.com/samuelrawrs/instagram-comment-scraper/blob/main/instagram-comment-scraper.ipynb)) but here's a sneak peek:

## The inspiration
My friend **kwokho** participated in an instagram competition by GOMObysingtel. The challenge was to get as many comments tagged to his number (2). However, we started observing many suspicious accounts with 10 or less followers/following commenting for number 4, another participant.

This got me curious about how GOMO would actually count the number of comments and I wanted to find out if I was able to actually sieve through the comments to see who is considered a bot or not. SO LETS TRY THIS OUT.

