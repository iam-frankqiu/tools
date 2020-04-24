# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-sequence-arrow`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 28
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expected a semicolon or a line terminator'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 11
          index: 11
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'async'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 10
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 27
          index: 27
          line: 1
        }
        start: Object {
          column: 11
          index: 11
          line: 1
        }
      }
      expression: ArrowFunctionExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 27
            index: 27
            line: 1
          }
          start: Object {
            column: 11
            index: 11
            line: 1
          }
        }
        head: FunctionHead {
          async: false
          hasHoistedVars: false
          rest: undefined
          thisType: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 16
              index: 16
              line: 1
            }
            start: Object {
              column: 11
              index: 11
              line: 1
            }
          }
          params: Array [
            BindingIdentifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 12
                  index: 12
                  line: 1
                }
                start: Object {
                  column: 11
                  index: 11
                  line: 1
                }
              }
            }
          ]
        }
        body: BlockStatement {
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 27
              index: 27
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
          body: Array [
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 18
                  index: 18
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'await'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                  start: Object {
                    column: 18
                    index: 18
                    line: 1
                  }
                }
              }
            }
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 25
                  index: 25
                  line: 1
                }
                start: Object {
                  column: 24
                  index: 24
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'x'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 25
                    index: 25
                    line: 1
                  }
                  start: Object {
                    column: 24
                    index: 24
                    line: 1
                  }
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```