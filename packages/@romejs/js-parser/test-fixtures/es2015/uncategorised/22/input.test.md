# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 22`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 5
      index: 22
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 5
          index: 22
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: TemplateLiteral {
        expressions: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 5
            index: 22
            line: 3
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        quasis: Array [
          TemplateElement {
            cooked: '\n\r\b\x0b\t\f\u2028\u2029'
            raw: '\\n\\r\\b\\v\\t\\f\\\n\\\n\\\u2028\\\u2029'
            tail: true
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 4
                index: 21
                line: 3
              }
              start: Object {
                column: 1
                index: 1
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```