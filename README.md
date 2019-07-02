# Tbg

Tbg is a table generator. It reads Markdown-like input and generates a table using box-drawing characters.

## Usage

``` shell
tbg [file]
```
## Example

Input:

```
| Header1 | Header2 | Header3 | Header4 |
| :====== | ======= | :=====: | ======: |
| cell1   | cell2   | cell3   | cell4   |
| cell5   | cell6   | cell7   | cell8   |
| cell9   | cell10  | cell11  | cell12  |
| cell13  | cell14  | cell15  | cell16  |
```

Output:

```
┌─────────┬─────────┬─────────┬─────────┐
│ Header1 │ Header2 │ Header3 │ Header4 │
├─────────┼─────────┼─────────┼─────────┤
│ cell1   │  cell2  │  cell3  │   cell4 │
├─────────┼─────────┼─────────┼─────────┤
│ cell5   │  cell6  │  cell7  │   cell8 │
├─────────┼─────────┼─────────┼─────────┤
│ cell9   │  cell10 │  cell11 │  cell12 │
├─────────┼─────────┼─────────┼─────────┤
│ cell13  │  cell14 │  cell15 │  cell16 │
└─────────┴─────────┴─────────┴─────────┘
```

## License

[MIT](https://github.com/wadiim/tbg/blob/master/LICENSE)
