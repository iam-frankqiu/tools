# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0074`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSObjectExpression {
				properties: [
					JSObjectMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "s"
								loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:7-1:8 (s)
							}
							loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:7-1:8
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:12-1:15
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: [
								JSBindingIdentifier {
									name: ""
									meta: JSPatternMeta {
										loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:9-1:10
									}
									loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:9-1:10 ()
								}
							]
							loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:8-1:11
						}
						loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:3-1:15
					}
				]
				loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:1-1:17
			}
			loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:0-1:18
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
				message: RAW_MARKUP {value: "Expected an identifier"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/invalid-syntax/migrated_0074/input.js>
				end: Position 1:9
				start: Position 1:9
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/invalid-syntax/migrated_0074/input.js>
	loc: SourceLocation esprima/invalid-syntax/migrated_0074/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0074/input.js:1:9 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

    ({ set s(.) { } })
             ^


```
