# jkl

utils for jekyll: `npm install -g jkl`

## commands

### `new`

Create a new post:

```
$ jkl new i-love-jkl
created : ./2014-02-09-i-love-jkl.md
```

If you're in a jekyll project, it'll default to the `_posts` folder:

```
$ jkl new i-love-jkl
created : ./_posts/2014-02-09-i-love-jkl.md
```

You can also specifiy a directory:

```
$ jkl new i-love-jkl _drafts
created : ./_drafts/2014-02-09-i-love-jkl.md
```

### `rm`

Delete a new post.

```
$ jkl rm i-love-jkl
deleted : ./2014-02-09-i-love-jkl.md
```

This has the same behaviour as `new`.

### `draft`

Like `new`, but defaults to `_drafts`.

## license

MIT


