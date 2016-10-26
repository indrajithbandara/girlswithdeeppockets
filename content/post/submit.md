+++
title = "Submitting a post"
date = "2016-10-26T16:56:43+02:00"
tags = ["gwdp","using the site"]
categories = ["gwdp"]
menu = ""
images = []
banner = "banners/coding.jpg"
draft = false
+++

To submit a post directly to the site, then at the moment it requires you to be reasonably comfortable with GitHub and markdown. 

> If that's put you off, simply fill in [this form](https://1drv.ms/xs/s!AiZm2P6YHtSfiW39itkxlFlmu4gt) which asks you for information and we'll get around to penning a blog post on your behalf.

## Getting ready to write your post
1. [Fork](https://guides.github.com/activities/forking/) this [repository (stephlocke/girlswithdeeppockets)](https://github.com/stephlocke/girlswithdeeppockets) to your own GitHub account
1. [Clone](https://help.github.com/articles/cloning-a-repository/) this to your computer
1. Create a new file called `[SOMETHINGRELEVANT].md` in `girlswithdeeppockets\content\post` and copy the typical header content into the top of the file and amend it

```
+++
title = "Submitting a post"
date = "2016-10-26T16:56:43+02:00"
tags = ["gwdp","using the site"]
categories = ["gwdp"]
menu = ""
images = []
banner = "banners/placeholder.png"
draft = false
+++
```

## Writing your post
1. Use [markdown](https://gohugo.io/content/example/) to write your piece.
1. Add a good quality image into `static/banners` and amend the reference in the header
1. Add tags and categories that make sense to the header info
1. Verify your markdown and spelling on [StackEdit](https://stackedit.io/editor)

## Submitting your post
1. Using git, add any new files, commit them, and push the change to GitHub
1. Alternatively, you can upload your files [directly to GitHub](https://help.github.com/articles/adding-a-file-to-a-repository/) since you probably won't be making changes to any existing content
1. [Submit a pull request](https://help.github.com/articles/creating-a-pull-request/) to the main repository for us to incorporate into the site


## Submission guidelines
1. Make sure to include in the intro who you are and link to your twitter (or some other social media dohicky)
1. Keep it clean! Frick is as hard a swear word allowed
1. You can talk about most pocket related topics like:
    + An item of clothing you found that has decent pockets
	+ A line of clothing that is gives us pockets
	+ Tips for adding pockets to outfits
	+ Thoughts on how we can tackle a lack of pockets
	+ Other resources in the fight for pockets
1. Pictures are great, the more the merrier, so you can do a gallery or use some [image shortcodes](https://gohugo.io/extras/shortcodes/index.html#figure).

    {{</* gallery
        "/banners/placeholder.png"
        "/banners/placeholder.png"
        "/banners/placeholder.png"
    */>}}
	
## Copyright
You'll own the copyright to whatever you write, but you grant us permission to use it on the site, include it in a syndicated feed from the site, and use it for marketing purposes towards getting more pockets on our clothes.