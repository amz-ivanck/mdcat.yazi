# mdcat.yazi

Preview markdown files in [yazi](https://github.com/sxyazi/yazi) with [mdcat](https://github.com/swsnr/mdcat).

Install this plugin with:

```bash
ya pkg add amz-ivanck/mdcat
```

Then set it up in your `yazi.toml` file by adding:

```toml
[plugin]
prepend_previewers = [
  { name = "*.md", run = "mdcat" },
]
```
