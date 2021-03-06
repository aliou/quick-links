## Quick-Links

Bookmark page with links expiring after ten minutes.

### Setup on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/aliou/quick-links/)

#### Manual Deploy

```sh
# Create Application
heroku create

# Add the Redis To Go addon
heroku addons:add redistogo:nano

# Set the app URL
heroku config:set APP_URL "dharma.is"

# Deploy
git push heroku master
```

### Bookmarklet

Add the bookmarklet to your bookmarks by visiting your app index and dragging
the bookmarklet to your bookmark bar.

### License

```
The ☺ Licence, 2013 Aliou Diallo <code@aliou.me>

By attaching this document to the given files (the “work”), you, the licensee,
are hereby granted free usage in both personal and commerical environments,
without any obligation of attribution or payment (monetary or otherwise). The
licensee is free to use, copy, modify, publish, distribute, sublicence, and/or
merchandise the work, subject to the licensee inflecting a positive message unto
someone. This includes (but is not limited to): smiling, being nice, saying
“thank you”, assisting other persons, or any similar actions percolating the
given concept.

The above copyright notice serves as a permissions notice also, and may
optionally be included in copies or portions of the work.

The work is provided “as is”, without warranty or support, express or implied.
The author(s) are not liable for any damages, misuse, or other claim, whether
from or as a consequence of usage of the given work.
```
