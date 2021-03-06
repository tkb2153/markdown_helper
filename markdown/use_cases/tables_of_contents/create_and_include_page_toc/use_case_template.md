### Create and Include Page TOC

1.  Maintain markdown text in a separate file.
2.  Create a table of contents for the text.
3.  Use an includer file to include the contents and the text.

#### Text File

It's big, so linking instead of including:  [text file](text.md#lorem-ipsum).

#### Includer File

@[markdown](includer.md)

#### CLI

You can use the command-line interface to perform the creation and inclusion.

##### Command

@[sh](create_and_include.sh)

@[:markdown](../../pristine.md)

#### API

You can use the API to perform the creation and inclusion.

##### Ruby Code

@[ruby](create_and_include.rb)

##### Command

```sh
ruby create_and_include.rb
```

### Finished Page
            
It's big, so linking instead of including:  [page file](page.md#page-contents).

