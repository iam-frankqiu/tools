# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0099`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSArrowFunctionExpression {
				body: JSNumericLiteral {
					value: 0
					format: "octal"
					loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:12-1:14
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					params: [
						JSBindingIdentifier {
							name: "INVALID_PLACEHOLDER"
							loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:12-1:11
						}
						JSBindingIdentifier {
							name: "INVALID_PLACEHOLDER"
							loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:12-1:11
						}
					]
					loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:0-1:11
				}
				loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:0-1:14
			}
			loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:0-1:14
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
				message: [RAW_MARKUP {value: "Invalid left-hand side in "}, "arrow function parameters"]
			}
			location: {
				language: "js"
				path: UIDPath<esprima/invalid-syntax/migrated_0099/input.js>
				end: Position 1:3
				start: Position 1:1
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/invalid-syntax/migrated_0099/input.js>
	loc: SourceLocation esprima/invalid-syntax/migrated_0099/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0099/input.js:1:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid left-hand side in arrow function parameters

    (10, 20) => 00
     ^^


```
