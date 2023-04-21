# XFileManager

A feature-tree based file manager for all platforms.

## Description

XFileManager is a file manager that uses a feature-tree to display files and folders. It's main feature is **feature-tree**.

A feature-tree is similar to a file-tree, but it's **built up by rules**, which related to each file's features. And, the rules can be customized by users.

For example, we can build a new feature-tree by the following rules:

- Files that have a ".git" folder at the same or upper level should be grouped into a feature named "Git".
- Files with extension ".pdf|.doc|.docx|.xls|.xlsx|.ppt|.pptx|.txt|.md|.epub|.mobi" should be grouped into a feature named "Document".
- Files that belongs to media files(like photos, videos, songs) should be grouped into a feature named "Image", and under the feature, the files should be grouped by time (year/month/day).
- Files that matches \[project\]*.* should be grouped into a feature named "Project", with files and folders at/under its directory in one diretory.

By these rules, we can build a feature-tree. It has root dirs like "Git", "Document", "Image", "Project", and each of them has sub dirs.

And this is only one feature-tree. We can build more feature-trees by different rules. The trees can fit different requirements.

## Tech Stack

For cross-platform support, XFileManager is built with C++ as backend. For the UI, it's still under consideration.
