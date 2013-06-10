# Octopress Theme - YinYang

YinYang (陰陽) is a minimal, responsive theme for Octopress.
Based on [Greyshade](https://github.com/shashankmehta/greyshade)

[Demo](http://blog.due.io/)

## Install

	$ git clone git@github.com:qingwang/octopress-theme-yinyang.git .themes/yinyang
	$ rake "install[yinyang]"
	$ rake generate

## Featured Image

One featured image can be added to each post. To do this, add a `featured` parameter to your markdown file. For example:
```markdown
---
layout: post
title: This is a post
categories:
- blah
comments: true
featured: "http://the.url.to/your_image.jpg"
published: true
---
```

## Sharing Icons

At the moment YinYang uses [AddThis](http://www.addthis.com/). You need to register an account with them and put your id in `_config.yml`. `source/_includes/post/sharing.html` needs to be customised to your own settings as well. I might change this in the future. Their icons do not look fit.

## Known Issues

On a horizontal iPad, the menu and the profile picture may overlap if profile description is too long and/or menu items are too many.

## Credits

[Greyshade](https://github.com/shashankmehta/greyshade) | [Orange on gray](https://kuler.adobe.com/Orange-on-gray-color-theme-2221/)

## License

MIT
