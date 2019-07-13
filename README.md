# Tbg

Tbg is a table generator. It reads Markdown-like input and generates a table using box-drawing characters.

## Usage

``` shell
tbg [file]
```
### Input syntax

Table definition consist of hyphens creating each column's header and pipes separating each column.

![example1](https://user-images.githubusercontent.com/33803413/61164872-c76bb180-a519-11e9-9f4a-a293cb09d9d2.png)

The pipes on either end of the table and the header row are optional.

![example2](https://user-images.githubusercontent.com/33803413/61164879-dbafae80-a519-11e9-85cf-d46537843e80.png)

Cells can vary in width and do not need to be perfectly aligned within columns. There must be at least one hyphen in each column of the header row.

![example3](https://user-images.githubusercontent.com/33803413/61164885-e8cc9d80-a519-11e9-873e-82e9ccb655c3.png)

You can align text to the left, right, or center of a column by including colons to the left, right, or on both sides of the hyphen(s) within the header row.

![example4](https://user-images.githubusercontent.com/33803413/61164891-f2560580-a519-11e9-9d3a-bee330a3f2e1.png)

## License

[MIT](https://github.com/wadiim/tbg/blob/master/LICENSE)
