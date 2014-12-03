# Octopress Themes

I got tired of looking for octopress themes through the table view on the [Octopress Wiki Pages](https://github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes) so I made a [simple gallery](octopressthemes.github.io) for easier browsing.
All the data was curated from the Octopress Wiki pages by using a simple [Ruby Script](https://github.com/octopressthemes/theme-crawler).

## Theme submission

This site built with jekyll, so you can easily submit pull requests by doing the next few steps:

1. Fork the repo
2. Create a new post in the `_posts` directory, named "YYYY-MM-DD-#{theme_name.underscore.dasherize}".
3. Add data to the post, following the [Jekyll front matter format](http://jekyllrb.com/docs/frontmatter/), e.g:

```yaml
---
title: BlogTheme
slug: blog-theme
github_link: https://github.com/username/repo
demo_preview: http://example-demo.com
demo_screenshot: http://example-screenshot.com (this is only needed if there isn't a live demo)
description: E.G: Minimal and responsive theme
---
```

4. Add a screenshot sized 400x300px in the `screenshots` folder. The screenshot should be a png, and have a slug name (so, if the name of the theme is 'SuperTheme', the screenshot should be 'super-theme.png').

## Credits

The layout used is an open source theme called [Drifolio-Bootstrap](https://github.com/srizon/Drifolio-Bootstrap) by [@srizon](https://github.com/srizon).
