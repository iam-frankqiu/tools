# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2019 > json-strings > string-line-separator`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			trailingComments: ["0"]
			expression: JSStringLiteral {
				value: "before\u2028after"
				loc: SourceLocation es2019/json-strings/string-line-separator/input.js 1:1-2:15
			}
			loc: SourceLocation es2019/json-strings/string-line-separator/input.js 1:0-2:17
		}
	]
	comments: [
		CommentLine {
			id: "0"
			value: "      ^ That's a U+2028 LINE SEPARATOR UTF-16 char (between 'before' and 'after')"
			loc: SourceLocation es2019/json-strings/string-line-separator/input.js 3:0-3:83
		}
	]
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2019/json-strings/string-line-separator/input.js>
	loc: SourceLocation es2019/json-strings/string-line-separator/input.js 1:0-4:0
}
```

### `diagnostics`

```

```
