## What is Web Scraping?

- Web scraping is the process of gathering information from the Internet. 
- The words “web scraping” usually refer to a process that involves automation. 
- Some websites don’t like it when automatic scrapers gather their data, while others don’t mind.

## Reasons for Web Scraping
- Automated web scraping can be a solution to speed up the data collection process. 
- You write your code once, and it will get the information you want many times and from many pages.
- Manual web scraping can take a lot of time and repetition.

## Challenges of Web Scraping
- The Web combines many different technologies, styles, and personalities, and it continues to grow to this day. 
- In other words, the Web is a hot mess! Because of this, you’ll run into some challenges when scraping the Web:

<b>Variety:</b> Every website is different. While you’ll encounter general structures that repeat themselves, each website is unique and will need personal treatment if you want to extract the relevant information.

<b>Durability:</b> Websites constantly change. Say you’ve built a shiny new web scraper that automatically cherry-picks what you want from your resource of interest. The first time you run your script, it works flawlessly. 
But when you run the same script only a short while later, you run into a discouraging and lengthy stack of tracebacks!
Once the site’s structure has changed, your scraper might not be able to navigate the sitemap correctly or find the relevant information. 
he good news is that many changes to websites are small and incremental, so you’ll likely be able to update your scraper with only minimal adjustments.

## An Alternative to Web Scraping?: APIs

- Some website providers offer application programming interfaces (APIs) that allow you to access their data in a predefined manner. 
- With APIs, you can avoid parsing HTML. 
- Instead, you can access the data directly using formats like JSON and XML. 
- HTML is primarily a way to present content to users visually.
- When you use an API, the process is generally more stable than gathering the data through web scraping.
- The structure of an API is usually more permanent, which means it’s a more reliable source of the site’s data.
- However,in rare ocasions, APIs can change as well.
