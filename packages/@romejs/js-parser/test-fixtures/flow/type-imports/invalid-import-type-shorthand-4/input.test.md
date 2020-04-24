# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-imports > invalid-import-type-shorthand-4`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 35
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Cannot overwrite primitive type string'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 9
          index: 9
          line: 1
        }
      }
    }
  ]
  body: Array [
    ImportDeclaration {
      defaultSpecifier: undefined
      importKind: undefined
      namespaceSpecifier: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 34
          index: 34
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      source: StringLiteral {
        value: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 33
            index: 33
            line: 1
          }
          start: Object {
            column: 28
            index: 28
            line: 1
          }
        }
      }
      namedSpecifiers: Array [
        ImportSpecifier {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 20
              index: 20
              line: 1
            }
            start: Object {
              column: 9
              index: 9
              line: 1
            }
          }
          imported: Identifier {
            name: 'string'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 14
                index: 14
                line: 1
              }
            }
          }
          local: ImportSpecifierLocal {
            name: BindingIdentifier {
              name: 'string'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 20
                  index: 20
                  line: 1
                }
                start: Object {
                  column: 14
                  index: 14
                  line: 1
                }
              }
            }
            importKind: 'type'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
        }
      ]
    }
  ]
}
```