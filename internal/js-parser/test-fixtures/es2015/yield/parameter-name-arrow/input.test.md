# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-name-arrow`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSArrowFunctionExpression {
				body: JSBlockStatement {
					body: []
					directives: []
					loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:11-1:13
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					params: [
						JSBindingIdentifier {
							name: "yield"
							loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:1-1:6 (yield)
						}
					]
					loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:0-1:10
				}
				loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:0-1:13
			}
			loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:0-1:13
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/yield/parameter-name-arrow/input.js>
	loc: SourceLocation es2015/yield/parameter-name-arrow/input.js 1:0-1:13
}
```

### `diagnostics`

```

```
