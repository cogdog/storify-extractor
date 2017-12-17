# Storify Embeddable Link Extractor

by @cogdog http://cog.dog

![](images/extractor.png "Extractor image")

A means to pull out all embeddable links and text blocks from a Storify that can be quickly copy/pasted to Wordpress.


## What/Why?

[Storify is going away](https://storify.com/faq-eol) and taking your stuff with it. Reclaim your storifies now, this can work as an Wordpress site, these are the links that can be autoembedded on any Wordpress page or Post. The extractor should also pull any headings or captions added to the timeline.

It may not be perfect, and might need some cleanup, but this will save me a lot of time trying to archive my Storify content.

## Here's how to do it:
			
1. Go to your Storify you wish to preserve, e.g. `https://storify.com/cogdog/ds106-tips-for-audio-storytelling`
2. In the browser url field, add `.html` and go to this new location, e.g.  `https://storify.com/cogdog/ds106-tips-for-audio-storytelling.html` This is the static HTML versiom you get from the Storify export instructions.
3. Use your browser features to `View Source`, copy the entire source HTML
4. Go to the Extractor tool at http://cogdog.github.io/storify-extractor
5. Paste the copied HTML content into the Input field
6. Click `Get Links`
7. There it is! Copy the contents from the Extracted Links field, and paste into a blank Wordpress post. Watch the embedding happen.

Dress up your post with featured images, dancing baby gifs, and anything else you like. [See how the example above turned out](http://ds106.us/handbook/tools/audio-storytelling-tips/). You have reclaimed your storify. Celebrate. Reclaim.

## Credits

Blame all ugly and juvenile grep coding on me. Not elegant at all. StackExchange saved me so many times I lost count.

[Pixabay Image](https://pixabay.com/en/tongs-steel-blacksmith-utensil-24241/) by [Clker Free-Vector Images](https://pixabay.com/en/users/Clker-Free-Vector-Images-3736/) shared into the public domain using [Creative Commons CC0](https://pixabay.com/en/service/terms/#usage)


