# Storify Embeddable Link Extractor
A means to pull out all embeddable links from a Storify that can be quickly copy/pasted to Wordpress.

Utterly, crudely alpha

## What/Why?

[Storify is going away](https://storify.com/faq-eol) and taking your stuff with it. Reclaim your storifies now, this can work as an Wordpress site, these are the links that can be autoembedded on any Wordpress page or Post. 

Here's how:
			
1. Go to your Storify you wish to preserve, e.g. `https://storify.com/cogdog/ds106-tips-for-audio-storytelling`
2. In the browser url field, add `.html` and go to this new location, e.g.  `https://storify.com/cogdog/ds106-tips-for-audio-storytelling.html` This is the static HTML versiom you get from the Storify export instructions.
3. Use your browser features to `View Source`, copy the entire source HTML
4. Go to the Extractor tool at http://cogdog.github.io/storify-extractor
5. Paste the copied HTML content into the Inpu field
6. Click `Get Links`
7. There it is! Copy the contents from the Extracted Links field, and paste into a blank Wordpress post. Watch the embedding happen.

Dress up your post with featured images, dancing baby gifs, and anything else you like. [See how the example above turned out](http://ds106.us/handbook/tools/audio-storytelling-tips/). You have reclaimed your storify. Celebrate. Reclaim.


