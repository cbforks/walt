# Snapshot report for `src/parser/__tests__/declaration-spec.js`

The actual snapshot is saved in `declaration-spec.js.snap`.

Generated by [AVA](https://ava.li).

## array declaration

> Snapshot 1

    {
      Type: 'Declaration',
      id: 'arr',
      meta: [
        {
          payload: 'f32',
          type: 'type/array',
        },
        {
          payload: 0,
          type: 'local/index',
        },
      ],
      params: [
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 17,
              line: 1,
            },
            {
              col: 18,
              line: 1,
            },
          ],
          type: 'i32',
          value: '0',
        },
      ],
      range: [
        {
          col: 0,
          line: 1,
        },
        {
          col: 19,
          line: 1,
        },
      ],
      type: 'i32',
      value: 'let',
    }

## object declaration

> Snapshot 1

    {
      Type: 'Declaration',
      id: 'obj',
      meta: [
        {
          payload: {
            id: 'Foo',
          },
          type: 'type/user',
        },
        {
          payload: 0,
          type: 'local/index',
        },
      ],
      params: [
        {
          Type: 'Constant',
          meta: [],
          params: [],
          range: [
            {
              col: 15,
              line: 1,
            },
            {
              col: 16,
              line: 1,
            },
          ],
          type: 'i32',
          value: '0',
        },
      ],
      range: [
        {
          col: 0,
          line: 1,
        },
        {
          col: 17,
          line: 1,
        },
      ],
      type: 'i32',
      value: 'let',
    }