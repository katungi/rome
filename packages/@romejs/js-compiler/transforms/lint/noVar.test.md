# `noVar.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/transforms/lint/noVar.test.ts --update-snapshots` to update.

## `disallow var`

```javascript
Object {
  src: 'var foobar;\nfoobar'
  suppressions: Array []
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'lint'}]
      description: Object {
        category: 'lint/noVar'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Variable declarations using `var` are disallowed, use `let` or `const` instead.'}
      }
      location: Object {
        filename: 'unknown'
        language: 'js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 11
          index: 11
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
}
```