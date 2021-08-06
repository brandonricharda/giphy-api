# README

This is my solution to the Giphy API practice assignment, which is part of The Odin Project. Learn more about the assignment here:

https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript/lessons/working-with-apis

The goal of this assignment was to create a mini-application that retrieves GIFs from Giphy's API based on the user's input.

Learn more about Giphy's API here:

https://developers.giphy.com/docs/api/

I went one step further and incorporated the Open Emoji API, which you can learn about here:

https://emoji-api.com/

When the user searches for a GIF, I pass that query into the Open Emoji API. I then select the first result and update the button text to include that emoji. If no emoji is returned, the button simply ends up without an emoji.
