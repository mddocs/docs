---
menuTitle: Insert Links and Images
weight: 1.7
---

# Insert Links and Images

Mddocs supports two ways of inserting links inside ```.md``` files:
 - **Relative**: links to pages and content within repository
 - **Absolute**: links to pages and content outside repository

In order to place a link inside ```.md``` file use the generic [markdown](https://www.markdownguide.org/basic-syntax/#links) syntax:
- Image
```![Image Description](link)```
- Link
```[Link Title](link)```

## Relative links

Relative links considered to be relative to ```.md``` file where the link is placed.

### Relative to current document

The relative link could start with ```./``` or with nothing at all:
- ```[Link Title](./file.md)```
- ```[Link Title](file.md)```

### Relative to source folder

In order to insert a link relative to [Source Folder](./change_root_folder.md), use the ```/``` symbol at the beggining of link:

```[Link Title](/someFolderInSourceFolder/page.md)```

## Absolute links

You can use any of absolute links inside ```.md``` document:

- ```![Picture](https://github.com/mddocs/docs/blob/main/images/social.png?raw=true)```
- ```![Picture](https://docs.mddocs.io/images/social.png)```
- ```[Home](https://docs.mddocs.io/)```