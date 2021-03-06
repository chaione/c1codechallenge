---
layout: default
title: iOS - App.net client
---

## iOS App.net Client

Create an App.net client that just lists the most recent posts from the public timeline.

- Each post should be rendered in a table view cell, with the most recent at the top.
- Each cell should contain the user's avatar (bonus if the corners are rounded)
- Each cell should contain the poster's name in bold
- Each cell should contain the post text, and be variable height, depending on the text size
- Pull to refresh should be implemented to refresh the timeline
- The list should scroll quickly, without dropping frames on an iPhone 5
- The latest publicly released iOS SDK should be used
- Use of third party libraries are allowed but are not required

The timeline can be fetched here: [`https://alpha-api.app.net/stream/0/posts/stream/global`](https://alpha-api.app.net/stream/0/posts/stream/global).

Feel free to use any library you want. The code should reflect how you write classes, methods, etc in a normal application.
