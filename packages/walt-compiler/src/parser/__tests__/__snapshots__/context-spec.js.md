# Snapshot report for `src/parser/__tests__/context-spec.js`

The actual snapshot is saved in `context-spec.js.snap`.

Generated by [AVA](https://ava.li).

## syntaxError generates an accurate error string

> Snapshot 1

    `SyntaxError: ␊
    let x: i32 = someUnknownToken;␊
                 ^^^^^^^^^^^^^^^^^ unknown token␊
    Test Error␊
      at unknown (unknown:1:13)`

## unexpected generates syntax error

> Snapshot 1

    `SyntaxError: ␊
    let x: i32 = someUnknownToken;␊
                 ^^^^^^^^^^^^^^^^^ Unexpected token Identifier␊
    Expected: "someUnknownToken"␊
      at unknown (unknown:1:13)`

## unknown token generates syntax error

> Snapshot 1

    `SyntaxError: ␊
    let x: i32 = someUnknownToken;␊
                 ^^^^^^^^^^^^^^^^^ someUnknownToken␊
    Unknown token␊
      at unknown (unknown:1:13)`
