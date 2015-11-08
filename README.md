# jekyll-taggen
Yet another tag pages generator for Jekyll.

## How to use this  

 1. Add tags to your pages (or blog posts) in the front matter in this way  
 
```
tags:  
- xamarin  
- events
```  

 2. Copy both `_plugins` and `_layouts` to your jekyll's site source. If prompted, choose to merge contents.
 3. Modify `_layout\tag_index.html`, which is the index of all the tags your site will contain.
 4. Modify `_layout\tag_page.html`, which is the page of all the pages marked a given tag.
 5. Run your site and navigate to `[YourUrl]/tag` or `[YourUrl]/tag/[SomeTag]`.
 
That's it.

## Demo  
I use this in my site, you can check a sample of the tag page here: [#aprende-c-sharp](http://thatcsharpguy.com/tag/aprende-c-sharp)

## You did this?  
Nope, just modified it from [Charlie Park's implementation](http://charliepark.org/tags-in-jekyll/)
