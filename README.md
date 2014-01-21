# [Hexo](http://zespia.tw/hexo/) helper plugin that generates a list of recent posts

## Usage

### Install

```
npm install hexo-helper-recent_posts --save
```

### Use in your theme
Add: `<%- recent_posts({ count: 10 }) %>`

Default options :
```
{
    count: 5,
    ulClass: 'recent_posts',
    liClass: 'recent_post'
}
```

### Update

```
npm update
```

### Uninstall

```
npm uninstall hexo-helper-recent_posts
```

[Hexo]: http://zespia.tw/hexo