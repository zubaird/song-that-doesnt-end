# The song that doesn't end

Links:

* Youtube: https://www.youtube.com/watch?v=HNTxr2NJHa0
* Images:
    * http://rophydoes.rintin.com/wp-content/uploads/2011/01/lambchop1.jpg
    * http://i.ytimg.com/vi/1_47KVJV8DU/mqdefault.jpg
    * http://media-cache-ak0.pinimg.com/236x/4d/61/6c/4d616c5f67a37d1b7db7acc79a3dcf03.jpg
    * http://media-cache-ak0.pinimg.com/236x/75/a1/d4/75a1d4cba1954c1abee9b4bd85d21de9.jpg

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

```
Users should see a link to Youtube and the Homepage on every page
```

```
Users should see images on every verse, according to the wireframe
```

NOTE: 

* use the `.text-center` class to center images and text in the page.
* be sure to copy the images locally - don't reference the images by URL

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
