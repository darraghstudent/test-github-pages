# Writing your docs

How to layout and write your Markdown source files.

---

## File layout

The documentation source should be written as regular Markdown files. By default, the directory will be named `docs` and will exist at the top level of your project, alongside the `mkdocs.yml` configuration file.


By convention the project homepage is named `index.md` 

We create multi-page documentation, by creating several Markdown
files:


docs/
    index.md
        /explanation   
        /How To Guide
        /reference
        /tutorial  
```

The file layout determines the URLs that are used for the generated
pages. 

You can also include your Markdown files in nested directories.


docs/
    index.md
    How To Guide/overview.md
    How To Guide/configuration-options.md


Source files inside nested directories will cause pages to be generated with nested URLs, like so:


/user-guide/getting-started/
/user-guide/AWS-Cloudformation.md/


