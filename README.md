# my-pwp-nat
My PWP Repository:
This repository is used to store my personal website and the supporting documentation.

## Milestone 1 Feedback
Nice work on a well defined direction for your PWP. Based on the  Persona you've created it sounds like you have a good understanding of the target audience for your mom's yoga practice. You've done a really nice job of creating a Persona that reads like real person. Having access to information about your mom's current and prospective students will be a great asset for the upcoming design phase and content strategy. I look forward to seeing this project take shape.

Your project is set up according to spec, and your code looks good. Nice work. 

Your Milestone 1 passes at [Tier IV](https://bootcamp-coders.cnm.edu/projects/personal/rubric/).

### Edits &amp; Suggestions
Although this project is very small in scope, some basic SEO considerations could help your mom's search engine results. Google has a decent starter guide here: 
- https://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf 

A couple of other very simple things I would include at a minimum are a &lt;meta&gt; description tag, and SEO-aware file names and `alt` text for all images.

A very minor point here, but going forward I recommend not relying so much on the &lt;br&gt; tag for visual spacing of content. That's better done using CSS.

## Milestone 2&alpha; Feedback
Nice work - your ideas are clearly defined and the wireframes are well done. I had a much easier time getting a clear picture vs. the last time I looked at these. I think you're on the right track now.

I don't want to repeat the previous feedback I've already given you - but just take note of the points regarding image quality and content layout/length going as you go forward. 

It might be attractive to set the large image up top as a background with the title text placed on top. Something to consider. And when working with images there are some key considerations to keep in mind. Have the images exported and web-ready before you begin.

Suggestions:
- Keep the aspect ratios consistent across the entire image set. Both landscape and portrait images should all have the same proportions/aspect ratios between them. This will contribute to a far more professional presentation, and will also make your development easer.
- Recommended that the long axis of each image be the same dimension if possible. 
- Recommend max file size < 700kb for the largest images - ideally less. < 300 kb for all others.
- 72 ppi is the "old standard" for general-purpose web resolution. (Retina and print are different cases.) 
- .jpeg, .png, .gif formats only for images. SVG ok for vector graphics. (No .tiff, no .bmp). jpeg format preferred for photographs.
- SEO-aware file names and good `alt` text content recommended.

Your image gallery will require using a JavaScript solution. One of my favorite gallery plugins is [FancyBox3](http://fancyapps.com/fancybox/3/). It's touch/swipe enabled, responsive, and easy to integrate.

Your directory structure and code all look good. I think you're ready to begin development.

Build your PWP in a file named `index.php` inside `/public_html`. CSS, images, and JS directories should also be inside `public_html` and siblings to `/documentation`. We won't be using the `/documentation` directory any longer.

Nice work. Your Milestone 1 passes at [Tier III](https://bootcamp-coders.cnm.edu/projects/personal/rubric/). You're clear to begin development!
 
### Edits &amp; Suggestions
- remove the `.php` file from the root of the project.
