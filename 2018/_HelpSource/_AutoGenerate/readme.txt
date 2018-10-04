With VS 2010+ Help, TOC and Index items are defined using topic meta tags.
So Empty TOC links, Duplicate TOC links, TOC links with Bookmarks, and TOC links to remote locations are not allowed.
We solve this problem by generating temporary HTML files in this folder. You will need to fix these problems at some stage.

Also note that with VS 2010+ Help TOC labels come from the topic <title> tag. So labels in your old TOC files are ignored during migration.
