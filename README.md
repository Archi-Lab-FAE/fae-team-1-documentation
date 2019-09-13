# fae-team-1-documentation

In this repository all decisions concerning only team 1 should be documented.

## Usage
To create a new entry first create a markdown file according to the following template.

```
Filename: YYYY-MM-DD-TITLE.md
Example: 2019-09-12-Example.md
```

Attention: Each title must be unique, so the file is always found.

After you have created the file, the server needs some metadata to properly assign the entry. The metadata must be at the top of the file.

### Metadata
```
---
layout: post
title: The title // This does not have to be the same as the file name!
author: The name of the author // optional
categories: team1 // The Team Specific Category
---
```

Following the metadata comes the actual content. Once you commit and push an entry, the server is refreshed and provides the new entry.
