# Youtube Notification Bot
Simple and easy to use discord bot to notify members whenever a video is posted on a YouTube channel.

# Packages Used
- **[discord.js](https://npmjs.com/package/discord.js "View on npmjs")**
- **[quick.db](https://npmjs.com/package/quick.db "View on npmjs")**
- **[rss-parser](https://npmjs.com/package/rss-parser "View on npmjs")**

# config.js

```js
module.exports = {
    token: "ODYxOTUzMzU4NzAwMDg1Mjg5.YORSnw.wsXn7t4RkQ_TuOlq9aYNW44Z6hI", // discord bot token
    channel: "887360968584220763", // channel id of a channel to send message
    messageTemplate: "Hello @everyone, **{author}** just now uploaded a video **{title}**!\n{url}", // message to send on discord
    channel_id: "UCr3IeCexPPnBaM-vKFtsYkw", // youtube channel id
    watchInterval: 30000 // Check every 30 seconds
};
```
