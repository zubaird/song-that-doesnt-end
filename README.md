# The song that doesn't end

Based off of https://www.youtube.com/watch?v=HNTxr2NJHa0

## Stories

### Basic

```
Users should be able to see the first verse on the homepage
```

```
Users should be able to see a page with the second verse
The homepage should link to the second verse page
```

```
Users should be able to see a page with the third verse
The second verse page should link to the third verse page
```

```
Users should be able to see a page with the fourth verse
The third verse page should link to the fourth verse page
The fourth verse page should link to the homepage
```

### Extra

```
Only use the index view to serve all pages

For example:

def verse2
  render "index"
end

def verse3
  render "index"
end

HINT: you'll need an if-statement in your view
```

## Wireframes

![](https://galvanize.mybalsamiq.com/mockups/2326897.png?key=ed1559654fd129e94319ca82828d854c8978fe2e)
