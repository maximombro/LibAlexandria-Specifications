# Library Structure

>
> This page may be updated in the future to be more verbose.
> As it stands now, this is as simple and accurate as possible.
>

## Overview

* LibAlexandria Libaries are composed of a series of directories.
* LibAlexandria Libaries have a `README.md` file in thier root directory.
    * The `README.md` file provides and introduction to the specific library.
* LibAlexandria Libary categories can be labeled as anything the user wants.
* LibAlexandria Items contain the item's content and `meta.json` file unique to the content.

## Example Directory Map

```
LibAlexandria Library
|   README.md
|
└─── CategoryA
|   |
|   └─── WrittenWorkA
|       | meta.json
|       | workA.txt
|       | ...
|       |
|   └─── WrittenWorkB
|       | meta.json
|       | workB.txt
|       | ...
|
└─── CategoryB
|   |
|   └─── SubCategoryA
|   |   |
|   |   └─── WrittenWorkC
|   |       | meta.json
|   |       | workC.txt
|   |       | ...
|   |
|   └─── SubCategoryB
|       |
|       └─── WrittenWorkD
|       |   | meta.json
|       |   | workD.txt
|       |   | ...
|       |
|       └─── WrittenWorkD
|           | meta.json
|           | workD.txt
|           | ...
|
| ...
```
