# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 23`

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
      column: 0
      index: 7
      line: 5
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
          column: 2
          index: 6
          line: 4
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
            column: 1
            index: 5
            line: 4
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        quasis: Array [
          TemplateElement {
            cooked: '\n\n\n'
            raw: '\n\n\n'
            tail: true
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 0
                index: 4
                line: 4
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