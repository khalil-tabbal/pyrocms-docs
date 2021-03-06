# Tag Reference

Tags are a way to put dynamic content into your theme or page content. They may also be used to as a shorthand way to insert an image tag, link to javascript files, etc. They can be embedded in Page content, Blog posts, and directly in a Theme file.

For example, here is a simple tag that returns the site's URL:

	{{ noparse }}{{ url:site }}{{ /noparse }}

Tags can range from variables, like this, to more advanced functionality like displaying blog posts.

It's important to note that some tags accept attributes that affect their output. For example the list of plugins that you see on the right side of this page is generated by a plugin within the core of PyroCMS. The output is placed in this page by embedding the page_tree tag, which is part of the pages plugin:

	{{ noparse }}{{ pages:page_tree start-id=&quot;foo&quot; }}{{ /noparse }}

For a more complete tutorial on the PyroCMS tag syntax, see the <a href="http://www.pyrocms.com/docs/2.0/manuals/designers/tag-syntax">tag syntax</a> page.

## Under the hood

If you are developer and want to more about how plugin tags work and how you can make your own, check out the <a href="http://www.pyrocms.com/docs/2.0/developers">developer docs</a>.{{ /noparse }}</p>
