# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 3`

### `ast`

```javascript
JSRoot {
	body: [
		JSVariableDeclarationStatement {
			declaration: JSVariableDeclaration {
				kind: "var"
				declarations: [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "foo"
							loc: SourceLocation es2017/async-functions/3/input.js 1:4-1:7 (foo)
						}
						init: JSArrowFunctionExpression {
							body: JSBlockStatement {
								body: []
								directives: []
								loc: SourceLocation es2017/async-functions/3/input.js 1:27-1:29
							}
							head: JSFunctionHead {
								async: true
								hasHoistedVars: false
								params: [
									JSBindingIdentifier {
										name: "foo"
										loc: SourceLocation es2017/async-functions/3/input.js 1:18-1:21 (foo)
									}
								]
								loc: SourceLocation es2017/async-functions/3/input.js 1:10-1:26
							}
							loc: SourceLocation es2017/async-functions/3/input.js 1:10-1:29
						}
						loc: SourceLocation es2017/async-functions/3/input.js 1:4-1:29
					}
				]
				loc: SourceLocation es2017/async-functions/3/input.js 1:0-1:30
			}
			loc: SourceLocation es2017/async-functions/3/input.js 1:0-1:30
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Function parameters can't be parenthesized"}
			}
			location: {
				language: "js"
				path: UIDPath<es2017/async-functions/3/input.js>
				end: Position 1:17
				start: Position 1:17
			}
		}
	]
	directives: []
	hasHoistedVars: true
	sourceType: "script"
	syntax: []
	path: UIDPath<es2017/async-functions/3/input.js>
	loc: SourceLocation es2017/async-functions/3/input.js 1:0-2:0
}
```

### `diagnostics`

```

 es2017/async-functions/3/input.js:1:17 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Function parameters can't be parenthesized

    var foo = async ((foo)) => {};
                     ^


```
