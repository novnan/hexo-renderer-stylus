# hexo-renderer-stylus-plus

This renderer plugin is forked from [hexo-renderer-stylus](https://github.com/hexojs/hexo-renderer-stylus/blob/master/lib/renderer.js). Add get site configuration function.

## Install

Prerequisites:
- Hexo 3: >= 0.2
- Hexo 2: 0.1.x

``` bash
$ npm install hexo-renderer-stylus-plus --save
```

## Options

You can configure this plugin in `_config.yml`.

``` yaml
stylus:
  compress: false
  sourcemaps:
    comment: true
    inline: true
    sourceRoot: ''
    basePath: .
```

- **Stylus**:
  - **compress** - Compress generated CSS (default: `false`)


- **Sourcemaps**
  - **comment** - Adds a comment with the `sourceMappingURL` to the generated CSS (default: `true`)
  - **inline** - Inlines the sourcemap with full source text in base64 format (default: `false`)
  - **sourceRoot** - `sourceRoot` property of the generated sourcemap
  - **basePath** - Base path from which sourcemap and all sources are relative (default: `.`)

[Stylus]: http://stylus-lang.com/
[nib]: http://tj.github.io/nib/
