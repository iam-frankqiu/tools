# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 408`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "a"
				loc: SourceLocation core/uncategorised/408/input.js 1:0-1:1 (a)
			}
			loc: SourceLocation core/uncategorised/408/input.js 1:0-1:1
		}
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation core/uncategorised/408/input.js 1:7-1:7
			}
			meta: JSClassHead {
				body: []
				loc: SourceLocation core/uncategorised/408/input.js 1:2-1:8
			}
			loc: SourceLocation core/uncategorised/408/input.js 1:2-1:8
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
				path: UIDPath<core/uncategorised/408/input.js>
				end: Position 1:1
				start: Position 1:2
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<core/uncategorised/408/input.js>
	loc: SourceLocation core/uncategorised/408/input.js 1:0-1:8
}
```

### `diagnostics`

```

 core/uncategorised/408/input.js:1:2 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected a semicolon or a line terminator

    a class;
      ^


```
