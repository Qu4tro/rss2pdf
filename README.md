rss2pdf
========

* Convert rss feeds to pdfs and uses etag and last modified time to avoid redownloading feeds.

Quick usage overview:

```bash
rss2pdf --feed="http://example.com/feed" --directory="/home/user/feeds"
```

Requires:

    * wkhtmltopdf tool
    * click
    * feedparser

