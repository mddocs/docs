---
menuTitle: Insert Links and Images
weight: 1.7
---

# Options

Mddocs supports two options for providing links inside .md files:
 - **Internal** (links to pages and content within repository)
 - **External** (links to pages and content outside repository)

## Internal links

Internal links considered to be relative to .md file inside repository.

To insert the link to .md content use the generic markdown syntax
- Image
```![ImageDescription](relativeLink)```
- Link
```[LinkTitle](relativeLink)```

### Relative to current ```.md``` document

The relative link could start with ```./``` or with nothing at all:
- ```[LinkTitle](./file.md)```
- ```[LinkTitle](file.md)```

### Relative to Source Folder

If you need to insert the link relative to [Source Folder](./change_root_folder.md), use ```/``` at start of link:

```[LinkTitle](/someFolderInSourceFolder/page.md)```

## External links

You can use any of absolute links inside ```.md``` document.

# Examples

Take a look into [LinksExample](https://github.com/mddocs/examples/LinksExamples) part of Mddocs repository