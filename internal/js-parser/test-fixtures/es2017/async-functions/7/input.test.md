# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 7`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSCallExpression {
				arguments: [
					JSObjectExpression {
						properties: [
							JSObjectProperty {
								key: JSStaticPropertyKey {
									value: JSIdentifier {
										name: "async"
										loc: SourceLocation es2017/async-functions/7/input.js 1:6-1:11 (async)
									}
									loc: SourceLocation es2017/async-functions/7/input.js 1:6-1:11 (async)
								}
								value: JSReferenceIdentifier {
									name: "async"
									loc: SourceLocation es2017/async-functions/7/input.js 1:6-1:11 (async)
								}
								loc: SourceLocation es2017/async-functions/7/input.js 1:6-1:11
							}
						]
						loc: SourceLocation es2017/async-functions/7/input.js 1:4-1:13
					}
				]
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: SourceLocation es2017/async-functions/7/input.js 1:0-1:3 (foo)
				}
				loc: SourceLocation es2017/async-functions/7/input.js 1:0-1:14
			}
			loc: SourceLocation es2017/async-functions/7/input.js 1:0-1:15
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2017/async-functions/7/input.js>
	loc: SourceLocation es2017/async-functions/7/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
