# 1.1.0 Meta File Specifications

The file must be named `meta.json` and be placed within the library item's directory.

## meta.json

```json
{
    "_infover": "1.1.0",
    "classification": "AS",
    "title": "Lorem Ipsum",
    "author": "John Doe",
    "date": "1990-01-01",
    "sourceFile": "LoremIpsum.txt",
    "otherFiles": [
        {
            "label": "Lorem Ipsum PDF",
            "path": "LoremIpsum.pdf",
            "description": "Lorem Ipsum in a PDF format."
        }
    ],
    "flags": ["text", "prose", "example", "libalexandria"],
    "description": "An example LibAlexandria Item."
}
```

* `_infover`: Version code of the meta file.
* `classification`: The alphabetical component of the United States Library of Congress classification code that best describes the associated work. The classification codes can be found either on the [Library of Congress' website](https://www.loc.gov/catdir/cpso/lcco/) or [Wikipedia](https://en.wikipedia.org/wiki/Library_of_Congress_Classification#Classification).
* `title`: Title of the associated work.
* `author`: The name of the author or authors of the associated work.
* `date`: The date of creation for the associated work in the `YYYY-MM-DD` format.
* `sourceFile`: A local, relative, filepath to the associated work's primary content file.
* `otherFiles`: A list of other files related to the associated work. The value of this key can also be `null` to indicate no additional files are specified.
    * `label`: Title or generic label for this additional file.
    * `path`: A local, relative, filepath to this additional file.
    * `description`: A description of the content within this additional file.
* `flags`: An array of string tags for the associated work. The value of this key can also be `null` to indicate no flags are specified.
* `description`: A description of the content within the associated work.
