# Tbg

Tbg is a table generator. It reads Markdown-like input and generates a table using box-drawing characters.

## Usage

``` shell
tbg [file]
```
### Input syntax

Table definition consist of hyphens creating each column's header and pipes separating each column.

```
| First Header | Second Header |
| ------------ | ------------- |
| Cell         | Cell          |
| Cell         | Cell          |
```

| First Header | Second Header |
| ------------ | ------------- |
| Cell         | Cell          |
| Cell         | Cell          |

The pipes on either end of the table and the header row are optional.

```
First Header | Second Header
Cell         | Cell
Cell         | Cell
```

| First Header | Second Header |
| ------------ | ------------- |
| Cell         | Cell          |
| Cell         | Cell          |

Cells can vary in width and do not need to be perfectly aligned within columns. There must be at least one hyphen in each column of the header row.

```
| First Header | Second Header |
| - | - |
| Cell | Cell |
| Cell | Cell |
```

| First Header | Second Header |
| --- | --- |
| Cell | Cell |
| Cell | Cell |

You can align text to the left, right, or center of a column by including colons to the left, right, or on both sides of the hyphen(s) within the header row.

```
| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| Cell         | Cell           | Cell          |
| Cell         | Cell           | Cell          |
```

| Left-aligned | Center-aligned | Right-aligned |
| :----------- | :------------: | ------------: |
| Cell         | Cell           | Cell          |
| Cell         | Cell           | Cell          |

## License

[MIT](https://github.com/wadiim/tbg/blob/master/LICENSE)
