# Scraper API

This is an API *(in progress)* allows to scrape data from various website using <a href="https://playwright.dev">playwrighter</a>.
Documentation upcoming.

## Tiktok Hashtags

Use : 
```py
with sync_playwright() as playwright:
    scraper = Scraper(playwright)
    scraper.tiktokHashtags("<your tag>")
```

Replace `<your tag>` by one of the tags available in <a href="https://ads.tiktok.com/business/creativecenter/inspiration/popular/hashtag/pc/en">TikTok Creative Center</a>.

<details>
<summary>Tags Available</summary>
- Apparel & Accessories<br>
- Baby, Kids & Maternity<br>
- Beauty & Personal Care<br>
- Business Services<br>
- Education<br>
- Financial Services<br>
- Food & Beverage<br>
- Games<br>
- Health<br>
- Home Improvement<br>
- Household Products<br>
- Life Services<br>
- News & Entertainment<br>
- Pets<br>
- Sports & Outdoor<br>
- Tech & Electronics<br>
- Travel<br>
- Vehicle & Transportation<br>
</details>