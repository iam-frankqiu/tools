# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > arrow-functions > no-binary-left`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSArrowFunctionExpression {
				body: JSBlockStatement {
					body: []
					directives: []
					loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:6-1:8
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					params: []
					loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:0-1:5
				}
				loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:0-1:8
			}
			loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:0-1:8
		}
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:9-1:11
			}
			loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:9-1:11
		}
		JSExpressionStatement {
			expression: JSBooleanLiteral {
				value: true
				loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:12-1:16
			}
			loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:12-1:16
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Expected a semicolon or a line terminator"}
			}
			location: {
				language: "js"
				path: UIDPath<es2015/arrow-functions/no-binary-left/input.js>
				end: Position 1:8
				start: Position 1:9
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/arrow-functions/no-binary-left/input.js>
	loc: SourceLocation es2015/arrow-functions/no-binary-left/input.js 1:0-1:16
}
```

### `diagnostics`

```

 es2015/arrow-functions/no-binary-left/input.js:1:9 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected a semicolon or a line terminator

    () => {} || true
             ^


```
